---
layout: essay
type: essay
title: Be a User Not a Luser
# All dates must be YYYY-MM-DD format!
date: 2019-09-11
labels:
  - Eric Raymond
  - Smart Questions
  - Stack Overflow
---
<img class="ui medium center image" src="../images/question.jpg">

In Eric Raymond’s essay <a href = "http://www.catb.org/esr/faqs/smart-questions.html">How to Ask Questions the Smart Way</a>, Raymond describes the best way to ask a programming or software question to a group of software engineers to ensure a quality and efficient answer. By following these guidelines, users who are requesting assistance ensure that they do not become “lusers,” a humorous term for users asking questions to the like of “My program isn’t working, here’s 1000 lines of my source code” or “Urgent question, what’s a Macintosh?”. Vague or easily searchable questions are obviously annoying, and usually a waste of time to answer. But is asking smart questions really necessary to be a good software engineer?

## What’s a poor question?

<img class="ui medium center image" src="../images/stupid.jpg">

In <a href = "https://stackoverflow.com/questions/31211470/remove-arrayindexoutofboundsexception">this</a> poorly written question, this “luser” is asking about how they can remove an “ArrayIndexOutOfBoundsException” from their program. At face value, this seems like a reasonable request, so what makes this user a “luser”? First of all, it is clear that they are either extremely lazy or have not even searched up what this error is. Instead of providing a snippet of their source code to just include the arrays and where they are used, they copy/paste their entire program into the description. Just from the name of the exception, anyone can narrow down the error to the arrays in the program. Providing the whole source code instead of just the problematic section forces the reader to look for what the problem is. The requestor, the user, should be providing the problem, not the person who is trying to help. 

Secondly, they do not provide any steps on what they have done to troubleshoot their error. Some reasonable troubleshooting steps would be to trace through the loops that deal with the arrays, check what values the arrays spit out and compare them against the expected values. In this case, by tracing through their code, they would have easily resolved their error, as it was a mix-up between the variables used in the for-loops. As such, troubleshooting an error before asking a question is essential, it gives valuable insight into the problem and can help you resolve the issue on your own. 

Lastly, the question asked by this “luser”, “How to fix it?”, just exudes laziness and entitlement. This type of question isn’t asking for a point in the right direction, it wants the problem to be fixed. It puts an expectation on potential answers of the problem to guide the “luser” through what they need to do. Instead, a better way to ask this question would be to list what they’ve tried, and maybe ask “I’ve narrowed it down to the for loops and I’ve traced through the program. Is it an issue with the variables?”. By approaching the question in this manner, they not only show respect towards the people answering the question by troubleshooting the problem beforehand but also paint themselves as peer by demonstrating their knowledge of the subject. 

## What makes a question smart?

<img class="ui medium center image" src="../images/smart.jpg">

In <a href= "https://stackoverflow.com/questions/1335851/what-does-use-strict-do-in-javascript-and-what-is-the-reasoning-behind-it?rq=1">this</a> well-written question, this user is asking about the function of the “use strict” statement and why it was created. So what makes this question a smart question? Considering this question is 10 years old, I am assuming that at the time, it was either recently added to Javascript or Javascript documentation had not included the function of this statement yet. Even so, this user has done a little research and searched up this statement on Google. While they were unable to figure out exactly what “use strict” does, they came up with a theory that it changes how Javascript is interpreted by your browser, based on what the examples they found. This shows that the user was willing to try to answer their question on their own before consulting other people. Not only does this extra level of effort increase the quality of questions asked, it also prevents the same question from being asked multiple times. As such, researching the question beforehand prevents other users from wasting time and might help the user resolve their issue faster.

In addition, the user provides context for their question. They list the exact error they received, what they ran their code through to receive the error, and why they are curious about the “use strict” statement. While not always necessary, this helps other users to see if this question, and potential answers they receive, is relevant to what they need assistance with. Providing context also gives insight into the user’s thought process, and helps other users know if something went awry leading to the user’s question.

The last main thing that makes this a great question is that it leads the way to a more meaningful discussion than just discussing what it is. The user specifically asks, as a couple of follow up questions, if it’s still relevant and what browsers currently support it. This opens the discussion to include other pieces of information that can help future programmers troubleshoot issues if they use this statement in their code. Consequently, a good question will not only help the user asking the question, but will also help those who have an issue related to that same subject. 

## So is it necessary?

After going through these questions, it’s clear that asking smart questions will not only attract smarter answers, but will also perpetuate knowledge into the community. Smarter questions help other users narrow down what the problem is and provide answers that are more likely to help the user with their issue. In addition, future users who search up a similar question can use the insight from discussions in those questions to either solve their problem or branch off into a different direction based on the information given. Smart questions save time, both in the present and the future.
