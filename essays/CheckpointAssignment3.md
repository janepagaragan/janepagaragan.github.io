---
layout: essay
type: essay
title: Checkpoint Assignment 3
date: 2021-05-06
labels:
  - Assignment 3
  - Checkpoint
  - Screencast
---
<img src="https://github.com/janepagaragan/janepagaragan.github.io/blob/master/images/ASS3.png?raw=true" width="90%" height="90%">

My screencast can be accessed <a href="https://youtu.be/CLWxMIsOq7o">here</a>.

A brief summary of the points from the screencast below.

<h1>Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</h1>
My shopping cart will only be accessible through the link on the navbar. My intention by doing so is to prevent the user from being redirected to the cart page every single time they press Add to Cart. On the cart page, the user will be able to add or subtract quantities from existing items and be able to remove them. I also will incorporate a continue shopping button that will redirect the user back to the home page. There will also be a purchase button that brings them to the thank you page.

<h1>Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</h1>
I will use sessions to save the items and quantities that users select. The session will then be loaded into the cart upon the request. 

<h1>How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</h1>
I will avoid access by restricting purchases to only those who have logged in and or registered. To do so, I will use cookies to ensure the site can decipher those that have already gone through the login/registration process. A security concern I must address is to prevent those who have no information from logging in/registering from making any purchases and making sure that users can't purchase without any quantities selected.

<h1>Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)</h1>
I provided personalization by incorporating the user's username or full name to the invoice, which is where they are directed upon sucessful login/registration. The page displays a welcome back 'x' or welcome to (website name) 'x'. When my assignment 3 is up and running, the purchase page will also have a personalized thank you message.

<h1>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</h1>
I will be working alone.

<h1>How are you approaching Assignment 3 differently than Assignment 2?</h1>
I am approaching Assignment 3 differently by taking the time of thinking about how I want the website to function and what I want it to do. This would allow me to know what to do with the coding easier. I am also planning it out more efficiently by dividing the work and giving myself scheduled times to do those parts. Unlike Assignment 2, I will also spread the work out over the course of a week vs. 2 days.
