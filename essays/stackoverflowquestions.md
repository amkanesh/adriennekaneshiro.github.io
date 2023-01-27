---
layout: essay
type: essay
title: "Dos and Don'ts of StackOverflow"
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="https://simpleprogrammer.com/wp-content/uploads/2016/11/Bored-PC-1024x576.png">

## What to do when faced with a problem?

Getting stuck on a problem is normal. Everyone has had some sort of issue they couldn’t solve immediately, especially when learning something new. And extra-especially in Computer Science, where minor errors can sometimes mean major consequences for your entire program. When faced with a vexing problem that can’t be solved even after countless Google searches or read-throughs of the documentation, what is a confused programmer to do? Well, perhaps it’s time to turn to StackOverflow.

StackOverflow is a great resource for solving problems, but there is a certain way to go about asking for help. You can’t just barge in and expect people to immediately answer all your questions in perfect detail, especially if you haven’t described your original problem very well in the first place. In essence, vague questions will receive equally vague (and occasionally snarky) answers. 

## What NOT to do!

Take [this](https://stackoverflow.com/questions/75250859/when-char-return-char-in-c) developer for instance. 

```
Q: When char return char in c++

I wanted to ask when char returns character and when number,

The problem is that I once saw in a tutorial that char can return a character number. Sometimes the typed character may turn into a number. Unfortunately, I don't know how it works.

When I wrote a program and used a char variable, the value was always this one. Didn't convert to character code from character or character from character code.
```
Their question, simply titled “When char return char in c++”, is unclear. Actually, this isn’t even a question to begin with. They elaborate about their confusion concerning chars and their numeric values, and as I kept reading, it struck me as the type of question one asks when they’re so confused they don’t know what to ask in the first place. Questions like these leave the respondents guessing as to what the asker wants, and indeed every answer had a slightly different idea of what this developer wanted to know. 

Generally though, the respondents guessed the poster was talking about letters and their ASCII codes, and everyone was surprisingly courteous and nice about the whole thing. One answer inevitably gave the “read the manual ''-type response, which should be done prior to asking these sorts of questions anyways. To top it off, the post itself was closed a few hours after I first saw it for lack of clarity. 

## So... what makes a good question?

If this is a prime example of how not to ask a question, then what is a better way? Let’s look at [this](https://stackoverflow.com/questions/73491512/how-to-create-a-dropdown-menu-in-flexdashboard) developer’s post, summarized briefly.
```
Q: How to create a dropdown menu in flexdashboard?

I have the following data:

[user's code written here]

Using this data, I made these maps:

[user's code written here]

I found this R markdown template that I like over here (https://beta.rstudioconnect.com/jjallaire/htmlwidgets-showcase-storyboard/htmlwidgets-showcase-storyboard.html):

I am interested in seeing if the following task is possible:
I would like to place "Map 1" in the first tab, create a dropdown menu for the second tab that allows the user to view "Map 2" and "Map 3", and create a third tab with "Map 4".

I am not sure how I to modify the Rmarkdown template to create this dropdown menu. I found some related posts online that discuss similar topics (e.g. How to add dropdown menu on tab / tabset [rmarkdown / bootstrap]), but I am not sure how to adapt the Rmarkdown template to add this option. I tried to modify the template and do this myself with the following code:

[again, user's code written here]

This above code ran, but this code has not created the dropdown menu. Can someone please show me how I can fix this?

Thank you!
```
Even without seeing the code specifics, it already has more of a clear structure than the last person's question. It starts with a more descriptive title of “How to create a dropdown menu in flexdashboard?”, then gives their code in text form and the steps they tried previously. They mention looking for other resources and provide links, but explain that they didn’t understand how to modify the existing code to create the desired dropdown menu. Their explanation even ends with a word of thanks to potential respondents. They did ask for a way to fix the code rather than what was wrong with it, but all in all, this question’s correct grammar, specificity, and politeness add up to a post that did get a succinct answer.

## Courtesy is king

Before looking at all this, one would assume that good questions receive better answers.

And yet, after looking at dozens of bad questions on StackOverflow, I’ve realized that many posts get good, earnest answers regardless of how badly the question was worded. (...Excluding the more egregious examples that followed none of the StackOverflow guidelines.) Many respondents seem like they genuinely want to help the best they can. That being said, in asking a question, you are taking time out of someone else’s day in order to find a solution. Even if you’d get a good answer either way, making the other person’s life easier is just the right thing to do.
