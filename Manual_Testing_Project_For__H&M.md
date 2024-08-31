<h1>Testing Project for H&M</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **H&M**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The stories attached [here](https://github.com/FratilaAndreea98/Testare-Manuala/blob/main/Jira-HmStories.pdf) was created in Jira and describes the functional specifications of the "User atuthentication and registration" module, for which the final project is performed upon.

You can find a example of one of the stories that were created below: 

![image](https://github.com/user-attachments/assets/ab7beff8-42d9-4140-b894-1f2884ad7250)


<h3>Realease</h3>
Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/b67ba450-31ef-46de-87a8-1808699d273c)



<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for User authentication module for Media Galaxy e-commerce app.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the project risks associated with the plan. 

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<table>
<tr><td>Project manager</td> <td>Mihai Greiere</td></tr>
<tr><td>Product owner</td><td>Ovidiu Cristian</td></tr>
<tr><td>Software developer</td><td>Denisa Manolache</td></tr>
<tr><td>QA Engineer</td><td>Fratila Andreea</td></tr> 
</table>

<h4> 1.1.2 Entry criteria defined </h4>

<li>The bussiness requirments must be finalized
<li>The roles should be alcoated
<li>Test plan must be finished and sent to stakeholders
<li>The Entry Criteria And exit Criteria must be defined
<li>The project risks must have been identified and mitigated

<h4> 1.1.3 Exit criteria defined </h4>

<li>All key features of the software have been tested and work according to specifications.
<li>All critical use cases have been successfully tested.
<li>No major or critical defects have been identified that could impact the usability of the software.
<li>The software is compatible with other systems and applications that it needs to interact with.
<li>No significant compatibility issues have been identified that could prevent the software from being used
<li>The deadline has been reached

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

In order to fullfill the testing objectives we are going to focus on the Register Module(and Log In Module) which has been places on the scope and has been targeted for improvement over the next 3 months.

From the point of view the testing types and tehniques we are going to use are mostly black box testing with the following test design tehniques:
<li>Boundary Value Analysis
<li>Equivalence Partiotioning
<li>Decision table

From non-functional testing we are going to cover only usability testing and compatibility testing.
Also negative and positive testing are to be done and retesting and regression testing will be done when defects are be going to be fixed or when modification of any type are going to be brought to the code.

<h5>Tests not in scope: </h5>

Performance and security testing will not be performed during this session of testing.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

<li>An important risk in any project is the risk of delay. This risk can be caused by a number of factors, such as: incorrect time estimates, insufficient resources, changes in requirements<br>
<li>Another important risk in any project is the risk of going over budget. This risk can be caused by a number of factors, such as: incorrect cost estimates, unforeseen problems


<h5> Product risks: </h5>
<li>Bad reputation risk: Users may repeatedly try to sign up with an existing email address, leading to frustration and abandonment of the signup process. This can lead to negative reviews and affect the overall reputation of the site.
<li>Loss of potential customers: Users who prefer to register through their existing social media accounts may abandon the process if they do not find this option. This can lead to the loss of potential customers.
<li>Security Vulnerability: Accounts with invalid emails can be used for fraudulent or spam activities. Also, password recovery for these accounts becomes impossible.<br>
<li>Email delivery issues: Account confirmation emails or other communications sent to invalid addresses will never be delivered, leaving users uncertain about their account status<br>
<li>Password recovery issues: Users who forget their password cannot receive password reset emails to invalid addresses. This prevents them from accessing their own accounts, leading to frustration.
<li>Incorrect data: Incomplete or incorrect user data may affect the functionality of the site and prevent the delivery of essential communications. It can also create difficulties in user analysis and strategic decision making.


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

The monitoring and control phase is a crucial step in the software testing process, offering several key benefits:Quality Assurance,Efficiency Optimization,Enhanced User Satisfaction.<br>
The monitoring and control phase was carried out through:<br>

Test Monitoring:<br>

<li>Tracks test progress, execution times, and success/failure rates.
<li>Identifies frequently failing tests or those with significant execution times.
<li>Analyzes test results to identify trends and patterns indicating potential issues.

Test Control:<br>

<li>Adapts the testing plan based on monitoring results.
<li>Prioritizes tests based on risk and potential defect impact.
<li>Reallocates testing resources to areas requiring increased focus.


![image](https://github.com/user-attachments/assets/02e6cc63-5d96-4be4-b541-7d92e511f2c0)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. 

The following test conditions were found: <br>
![image](https://github.com/user-attachments/assets/3a8ff484-e9af-48a9-b38f-3306afd3297d)





<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/FratilaAndreea98/Testare-Manuala/blob/main/Jira-HmTestCases.pdf).

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:



<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: User Authentication

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/FratilaAndreea98/Testare-Manuala/blob/main/Jira-HmBugs.pdf).

The following is a summary of the bugs that have been found
![image](https://github.com/user-attachments/assets/05504845-5006-4091-959f-5b0143f2d1e6)


<li>FAS-26 Priority Medium, Severity High
<li>FAS-25 Priority Medium, Severity High



Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3>1.7 Test Completion</h3>
Having fulfilled all stipulated exit criteria, the testing team recommends the feature for deployment.

The traceability matrix was generated and can be found here: 

![image](https://github.com/user-attachments/assets/a8a39786-d87a-456d-ad81-80477fb21b51)



Test execution chart was generated and can be found below. 

![image](https://github.com/user-attachments/assets/8439cfd4-1134-4513-8674-42f219ce4732)



The final report shows that a number 10 tests have failed of a total of 2.

A number of 2 total bugs were found, both of them have medium priority.

Software testing incomplete: defects identified in stories 1 and 2. 80% requirement coverage achieved, but minor bugs require fixing before launch. Recommend additional testing for remaining requirements (20%) and post-launch monitoring for continued stability.
