Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

Part II
2. The value returned is 0 cents.
3. Even if you insert a lot of money into the machine, as soon as you print a ticket, the balance returns to 0. There are no refunds, even if you insert more money than for one ticket. Even if there isn't enough money in the balance, a ticket will still be printed and the balance returns to 0.
5. Between the tickets of the two TicketMachine objects, the only difference is the price. One ticket will have the price of the first ticket, while the other has the price of the second ticket(ex:10 cents and 85 cents respectively).

6. For the Student class: public class Student
   For the LabClass class: public class LabClass
7. Yes, it does matter. 
-Do you notice a change in the class diagram?
   When you switch "class" and "public"'s places, the diagram for the TicketMachine class becomes hatched in red.
-What error message do you get when you now press the Compile button? Do you think this message clearly explains what is wrong?
   The messages " identifier expected"(between class and public) and "class, interface, enum or record expected"(between public and TicketMachine). It mildly explains what is wrong. The "identifier" I'm assuming is the visibility modifier, since it is usually first. The "class, interface, enum or record expected" is asking for a class to be put between "public" and "TicketMachine".
8. Yes, it is possible to remove "public".
9. No, it isn't possible to remove "class"(error message: "class, interface, enum or record expected").

10.  
11.
12.private int count; = int
   private Student representative; = string
   private Server host; = string
13.private boolean alive; = life
   private Person tutor; = job
   private Game game; =
14. Student, Server, Person, Game.
15. Yes, the order does matter. Once again, the diagram is hatched in red and it won't let you creat a new object.
16. Yes, it is important to put a semicolon at the end of a field.

17. private int status;
18. The Student class.
19. It has 2 parameters(String title, double price) and their types are respectively string and int.
20. Yes?
   -private String title;
   -private int price;
21. name = petsName 
22. Public Date (stringMonth, int day, int year)
23. Header: one says getPrice and the other says getBalance. 
    Body: One is asking to return the price of a ticket, the other one is asking to return the amount of money in the balance for the next ticket.
24. "How much money do I have left?"
25. No, the return statement doesn't need to be changed. It tells me that the names of the header and the accessor method aren't really important, since the method "return balance" will work even if the header says "public int getAnything". It's more for consistency.

27. The error message is "missing return statement".
28.
29.
30.
31.
32.

