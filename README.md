Download Link: https://assignmentchef.com/product/solved-cse271-lab-5-implement-two-of-your-own-inheritance-hierarchies
<br>



For today’s lab you will be implementing two of your own inheritance hierarchies. It is a smaller/simpler lab, with an earlier deadline. The expectation being that you will also use this time to start your Project #1.

Part 1

Implement a superclass <sub>Person</sub>.

Make two classes, <sub>Student</sub> and <sub>Instructor</sub>, that inherit from <sub>Person</sub>.

<ul>

 <li>A person has a name and a year of birth (2 points)</li>

 <li>A student has a major (2 points)</li>

 <li>An instructor has a salary (2 points)</li>

</ul>




Write

<ul>

 <li>The class declarations (1 point each x 3 = 3 points)</li>

 <li>The appropriate constructors (2 points each for sub x 1, 1 point for super= 5 points) o Make one for each class that initializes all the data and utilizes the “Super(…)” constructor appropriately.

  <ul>

   <li>That is, the student and instructor constructors will call the super constructor with the appropriate data to initialize the person’s instance variables.</li>

   <li>For example, the student and instructor constructors will need the information necessary (parameters) that includes person information</li>

  </ul></li>

 <li>The (appropriate and overridden) <sub>toString</sub> methods for all classes. (3 points) o For each class’ implementation of <sub>toString</sub>, use (extend) behavior from each super class’ toString’s method in order to avoid duplicate code (Negative points for duplicate code)!</li>

 <li>Getters and Setters (Negative points if done wrong)</li>

</ul>




Supply a single test program that tests these classes and methods, including the constructors. (2 points)




Part 2




<ul>

 <li>Make a class <sub>Employee</sub> with a name and salary. (2 points)</li>

 <li>Make a class Manager that extends Employee.

  <ul>

   <li>Add an instance variable for type <sub>Manager</sub>, named <sub>department</sub>, of type String.</li>

  </ul></li>

</ul>

(4 points)

<ul>

 <li>Make a class <sub>Executive</sub> inherit from <sub>Manager</sub>.

  <ul>

   <li>An Executive has a String that represents their office location. (3 points)</li>

  </ul></li>

 <li>Implement the appropriate constructors (2 points each for sub x 1, 1 point for super= 5 points) o Make one for each class that initializes all the data and utilizes the “super(…)” constructor appropriately.

  <ul>

   <li>That is, the Manager constructor will call the super constructor with the appropriate data to initialize the Employee’s instance variables. Same for executive.</li>

  </ul></li>

 <li>Supply appropriate <sub>toString</sub> methods for all classes. (4 points)  o For each implementation of <sub>toString</sub>, use (extend) behavior from each super class’ toString’s method in order to avoid duplicate code. (Negative points if not done)

  <ul>

   <li>For example, override the method <sub>toString</sub> to print the Manager’s name, department, and salary.</li>

   <li>The Executive toString will include Manager and Employee information as well.</li>

  </ul></li>

 <li>Include Getters and Setters (Negative points if done wrong)</li>

</ul>




Supply a single test program that tests these classes and methods, including the constructors. (2 points)

<h1>Tips and Additional Requirements</h1>

<ul>

 <li>You do not have to test your getters and setters.</li>

 <li>You do have to test your constructors. You can do that by

  <ol>

   <li>Creating the object</li>

   <li>Testing that the instance variables were set correctly by the constructor. You can do this using the getters and setters.</li>

  </ol></li>

</ul>

You need not use the automated/generated “toString” text that Eclipse provides. You can change it in your various classes to be something more aesthetically pleasing, for example,

“I am a student majoring in X.  I am also a Person whose name is A and was born in B.”

All we will be checking for is that you output all the information at each level and use the super call appropriately.