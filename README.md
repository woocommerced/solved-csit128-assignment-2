Download Link: https://assignmentchef.com/product/solved-csit128-assignment-2
<br>
<strong>Question 1. </strong>Consider​ the following fictional scenario. At the <strong>Whosville</strong>​<strong> Holiday Reserve</strong>,​ there are 3 accommodation options: <em>Cabin</em>​ ​, ​<em>Dormitory</em> ​, and <em>Cottage</em>​ ​. They also provide a number of guided tours to local caves: <em>the</em>​<em> Ktar Koon Cave</em>​, <em>the</em>​<em> Beyoh Boon Cave</em>​, <em>the</em>​<em> Sontain Soon Cave</em> and the famous <em>Tahoot</em>​<em> Toon Cave</em>​. There are also <em>internet</em>​<em> services</em> at low price. The holiday reserve website has a web form that allows customers to query for a <strong>price</strong>​<strong> quote</strong>,​ which depends on the type of accomodation, the number of adults and children, the number of days they want to stay, whether they want to include some of the cave tours, or whether they want to include internet service. The web form also has a text area where customers can submit questions regarding the holiday reserve.

The back-end service is running at http://whosville.com/price_enquiry and it accepts <strong>GET</strong>​   request with the following parameters:​

<ul>

 <li>adult: this parameter is to specify the number of adults</li>

 <li>child: this parameter is to specify the number of children</li>

 <li>days: this parameter is to specify the number of days the customer wants to stay</li>

 <li>atype: this parameter is to specify the accommodation type, the acceptable values are:

  <ul>

   <li>cab: for Cabin</li>

  </ul></li>

</ul>

○ dor: for Dormitory

○ cot: for Cottage

<ul>

 <li>tour: this parameter is to specify which cave tours the customer wants to include, it accepts zero to multiple values, and the acceptable values are:

  <ul>

   <li>1: for Ktar Koon Cave tour</li>

  </ul></li>

</ul>

○ 2: for Beyoh Boon Cave tour

○ 3: for Sontain Soon Cave tour

○ 4: for Tahoot Toon Cave tour

<ul>

 <li>internet: this parameter is to specify whether the customer would like to include the internet service, and the acceptable values are:

  <ul>

   <li>yes: for include internet service</li>

  </ul></li>

</ul>

○ no: for no internet

<ul>

 <li>query: this parameter is for customers to ask any question about the holiday reserve.</li>

</ul>

Create a web form for the <em>Whosville Holiday Reserve</em>​ ​ with the following requirement:

<ul>

 <li>Use a text field: for the number of adults</li>

 <li>Use a text field: for the number of children</li>

 <li>Use a drop-down list: for the accomodation type</li>

 <li>Use a text field: for the number of days</li>

 <li>Use checkboxes: for the cave tours</li>

 <li>Use 2 radio buttons: for the internet service</li>

 <li>Use a text area: for customer query</li>

</ul>

The webform has 2 buttons: one for submit and one for reset the form.

Use table arrangement so that your webform looks presentable for the users.

Your webform must explicitly specify the correct <strong>action</strong>​ and ​ <strong>method</strong>​ .​

You should test the web form to see if it submits the correct parameters and values to the server.

<strong>Question 2. </strong>Go​ to the website https://www.amazon.com.au​ and play with the search web form. Type some keyword and choose some category to search. Try to find out the following information:

<ul>

 <li>What is the action of the form?</li>

 <li>What is the parameter for the keyword?</li>

 <li>What is the parameter for the category?</li>

 <li>Choose 5 different categories of your choice and find out what the corresponding values for those categories are.</li>

</ul>

After obtain the above information, create a web form with the following requirement:

<ul>

 <li>Use a text field: for the keyword;</li>

 <li>Use 5 radio buttons for your 5 chosen categories;</li>

</ul>

The webform has 2 buttons: one for submit and one for reset the form.

You should test the web form to see if it submits the correct parameters and values to the server.

<strong>Question 3. </strong>On​ the web page displays 2 text fields and 2 buttons: “Swap Text” and “Clear Text”.

<ul>

 <li>When the button “Swap Text” is clicked, then the texts entered in the two text fields will be swapped. For example, if the user enters John in the first text field and Lee in the second text field, and if the user clicks the “Swap Text” button, then the first text field should display Lee and the second text field should display John.</li>

 <li>When the button “Clear Text” is clicked, then the texts entered in the two text fields will be cleared.<strong>  </strong></li>

</ul>

<strong>Question 4. </strong>On the web page displays two text fields and a button “Calculate” as follows​ :​

When the user enters two numbers into the two text fields and clicks the button “Calculate”, then a message is displayed on the web page showing the minimum number, the maximum number, and the sum of the two numbers as illustrated by the following example:

<strong>Question 5. .</strong> On the web page displays five animal images and four “Switch” buttons as​      follows.

Whenever the user clicks on a switch button, the two images next to the button switch their places. You can use any animal images to do this task.

<strong>Question 6. </strong> On the web page displays “Enter command: ”, followed by a text field for the​ user to enter a command, followed by a button “Execute command”.

Here are the list of valid commands and command’s output:

<table width="624">

 <tbody>

  <tr>

   <td width="159"><strong>Command </strong></td>

   <td width="465"><strong>Command output </strong></td>

  </tr>

  <tr>

   <td width="159">make duck noise</td>

   <td width="465">Display “QUACK QUACK” in a big font and color of your choice on the webpage. Do not choose black or white color.</td>

  </tr>

  <tr>

   <td width="159">make rooster noise</td>

   <td width="465">Display “COCK-A-DOODLE-DOO” in a big font and color of your choice on the webpage. Do not choose black or white color.</td>

  </tr>

  <tr>

   <td width="159">show duck image</td>

   <td width="465">Show an image of a duck on the webpage.</td>

  </tr>

  <tr>

   <td width="159">show rooster image</td>

   <td width="465">Show an image of a rooster on the webpage.</td>

  </tr>

  <tr>

   <td width="159">show frog face</td>

   <td width="465">Using the character entity to show an image of a frog face.(Read the lab exercise to see the character entity of the frog face)</td>

  </tr>

 </tbody>

</table>




Any other command that is different from the above exact 4 commands are deemed as an invalid command.

<ul>

 <li>If the user enters an <strong>invalid command</strong>​ and presses the button “Execute command” then​     an alert window appears which says “You have entered an invalid command”.</li>

 <li>If the user enters a <strong>valid command</strong>​ and presses the button “Execute command” then the​           previous command output should disappear from the webpage and the new command output should appear on the webpage.</li>

</ul>