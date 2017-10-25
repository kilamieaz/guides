---
title: PHP
---

## What is PHP?

PHP is a server-side scripting language created in 1995 by Rasmus Lerdorf.

## What does the acronym PHP stand for?

Originally PHP stood for 'Personal Home Page', as Rasmus Lerdorf created it for use on his own website. Then in 1997 more developers expanded the language and the acronym also changed to what it stands for today: 'PHP: Hypertext Preprocessor'. As the first 'P' in PHP also stands for 'PHP', it is known as a 'recursive acronym'.

## What is PHP used for?

It is typically used to generate web page content dynamically. For example, if you have a blog website, you might write some PHP scripts to retrieve your blog posts from a database and display them. Other things that PHP scripts could be used for include:

* Processing and saving user input from form data
* Setting and working with website cookies
* Restricting access to certain pages of your website

## How does PHP work?

All PHP code is executed on a web server only, not on your local computer. For example, if you complete a form on a website and submit it, or click a link to a web page written in PHP, no actual PHP code runs on your computer. Instead, the form data or request for the web page gets sent to a web server to be processed by the PHP scripts. The web server then sends the processed HTML back to you (which is where 'Hypertext Preprocessor' in the name comes from), and your web browser displays the results. For this reason, you cannot see the PHP code of a website, only the resulting HTML that the PHP scripts have produced.

##Struct

Usually, a variable can store a single data type and a single scalar data type can only store a single value.
There are many situations where we might need to group some data types together as a single complex
data type. For example, we want to store some student information together in a student data type. We
need the student name, address, phone number, email, date of birth, current class, and so on. In order to
store each student record to a unique student data type, we will need a special structure which will allow
us to do that. This can be easily achieved by struct. In other words, a struct is a container of values which
is typically accessed using names. Though structs are very popular in C programming language, we can
use a similar concept in PHP as well.
