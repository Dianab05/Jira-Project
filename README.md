<h1>Testing Project for Guru 99 Banking</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: **Guru 99 Banking**

Tools used: **Jira, Zephyr Squad**

<h2>Functional specifications:</h2>

The stories below was created in Jira and describes the functional specifications of the "New customer" and "Edit customer" modules, for which the final project is performed upon.

![story1](https://github.com/Dianab05/Jira-Project/assets/166596469/2adfdb65-fd88-445f-bd55-2e79d0ca74e3)



![story 2](https://github.com/Dianab05/Jira-Project/assets/166596469/4a77f7d4-6e74-4dd7-bfbb-162e8a7ff157)


<h2>Release </h2>

Here you can find the release that was created for this project:

![release](https://github.com/Dianab05/Jira-Project/assets/166596469/bcb88202-7053-4f22-ba9c-a78abdab1eeb)



<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the Guru99 Banking aplication.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

The **test plan** that was created for this project can be found [here](https://github.com/Dianab05/Jira-Project/blob/main/Test%20Plan%20Guru%2099%20Banking.pdf)

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<table>
<tr><td>Project manager </td><td>Ion Popescu</td> </tr>
<tr><td>Product owner</td><td>Maria Ionescu</td></tr>
<tr><td>Software developer</td><td>Mihai Apostol</td></tr>
<tr><td>QA Engineer</td><td>Batrinu Diana</td></tr>
</table>

<h4> 1.1.2 Entry criteria defined </h4>

• Testing environment is up and running  <br>
• Business requirements are completed by the analysis team and are delivered to the 
appropriate testing team for evaluation <br>
• Potential project risks are detected and mitigated <br>
• Roles and responsibilities are allocated <br>
• Test plan should be finalized before entering the next phase of testing <br>
• Define the objectives of testing and the accepted level of quality 
<br>

<h4> 1.1.3 Exit criteria defined </h4>

• All the test cases were executed, run rate is mandatory to be 100% <br>
• 90% or more of the test cases are passed  <br>
• All detected errors have been reported and closed <br>
• No critical issues have status open <br>
• The project budget was reached <br>
• The project deadline was reached <br>
• The remaining defects/bugs have low severity and low priority  <br>
• Test completion report has been created and sent to the stakeholders <br>
• Product risks have been identified and mitigated<br>

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

For this version of the application the functionalities in the scope of testing are:  
Some of the features of Manager module for the Web application which were defined in 
Guru99 Banking Project software requirements specification:  
✓ New Customer <br>
✓ Edit Customer  <br>
✓ Delete Customer  <br>

From the point of view of the testing techniques we are going to use mostly blackbox testing with the following test design techniques: 
- equivalence partitioning
- boundary value analysis
- decision table
  
From a testing type perspective we are going to use non-functional testing  where we are going to cover only usability testing and compatibility testing. <br>

Also, positive testing and negative testing are to be done, and (according to the needs) retesting and regression testing will be done when defects are going 
to be fixed or when modifications of any type are going to be brought to the code. <br>

The testing process will be focused on the Chrome browser version 27 and above <br>

<h5>Tests not in scope: </h5>

From the perspective of the modules covered, any other functionality that is located outside of the specified modules are not to be tested.

We are not going to cover during the testing process any techniques related to whitebox testing. 

Also, security testing and non-functional testing like performance, stress, volume or logical database testing will not be performed during this session of testing. 

Test process for mobile application is out of scope.

Other browsers except Chrome are out of scope.

Automation testing is beyond scope.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

•	The team does not have the proper knowledge or experience in order to guarantee the desired level of quality for the application <br>
•	Not enough time has been allocated in order to properly test and cover all the functionalities in scope<br>
•	All that the data that is going to be used will have to be created explicitly in the scope of testing, which will cut off from the time allocated for testing, generating a risk of not reaching the deadline<br>
•	Test environment not working <br>
•	Due to the company changes we might have levers <br>

<h5> Product risks: </h5>

•	All the data that is going to be used will be test data, which will not give us an experience of the application close enough to the ones that the user will experience <br>
•	Taking into account that only 3 modules are in the scope of testing, the rest of the modules will still be at risk of not fulfilling the user needs<br>
•	Validation constraints on some of the fields might be too restrictive<br>

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

**Reason for Monitoring and Control** <br>

The monitoring and control stage was conducted to ensure that the testing process proceeds according to plan and that all requirements and specifications are met. <br>
This stage is essential for promptly identifying and addressing issues that arise during testing, evaluating progress and performance, and making informed decisions about necessary adjustments. <br>
By closely monitoring, it can be ensured that all critical bugs are addressed and that the final product will be of high quality and ready for release. <br>


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.<br>

You can find below an example of some of the test conditions that were created in the scope of this project: <br>

![list of tests](https://github.com/Dianab05/Jira-Project/assets/166596469/93d131b5-a452-481a-8f64-0eb13d8d76a9)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. <br>

The **test cases** can be accessed [here](https://github.com/Dianab05/Jira-Project/blob/main/Zephyr%20Test%20Steps%20(Jira)%20SDB.pdf)


<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**Test Plan:** <br>
A comprehensive test plan outlining the scope, objectives, resources, schedule, and activities involved in testing.<br>

**Test Cases:** <br>
Detailed test cases covering all functional and non-functional requirements. These should include inputs, execution steps, and expected results. <br>

**Test Environment:**  <br>
A properly configured test environment that mirrors the production environment as closely as possible. This includes hardware, software, network configurations, and databases.

**Test Data:** <br>
Representative test data that covers all possible scenarios, including edge cases and boundary conditions. This data should be prepared and validated. <br>

**Test Tools:**  <br>
Selection and setup of test automation tools, defect tracking tools, and any other testing tools that will be used during the test execution phase.  <br>

**Test Team:**  <br>
A well-prepared test team with clearly defined roles and responsibilities. Team members should be trained and familiar with the test plan, tools, and procedures. <br>


<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: <br>

![cycle summary](https://github.com/Dianab05/Jira-Project/assets/166596469/2538601f-33d1-4610-99c6-2d8923a772df)

Bugs have been created based on the failed tests. <br> 

The **complete bug report** can be found [here](https://github.com/Dianab05/Jira-Project/blob/main/Jira%20BUG%20REPORT%20.pdf)

The following is a summary of the bugs that have been found:

![list of bugs](https://github.com/Dianab05/Jira-Project/assets/166596469/19b6d2e1-52f7-4ae0-abaa-823d2da945bd)

SDB-18 -> Priority Low, Severity Low <br> 
SDB-20 -> Priority Low, Severity Low <br> 
SDB-35 -> Priority Low, Severity Low <br> 
SDB-43 -> Priority High, Severity Medium <br>
SDB-44 -> Priority Low, Severity Low <br> 

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion </h3>

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

**The traceability matrix** was generated and can be found [here](https://github.com/Dianab05/Jira-Project/blob/main/Forward%20Traceability_Matrix%20SDB.xlsx) 

![Traceability Matrix](https://github.com/Dianab05/Jira-Project/assets/166596469/5b7859c6-a250-4820-9266-b9a36616aede)

**Test execution chart** was generated and can be found below. 

![test execution report](https://github.com/Dianab05/Jira-Project/assets/166596469/608f2aa4-b2d5-48f1-a0e6-55d03aeb259e)

The final report shows that a number of 3 tests have failed of a total of 17 for the "New Customer" cycle, and a number of 2 tests have failed of a total of 9 for the "Edit Customer" cycle. 

A number of 5 total bugs were found, from which the priority is: 4 are low and 1 is medium.

<h3> General Conclusion of Testing </h3>

**Overview**
Total number of tests created: 26 <br>
Total number of tests executed: 26 <br>
Percentage of requirements covered: Approximately 95% <br>

**Requirements Coverage** 
Covered Requirements: Most of the specified requirements in the project scope have been rigorously tested.<br>
Untested Functionalities: There are a few minor functionalities that were not tested due to time and resource constraints:<br>
- CSV export functionality<br>
- Advanced filtering options<br>

**Bug Impact and Resolution**
Identified Bugs: A total of 5 bugs were reported during testing.<br>
Medium Bugs: 1 (can be fixed later, but should be documented and scheduled for the next development cycle)<br>
Minor Bugs: 4 (do not impact primary functionality, can be resolved in the future)<br>

Impact on Launch: The bugs can be addressed in subsequent development cycles. <br>

**Risk Identification and Recommendations**
Identified Risks: <br>
- Taking into account that only 3 modules were in the scope of testing, the rest of the modules will still be at risk of not fulfilling the user needs <br>
- Validation constraints on some of the fields might be too restrictive <br>

**Recommendations for Launch:**
- Plan a post-launch testing cycle to address medium and minor bugs. <br>
- Closely monitor system performance and user feedback in the initial weeks post-launch. <br>
- Encourage users to report any encountered issues so they can be quickly addressed.<br>

**Lessons Learned**
Planning and Resources: Allocate enough time and resources to test all functionalities, including secondary ones, to ensure complete coverage. <br>
Automation: Implementing test automation tools can significantly speed up the process and improve testing accuracy.<br>
Communication: Maintain effective communication between development and testing teams to prevent issues and ensure all requirements are properly understood and covered.<br>
Documentation: Keep detailed and updated documentation of tests performed, identified bugs, and implemented solutions to facilitate future development cycles.<br>
These conclusions and recommendations will help improve the development and testing process for future projects, ensuring a smoother launch and a better user experience.<br>




