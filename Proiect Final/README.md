# Proiect-practic-testare-manuala
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

Application under test: [JpetStore Demo](https://jpetstore.aspectran.com/catalog/)




Tools used: Jira, Zephyr Squad.

# Functional specifications
The below story was created in Jira and describes the functional specifications of the "Product" module, for which the final project is performed upon.

![story](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/assets/133696127/408925a7-ceef-40de-9311-d313033be739)

# 1 Testing section
## 1.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

**Roles asigned to the project and persons allocated**

- Project manager - Andrei Popescu
- Product owner - Madalina Gheorghe
- Software developer - Gabriel Tomescu
- QA Engineer - Adina Anghel

**1.1.2 Entry criteria defined**

- functional specifications are defined
- roles needed for the project are allocated.
- initial project risks were detected and mitigated.
- test schedule is prepared.
- the test plan must be created.
- input requirements must be met.

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
  
- Poor communication and collaboration between team members, stakeholders or external suppliers can lead to misunderstandings, delays and rework.
- Lack of Testing: Insufficient testing can result in undiscovered bugs and issues that may surface after the site's launch.

- Lack of user involvement: Inadequate user feedback and involvement during the development process can result in a site that does not meet users' needs.
- Budget Overruns: Unexpected expenses can strain the project budget, potentially requiring trade-offs in features or quality.

  
 Product risks:
  
- Payment Processing Issues: If there are any flaws in the payment processing system, it could lead to financial losses for both the customers and the business. Issues like transaction failures or unauthorized access to payment details are significant concerns.
- Management of returns and refunds: Complicated handling of returns and refunds might result in irate customers and monetary losses.
- Reputation Management: Negative reviews or social media backlash due to any of the above issues can harm the reputation of the business.
- Website performance: Poor website performance, such as long loading times or problems, can annoy visitors and cost businesses sales.

**1.1.6 Evaluating entry criteria**

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control
This is the execution report that was generated after running the tests.

![monitoring control](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/assets/133696127/c5bfbca4-bc64-41b9-889c-48d8b95569d9)


## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Products module. The following test conditions were found:

-Verify that if all fields are left blank an error message will be displayed.

-Verify that a new user can create an account ussing all fields

-Verify that the required/mandatory fields are marked with the ‘*’ symbol

-Verify that a validation message is displayed when an incorrect email format is used.

-Verify that the user cannot create an account by filling out only the email input field

-Verify that the checkboxes from the profil information section are working.

-Verify that a new user can choose a language from the dropdown menu.

-Verify that a registered user cannot create another account using the same email address. 

-Verify that a new user cannot create a password using just letters.

-Check the Enter button.

-Verify that a confirmation message or email is sent to the user after successful account creation.

-Verify whether shopping cart icon is clickable.

-Check whether the subtotal is getting changed when the user removes any item from the cart.

-Verify that the user is redirected to the checkout page after clicking on the “Proceed to checkout “button.

-Verify that the user is able to change the number of items from the cart.

-Verify if the cart is editable then check that the user is able to enter special characters.

-Verify that the products remain in the shopping cart after the user close the browser and reopen the same site.

-Verify that the user can add the same product in the shopping cart,after entering a negative value in the "Quantity"input field.

-Check whether the user is able to add the item to the cart.

-Verify that the user is able to proceed with a negative number like (-1,-2,-3….) 

-Verify that only registered users are allowed to access the Checkout Address Page.

-Verify that Next Button and Cancel Button are available in the Checkout Address Page.

-Verify that Name, Street Address, City, State, Country, Postal code is the mandatory field in the Checkout Address page (Billing Address).

-Verify that error message is displayed when the user enters invalid values in all the fields in the checkout  page.

-Verify that images of products are  displayed correctly.

-Verify that the prices are displayed correctly.

-Verify the search bar functionality when using a valid value.

-Verify that production stock information are displayed.

## 1.4 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.

**Test cases:**
![Test Case nou](
https://github.com/IamCharlie24/Manual-Testing-Project/assets/133395092/15b08de3-038d-4a7a-b8ff-2c2089226fed)



The test cases with steps can be viewed here: [JPetStore_test_cases.pdf](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/Test%20Case%20Report.csv)



## 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Testing environment is up and running: [JPetStore](https://jpetstore.aspectran.com/catalog/)
- Access to the testing environment is given: Username : Adina2711 | Password : Anaaremere23!
- Cycle summary was created
- Test cases were added to the cycle summary


## 1.6 Test Execution
- Test cases are executed on the created test Cycle summary: [JPetStore_cycle_summary_execution.pdf](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/Cycle_summary.pdf)
- Bugs have been created based on the failed tests. The complete bug reports can be found here: [JPetStore_created_bugs.pdf](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/Bugs%20Report.pdf)
  
- Full regression testing is needed after the bugs are fixed

## 1.7 Test Completion
- As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
- The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/blob/main/Proiect%20Final/Traceability%20Matrix.xlsx)
- Test execution chart was generated, the final report shows that a number 9 tests have failed of a total of 30
- A number of 30 test cases were planned for execution and all of them were executed
- A number of 9 total bugs were found, from which the priority is: 1 are high and 8 are medium.
  ![Dashboard_Raport](
![Screenshot 2023-11-15 190519](https://github.com/Adinaadd27/Proiect-Practic-Testare-Manuala/assets/133696127/7e59deca-a14a-4f78-a9bb-0c87a4e3bab2))


