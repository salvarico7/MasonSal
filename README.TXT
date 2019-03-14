------------------------------------------------------------------------
This is the project README file. Here, you should describe your project.
Tell the reader (someone who does not know anything about this project)
all he/she needs to know. The comments should usually include at least:
------------------------------------------------------------------------

PROJECT TITLE:Coding Assignment 10: Tickets
PURPOSE OF PROJECT:
            Consider the task of representing types of tickets to campus events. Each ticket has a unique number and a price. There are three types of tickets: walk-up tickets, advance tickets, and student advance tickets.
Walk up tickets are purchased the day of the event and cost $50.
Advance tickets purchased 10 or more days before the event cost $30, and advance tickets purchased fewer than 10 days before the event cost $40.
Student advance tickets are sold at half the price of normal advance tickets: When they are purchased 10 or more days early they cost $15, and when they are purchased fewer than 10 days early they cost $20.
            Implement a class called Ticket that will serve as the superclass for all three types of tickets. Define all common operations in this class, and specify all differing operations in such a way that every subclass must implement them. No actual objects of type Ticket will be created: Each actual ticket will be an object of a subclass type. Define the following operations:
                The ability to construct a ticket by number.
                The ability to ask for a ticket’s price. 
                The ability to println a ticket object as a String.  An example String would be “Number: 17, Price: 50.0”.
            Implement a class called WalkupTicket to represent a walk-up event ticket. Walk-up tickets are also constructed by number, and they have a price of $50. 
            Implement a class called AdvanceTicket to represent tickets purchased in advance. An advance ticket is constructed with a ticket number and with the number of days in advance that the ticket was purchased. Advance tickets purchased 10 or more days before the event cost $30, and advance tickets purchased fewer than 10 days before the event cost $40.
            Implement a class called StudentAdvanceTicket to represent tickets purchased in advance by students. A student advance ticket is constructed with a ticket number and with the number of days in advance that the ticket was purchased. Student advance tickets purchased 10 or more days before the event cost $15, and student advance tickets purchased fewer than 10 days before the event cost $20 (half of a normal advance ticket).  When a student advance ticket is printed, the String should mention that the student must show his or her student ID (for example, “Number: 17, Price: 15.0 (ID Required)”.
VERSION or DATE: 3/14/19
HOW TO START THIS PROJECT:Use the TicketMain class below to test your code
AUTHORS:Mason Marrero and Salvador Rico
USER INSTRUCTIONS:
