# Lab - Form Basics

In this lab, you'll learn a bit more about forms and how they are processed.   Because you'll need some page that demonstrates server-side processing, we'll create a PHP file to respond to the form submission.

And we'll take this opportunity to learn how to put our work on the web on Heroku, where - unlike Cloud9 - the server processes won't time out and exit.

##Step 1

Clone this repository into your Cloud9 workspace.

##Step 2

Open the index.html file, add some form controls to the form.

Give the form a submit button.

Give the form an **action** attribute with a value of **https://preview.c9users.io/dphayes/it202/lab-forms-and-heroku/form_handler.php**

Give the form an **id** attribute with a value of **formTest**.

##Step 3

Preview your form.

Open the Dev Tools Network tab.

Enter some values in your form, and hit submit.  

Look at the URL in your browser's location bar. Are URL parameters present? 

In the Network tab, examine the headers of the returned file. What HTTP method was used?  

##Step 4

Edit your index.html file, and give your form a **method** attribute with a value of **post**.

Preview your page with the Network tab open, and hit submit.

As above, look at the URL and look at the headers.   What's different?


##Step 5

Make sure to use the git commands to add and commit your files.


##Exploration1

Reload your preview page with the Dev Tools Console open.

Use document.getElementById to get the form element, and run the submit() method.


##Exploration2

In a new tab, navigate to **https://www.google.com/*

Look at the attributes on the form tag (inspect the text box, then navigate up the DOM until you find the form.)

What is the value of the **method** attribute?

Look at the value of the **onsubmit** attribute;  what does that do?

Enter a search term and submit.   Look at the URL of the results page.



##Comments and Hints









