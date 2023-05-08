Download Link: https://assignmentchef.com/product/solved-ticketsystem
<br>
This assignment contains elements that you have learned over the past few weeks, including:

An event planning document outlining objects, triggers, and events that will be used to drive the application.

Designing well-written and readable programs using a disciplined coding style, including documentation and indentation standards.

Demonstrating how to implement logic involving sequence, selection, and repetition using Visual Basic.

Creating useful and well-designed programs that use subroutines, functions, menus, dialog boxes, and other related form objects to solve practical business problems.

This is the second of a two (2) phase assignment. You must submit both parts as separate files for the completion of this assignment. Remember, you are only to demonstrate the menu function and not create a major database to track sales.

Ticket Seller is a new startup ticketing company. It has contracted you to develop a Visual Basic system to sell and print tickets for your local basketball arena. The system will provide sales in a Microsoft Windows environment at the ticket office. Management will use your program as a prototype for a future global ticket system. Create your own sample data for the designs. Use your creativity in this design.

The second part of the assignment is the coding phase (see Part II below). This is the actual Visual Basic code to complete the actions defined in the event planning document. For this part of the assignment, you will turn in six (6) screen shots and a copy of all the code created to implement this ticket system.

Part II: Coding Phase

The next step in the process is to take the design you created in the last phase and implement it into Visual Basic. First create the forms and drop the objects into the form. Next write the code behind the scenes to create the menus. Remember, you are only to demonstrate the menu function and not create a major database to track sales.

Create a Windows application to demonstrate the menu flow, include the following elements:

Create a main menu system for the:

setup game / ticket menu.

sell tickets menu.

reporting menu.

Create a setup subsystem to enter:

games.

dates.

prices.

seats.

Create a sell subsystem to:

display available tickets.

sell tickets and take them out of the available ticket pool.

keep track of the total sales.

provide a group discount (10 or more tickets for 1 transaction – 10% off).

Business requires two (2) new screen reports to be generated from the ticketing system. The first screen report shows the daily activity, which shows the number of tickets sold and revenue generated. The second screen report is weekly results. It has the total tickets sold, the total revenue generated, and tickets available for sale. Create a report subsystem for daily and weekly sales.

Provide a total of six (6) screen shots, one (1) for each screen including setup screen menu, main menu, sell screen, report screen menu, daily report screen, and weekly report screen.

Provide the Visual Basic code for the entire subsystem.

The specific course learning outcomes associated with this assignment are:

Apply graphical user interface design principles.

Design conditional and iteration constructs appropriate to a given programming task.

Design well-written and readable programs using a disciplined coding style, including documentation and indentation standards.

Create Visual Basic applications that deploy on multiple platforms such as Web pages, Windows, and Office environments.

Demonstrate how to implement logic involving sequence, selection, and repetition using Visual Basic.

Create useful and well-designed programs that use subroutines, functions, menus, dialog boxes, and other related form objects to solve practical business problems.

Please  user the design document to code the lab  and please Use Visual Studio 2015

Technical Design Document for Ticketing System for Basketball Arena

Program Name: Ticketing System

Description: The system will allow user to capture sales information and provide sales report in a Microsoft Windows environment at the ticket office for basketball arena. Management will use program as a prototype for a future global ticket system.

Windows Form will be used to display UI for the application and below lists different components for developing application:

Main Form: Use MenuStrip to define menu options for Setup Game, Sell Tickets, Reports and Exit; Use Buttons to open Setup Game and Sell Tickets forms in addition to select that from menu; Use PictureBox to display picture for application.

Setup Game Form: Use Textbox for getting user input; Use Button to close window

Sell Tickets Form: Use Textbox to display and get user input; Use Button to save changes and close window

Report Form: Use RadioButton to select daily or weekly report to view tickets sold at arena; Use ListBox to display daily/weekly report; Use Button to close window

Programming Conventions that will be used in the program code are as below:

Code will have a consistent look, so that readers can better focus on content, not layout.

Code will use consistent set of naming conventions in the development of the application for usability and maintaining the code

The code will be indented for better readability

The code will use one statement per line and one declaration per line

The code will use at least one blank line between method and property definitions

The code will have comments at every logical step and for every methods so the code is properly documented

The code will use Try…Catch and Using Statements while using Exception Handling

Below is the logical flow of subsystems

Setup Game or Ticket Menu subsystem: This subsystem is a must and needs to be used before any other subsystem is used. If the user is in the set-up game or ticket menu subsystem, they will be able to initialize number of games that will be played at the arena and add/update the dates, price and total seats available for each game.

Sells Ticket subsystem: This subsystem allows user to view available tickets and sell the tickets for each game. If the user is in the sells ticket subsystem, they will be to view total available tickets for next 2 months showing information one week at a time. The user will be able to sell tickets and application will update available ticket by removing the sold from the available ticket pool. Sell Ticket will keep track of total sales and provide a group discount of 10% if 10 or more tickets are sold to a customer as 1 transaction

Reports subsystem: This subsystem allows user to view daily or weekly sales report.

Below provides Graphical rendering (such as flowchart, use case), of the application components and interactions.

Main Form Flow Diagram and Screen Mockup

Setup Game Subsystem Flow Diagram

Sell Ticket Subsystem Flow Diagram and Screen Mockup

Reports Flow Diagram and Screen Mockup with Data for Daily/Weekly Report