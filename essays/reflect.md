---
layout: essay
type: essay
title: "Software Engineering Is How You Work, Not Just What You Build"
date: 2025-12-17
published: true
labels:
  - IDPM
  - Configuration Management
  - Software Engineering
  - Ethics
---

## The biggest shift I had this semester

At the start, it was really easy to see this class as “the web app class” because we used a modern stack and built a real site. But by the end, the main thing I learned is that software engineering is less about the specific tools and more about the way you plan, coordinate, and make decisions so the work stays reliable as the project grows. The web app is just the environment where all those habits get tested.

Three ideas stand out for me because they clearly matter beyond web development: Agile project management (specifically Issue Driven Project Management), configuration management, and ethics in software engineering.

## Agile project management and why Issue Driven Project Management works outside web apps

Agile project management is an approach to building things where you deliver in small increments, get feedback early, and adjust as you learn more. Instead of betting everything on one huge plan that has to be perfect from day one, Agile assumes change is normal and designs the workflow around that reality.

In this class, the version of Agile I got the most experience with was Issue Driven Project Management (IDPM). IDPM is basically a way of running a project where “issues” are the source of truth for what needs to happen next. An issue is a written unit of work that explains what needs to be done, why it matters, and what “done” looks like. The big difference from random to do lists is that issues are meant to be trackable, discussable, and testable. They can be assigned, estimated, connected to milestones, and reviewed later when you want to understand why a decision happened.

What made IDPM feel like real software engineering is that it forced structure even when the project got messy. When multiple people are working at once, it is not enough to “just communicate.” You need a shared system so that:

- work does not get duplicated

- tasks do not get forgotten

- people do not block each other without realizing it

- progress is visible without meetings every five minutes

I can easily see myself using IDPM for projects that are not web apps. For example, in a data science project, issues could represent dataset cleaning tasks, evaluation benchmarks, and documentation deliverables. In a robotics project, issues could track sensor integration, calibration steps, and safety checks. Even outside coding, the same idea works. If I was organizing a fundraising event, issues could cover sponsor outreach, logistics, volunteer roles, and contingency plans, with clear acceptance criteria like “sponsor confirmed by email” or “supply list purchased and stored.” IDPM is not tied to React or Next.js at all. It is a coordination system for any project where people need clarity and accountability.

## Configuration management as the backbone of teamwork

Configuration management is the practice of controlling and tracking changes to a system over time, so you can reproduce builds, know what version is running, and avoid chaos when multiple changes happen at once. In simple terms, it answers questions like:

- What changed

- Who changed it

- When it changed

- Why it changed

- How to go back if it broke something

In this course, configuration management showed up everywhere, even when it did not feel like it had a name. Using Git for version control is configuration management. Branching is configuration management. Pull requests and code review are configuration management. Tagging releases and deploying known versions is configuration management. Even keeping environment variables organized is part of it because the app does not behave the same way if the environment is different.

The reason configuration management matters beyond web apps is that any serious technical project becomes unmanageable without it. It is not just about avoiding mistakes. It is about making progress possible. If you cannot reproduce a working version of your system, then every bug fix becomes risky because you do not know what you might break. If you cannot trace changes, then debugging becomes guesswork. If you cannot isolate features with branches, then teamwork turns into everyone stepping on each other.

A good example is when tests are involved. Automated testing only helps if you can trust the environment and the version you are testing. If “it works on my machine” becomes the normal outcome, that is usually a configuration management problem, not a skill problem. The more I worked with a team project, the more obvious it became that clean branching practices, consistent pull request habits, and repeatable setup steps are what keep a project stable.

That is why configuration management is a core software engineering idea. It is basically the discipline that lets a project scale from one person to a team, and from one week of work to a whole semester.

## Ethics in software engineering is not optional

Ethics in software engineering means thinking about how software impacts people, and taking responsibility for the consequences of your design choices. That includes privacy, security, accessibility, honesty about what the system does, and fairness in how systems affect different users. It also includes professional responsibility like not cutting corners in ways that could harm users later.

What changed for me is that I started to see ethics as something that shows up in normal development decisions, not only in dramatic situations like hacking or huge scandals. For example:

- If you collect user data, you are making a privacy decision, even if you did not “mean” to

- If you store passwords incorrectly, you are making a security decision, even if you did not think of it that way

- If your UI is confusing or hard to use, that can become an accessibility and fairness issue because some users get locked out more than others

- If you rely on tools like AI without verifying outputs, you can introduce hidden risk into a codebase that teammates now have to maintain

Ethics also connects to team behavior. If you do not document things, that pushes risk onto whoever comes later. If you skip tests to move faster, you are basically borrowing time from the future and making someone else pay the interest. That is an ethical choice too because it affects other people’s workload and the reliability users experience.

The main lesson I am taking with me is that “shipping” is not the only goal. The goal is building something dependable that respects users and can be maintained. That mindset applies to any software role, even if I never touch web development again.

## What I am taking forward

This class did teach me web development skills, but the more valuable outcome is that I now understand what professional software work is supposed to look like when more than one person is involved and the project actually matters.

If I had to summarize it: Agile and IDPM taught me how to plan and adapt, configuration management taught me how to stay organized and stable, and ethics taught me how to stay responsible while doing it. Those three ideas are bigger than any stack. They are the difference between “I wrote code that runs” and “we built a system that people can trust.”
