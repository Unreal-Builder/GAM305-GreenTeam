Project Log Assignments

____________________________________________

-Module Five Project Log - Team Reflection

In evaluating the QA and testing plan we created during Module Three, our team has made steady progress, despite early challenges with inactive team members. From a technical and programming standpoint, the plan has provided a solid foundation for structuring our Alpha and Beta development cycles, ensuring testing was integrated throughout implementation.

What Went Well:
The use of a shared Microsoft Excel test plan and traceability matrix, along with GitHub version control, proved highly effective in organizing and managing both development and QA tasks. Andrew and I have taken on most of the active responsibilities due to lack of consistent participation from the rest of the team, and these tools allowed us to stay aligned and efficient. The Excel sheets served not only to document test cases and bugs but also acted as a development tracker for upcoming and in-progress features.
Frequent playtests and targeted debugging helped us refine core gameplay systems, including the chargeable rifle mechanic, regenerating energy HUD, and conditional damage states like overcharge backlash. We also successfully responded to Alpha-stage feedback by implementing a full gameplay loop: players now clear virus entities to activate a gravity elevator, which in turn triggers a cinematic revealing the new area and leads to a final boss encounter. The addition of a main menu, win/loss screens, and energy-based shooting feedback helped shift the experience from a sandbox demo to a fully structured game.

What Went Wrong:
While our core systems and QA tracking structure remained reliable, we struggled initially with a lack of defined task ownership, mainly due to missing team members. This led to delays in updating visual assets and environment polish, which Andrew and I have since absorbed into our own workloads. Our reliance on Discord for quick communication was strong, but we could have used GitHub Issues more rigorously to formalize task assignment and bug resolution steps. This would have saved time in some coordination and bug tracebacks.

Integration of Previous Evaluations:
Previous evaluation feedback directly shaped our priorities for the Beta stage. For example, the suggestion to move beyond placeholders and define game objectives was implemented with our updated weapon system, mission progression, and final boss sequence. The HUD now provides visual and gameplay cues (like energy consumption and overcharge penalties) that give the player feedback beyond visual placeholders.

Improvements for Collaboration:
To improve collaboration moving forward, we plan to continue using our shared Microsoft Word-based traceability matrix and Excel project log to track all remaining development items, such as polish passes, final bug fixes, and implementation of cinematics. Instead of shifting to GitHub Issues, we found that our documentation-driven approach better supports our current workflow and team availability. The traceability matrix allows us to assign ownership directly within the document, while maintaining visibility across all planned tasks.
In addition, we are incorporating new narrative and cinematic sequences this week to enhance storytelling and feedback during gameplay. These include scenes for death, game over, startup, and respawn. A specific example is when the player activates the hidden gravity elevator, a cutscene visually reveals the opened path, guiding progression and adding polish to the experience. These enhancements support both immersion and gameplay clarity.

Tools and Techniques Found Less Helpful:
Slack was initially proposed as a communication tool, but it has proven unnecessary. Our entire team shifted to Discord for text, voice, and file sharing, which better suited our needs. Additionally, while the test plan in Sheets has been valuable, some formatting limitations (like tracking historical changes) made it less ideal for long-term regression tracking compared to a GitHub-based issue log.

Beta Development Status:
At this stage, our Beta build includes all core gameplay systems: movement, combat mechanics, clear win/loss states, interactive elements (pickups, objectives), functional HUD, and a playable boss fight. Our remaining goals for the Final Release include cinematic sequences, polish passes on environment and audio, improved enemy animations, and final asset swaps. We are on track to meet our final development deadline, provided we maintain our current production pace.

Conclusion:
In summary, while the project faced early team challenges, our technical and QA planning allowed us to adapt and continue forward. With a structured system and open communication, we are confident in completing a polished final version of the game.


___________________________________________

- Module Four Project Log – Team Reflection

Throughout the QA and testing phase of our Alpha-stage project, the team maintained a strong and consistent approach to quality assurance. Testing was an integral part of our development process, with regular evaluations occurring as features were implemented. This continuous testing helped ensure that issues were detected early and resolved efficiently.

Bug identification and correction were handled collaboratively and effectively. Bugs were caught through frequent playtesting and cross-checking against our test cases. All identified issues were logged and discussed through our team communication channels, and fixes were applied in a timely manner. We utilized both GitHub and a shared Google Sheets-based test plan and QA tracker, which allowed the team to document test cases, mark pass/fail results, and track bugs and updates in a transparent and accessible way.

