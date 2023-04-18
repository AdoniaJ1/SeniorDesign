# Part I: Description of Test Plan
## Test driven development
### Our approach is to utilize test driven development. This means that we will consider a “base case” for each feature or function we want to implement. We will write this test case and complete the least amount of 
## Integration tests
### Also, at designated time intervals we labeled as milestones, we will perform build tests to see if the new objectives are correctly added to the previous existing versions

# Part II:Tests
### Empty Sandbox Test
- purpose of test: Ensure program is executable and ensure game is stable and environment is visually present in VR headset, perspective is maintained
- description of test: Execute game on VR hardware and observe surroundings
- inputs used for test: No input just running game
- expected outputs/results: Game does not crash, perspective is maintained visually
- normal/abnormal/boundary case indication: Game is not executable, observable sensory confusion 
- Blackbox indication: Game is executable, no observable sensory confusion
 - functional/performance
 - unit/integration

### Controller Giving Feedback Test
- purpose of test: Ensure the controller is connected to the interface during execution and that every user's input in the control is shown in the environment.
- description of test: Execute game on VR hardware and observe if the inputs are shown in the environment
- inputs used for test: user input all button controls on the hardware.
- expected outputs/results: Game shows all users input in the environment.
- normal/abnormal/boundary case indication: Game does not show any inputs or missing inputs the user makes in the environment;.
- Blackbox indication: Game is executable, all inputs are shown in the environments.
- functional/performance: expected functional performance is that the environment shows users input.


### Build Test 1: Regular build tests to test pre-decided packaged features # integration test
- purpose of test: Ensure all tasks in this milestone are well integrated.
- #### description of test: To execute the tests and ensure no abnormal behavior
- inputs used for test: All inputs for this milestone
- expected outputs/results:no abnormal behavior and no abnormal sensory behavior, reference all tests above.
- normal/abnormal/boundary case indication: Game is not executable, observable sensory confusion, user input not shown in environment. reference all tests above.
- Blackbox indication: Game is executable, no observable sensory confusion, no user input shown in environment.
- unit/integration: expect no abnormal behavior.

### Player Movement with Stick Test
- purpose of test: Ensure player movement is smooth and effectively moves the player. Ensure movement is stable and the environment is visually presented well in VR headset, perspective is maintained.
- description of test: Use player movement tool on VR hardware to move in all directions and observe surroundings
- inputs used for test: player movement tool selection, player movement inputs
- expected outputs/results: Game does not crash, perspective is maintained visually during movement, player moves across the  environment
- normal/abnormal/boundary case indication: Game is not executable, observable sensory confusion, no movement by player in environment, movement controls do not act as specified
- Whitebox indication: Game is executable, no observable sensory confusion, movement is following correct physics.
- Functional: Game is executable, no observable sensory confusion, movement follows behavior elicited.

### Object Interaction/Grab Test
- purpose of test: Ensure player can grab and move objects with controller
- description of test: Player will attempt to grab and move an object in xyz plane and move object into another object 
- Inputs: N/A
- expected outputs/results: object is moved smoothly by player and objects do not clip into each other
- normal
- functional
- integration test indication	

### Spawn Object Test
- purpose of test: Ensure Spawning object off of input works
- Description of test: Attempt to use the depress button to spawn object
- Inputs: spawn button
- expected outputs/results: selected shape will appear where indicated when button depressed
- normal
- blackbox
- functional
- integration test

