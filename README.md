# Proiect-static-tesstare-manuala
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

Application under test: link to application

API Documentation: link to API documentation if exists or N/A

**The final project will be stplit into 2 section: [Testing section]() and  [SQL section]()**

Tools used: Jira, Zephyr Squad, Postman, My SQL Workbench.

# Functional specifications
The below story was created in Jira and describes the functional specifications of the Dependants moldule, for which the final project is performed upon

# 1 Testing section
## 1.1 Test planning

The Test Plan is designed to describe all details of testing for the Dependants module from the OrangeHRM application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

**Roles asigned to the project and persons allocated**

- Project manager - Andrei Popescu
- Product owner - Madalina Ionescu
- Software developer - Gabriela Tomescu
- QA Engineer - Iulia Albu

**1.1.2 Entry criteria defined**

- functional specifications are defined
- roles needed for the project are allocated
- initial project risks were detected and mitigated

**1.1.3 Exit criteria defined**

- number of unresolved bugs is insignificant or they have low priority
- all tests have been executed
- all resolved bugs have been re-tested and approved by the QA team
- deadline was reached
- no detected major risk remained un-mitigated
- exploratory regression testing must be performed on the My Info module, which includes the Dependents section

**1.1.4 Test scope**

- **Tests in scope**: All the feature of Dependents module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing
- **Tests not in scope**: performance testing, integrations of the dependents module with other modules, compatibility testing with multiple browsers

**1.1.5 Risks detected**

- Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial, unavailability of test environment
- Product risks: validation constraints on the fields might be too restrictive to the end-user

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



