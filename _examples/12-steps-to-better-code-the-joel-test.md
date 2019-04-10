---
title: The Joel Test 12 Steps to Better Code
author: Joel Spolsky
role:  interviewee
overview: test to rate the quality of a software team, can be also applied during interview process
link: https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/
overview-author: spolsky
questions:
- question: Do you use source control?
  summary: if you don’t have source control, you’re going to stress out trying to get programmers to work together. Programmers have no way to know what other people did. Mistakes can’t be rolled back easily
- question: Can you make a build in one step?
  summary: how many steps does it take to make a shipping build from the latest source snapshot? If the process takes any more than one step, it is prone to errors. And when you get closer to shipping, you want to have a very fast cycle of fixing the “last” bug, making the final EXEs, etc. If it takes 20 steps to compile the code, run the installation builder, etc., you’re going to go crazy and you’re going to make silly mistakes.
- question: Do you make daily builds?
- question: Do you have a bug database?
- question: Do you fix bugs before writing new code?
- question: Do you have an up-to-date schedule?
  summary: If your code is at all important to the business, there are lots of reasons why it’s important to the business to know when the code is going to be done.
- question: Do you have a spec?
- question: Do programmers have quiet working conditions?
- question: Do you use the best tools money can buy?
- question: Do you have testers?
- question: Do new candidates write code during their interview?
- question: Do you do hallway usability testing?
tags: [interviewer, general]
---
