# Grazioso
<h1> SNHU IT.145 Module Five Milestone </h1>

<h2>Overview</h2>

<p>Nearly every Java application involves multiple classes. As you have learned, designing a program around classes and objects is a key feature of object-oriented programming and provides many benefits, such as more readable and maintainable code. However, it is not enough to just have multiple classes. You also need to make sure that these classes can work together within a program. This involves making sure that any relationships, such as inheritance, are properly implemented in the code. It also involves having a main() method, usually located in a special class called the “Driver” class, that runs the program.</p>

<p>In this assignment, you will gain experience putting together a multiple-class program by creating a class that inherits from another (existing) class, and modifying or implementing methods in the Driver class. This milestone will also give you the opportunity to begin coding a part of the solution for Project Two. This will allow you to get feedback on your work before you complete the full project in Module Seven.</p>

<h2>Prompt</h2>

<ol>
  <li>To gain a clear understanding of the client’s requirements, review the Grazioso Salvare Specification Document. As you read, pay close attention to the attributes and methods that you will need to implement into the program.</li?
  <li>The Grazioso.zip folder contains three starter code files: Driver.java, RescueAnimal.java, and Dog.java. Once you have uploaded the files, compile the code. Although the program is not complete, it should compile without error.</li>
  <li>Read through the code for each class that you have been given. This will help you understand what code has been created and what code must be modified or created to meet the requirements.</li>
  <li>You have been asked to demonstrate industry standard best practices in all the code that you create to ensure clarity, consistency, and efficiency among all software developers working on the program. In your code for each class, be sure to include the following:
      <ul>
        <li><b>In-line comments that denote your changes and briefly describe the functionality of each method or element of the class.</b></li>
        <li><b>Appropriate variable and method naming conventions.</b></li>
      </ul>
  <li>In a new Java file, create the Monkey class, using the specification document as a guide. The Monkey class must do the following:
    <ul>
      <li><b>Inherit</b> from the RescueAnimal class.</li>
      <li><b>Implement all attributes</b> to meet the specifications.</li>
      <li><b>Include a constructor.</b> You may use a default constructor. To score “exemplary” on this criterion, you must include the more detailed constructor that takes all values for the attributes and sets them. Refer to the constructor in the Dog class for an example.</li>
      <li><b>Include accessors and mutators</b> for all implemented attributes.</li>
    </ul>
  </li>
  <li>In the Driver.java class, modify the main method. In main(), you must <b>create a menu loop that does the following:</b>
    <ul>
       <li><b>Displays the menu</b> by calling the displayMenu method. This method is in the Driver.java class.</li>
       <li><b>Prompts the user for input.</b></li>
       <li><b>Takes the appropriate action</b> based on the value that the user entered.</li>
     </ul>

  <p><b>IMPORTANT:</b> You do not need to complete all of the methods included in the menu for this milestone. Simple placeholder print statements for these methods have been included in the starter code so that you can test your menu functionality.</p>
  </li>
  <li>Next, you will need to <b>create a monkey ArrayList</b> in the Driver.java class. Refer to the dog ArrayList, which is included right before main(), as an example. Creating this ArrayList is necessary for the intakeNewMonkey() method, which you will implement in the next step. Though it is not required, it may be helpful to pre-populate your ArrayList with a few test monkey objects in the initializeMonkeyList() method.</li>
  <li>Finally, you will <b>implement the intakeNewMonkey() method</b> in the Driver.java class. Your completed method should do the following:
    <ul>
      <li><b>Prompt the user for input.</b></li>
      <li><b>Set data for all attributes based on user input.</b></li>
      <li><b>Add the newly instantiated monkey to an ArrayList.</b></li>
    </ul>
    <p>Tips: Remember to refer to the accessors and mutators in your Monkey and RescueAnimal classes as you create this method. Additionally, you should use the nextLine method of the scanner to receive the user’s input. Refer back to Section 1.15 in zyBooks for a refresher on how to use this method.</p>