Our most effective communication tool has been Discord, specifically our Green Team text and voice channels. While Slack was considered initially, it was eventually dropped in favor of Discord, which provided a more immediate and flexible environment for collaboration. Voice chats enabled quick discussions during testing, and text channels kept a running log of decisions, questions, and outcomes.

The shared Google Sheets documents served as our centralized QA plan and traceability matrix, enabling each team member to update and review testing status as development progressed. This setup allowed for real-time tracking of testing outcomes and changes to the design, while GitHub supported version control and issue tracking for development and testing tasks.

Reflecting on our process, one area for future improvement would be to expand our use of GitHub Issues to formalize bug tracking and task assignments further. While our current workflow is effective, a structured ticketing system would help scale our QA efforts in more complex stages of the project.

Our initial analysis of the game design document played a critical role in shaping our QA and testing strategies. The entire team was involved in reviewing the document, identifying key mechanics, and determining which components would require early testing focus. This shared understanding helped align our QA efforts with the game’s functional goals and design intentions.

In summary, the team’s QA and testing efforts have gone well. Testing was continuous, bugs were identified and fixed efficiently, and our use of Discord, Google Sheets, and GitHub provided a strong foundation for collaboration and tracking. Moving forward, we will look to refine our tracking methods further, but our current strategy has proven effective for Alpha development.

We are well on our way to meeting all deliverables required and will exceed all requirements!
WTG Green Team!


____________________________________________________________________

- Module Three Project Log – Team Development: QA and Testing Plan

Project Title: BioSynth: Inner War

As a development team, we have created the following plan for quality assurance and testing throughout our project timeline.

Preferred Communication and Collaboration Methods

Our team will be using Discord as the primary communication platform. We will hold regular check-ins two to three times per week, depending on availability, using designated channels for general discussion, bug reports, task updates, and asset sharing.

For collaborative documentation, we are using a shared Excel file to maintain our test plan and traceability matrix. This Excel document will be updated continuously throughout development and added to version control once final testing and submissions are complete.

QA Testing Plan and Schedule

We have established a structured testing process during our development cycle:

Play Testing will begin during early development (Week 3–4) and focus on validating core systems such as player movement, item pickups, and HUD functionality.

Demo Testing will occur around Week 5–6, before any public-facing or marketing demos. This stage will test overall gameplay balance, usability, and system stability.

Code Release Testing will happen in Week 7 and include a full review of all game systems, ensuring that the final build is functioning correctly and free of major issues.

What Will Be Tested

We will conduct QA on a range of game elements, including:

Core gameplay systems: player movement, magnetic lift, EMP bomb usage, AI behavior, and triangulation HUD signals.

Interactions: item pickups, weapon systems, virus detection and replication, and win/loss conditions.

Environment: navigation, lighting, sound, and potential issues with collision or level design.

UI/UX elements: HUD feedback, menu navigation, signal displays, and visual/audio responses for actions.

Each item will be marked with a simple pass or fail status during testing. We will also note any related issues in our bug tracking system.

Updating the Test Plan

The test plan is a living document and will be updated regularly as new features are added or changes are made to the design. Any changes to game mechanics, UI, or levels will prompt a review and adjustment of related test cases. This ensures that QA stays aligned with development progress.

After final testing is complete and the project is ready for submission, we will add the test plan and traceability matrix to our GitHub repository under version control.

Bug Reporting and Tracking

All bugs will be reported in the team’s Discord channel designated for bug reports. Each report will include:

A short description of the issue

Reproduction steps

The expected and actual outcomes

The date it was discovered

The tester’s name

Bugs will also be logged in our shared Excel document. This document includes details such as the bug ID, description, status (open, in progress, fixed), who it’s assigned to, and when it was fixed. A separate section of the file tracks changes over time so we can maintain a clear history of what was updated and when.

This QA plan will help ensure the final game is functional, engaging, and stable. Once the final round of testing is complete, all QA documentation will be formally added to version control and submitted with the project.

______________________________________________

- Module Two Team Project Plan.

Project BioSynth: Team Development Plan

- Scenario Overview:

o	Title: BioSynth: Inner War

