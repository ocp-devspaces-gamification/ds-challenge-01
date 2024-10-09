## Challenge-01

### Scenario
* This simulates the scenario of a developer who is given a task of enhancing an existing service that was created by another developer
* The challenge (pain) of understanding required extensions is borne done by the developer that is assigned this enhancement task

### Set Up + verification
* Reminder : You should have created this workspace from your teams challenges folder in source control
* Open a terminal. Run the command "chmod 755 mvnw" to change the mvnw file to be executable
* Run the quarkus application in live coding mode with the command : "./mvnw quarkus:dev"
* Select your option "y/n" to the question (if asked) : Do you agree to contribute anonymous build time data to the Quarkus community? 
* On the prompt press [r] to resume testing. This will result in an error
* Open the "src/main/java/org/acme/DateResource.java". You will observe the method "getCurrentDate" needs to be fixed.
* When you select all the code, right click and choose "Refactor"", the code does not format

### Success Criteria
* Fix the formatting by Installing Required extensions. Code is formatted with the extensions
* Restart your workspace for setting to be reflected
* Method getCurrentDate code is completed. The code should show java intellisense in action
* The live coding mode shows no errors

### Resources
* Look for hidden clue(s) in source files that can help finishing the task sooner!

### What did we learn
* Developer have challenging tasks : Example -- finding out which extensions are needed
* Unless there is a documentation and or guidance (like this scenario sections), it will be trial-and-error
* No guidance also results in lost time, productivity and delays the joy of coding
