##Epilogue
###Andromedus
Alexis Hoshino, Eric Tian, HQ Pham-Nguyen, Kathleen Enverga
21 October 2014

####Revision History
Version | Sections Updated | Summary
---   | ---   | ---
v.0   | Draft   | Initial draft creation

## Introduction
#### Overview
Epilogue’s test plan is to go through each feature (photos, videos, collaborators, stories) with a user to ensure that the application is the desirable product of Jed’s focus group.

#### Goals and Objectives
- Our primary goal is to ensure that the workflow is consistent with the user’s expectations. We will have a set of features for the users to test out and it will give insight whether or not what was implemented meets the needs of the Jed’s focus group.
- We want to be able to give the user a task and have the user complete each task within the given time frame to make sure that the user interface and application performance are both intuitive. We want to ensure our integration with Facebook is processed seamlessly. 

#### Constraints
- We do not have direct contact with Jed’s focus group. Jed and his research team will be our primary contact between Andromedus and the focus group. Andromedus will be receiving the data from a secondary source since we are not the ones conducting the tests.

#### Assumptions and Dependencies
- We assume that the user has some motivation to create a digital memorial for a friend.
- We assume that the user has a Facebook account with at least one friend to create a memorial for, and that they will have basic familiarity with Facebook’s notification system in order to accept an invitation to Epilogue.
- Our tests depend on the stable functionality of the Facebook Graph API across updates. Since Epilogue is hosted locally on machines, the tests will also be dependent upon the proper setup of the user’s computer (i.e. the application environment).

#### Test Item Pass/Fail Criteria:
-Specify the criteria that will be used to determine whether each test item (software/product) has passed or failed testing.
- A failure criteria is as follows: “Unexpected error,” “Facebook media fails to display on memorial page”
- A passing criteria is as follows: “Facebook media displays on memorial page,” “User successfully created memorial,” “User receives and accepts collaboration invitation,” “Facebook media successfully gets stored into database”
- Unit/Modules Test Suite: PHP Unit for individual Facebook API calls for user media content.
- Integration Test Suite: Testing out database, making sure that media has been recorded, downloaded, and deleted as expected. (e.g. when a memorial is deleted, this action is reflected in the database as well)
- Scenario or Use case based Test Suite: 
- Example: Creating a memorial
- Log in using a Facebook account
- Click on “Create Memorial” and input information in the appropriate fields.
- Press Submit 
- Memorial is successfully created when you are able to access the memorial’s view along with the corresponding Facebook data.
- System Test Suite
- Multiple single use cases performed consecutively for the full feel of using Epilogue.
 
#### Test Deliverables: TBA
- List test deliverables, and links to them if available, including the following:
- Test Plan (this document itself)
- Test Cases
- Test Scripts
- Defect/Enhancement Logs
- Test Reports
 
## Part II:  User Testing Plan

#### Heuristic Evaluation / Checklist
- Interface materials: Mockups, cognitive walkthrough, wireframe
- Recording of findings: Notes taken during each user session, user diary logs

#### User Testing
- User Recruitment Criteria: Jed’s focus group
- Number of Test Users: (unknown - TBA)
- Interface: Staged branch of Epilogue application on GitHub.
- Test Session Schedule: TBA
- Tasks: Logging in using Facebook account, creating a memorial, upload/delete photos, videos, statuses, stories, add/delete collaborators.
- Recording Techniques: Note-taking during observation, copying user diary logs, cursor-tracking
- Change Implementation Schedule: TBA
