# videostore

The videostore example from Episode 3 of cleancoders.com. 

Based upon, but not identical to, the first chapter of Martin Fowler's classic book: Refactoring.

## Codebase
* There are three production files and one test case for the whole system
* The **Customer** class is the main meat of the project: 
  * creating a statement for a customer at a video store
  * Obviously this code has been around for some time
* The two other classes **Movie** and **Rental** don't really have any behaviour
* The testcase tests that the generated statements are correct

## Setup
* Import the profile settings profile from the idea-settings folder
* `Preferences > Inspections > Import Profile`

## Refactoring
### Updating Code from Junit3 to Junit4
* Update **VideoStoreTest** to use the more recent version of the test framework