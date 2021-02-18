# Black Box and Transparent Box Testing

# What is the difference between Black Box testing and Transparent box testing

Black Box is high level testing focused on testing the software from an external user prespective. It is a testing approach used to test software without the knowledge of the internal workings of an application.

Transparent Box requires a knowledge of the internal workings of the program and tests the internal structure of the program.

| Parameter            | Black Box                                                            | Transparent Box                                                |
|----------------------|----------------------------------------------------------------------|----------------------------------------------------------------|
| Usage                | High level testing like User Acceptance Testing                      | Low level testing like Unit Testing                            |
| Automation           | Hard to automate without programming knowledge                       | Easy to automate                                               |
| Objective            | Test the functionality of the application                            | Test the code of the application                               |
| Basis for test cases | Requirement specification document                                   | Detail design document                                         |
| Tested by	           | End user, the Product team, developer, and QA 	                      | QA and developers                                              |
| Drawbacks            | Frequently update testing script if functionality updates often      | Tests can become outdated with frequent code updates           |
| Benefits             | Can test large swaths of code                                        | Can ensure existing code isn't negatively impacted by new code |
| Benefits (2)         | Make sure feature meets requirements                                 | Can ensure code being develop meets requirements               |