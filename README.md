Download Link: https://assignmentchef.com/product/solved-solvedproject-2-generics-linked-lists-stacks-and-apps
<br>
1. OverviewThe goals of this project are to ensure that students can do the following:

· Create a runnable application that uses a Queue

· Implement a Stack ADT

· Implement a Linked List and use it in a runnable application

· Set up a unit testing environment and run unit tests which validate and verify program integrity

· Write Java code that adheres to best practices (e.g. abstraction) and OOP

· Analyze the efficiency of all non-test code using Big-O notation.

In order to achieve these goals, students will create 3 programs:

1. A supermarket simulation that uses a Queue class to model lines of customers in a supermarket

2. A simple generic implementation of a Stack ADT

3. A game simulation that is similar to duck-duck-goose

Unit TestingThis project requires that for each part you must run the included unit tests to validate and verify the correctness and integrity of your programs, as well as to drive a test-driven development approach. Remember that test-driven development means that test and compilation errors are not necessarily a bad thing; you should use them as an indication of you what code you need to create or fix next.

Start by downloading the interface and unit tests files provided for this assignment and setting-up JUnit for your specific Java development setup. Below are some quick tips for getting started running JUnit tests in several common development setups.

IntelliJ:· Create a new project and add the interface and test files to the src directory

· Open up one of the test files from within IntelliJ and click on one of the lines underlined with an error

· Press alt+enter (option+enter on mac) and select the option to import the JUnit library into your project

· You should now be able to run each of the tests (right-click the file and choose run), or all of the tests (right-click on the project and choose to run all tests) once you create the classes required for this project

Eclipse· Create a new project and add the interface and test files to the project src directory (you might need to right-click and refresh the src icon in Eclipse)

· Right-click on the project in the Package Explorer panel, go to Build Path-Add Libraries, and select JUnit

· You should now be able to run the unit tests by right-clicking on the project or test files under Project Explorer, or by going to the run-run as menu

Command LineFor a command line development environment, you will need to perform several steps:

· Download the required JUnit JAR files to your project directory

· Add the JAR files to your project class path when compiling and running

· Create your own driver class (a class with a main method) to run the tests and print out the results

2. InstructionsYou must implement the indicated interfaces as directed in the directions below. You may NOT modify any aspect of the interface files and you must implement each method as described by the interface if you wish to receive full credit.

Part I – Supermarket SimulationQueues are often used to simulate the linear flow of people, cars, airplanes, transactions, and so on. Create a program that models the checkout lines at a supermarket following the following instructions.

SupermarketCheckouts.java

1. Create a SupermarketCheckouts.java class to simulate the operation of checkout lines at a supermarket. Your class must implement the provided Supermarket.java interface according to the requirements outlined in the comments of the interface file

2. Note that the SupermarketCheckouts constructor should create an empty supermarket object; the buildMarket method is what is called to create the checkout lines, etc.

3. Your SupermarketCheckouts.java class should use or adapt your Queue class from Project 1 to model a checkout line. If you were unable to complete this class, then adapt the code given in the book and cite the book as a source in your project write-up

4. Run the unit tests provided in SupermarketCheckoutsTest.java to ensure that your code is fully functional. Include a screenshot of the final output of your unit tests in the write-up

SupermarketApp.java

5. Write a runnable application class called SupermarketApp.java that provides a user interface to your simulation. It should take in two parameters as input from the user: the number of clerks (checkout lines) in the supermarket simulation, and the maximum length of a checkout lines. This class should then repeatedly prompt the user for input about how to next proceed with the simulation:

· Display the lines

· Simulate a minute of time passing (tick)

· Add a new customer into a queue

· Quit the simulation

6. Take two screenshots of your supermarket application running and add them to your write-up.

Part II – Generic StackImplement a Stack ADT according to the following requirements

SimpleStack.java (and supporting classes)

1. Implement a generic (using Java Generics) Stack class (SimpleStack.java) that implements the provided Stack.java interface according to the method descriptions in the comments of the interface file.

2. Your Stack class may be implemented with an array or with another ADT (e.g. a LinkedList class) as long as it is generic and you write it all yourself. You may NOT use anything provided by Java (such as the LinkedList or ArrayList classes) other than arrays.

3. Run the unit tests provided in SimpleStackTest.java to ensure that your stack implementation is fully functional. Include a screenshot of the final output of your unit tests in the write-up.

Part III – Elimination Game SimulatorSuppose there is a game that exists with the goal of being the last person eliminated from a group. The way the game works is:

1. All players form a circle with one person chosen as the starting point

2. An elimination number is randomly chosen (A positive integer greater than 0)

3. Starting with the starting point, players count off in a clock-wise fashion up to the elimination number

4. When the count-off reaches the elimination number, that player is eliminated

5. The count begins again at 1 with the next player in the circle (i.e. the next player clockwise from the player who was eliminated).

6. The last person in the circle wins the event.

Think of Duck-duck-goose without the chasing. Design and implement an application to simulate this game according to the following requirements.

EliminationApp.java

1. Implement a generic circular singly-linked list. There is no interface that you must implement so use any helper classes and names that you deem necessary. However, make sure to follow good programming practices.

2. Create an EliminationApp.java class that runs this elimination game simulation. The class must implement the Elimination.java interface to support the simulation methods as described in the interface file.

3. You must use your circular, singly-linked linked list as the underlying structure for this simulation

4. Players should have a name (a String) that represents their original position in the circle using the following convention: “player” plus position (e.g., “player1”, “player2”, etc.)

5. The output from your application should be the list of players eliminated (in order of elimination) as well as the name of the last player remaining.

6. Run the unit tests provided in EliminationAppTest.java to ensure that your simulation is fully functional. Include a screenshot of the final output of these tests in your write-up

7. Take a screenshot of your simulation output and submit it with your write-up.

3. Writeup and Submission· For each part of the project, describe your approach, solutions, describe any difficulties that you encountered, and detail the efficiency of all non-test methods in your code using Big-O notation. Include any requested output and screenshots for each part.

· Add all of your .java files and your write-up document to a .zip or .tar.gz archive and submit it on Bb Learn

· You must write and submit your own code. You must also clearly identify and online or text sources that you used as references, any collaborators with which you discussed the project (or lack thereof), and how the source was beneficial.

4. Grading (100 pts)20 points – Design and Code Quality

These points will be assigned according to the quality of your code:

· Good object-oriented design, consistent comments, white space, indentation, etc.

60 points – Implementation and Write-up

These points will be assigned according to the output of the unit tests, the output in the screenshots, and following the requirements (correctly implementing the interfaces, using generics, etc…)

· 20 pts – Part I: Supermarket Simulation

· 20 pts – Part II: Generic Stack using a circularly linked list

· 20pts – Part III: Elimination Contest Application

20pts – Write Up and Submission

These points will be assigned according to your inclusion of the required information and correctly identifying the complexity of each of your methods.

IN NEED of othe CS 249 projects and assignments please follow and inbox me for discounted solutions as a package