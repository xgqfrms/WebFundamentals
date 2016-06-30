---
layout: shared/narrow-pages-list
title: "Focus"
description: "An overview of the role of focus in accessibility"
published_on: 2016-03-01
updated_on: 2016-03-01
order: 1
translation_priority: 0
authors:
  - megginkearney
  - dgash
key-takeaways:
  tldr: 
    - "Learn what focus is and how it affects accessibility efforts."
notes:
  efficiency:
    - "Understanding the accessibility issue, its scope, and its impact can make you a better web developer."
  problem-solving:
    - "Catching, identifying, and removing potential accessibility roadblocks before they happen can improve your development process and reduce maintenance requirements."
---

{% include shared/takeaway.liquid list=page.key-takeaways.tldr %}

In this lesson we'll talk about *focus* and how you can manage it in your application. In a nutshell, screen focus refers to which *control* (an input item such as a field, checkbox, button, or link) on the screen currently receives input from the keyboard (and from the clipboard when you paste content).

You're probably familiar with focus for text fields. To type into a text field, you click it with the mouse, giving it focus. You may also know that if you press `Tab`, focus moves to the next control on the page. This is a great place to start learning about accessibility because we all know how to use a keyboard, it's easy to relate to and test, and it benefits virtually all users. 

Those users with motor impairments, which could be caused by anything from paralysis to a broken arm, may be relying on a keyboard or switch device to navigate your page, so a good focus strategy will be critical to providing a good experience for them.

And for the power users who know every keyboard shortcut on their machine and hate having to use the mouse, being able to quickly navigate your site with the keyboard is going to make them more productive.

Thus, a well implemented focus strategy means everyone using your application will have a better experience. We'll see in the upcoming lessons that the work we do on focus is actually an important basis for supporting assistive technology users.
