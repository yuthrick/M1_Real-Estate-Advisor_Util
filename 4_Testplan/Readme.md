## Test Plan

## High Level Test Plan
| ID |	Description |	Expected I/P |	Expected O/P |	Actual O/P | Type of Test |
| --- | ----- | ------ | ------ | ----- | ------ |
| HP01 |	Sellers interface |	Character s |	Enters to sellers module| Pass |	Requirement |
| HP02 |	Buyers interface |	Character b |	Enters to buyers module |	Pass |	Requirement |

## Low Level Test Plan
| ID |	Description |	Expected I/P |	Expected O/P | Actual O/P |	Type of Test |
| --- | ---------- | --------- | ------ | ----- | ----- | 
| LP01 | Buyer viewing all the properties available |	Integer 1 |	Views all properties and exits |	Pass |	Requirement |
| LP02 |	Buyer views by type of property |	Integer 2 |	Views by type and asks to view another type |	Pass | 	Requirement |
| LP03 |	Buyer has an option to exit |	Integer 4 |	Exits	| Pass |	Requirement |
| LP04 |	Buyer can see total number of properties available |	Integer 3 |	2 |	2 |	Requirement |
| LP05 |	Seller can register his property |	Integer 1, Char name, Long int cmunber, Char ptype, int ext, char place, char country |	Exits after entering details |	Pass |	Requirement |
|LP06 |	 Seller can register another property |	char y |	Opens register module |	Pass |	Requirement |
|LP07 |	Seller can remove property | char name |	Removes from file |	Pass |	Requirement |
|LP08 |	Seller can modify if there are errors while entering information |	Char name |	Opens modify module |	Pass |	Requirement |
| LP09 | seller can modify another |	char y |	Modifies another information |	Pass |	Requirement |
|LP10 |	Seller can exit |Integer 4 |	Exits from module|	Pass |	Requirement |


## usage of unity frame work

* The Unity Test Framework (UTF) enables Unity users to test their code in both Edit Mode and Play Mode, and also on target platforms such as Standalone, Android, iOS, etc.

* UTF uses a Unity integration of NUnit library, which is an open-source unit testing library for .Net languages.

* It is possible to extend the Unity Test Framework (UTF) in many ways, for custom workflows for your projects and for other packages to build on top of UTF.

## Best Practices
 - [x] Checked all the possibilities of output
 - [x] Mentioned all the inputs for better understanding
 - [x] Presented in tabular form for easy understanding
 - [x] Both High level and low level Test plans are shown