o	Setting: You are a highly advanced nanobot inserted into a futuristic synthetic organism inside a cyborg-human hybrid.

o	Goal: Disable 20 rogue nanoviruses threatening to overtake the biomechanical host from within.

o	Theme: Cyber-biological — featuring glowing wire networks, semi-organic mechanical corridors, red muscle fibers fused with circuit boards, and a digital/organic atmosphere.

- Key Game Elements

o	Magnetic Lifts: Horizontal and vertical hover elevators for navigating biomechanical corridors.

o	EMP Bomb Pickups: Collectible devices that temporarily disable virus shields.

o	Virus Behavior: Rogue nanoviruses replicate via data corruption, not cellular splitting.

o	Triangulation HUD: Signal-tracking HUD showing virus locations by visual pings and signal strength.

o	Futuristic Weapon Pickups

________________________________________
- Development Timeline

Week 2: Planning & Scenario Definition

o	Define game scenario, core gameplay loop, and level goals

o	Confirm team roles and responsibilities

o	Choose key game elements and features

o	Begin Design Document and Traceability Matrix in GitHub

o	Plan-level layout and overall visual style

________________________________________
- Weeks 3–4: Pre-Alpha Milestone

o	Implement player movement and magnetic lift mechanics

o	Create blockout of level corridor with placeholder assets

o	Develop initial virus AI (non-replicating)

o	Begin basic HUD mockup development

o	Implement EMP pickup placeholder functionality

________________________________________
- Week 5: Alpha Milestone

o	Develop triangulation HUD system prototype

o	Integrate EMP pickup and virus shield interaction

o	Script early virus replication mechanics

o	Build first complete playable level zone with rough visuals and lighting

o	Actively update Traceability Matrix with progress

o	Conduct internal playtesting and gather feedback

________________________________________
- Week 6: Beta Milestone

o	Finalize virus types and replication system

o	Complete level environmental art, lighting, and sound

o	Polish triangulation HUD and gameplay feedback

o	Refine EMP and virus interaction mechanics

o	Prepare game loop for full playthrough

o	Continue bug fixing and optimization

________________________________________
- Week 7: Final Polish & Submission

o	Add menus, intro sequences, and game over logic

o	Finalize sound effects and ambient audio

o	Perform final visual polish and bug fixes

o	Complete all testing and update Test Plan in Excel

o	Submit final build, documentation, and presentation materials

________________________________________
- Development Milestone Goals

* Alpha Goals

o	Fully functional player movement and magnetic lifts

o	Placeholder corridor level design complete

o	Basic virus AI and EMP pickups implemented

o	Triangulation HUD prototype operational

o	Traceability Matrix maintained and up to date

* Beta Goals

o	Virus replication and shield/EMP interactions fully implemented

o	Complete playable level with environment design and lighting

o	Polished HUD, audio, and visual feedback

o	Game loop fully playable from start to finish

o	Testing fully documented in UE5 Test Plan

________________________________________
- Communication Plan

o	Primary Tool: Discord

o	Meeting Frequency: Twice a week or when a member is ready available

o	Preferred Days: Monday, Tuesday, Thursday, or Saturday or based on teammate availability (weekly schedule confirmed by team availability)

o	Discord Channels: Green Team

o	General discussion

o	Task updates

o	Bug reports

o	Asset sharing

o Model cohesion and preference

________________________________________
- Task Management & Tracking

o	GitHub: GAM305-GreenTeam

o	Repository for code, documentation, and version control

o	Design Document and Traceability Matrix collaboratively maintained

o	Microsoft Excel: not needed

o	Used for Traceability Matrix and Test Plan

o	Shared via GitHub or OneDrive for real-time collaboration

o	Traceability Matrix Tracks: Primarily handled in Discord

*	Task name, description, assignee, due date, status, notes

o	Test Plan Tracks: Primarily handled in Discord

*	Features, test steps, expected and actual results, pass/fail, tester info

o	Microsoft Word: Kenan T. Avila Documentation

o	Design documentation, planning notes, and final deliverables stored in GitHub

________________________________________
Team Members & Roles

o	Justin: Programming & Systems Development

o	Andrew: Level Design, Mechanics, and Gameplay Tuning

o	Douglas: Pending inclusion (Absent)

o	Kenan: Model Designer
