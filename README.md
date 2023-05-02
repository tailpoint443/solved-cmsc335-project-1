Download Link: https://assignmentchef.com/product/solved-cmsc335-project-1
<br>
<strong>Overview </strong>

In the project you will use Java Inheritance to create a series of related classes with a “Shape” theme. Before completing this exercise, be sure to review and try the Java class and inheritance examples and materials found in this free Safari resource:

https://learning.oreilly.com/library/view/java-the-complete/9781260440249/

You should focus on Chapters 6, 7 and 8.

If you have previously signed up for the Safari account you don’t need to sign-up again. Just use this link: <a href="https://learning.oreilly.com/accounts/login/?next=/library/view/temporary-access/">https://learning.oreilly.com/accounts/login/?next=/library/view/temporary</a><a href="https://learning.oreilly.com/accounts/login/?next=/library/view/temporary-access/">–</a><a href="https://learning.oreilly.com/accounts/login/?next=/library/view/temporary-access/">access/</a>

If you have not previously requested a Safari account follow the details on this page to sign-up for your Safari Account: <a href="https://libguides.umuc.edu/safari">https://libguides.umuc.edu/safari</a>

You’ll need to sign in using your UMGC student email account. Once you sign in, you’ll have immediate access to the content, and you’ll shortly receive an e-mail from Safari prompting you to set up a password and complete your account creation (recommended).

Students: Your UMUC e-mail account is your username + @student.umuc.edu (example: <u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="fb9388949794c9bb888f8e9f9e958fd58e968e98d59e9f8e">[email protected]</a>)</u>.

<strong>Note: Be sure to review is-a and has-a class relationships prior to starting this exercise as well. </strong>

<strong>Assignment Details </strong>

Design, implement and test a Java class Inheritance hierarchy that would satisfy the following is-a and has-a relationships:

<ul>

 <li>A Shape is an object</li>

 <li>A TwoDimensionalShape is a Shape</li>

 <li>A ThreeDimensionalShape is a Shape</li>

 <li>A Circle is a TwoDimensionalShape</li>

 <li>A Square is a TwoDimensionalShape</li>

 <li>A Triangle is a TwoDimensionalShape</li>

 <li>A Rectangle is a TwoDimensionalShape</li>

 <li>A Sphere is a ThreeDimensionalShape</li>

 <li>A Cube is a ThreeDimensionalShape</li>

 <li>A Cone is a ThreeDimensionalShape</li>

 <li>A Cylinder is a ThreeDimensionalShape</li>

 <li>A Torus is a ThreeDimensionalShape</li>

 <li>A Shape has a NumberofDimensions</li>

 <li>A TwoDimensionalShape has an area</li>

 <li>A ThreeDimensionalShape has a volume</li>

</ul>

Note you should fill in additional methods and variables that make sense for each of the classes. Also some assumptions about shape types is appropriate and should be documented in the code and documents submitted. For example, type of triangle …

Create a command line driven menu that allows a user to construct each of the TwoDimensional and ThreeDimensional Shape subclasses. The menu should continue to loop prompting for a specific class and then prompt for appropriate input parameters. The values returned should be the volume or area as appropriate to the shape.  Error checks should be in developed to make sure appropriate menu items and types of data were input and prompt the user to enter to correct data. An option to exit the program should be available as well that will provide an appropriate Thank you message along with the current date and time.

The following represents a possible menu session for a user: *********Welcome to the Java OO Shapes Program **********

Select from the menu below:

<ol>

 <li>Construct a Circle</li>

 <li>Construct a Rectangle</li>

 <li>Construct a Square</li>

 <li>Construct a Triangle</li>

 <li>Construct a Sphere</li>

 <li>Construct a Cube</li>

 <li>Construct a Cone</li>

 <li>Construct a Cylinder</li>

 <li>Construct a Torus</li>

 <li>Exit the program</li>

</ol>

2

You have selected a Rectangle

What is the length?

4

What is the Width?

9.5

The area of the Rectangle is 38.

Would you like to continue? (Y or N)

3

Sorry I do not understand. Enter Y or N

Y

Select from the menu below:

