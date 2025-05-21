# Test automation questions

## Testing Basics (ISTQB related)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ What is the purpose of testing? What is not?
    It's purpose is to reveal wheter or not are there defects present, but it can't prove that there are no problems.

#### ✅ What are the testing principles?
    There are seven principles, the following are :
    -Testing shows the presence of defects.
    -Exhaustive testing is impossible.
    -Early testing.
    -Defect clustering.
    -Pesticide paradox
    -Testing is context dependent
    -Absence-of-errors fallacy
#### ✅ What is unit testing? Who is responibile to write unit tests?
     It is the testing of the smallest independetly executable code.It's the code's author or developer who's responsible for this test.
#### ✅ What are Test Levels, what is the difference between them?
    There are 4 different test levels:
    -Unit(component) testing
    -Integration testing
    -System testing
    -Acceptance testing
    Each level of testing reveals a different set of problems.
#### ✅ What is the difference between verification and validation?
    Verification checks if the product is being built correctly.
    Ensures the product meets the design specifications and requirements.
    Example methods: Reviews, inspections, walkthroughs.
    Focuses on static testing techniques.
    While Validation checks if the right product is being built.
    Ensures the product fulfills the intended use and user requirements.
    Example methods: Functional testing, system testing, UAT.
    Focuses on dynamic testing techniques.
#### ✅ What are Testing Types, what is the difference between them?
    Functional Testing: Validates the functionality of the software against requirements.
    Non-Functional Testing: Focuses on aspects like performance, usability, security, scalability.
    Regression Testing: Ensures existing functionality works after changes.
    Acceptance Testing: Confirms the product meets business needs.
    Exploratory Testing: Simultaneously learning, designing, and executing tests.

    Functional ensures correctness; non-functional ensures robustness and usability.
    Static involves code review; dynamic involves actual execution.
    Manual relies on human execution; automation uses tools/scripts.
#### ✅ What is the difference between white box, grey boy and black box testing?
    White Box Testing is when the tester has full knowledge of the system's internal structure.
    Focuses on code coverage, paths, and conditions.
    Examples: Unit testing, code reviews.

    Grey Box Testing when the tester has partial knowledge of the system's internal workings.
    Combines black-box techniques with some internal insights.
    Examples: Integration testing, penetration testing.

    Black Box Testing when the tester has no knowledge of the internal structure.
    Focuses on inputs, outputs, and user-facing functionality.
    Examples: Functional testing, UAT.
#### ✅ What is the difference between UAT (User Acceptance Testing) and System testing?
    UAT (User Acceptance Testing) focuses on ensuring that the software meets business needs and requirements.
    It is performed by End-users or business stakeholders.
    In an environment that Closely mimics the production environment.
    With the goal of validating real-world usability.

    System Testing Focuses on verifying the system's compliance with technical and functional specifications.
    It is Performed by QA testers.
    In a Controlled test environment.
    With the goal of finding bugs and ensuring complete system functionality.
#### ✅ Mention the differences between Regression Testing, Smoke Testing and Retesting?
    Regression Testing ensures no new bugs were introduced after changes
    Smoke Testing is a Quick test of basic functionality to check if the build is testable.
    Retesting Verifies fixes for specific defects.
#### ✅ What is the difference between Static and Dynamic Testing?
    Static Testing involves reviewing documents and code without execution.
    It is cost-effective for finding defects early.

    Dynamic Testing involves executing the code or application.
    It Identifies issues in runtime behavior.
#### ✅ Compare V-modell, Waterfall, Agile from testing perspective!
<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">


    The V-modell's zesting begins early in parallel with development.And it's less flexible, following rigid phases.
        
    The Waterfall's Testing occurs only after development phases.With very rigid, sequential phases.
    
    Agile testing has very rigid, sequential  phases. With high flexibility, and adaption to changes.


## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ What steps would you follow when you find a defect?
    First, identify and verify the bug by ensuring it's a real issue and not a user error. Then, create a clear and concise title, followed by a detailed description of the bug, including how to reproduce it, the expected vs. actual behavior, and any error messages or logs. Finally, categorize the bug by severity and priority, and provide any additional context. 
#### ✅ Talk about common test reports, and about their details.
    Test Summary Report:
    -Provides a high-level overview of the entire testing process, including objectives,         methodologies, and overall results. 
   
    Bug Report/Error Report:
    -Details specific bugs found during testing, including their identifier, description, severity, priority, reproduction instructions, and current status. 
   
    Test Cycle Report: 
    -Documents the outcome of testing activities during each test cycle, helping monitor the application's health as it progresses through various testing levels.
  
#### ✅ What does a bug report contains?
    A bug report includes information such as a description of the issue, steps to reproduce it, the expected and actual outcomes, and details about the environment in which the bug was found.

#### ✅ How would you prioritize a bug?
    Assessing their severity and impact on users, Determine the frequency of occurrence, and business criticality.

## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Which testcases should be automated and which shouldn't?
    Test cases that are frequently repeated, prone to human error, involve large data sets, or require predictable results should be automated.
#### ✅ Describe a good automated test!
    The tests must be self-evaluative so that they can detect and report errors without manual inspection. The tests must be repeatable so that they can be run multiple times with the same results. Each test should be independent so that it can run by itself.
#### ✅ What is Selenium, Selenium IDE, Selenium WebDriver?
    -Selenium is an open-source framework used to automate web browser testing.
    -Selenium IDE is a browser extension that simplifies web application testing by allowing users to record and playback their interactions with a website.
    -Selenium WebDriver is a web framework that permits you to execute cross-browser tests. 
#### ✅ How can be web elements indentified?
    Common methods include using the element's ID, name, class, XPath, CSS selectors, tag name, and link text. Locators like "By.id()" and "By.className()" are commonly used in testing frameworks.
#### ✅ How can you wait for elements, what can go wrong? Collect possible errors and root causes.
    Using the Promise, await and async functions in conjunction with setTimeout() . 
#### ✅ Compare POM and Keyword Driven Testing!
    POM emphasizes a structured approach to organizing code and locators, while keyword-driven testing emphasizes a more abstract and flexible test design, allowing non-technical stakeholders to contribute to test case creation. 
#### ✅ Whats the difference between TDD and BDD?
    The primary differences between TDD and BDD lie in what is being tested and how. BDD predominantly focuses on the end user’s standpoint in its testing of the application behavior, whereas TDD focuses on smaller sections of functionality to be tested by itself.
#### ✅ What is API testing and why would you use that?
    API testing is a type of software testing that analyzes an application programming interface (API) to verify that it fulfills its expected functionality, security, performance and reliability.
#### ✅ What is Data Driven Testing and why is it useful?
    Data-driven testing is data that is external to your functional tests, and is loaded and used to extend your automated test cases.