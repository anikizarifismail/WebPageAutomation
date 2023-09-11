# WebPageAutomation
Included in the zip file is the solution, packages and source code required to solve the given assignment.

## Concerns
When the solution is executed for the first time, the web page may require authentication that the user is not a bot. 
At that point, a user intervention would be required to allow for the script to pass by rerunning so that the web page would bypass the authentication required.

## Decisions
The automation would invoke the use of reusable web page elements such as search bars, user preferences page and a simple validation.
The search query bar and user preferences webpage elements often appears on each interaction of the website. 
Hence, creating page abstractions will help reduce time to automate similar scripts in the future.

The validation on the price of queried items can also be made reusable by allowing scripter to select which element to be selected within the page.
For the purpose of this assignment, I have this simple by creating a method to select the first item price after query.

## How to execute
1. Unzip project
2. Open project/solution within Visual Studio
3. Execute AmazonWebTest.cs/AmazonWebPageAutomation.sln
