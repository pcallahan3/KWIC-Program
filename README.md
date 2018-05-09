# KWIC-Program

1. What criteria did you use to decompose the first design? 
   In the first design I looked at how the program flowed from one method to another to see where I might be able to make changes.
   
2. What criteria did you use to decompose the second design? In the 2nd design I saw that their were multiple classes being used so I determined how their were being used together and decided to add a helper class with the outputting of the file.
   
3. Which design is more resilient to change? And why? Them more resislent design would be the second one because there is less coupling then the first one.

4. What would have to change in the first design/implementation if the file were changed out for a database? I'd create a helper method to connect to the database.

5. What would have to change in the second design/implementation if the file were changed out for a database? I'd create a class to connect to the database.

6. What would have to change in the first vs second design/implementation if we wanted to use a graphical user interface instead of the traditional console UI (System.out)? We'd have to figure out how we'd want to read the file in and output the file with GUI componments.

7. Identify another change that may happen in the future, and how does design 1 compare to design 2 when it comes to impact of the change?One change could be to extract each method into its own class and have mutiple classes interacting together.

8. Which design/implementation is easier to understand? The 2nd desing is easier to understand.

9. Which design/implementation is better performing? The 2nd one seems to be performoing better.

10. How does the principle of information hiding relate to all of this? With the 2nd design a lot of business logic concenring seperations is extracted into their own classes so that if you dont have access to view those classes then you'll essientially not know how those the progrma works.
