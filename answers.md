
1) selected the src attribute in HTML and pasted random bear URL
var polarBear = document.querySelector('img');
polarBear.src = "https://placebear.com/200/300";

2) Selected the panda bear heading in HTML text, and changed it to my name

var heading = document.querySelector('h1');
heading.innerHTML = "Valerie Osei";

3) selected the text of the HTML and made it say something else
var title = document.querySelector('.info-title');
title.innerText = "Fun Activities";

4) selected body in CSS and changed the colour
var body = document.querySelector('body');
body.style.backgroundColor = '#9c64de';

5) changed the colour of the highlight class in CSS
var highlights = document.querySelectorAll('.highlight');
highlights.forEach(function(highlight){
highlight.style.backgroundColor = '#d545b2';})

6) selected h1 in CSS and changed the font
var titleHead = document.querySelector('h1');
titleHead.style.fontFamily = "monospace";

7) used dev tools to select the round icon by class and then changed colour
var icons = document.querySelectorAll('.action-icon-bg');
icons.forEach(function(icon){
    icon.style.backgroundColor = "#344a8b";})

8-9) changed the placeholder attribute of the name/message field
var placeholder = document.querySelector('#name');
placeholder.placeholder = "identify yourself";

var message = document.querySelector('#message');
message.placeholder = "state your business";

10) added value attribute with "yout nemesis"
var value = document.querySelector('#name');
value.value = "your nemesis";

11) add the email to value attribute
ar valueEmail = document.querySelector('#email');
valueEmail.value =  "koalathebear@gmail.com";
"koalathebear@gmail.com"

12) add "En Garde" to the value attribute
var valueSubmit = document.querySelector('#submit');
valueSubmit.value = "En garde!";

13) to stop panda bear from sending the email, add "disabled" to the end of the input tag for the email field
valueEmail.setAttribute("disabled", true);

14) Set the bio-info-value class to display: none in order to clear the personal info of panda bears
var personalInfo = document.querySelectorAll('.bio-info-value');
personalInfo.forEach(function(info){info.style.display = "none";})
//ANSWERS FOR THE DOM
