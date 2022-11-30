## Why Automate Manual Tasks in software testing ? 
Manual software testing has been around since the sixties, and was discovered during the early days of writing software. In history one of the most recognized errors in software was “The Mariner 1 Spacecraft, 1962”. This probe barely made it out of Cape Canaveral when it went off course. The protocol for this was to self destruct the probe because it was out of control. After the investigation it showed a small code error, a hyphen was removed which interfered with the guidance signals. These incidents caused the birth of software testing. This software testing at the beginning was totally manual, from a business standpoint manual labor is very expensive. Later in the years in the 2000’s,  software testing automation took off due to the growth of websites. In 2000, there were only 17,087,182 websites and as of 2018 there were 1,630,322,579 which is a significant growth. So while website growth was impactful the industry had to solve the problem of having to test these websites this is where Quality Assurance( QA) test automation was born. Also, the constant need for quick delivery of software has made it a strong need to be able to deliver good quality assurance. 
The first attempt of automation was very functional. The framework was very Intermittent and only one person would be able to work on it and it was very difficult for another developer to configure once there was a transition in personnel. 
Many automation frameworks were around in the 90’s such as Mercury and Segue, when Selenium made its appearance in 2004. While selenium is popular, it is not the only automation tool in the ecosystem. Known automation tools that exist are Puppeteer, Cypress, WebdriverIO, Playwright and Cucumber.  Many of these frameworks have key features that others do not have. For example Puppeteer has more control over Chrome and can enable web scraping while Cypress can run tests in the browser. The framework Playwright comes with parallel browser testing capabilities vs  Cucumber that has a feature layer that helps engage business stakeholders who cannot read code. Agile software development is the new upcoming development framework that uses an iteration approach with all types of areas such as planning, analysis, design, coding, unit testing and acceptance testing. The typical length of each iteration is 2 - 4 weeks which is a short time frame.  The previous software development waterfall approach would take months in different stages which includes System and Software requirements, Analysis, Design, Coding, Testing and Operations. In the first and second phase there is a 20% - 40% time invested with 30% - 40% coding with the last is testing. The criticism is that if there is an issue found later in this process  it can potentially cost 50 to 200 percent. This is why agile development is so popular because it has shorter iterations and issues are not hidden for months. 
With Agile development there arises Behavior-driven development which is summarized as where to start and what to test and what not to test. The focus is also on how much to test on one go, what tests will be called and understand why tests failed. This development specifies desired behavior of what is being tested.  Another development process called Test-driven development  is  converting software requirements into tests. In this approach,  the developer can go off of the requirements before creation of code. All tests should be run and most should fail because things aren’t all implemented correctly. Then,  the next phase should be working with revised tests so the new code will be inline with the test requirements. This whole phase is repeated for every step mentioned above.  Test structure has four steps: setup, execution, validation and cleanup.   The first step is the setup is put Unit Under Test with execution will drive the UUT to execute it’s intended behavior and capture all of the output. The Validation step ensures that the test cases are correct. The last step is the cleanup to restore  Unit Under Tests, bringing them back to pre-test state.  These two are fairly different where BDD tests the application’s behavior based upon the user’s standpoint and TDD is more focused on isolated pieces that test the functionality. 
Many companies have many challenges when it comes to implementing automation. The expectations of 100% automation is most of the time unrealistic because areas still need human inspection instead of automation checking many areas. One of the areas that's hard to automate is accessibility. One aspect is what to automate and how much to automate? Most of the time what is automated is actions that are mundane but how much to automate is a struggle because every little action can be automated but this can bog down the framework being used. The challenge of management not having experience with test automation which can have dire consequences on the automation process not having a clear understanding of what to automate and when to automate. One of the issues is not understanding the manual and exploratory testing where this kind of testing will dig deeper into the application finding issues that automation may not find. Exploratory testing does not follow a rigid path as automation and  has advantages where testing you can pivot and not follow a projected path if some behavior is experienced. 
While there are some pros and cons to automation testing it is still worth the investment if there are the right people to manage and work on the automation project. In most cases this is a challenge for someone to come into a QA department and create automation from scratch. This is because while they can automate they also need to be familiar with the application. In my experience we hired a QA engineer and the pressure was on for him to automate our application which really caused him not to really understand the application under test and even after five years of being there he was still hesitant of how the application functioned. I still believe that some automation testing is needed to perform the mundane tasks  in testing. While some people outside of QA believe that QA doesn’t need manual testing but this has been proven wrong it is still needed and required because the customer will perform manual task in their daily usage of the application. 

**References**
- 11 of the most costly software errors in history
https://raygun.com/blog/costly-software-errors-history/

- Total number of Websites
https://www.internetlivestats.com/total-number-of-websites/ 
 
- The Evolution of Automation Testing
https://www.accelq.com/blog/testing-evolution/
 
- Selenium history
https://www.selenium.dev/history/
 
- Automation 
https://www.browserstack.com/guide/top-selenium-alternatives
 
- Waterfall model
https://en.wikipedia.org/wiki/Waterfall_model

