# Proiect-practic-testare-manuala
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

Application under test: [JpetStore Demo](https://jpetstore.aspectran.com/catalog/)




Tools used: Jira, Zephyr Squad.

# Functional specifications
The below story was created in Jira and describes the functional specifications of the Dependants module, for which the final project is performed upon

# 1 Testing section
## 1.1 Test planning

The Test Plan is designed to describe all details of testing for the Dependants module from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

**Roles asigned to the project and persons allocated**

- Project manager - Andrei Popescu
- Product owner - Madalina Gheorghe
- Software developer - Gabriel Tomescu
- QA Engineer - Adina Anghel

**1.1.2 Entry criteria defined**

- functional specifications are defined
- roles needed for the project are allocated
- initial project risks were detected and mitigated
- test schedule is prepared.
- testing environment is up and running.
- test data should be available to cover the different scenarios and use cases that will be tested.

**1.1.3 Exit criteria defined**

- number of unresolved bugs is insignificant or they have low priority
- all tests have been executed
- all resolved bugs have been re-tested and approved by the QA team
- deadline was reached
- no detected major risk remained un-mitigated
- all required documentation, including test plans, test cases, and test results, has been completed and reviewed.
- 95% of tests are passed.
- no Critical issues have Open status


**1.1.4 Test scope**

 **Tests in scope**:
 
- To design a user-friendly interface that allows customers to browse and search for products easily.
- To provide photos for each product so the customers will know what they are gonna purchased.
- To add a variety of pets so you can have from where to choose from.
- Compatible with all most used browsers and old versions of Android and iOS.

 **Tests not in scope**: 

- Non-functional testing like stress, accessibility, performance is beyond scope of this project.
- Automation testing is beyond scope.

**1.1.5 Risks detected**

 Project risks:
  
- communication with the provider: Establish clear communication channels with the payment gateway provider to stay informed about updates, changes, and potential issues.
- regular testing: Conduct regular testing to ensure that the integration with the payment gateway functions correctly and is ready for deployment.
- communication breakdown: Poor communication and collaboration among team members, stakeholders, or external vendors can result in misunderstandings, delays, and rework.
- diversify payment options: Consider integrating with multiple payment gateways to provide redundancy and minimize the risk of a single-point failure.
- fallback mechanism: Develop a contingency plan for temporarily switching to an alternative payment gateway if the primary provider experiences prolonged downtime.
  
 Product risks:
  
- data breaches, payment frauds and regulatory compliance issues may appear after launching the website to the customers. 
- stability risks (crashes, disconnects, etc).
- return and Refund Management: Difficulty in managing and processing returns and refunds can lead to customer complaints and financial losses.
- market Saturation: The pet product e-commerce market may already be saturated with competitors, making it challenging for JPetStore to gain a significant market share.
- versions of IE older than Version 142.0.172.68 have security vulnerabilities (cross-site scripting( user data can be stolen after injecting malicious code in  the website), exploits on buying system).
- website performance: Suboptimal website performance, including slow loading times or technical glitches, can frustrate customers and result in lost sales.

**1.1.6 Evaluating entry criteria**

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control
Variou periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 40% of the test cases were executed, on 1st of April 2022:

## 1.3 Test Analysis
The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:

- Enter data only for mandatory fields and check that the dependant is created/updated
- Enter data for all available fields and check that the dependant is created/updated
- Leave mandatory fields empty and check that the dependant cannot be created/updated
- View dependant details and check they are correct
- View all dependants in a list
- Check all validation constraints for the fields

## 1.4 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.

The test cases with steps can be viewed here: [Dependents_test_cases.pdf]()

For the Dependants API, the following checklist was generated: [API_test_checklist.csv]()

## 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Testing environment is up and running: [https://opensource-demo.orangehrmlive.com/]()
- Access to the testing environment is given: Username : Admin | Password : admin123
- Cycle summary was created
- Test cases were added to the cycle summary
- Postman collection with the dependents API methods was created
- Authorization token was created for accessing the API

## 1.6 Test Execution
- Test cases are executed on the created test Cycle summary: [Dependents_cycle_summary_execution.pdf]()
- Bugs have been created based on the failed tests. The complete bug reports can be found here: [Dependents_created_bugs.pdf]()
  - Date format is not dd/mm/yyyy
  - Future "Date of Birth" can be selected from calendar
  - Only 50 characters are allowed for "Please Specify" field
  - Only 50 characters are allowed for "Name" field
  - Relationship "parent" is missing
- API tests are executed based on the checklist. The collection used can be found here: [JSON file with the collection of requests created for the Dependents API]()
- Full regression testing is needed after the bugs are fixed

## 1.7 Test Completion
- As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
- The traceability matrix was generated and can be found here: [Traceability_matrix.csv]()
- Test execution chart was generated, the final report shows that a number 5 tests have failed of a total of 23
- A number of 23 test cases were planned for execution and all of them were executed
- A number of 5 total bugs were found, from which the priority is: 1 is high, 4 are medium and 1 is low

# 2 SQL section
Created a database named 'orangehrm' and a table named 'dependents' with all the columns needed to save data per specifications. Performed different queries inside the sql file: [dependents.sql]()

