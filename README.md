## Table of contents
* [Goals](#goals)
* [Assets](#assets)
* [Project structure](#project_structure)

# naming-conventions
Naming Conventions
 
**Goals**
* To reduce the effort needed to read and understand source code;
* To enable code reviews to focus on more important issues than arguing over syntax and naming standards.
* To enable code quality review tools to focus their reporting mainly on significant issues other than syntax and style preferences.
 
**Assets**
 
*	Artifacts

* Project structure

* Flow names

* API fragments (Data types, traits, resource types, field names)

* Project resources (dataweave, sql)

* Test resources (Test suites, mocks files, asserts files)
 
Example:

Artifacts
 
Name must follow:

[system/process]-[layer]-[type]
Example:

mainframe-system-api

accounts-process-api

 
**Project structure**
 ```
src/
   /main/app/
  	global.xml
  	main.xml
  	errors.xml
  	flows.xml
   /main/api/
   	/data-types/
   	/resource-types/
   	/traits/
   	/security-schemas/
   	/examples/
   /main/resources/
  	/sql
  	/dw
   pom.xml
 ```
**Flow names**
 
Flow names should follow camel case

[purpose] [Flow/Subflow]

Example: getAccountsFlow

 
**Project resources**

Dataweave files names must be hyphen separated

Example: combine-users-accounts.dwl
 
**Test resources**

File names must be hyphen separated
 