### Player Teleport with Ray Interactor and Reticle Test
- purpose of test: Ensure player movement is smooth and effectively moves the player. Ensure movement is stable and the environment is visually presented well in VR headset, perspective is maintained. Ray interactor and reticle interact with environment
- description of test: Use teleport ray on VR hardware to move in all directions and observe surroundings, then release the teleport button and observe surroundings.
- inputs used for test: teleport button, hand aiming
- expected outputs/results: Game does not crash, perspective is maintained visually during movement, player moves across the  environment, reticle appears at the collision of the teleport ray and environment,
- normal/abnormal/boundary case indication: Game is not executable, observable sensory confusion, no movement by player in environment, movement controls do not act as specified
- Whitebox indication: Game is executable, no observable sensory confusion, movement is following correct physics.
- Functional: Game is executable, no observable sensory confusion, movement follows behavior elicited.
- Scale Objects Based on Hand Movement From User Test
- purpose of test: Ensure objects are able to be scaled up and down with hand movement while grabbed
- description of test: scale object up and then down based on the change in hand position while holding an object while depressing the grab and scale button
- Inputs: grab button, scale button, hand movement
- expected outputs/results: Shape will increase one unit on press of relevant buttons and decrease back to size on movement of hand in x,y,z
- normal
- blackbox
- functional
- integration test

### UI Selector Test:
- purpose of test: Ensure program is executable and the user is able to use UI interface in the environment.
- description of test: Execute game on VR hardware and is the UI selector in the environment
- inputs used for test: input all UI tool selections
- expected outputs/results: Game does not crash, UI selection effects are shown in the environment.
- normal/abnormal/boundary case indication: Game is not executable, UI selection effects are not shown in the environment.
- Whitebox indication: UI tool selector functions in system
- functional: UI tool selector effect is shown in the environment.


### Build Test 2: build tests on hardware to test pre-decided packaged features
- purpose of test: Ensure all tasks in this milestone are well integrated.
- description of test: To execute the tests and ensure no abnormal behavior
- inputs used for test: All inputs for this milestone
- expected outputs/results:no abnormal behavior and no abnormal sensory behavior, reference all tests above.
- normal/abnormal/boundary case indication: Game is not executable, observable sensory confusion, user input not shown in environment. reference all tests above.
- Blackbox indication: Game is executable, no observable sensory confusion, no user input shown in environment.
- integration

### Wrist Menu Test
- purpose of test: Ensure the wrist menu works correctly 
- Description of test: Attempt to use the wrist menu with UI selector
- Inputs:UI
- expected outputs/results: Ui indication on Wrist Menu
- normal
- blackbox
- functional
- integration test

### Wrist Menu Preset Object Test
- Please purpose of test: Ensure all preset shapes correctly work within the wrist menu
- Description of test: Attempt to use the wrist menu to create preset shapes (regular polygons, cube, sphere , cylinder, etc…)
- Inputs: N/A
- expected outputs/results: selected shape will appear where indicated when shape selected in the menu
- normal
- blackbox
- functional
- integration test

