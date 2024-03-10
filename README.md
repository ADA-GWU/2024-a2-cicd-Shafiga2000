
<h1>Introduction to the Application</h1>
This project is a Student Management System designed to add, update, and assign students to different courses. It provides functionalities to manage student information such as ID, first name, last name, and email. The main purpose of Assignment – To write Tests for it.<br>

<h2>Download the Project</h2>
To get the project, you can either clone the repository using Git:
1.git clone https://github.com/ADA-GWU/2024-a2-cicd-Shafiga2000.git 
2.download the project as a ZIP file and extract it.<br>

<h2>Prerequisites</h2>
Before running the Spring Boot application, it is needed to be installed:
•	Java Development Kit (JDK)
•	Maven
•	Visual Studio Code or IntelliJ IDEA<br>

<h2>Running the Application Tests</h2>
1.The tests can be run via terminal using the following commands inside the project:
mvn clean package or mvn test ( Tests results will be visible and BUILD SUCCESS will be shown)

2.Open the project via tool as Visual Studio Code or  IntelliJ IDEA . You can run tests from files in the test/config folder.

<h3>Functionality Tests<h3>
<p>To run functionality tests, navigate to the FunctionalityTests class. You can run all tests by selecting the sign which is located on left side from class , click and choose appropriate option or using the shortcut Ctrl + Shift + F10.</p>
Tests included:<br>
•	Test finding a student by ID<br>
•	Search by first or last name<br>
•	Test save a student – added by me<br>
<h3>Unit Tests</h3>
<p>To run unit tests, navigate to the UnitTests class. You can run all tests by selecting the sign which is located on left side from class , click and choose appropriate option or using the shortcut Ctrl + Shift + F10.</p>
Tests included:<br>
•	The number of courses shall correspond to the added courses<br>
•	The total credits shall correspond to the sum of the added credits <br>

<h3>Web Interface Tests</h3>
In case , you want to see visually , you need to navigate to the file called SeleniumConfig in the folder test/config , and change last part to this:<br>
WebDriverManager.firefoxdriver().setup();<br>
 //return new FirefoxDriver(options);<br>
return new FirefoxDriver();<br>

To run web interface tests, navigate to the WebInterfaceTests class. You can run all tests by selecting the appropriate option or using the shortcut Ctrl + Shift + F10.<br>
Tests included:<br>
•	Create a user<br>
•	Check the created user<br>
•	Get Student by ID – added by me