<ol>

 <li>Construct a Circle</li>

 <li>Construct a Rectangle</li>

 <li>Construct a Square</li>

 <li>Construct a Triangle</li>

 <li>Construct a Sphere</li>

 <li>Construct a Cube</li>

 <li>Construct a Cone</li>

 <li>Construct a Cylinder</li>

 <li>Construct a Torus</li>

 <li>Exit the program</li>

</ol>

10

Thanks for using the program. Today is Nov 11 at 1:40 PM.




<strong>Submission Requirements: </strong>

<ol>

 <li>Submit all of your Java source files (each class should be in a separate .java file). These files should be zipped and submitted with the documentation.</li>

 <li>UML class diagram showing the type of the class relationships.</li>

 <li>Developer’s guide describing how to compile and execute the program. The guide should include a comprehensive test plan that includes evidence of testing each component of the menu with screen captures and descriptions supporting each test. Documentation includes Lessons learned.</li>

</ol>

Your compressed zip file should be submitted to the Project 1 folder in LEO no later than the due date listed in the classroom calendar.

<strong>Grading Rubric</strong>:

<table width="618">

 <tbody>

  <tr>

   <td width="144"><strong>Attribute </strong></td>

   <td width="474"><strong>Meets </strong></td>

  </tr>

  <tr>

   <td width="144">Design</td>

   <td width="474"><strong>20 points </strong>Designs a Java class Inheritance hierarchy that would satisfy the following isa and has-a relationships:•       A Shape is an object•       A TwoDimensionalShape is a Shape•       A ThreeDimensionalShape is a Shape•       A Circle is a TwoDimensionalShape•       A Square is a TwoDimensionalShape•       A Triangle is a TwoDimensionalShape•       A Rectangle is a TwoDimensionalShape•       A Sphere is a ThreeDimensionalShape•       A Cube is a ThreeDimensionalShape</td>

  </tr>

 </tbody>

</table>




<table width="618">

 <tbody>

  <tr>

   <td width="144"> </td>

   <td width="474">•       A Cone is a ThreeDimensionalShape•       A Cylinder is a ThreeDimensionalShape•       A Torus is a ThreeDimensionalShape•       A Shape has a NumberofDimensions•       A TwoDimensionalShape has an area•       A ThreeDimensionalShape has a volume<strong> </strong></td>

  </tr>

  <tr>

   <td width="144">Functionality</td>

   <td width="474"><strong>40 points </strong>Contains no coding errors. Contains no compile warnings.Creates a command line driven menu that allows a user to construct each of the TwoDimensional and ThreeDimensional Shape subclasses. The menu should continue to loop prompting for a specific class and then prompt for appropriate input parameters. The values returned should be the volume or area as appropriate to the shape. Error checks should be in developed to make sure appropriate menu items and types of data were input and prompt the user to enter to correct data. An option to exit the program should be available as well that will provide an appropriate Thank you message along with the current date and time</td>

  </tr>

  <tr>

   <td width="144">Test Data</td>

   <td width="474"><strong>20 points </strong>Tests the application using multiple and varied test cases.<strong> </strong></td>

  </tr>

  <tr>

   <td width="144">Documentation and submission</td>

   <td width="474"><strong>20 points </strong>Source code files include header comment block, including file name, date, author, purpose, appropriate comments within the code, appropriate variable and function names, correct indentation. Submission includes Java source code files, Data files used to test your program, Configuration files used. Documentation includes a UML class diagram showing the type of the class relationships. Documentation includes a user’s Guide describing of how to set up and run your application. Documentation includes a test plan with sample input and <strong><em>expected</em></strong> results, test data and results and screen snapshots of some of your test cases. Documentation includes Lessons learned. Documentation is in an acceptable format.</td>

  </tr>

  <tr>

   <td width="144"> </td>

   <td width="474">Document is well-organized.The font size should be 12 point.The page margins should be one inch.The paragraphs should be double spaced.All figures, tables, equations, and references should be properly labeled and formatted using APA style.The document should contain minimal spelling and grammatical errors.</td>

  </tr>

 </tbody>

</table>




<strong>Any submissions that do not represent work originating from the student will be submitted to the Dean’s office and evaluated for possible academic integrity violations and sanctions</strong>.


