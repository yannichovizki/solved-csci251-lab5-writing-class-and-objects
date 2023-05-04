Download Link: https://assignmentchef.com/product/solved-csci251-lab5-writing-class-and-objects
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write C++ programs that involves writing class and objects. § Write C++ programs using class associations.</li>

</ul>

<h1>Question 1 (Class and Objects)</h1>

Write a C++ program to implement a class named Troll.  The Troll class should have the following properties:

<ul>

 <li>Data fields for name, type of Troll, and age.</li>

 <li>A private static field for the Troll toll, which has an initial value of RM15.00.</li>

 <li>A default constructor.</li>

 <li>A static function to change the Troll toll that takes a new toll value as parameter.</li>

 <li>A setField() function to change the name, type, and age of a Troll. A display function to display a Trolls details and the Troll toll.</li>

</ul>

Write a main function that creates several Troll objects, set and display the information. Then change the toll value and display all the Trolls information again. A sample output may look like the following.




Boris is a Mountain troll!!

Boris is 8 years old.

The Troll toll is RM15.00.




Igor is a Forest troll!!

Igor is 100 years old.

The Troll toll is RM15.00.

Enter new value for the toll: RM30.00

Boris is a Mountain troll!!

Boris is 8 years old.

The Troll toll is RM30.00.

Igor is a Forest troll!!

Igor is 100 years old. The Troll toll is RM30.00.

<h1>Question 2 (Class Associations)<strong> </strong></h1>

For this question, you are going to write three classes and relate them through associations.

First, create a Person class that includes fields for first name, last name, and age. Include a non-default constructor and a display function.

Second, create a Date class that contains three integer data members to represent the month, day, and year. Include also a non-default constructor and a display function for this class.

Lastly, create a class called DentalAppointment. This class should have fields for patient (an object of Person class above), date of the appointment (an object of the Date class above), and the duration of the appointment in minutes. The DentalAppointment class should also have a non-default constructor that receives the details of a Person, the details of a Date, and the duration as parameters. It should also have a display function to display the details of an appointment.

Write a main() function that creates a DentalAppointment object and display the details of the appointment.