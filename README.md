<h1>Testing Project for Guru 99 Banking</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: **Guru 99 Banking**

Tools used: **Jira, Zephyr Squad**

<h2>Functional specifications:</h2>

The stories below was created in Jira and describes the functional specifications of the Manager module, for which the final project is performed upon.

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

The test plan that was created for this project can be found [here](https://github.com/Dianab05/Jira-Project/blob/main/Test%20Plan%20Guru%2099%20Banking.pdf)

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
The monitoring and control stage was conducted to ensure that the testing process proceeds according to plan and that all requirements and specifications are met. 
This stage is essential for promptly identifying and addressing issues that arise during testing, evaluating progress and performance, and making informed decisions about necessary adjustments.
By closely monitoring, it can be ensured that all critical bugs are addressed and that the final product will be of high quality and ready for release.

![test execution report](https://github.com/Dianab05/Jira-Project/assets/166596469/4d68bd9e-2c60-4508-a53c-1cc04c198b7a)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.<br>

You can find below an example of some of the test conditions that were created in the scope of this project: <br>

![list of tests](https://github.com/Dianab05/Jira-Project/assets/166596469/93d131b5-a452-481a-8f64-0eb13d8d76a9)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. <br>

The test cases can be accessed here:
**(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**













#    Aeries - Test Plan -
### Revision History 
| Date | Description | Author  | Author |
|:---:| :---: | :---: | :---:|
| 27.03.2024 | Test Plan for Aeries Web Version 9.24.3.26    | Alina Pircalaboiu  | Aeries Web Version 9.24.3.26 (initial version) |
| 27.03.2024 | Test Plan for Aeries Web Version 9.24.3.26    | Alina Pircalaboiu  | Aeries Web Version 9.24.3.26 (initial version) |

### Table of Content:
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Forth line

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ol>
      <li>Indented item</li>
      <li>Indented item</li>
    </ol>
  </li>
  <li>Fourth item</li>
</ol>


Link catre fisier [Git repo screenshot](https://github.com/Dianab05/Jira-Project/blob/main/request%201%20tests.png)

![Daily report](https://github.com/Dianab05/Jira-Project/blob/main/request%201%20tests.png)

###  Functionalities in scope

For this version of the application the functionalities in the scope of testing are: 

+ All the features of Admin module for the Web application which were defined in OrangeHRM business requirements: **User Management**, Job, Organization, Qualifications, Nationalities, Configuration
+ For the testing process we will use: functional testing, positive testing, negative testing, regression testing and retesting.
+ The testing process will be focused on the following browsers: Chrome and Mozilla latest versions. 





