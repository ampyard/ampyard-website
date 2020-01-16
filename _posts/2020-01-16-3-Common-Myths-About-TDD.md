---
title: "3 Common Myths About Test Driven Development"
subtitle: "Are you doing TDD right?"
layout: blog_post
author: Vivek Ganesan
author-email: vivek.ganesan@ampyard.com
modal-id: 1
date: 2020-01-16
categories: ["tdd","xp","technical_agility"]
feature_image: "/img/tdd_blog_header.jpeg"
---

Did you know that Test Driven Development (aka TDD) is a vastly misunderstood subject in our community? In this article, I will be detailing three common myths about TDD.

## Myth -1: TDD is just writing unit tests after coding

TDD is not just about writing unit tests after coding. It involves writing code in a way that tests dictate. Here, tests drive the development activity. This is the reason for calling it 'Test Driven Development' and not 'Development and Testing'.

TDD is practiced using a well-known way called Red-Green-Refactor technique. It involves the following steps (strictly in the following order):

1. Write a unit test  
2. Run all tests  
3. Write production code to pass the unit test  
4. Run all tests  
5. Refactor  
6. Run all tests  
7. Repeat steps 1-6

Thus, we don’t write tests after coding. We write a single test at a time to drive the development.

## Myth -2: TDD is another name for Test-first development

Test-first development is where you write tests first. That’s true. But not all Test-first development qualifies as TDD.

Let me explain a little more. Is it still TDD if you write 100 tests before writing the first line of code? No! Because TDD expects you to write only one test at a time.

So, TDD is a subset of Test-first development, in a loose way but not all Test-first is TDD.

## Myth -3: A pair is a must if you want to do TDD

TDD in pairs is great. One developer wearing the hat of test-writer and another wearing the hat of the coder - All great! (Of course, switching roles often to put the monotony away is essential.)

But, is it the only way of doing TDD? Not necessarily. Just because you can’t pair with someone, you don't have to stop practicing TDD.

A single person can still do TDD if he/she follows the cycle religiously. Hence, you don’t necessarily need a pair.

These are the three most common myths that I have seen. I have come across some more myths too but, that’s for some other day. Have you come across any myths about TDD? I am all ears :)


----------

_**In case you want to explore TDD in depth, feel free to explore our [Technical Agility Trainings](/trainings.html).  Contact us with your requirements and we will work together!**_


Picture Credit:  [https://www.pexels.com/@hiteshchoudhary](https://www.pexels.com/@hiteshchoudhary)
