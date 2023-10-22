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
  
- data breaches, financial fraud, and challenges with regulatory compliance could occur once the website is made available to customers.
- risks to stability (crashes, disconnections, etc.).
- management of returns and refunds: Complicated handling of returns and refunds might result in irate customers and monetary losses.
- market Saturation: It may already be difficult for JPetStore to capture a sizable portion of the pet product e-commerce market due to the presence of so many rivals.
- internet Explorer versions older than 142.0.172.68 include security flaws (cross-site scripting, which allows for the theft of user data following the insertion of malicious code into a website, and exploits on the purchasing system).
- website performance: Poor website performance, such as long loading times or problems, can annoy visitors and cost businesses sales.

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

The test cases with steps can be viewed here: [Dependents_test_cases.pdf](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/JPetStore_test_cases.pdf.pdf)



## 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Testing environment is up and running: [JPetStore](https://jpetstore.aspectran.com/catalog/)
- Access to the testing environment is given: Username : Adina2711 | Password : Anaaremere23!
- Cycle summary was created
- Test cases were added to the cycle summary


## 1.6 Test Execution
- Test cases are executed on the created test Cycle summary: [Dependents_cycle_summary_execution.pdf]()
- Bugs have been created based on the failed tests. The complete bug reports can be found here: [Dependents_created_bugs.pdf](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/Dependents_created_bugs..pdf)
  - Date format is not dd/mm/yyyy
  - Future "Date of Birth" can be selected from calendar
  - Only 50 characters are allowed for "Please Specify" field
  - Only 50 characters are allowed for "Name" field
  - Relationship "parent" is missing
- API tests are executed based on the checklist. The collection used can be found here: [JSON file with the collection of requests created for the Dependents API]()
- Full regression testing is needed after the bugs are fixed

## 1.7 Test Completion
- As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
- The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/Traceability_Matrix..xlsx)
- Test execution chart was generated, the final report shows that a number 10 tests have failed of a total of 31
- A number of 31 test cases were planned for execution and all of them were executed
- A number of 10 total bugs were found, from which the priority is: 3 are high, 3 are medium and 4 are low
  ![test execution](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/assets/133696127/107c9c75-c89e-4642-adbb-8fcbeea6ae10)



