# JavaScript
**JavaScript** is a popular programming language used for web pages, which can also be used for non-browser environments. "Java" and "JavaScript" are both programming languages registered trademarks of Oracle in the US ad other countries, but have very different syntax and use. JavaScript uses input and output, just like a computer does. It also uses variables, similar to mathematics.

## Input/Output
If you want someone to enter their first and last name into your website, you must give the first name an iput id and the last name an input id. 

That would look something like this:

"First name: <input id="first_name">

Last name: <input id="last_name">

<button id="enter">Enter</button>"

The output would be whatever you want to happen once they enter their first and last name. You could make your webpage say "Welcome, "first and last name".

"<script>
    function enter() {
        var fname = document.getElementByID('first_name').value;
        var lname = document.getElementBYId('last_name').value;

        var html = 'Welcome <b> + fname + '</b>' + lname;

        document.getElementById('result').innerHTML = html;
    }"


## Variables
 The 3 ways to declare JavaScript variables are:
   <ul>
    <li><a>var</a></li>
        <li><a>let</a></li>
        <li><a>const</a></li>
   </ul>

**Variables** are containers for storing data. These variables must be indentified by unique names, or identifiers. Some rules for these names of variables are:
<ul> 
    <li><a>Must begin with a letter</a></li>
    <li><a>Can only contain letters, digits, underscores, and dollar signs</a></li>
    <li><a>Names are case sensitive</a></li>
    <li<a>Can begin with _ and $</a></li>
    <li><a>Cannot use reserved words such as JavaScript keywords</a></li>
</ul>