### Scale Objects Based on UI Input From User Test
- purpose of test: Ensure objects are able to be scaled up and down with UI
- description of test: scale object up one unit and then down with UI
- Inputs: UI button, aiming
- expected outputs/results: Shape will increase one unit on press of relevant button and decrease back to size on press of “-“ button or “+” button in x,y,z
- normal
- blackbox
- functional
- integration test
### Change Objects’ Physics Based on UI Input From User Test
- purpose of test: Ensure objects are able to have adjustable physics, specifically gravity, collision, and throwable
- description of test: use UI to select each option and interact with the object to ensure functionality
- Inputs: UI button, aiming
- expected outputs/results: Shape will act as buttons say
- normal
- blackbox
- functional
- integration test
### Change Objects’ Color Based on UI Input From User Test
- purpose of test: Ensure objects are able to have adjustable color from a dropdown
- description of test: use UI to select each option and look at object
- Inputs: UI button, aiming
- expected outputs/results: Shape will act as buttons say
- normal
- blackbox
- functional
- integration test
### Build Test 3: Regular build tests to test pre-decided packaged features
- Purpose of Test: Ensure all tasks in this milestone are well integrated.
- Description of Test: To execute the tests and ensure no abnormal behavior
- Inputs used for Test: All inputs for this milestone
- Expected Outputs/Results:no abnormal behavior, reference all tests above.
- Normal/Abnormal/Boundary Case Indication: Game is not executable or menus do not function as intended. reference all tests above.
- Blackbox indication: Game is executable, no files are lost and menus function as intended, no user input shown in the environment.
### Objects’ Physics Match Visuals After Scaling Test
- purpose of test: Ensure objects are able to have adjustable physics, that match the new scaled appearance
- description of test: use the scaling feature followed by the UI physics buttons to ensure that the new object acts as it should.
- Inputs: UI button, aiming
- expected outputs/results: Shape will act as buttons say
- normal
- blackbox
- functional
- integration test
### Scale Player Based on Wrist UI Input From User Test
- purpose of test: Ensure player is able to be scaled up and down with wrist UI
- description of test: scale plsyer up one unit and then down with wristUI
- Inputs: UI button, aiming
- expected outputs/results: player will increase one unit on press of relevant button and decrease back to size on press of “-“ button or “+” 
- normal
- blackbox
- functional
- integration test
### Return to Start Menu from Wrist Menu Test
- Purpose of Test: Ensure that the user can return to start menu from wrist
- Description of Test: From any scene, select return to start on the wrist menu
- Inputs used for Test:  wrist menu
- Expected Results: The player should be loaded into a fresh sandbox.
- Normal/Abnormal/Boundary Case Indication: Game crashes or otherwise does not create a new empty sandbox
- Whitebox Indication:  The player is loaded into an empty sandbox.
- Functional:  The player is loaded into a fresh new sandbox that they can edit from scratch. 
### Select Environment from Start Menu Test
- Purpose of Test: Ensure that the user can select a different environment from the start menu.
- Description of Test: From the main menu, select an environment option from the drop down and have the player load into that by clicking start on the main menu
- Inputs used for Test:  Main menu
- Expected Results: The player should be loaded into a fresh sandbox.
- Normal/Abnormal/Boundary Case Indication: Game crashes or otherwise does not create a new empty sandbox
- Whitebox Indication:  The player is loaded into an empty sandbox.
- Functional:  The player is loaded into a fresh new sandbox that they can edit from scratch.

### Replicate Objects Test
- purpose of test: Ensure object replicating tool is effective and is able to replicate the selected 3d item in the environment, replicated object is shown visually in VR headset.
- description of test: replicate selected 3d item in the environment and observe how the object is replicated in the environment, and that all settings are duplicated
- inputs used for test: inputs and motion control for selecting and replicating an object
- expected outputs/results: Game does not crash, environment is maintained around the replicated object. Object is presented well as a duplicate sitting next to the original objects
- normal/abnormal/boundary case indication:  Game is not executable, observable sensory confusion. No creation or imperfect duplication of object in environment, replicating controls do not act as specified
- Whitebox indication: Game is executable, no observable sensory confusion, replicating function behaves as expected.
- Functional: Game is executable, no observable sensory confusion, replicating follows behavior elicited.

### Physics Layers Test
-purpose of test: Ensure objects. Environments, and players are on different layers and interact as suspected in traditional physics. Player cannot move themself with objects
-description of test: use objects to try to interact with things
-Inputs: grabbing, aiming
-expected outputs/results: Shape will act as buttons say
-normal
-blackbox
-functional
-integration test

### Build Test 4: Regular build tests to test pre-decided packaged features
-purpose of test: Ensure all tasks in this milestone are well integrated into the system.
-description of test: Run all tests in this milestone, look for abnormal behavior.
-inputs used for test: reference each test’s inputs.
-expected outputs/results: Game does not crash, no observable sensory confusion. Note tests for unexpected behavior.
-normal/abnormal/boundary case indication: Game is not executable, observable sensory confusion. Note individual tests for unexpected behavior.
-Blackbox indication: Game is executable, no observable sensory confusion.  Reference tests for unexpected behavior.
-Integration: Game is executable, no observable sensory confusion. Reference tests for unexpected behavior.
