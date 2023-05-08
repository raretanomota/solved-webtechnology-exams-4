Download Link: https://assignmentchef.com/product/solved-web_technology-exams-4
<br>
<strong>Question 1 </strong>​​Create a webpage Question1.html.

On the webpage, display the following information about yourself and this subject.

(Note: you must use ​<strong>your own information</strong>​ and ​<strong>correct subject information</strong>​).

<strong>Question 2 </strong>​​<strong>. </strong>​Create a webpage Question2.html.

On the website, use ​<strong>your own full name</strong>​ and ​<strong>student number</strong>​ to display the following. (Here is an example of student name “John Smith” and student number “9610514”)

<strong>    </strong>

<strong>Question 3 </strong><strong>.</strong>​ Write​ an XML document called Question3.xml that represents the following player record and the XML must contain <strong>internal DTD</strong>​ .​

<strong>          </strong>

<strong>Question 4</strong><strong>. </strong>​ Create a webpage Question4.html.​

The web page should display 2 buttons “Start Animation” and “Stop Animation”.




Whenever the button “Start Animation” is clicked, every second, the website displays an equation based on your student number. The example below illustrates how the animation should work:

<ul>

 <li>Suppose that your student number is 9610514, then in the animation, the web page first displays the equation 9610514 + 1 = 9610515</li>

 <li>Then a second later, the equation becomes 9610514 + 2 = 9610516</li>

 <li>Then a second later, the equation becomes 9610514 + 3 = 9610517</li>

 <li>Then a second later, the equation becomes 9610514 + 4 = 9610518, etc…</li>

</ul>




In this animation, you must use <strong>your</strong>​<strong> own student number</strong> for the first number. The second number in the equation is increased by 1 every second.




Whenever the button “Stop Animation” is clicked, then the web page stops the animation. Whatever the equation is currently displayed will stay there on the page.<strong>        </strong>

<strong>Question 5 </strong><strong> </strong>​ Create a webpage Question5.html.​

On the web page displays “Enter command: ”, followed by a text field for the user to enter a command, followed by a button “Execute command”.

Below the button, display 5 images of the same height: a frog, a table, a chair, a phone and a car, in this exact order.




A valid command is of the form “Change X to Y” where X and Y are two different words from this list: frog, table, chair, phone, car.  Below are some examples of valid commands and invalid commands.




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Examples of valid command </strong></td>

   <td width="312"><strong>Examples of invalid command </strong></td>

  </tr>

  <tr>

   <td width="312">Change table to frog</td>

   <td width="312">frog</td>

  </tr>

  <tr>

   <td width="312">Change chair to phone</td>

   <td width="312">Change chair to chair</td>

  </tr>

  <tr>

   <td width="312">Change frog to car</td>

   <td width="312">Change frog to dog</td>

  </tr>

  <tr>

   <td width="312">Change car to chair</td>

   <td width="312">car to chair</td>

  </tr>

  <tr>

   <td width="312">Change table to phone</td>

   <td width="312">Change TABLE to PHONE</td>

  </tr>

 </tbody>

</table>




<ul>

 <li>If the user enters an <strong>invalid</strong>​<strong> command</strong> and presses the button “Execute command” then an alert window appears which says “You have entered an invalid command”.</li>

 <li>If the user enters a <strong>valid</strong>​<strong> command</strong> “Change X to Y” and presses the button “Execute command” then any image of X on the page will be replaced by the image of Y.</li>

</ul>

<strong> </strong>

The following example illustrates how the program should work:

<ul>

 <li>Initially, 5 images: a frog, a table, a chair, a phone and a car, displayed in this order.</li>

 <li>The user enters the command “Change table to chair” and presses the button “Execute command”, 5 images becomes: a frog, a chair, a chair, a phone and a car, in this order.</li>

 <li>Next, the user enters the command “Change car to frog” and presses the button “Execute command”, 5 images becomes: a frog, a chair, a chair, a phone and a frog, in this order.</li>

 <li>Next, the user enters the command “Change table to frog” and presses the button “Execute command”, 5 images unchanged: a frog, a chair, a chair, a phone and a frog.</li>

 <li>Next, the user enters the command “Change frog to car” and presses the button “Execute command”, 5 images becomes: a car, a chair, a chair, a phone and a car, in this order.</li>

</ul>





