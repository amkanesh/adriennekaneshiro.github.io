---
layout: essay
type: essay
title: "The Final Showdown"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Software Engineering
  - Design Patterns
---
<img width=200px src="https://media.istockphoto.com/id/148771691/vector/cartoon-boxing-gloves.jpg?s=612x612&w=0&k=20&c=uShuIGwuiBMj8KlcXG3kRuzjSb2T3AcO5aWXZETmzB8=">

## In the Ring
Coding, I’ve come to realize, is like a boxing match. 

You enter the ring—by opening your IDE of choice—and square up against your opponent. This should be easy, you think. It’s just a landing page. You’re confident in your ability to tackle this task until you render the page and bam, your opponent blindsides you with an inexplicable blank page and 9 errors in your browser console! Suddenly, you aren’t so confident anymore, and this supposedly simple landing page is quickly turning into a nightmare of additional problems.

However, there are tools to help you out: enter design patterns.

## Aiming for Victory

Design patterns can be thought of as a way to counter your opponent (i.e. your application) in the ring. They’re techniques to solve common problems in software engineering. Running with our boxing metaphor, it’s akin to hiring a coach to teach you how to handle different types of blows your opponent throws at you. 

I learned firsthand the convenience and importance of design patterns when designing my own application to host recipes, even if I wasn’t aware they were design patterns at the time.

One type of design pattern used in this application is the Singleton pattern. This essentially creates a global variable of a class that can be used wherever in the application. This was used to create an instance of the collection of user profiles in my application. 

Here is an excerpt from the code that shows the ProfilesCollection class being exported as a single instance.
```
export const Profiles = new ProfilesCollection();
```
This design pattern allows clients to modify this collection (which is managed by the ProfilesCollection class) by invoking various methods on it. For example, it enables clients to update or edit their profile information by editing some of the information contained in the collection.

Another design pattern used in my application is the Module pattern. This enables easy separation and organization of your code by splitting it into smaller, reusable pieces. To use this pattern, all you need to do is write whatever methods necessary for your task in a file, then export the necessary methods. Files outside of this one won’t be able to see any variables declared within that file, since those variables would be considered private.

This has  the advantage of being versatile and able to be applied to a wide variety of problems, with only minor modifications. Additionally, it helps to provide a layer of security to your applications. In the case of the profile page, you don’t want your clients to necessarily access/mess around with what can be sensitive information, so a module pattern that ensures that functions and data are kept private is very useful.  
