---
layout: essay
type: essay
title: "Estimating Time Is Not Guessing, It Is Managing"
date: 2025-12-14
published: true
labels:
  - IDPM
  - Effort Estimation
  - Project Management
---

## How I Made My Effort Estimates

When I first saw that we had to estimate effort for every issue, I treated it like I was supposed to predict the future and be right. Pretty quickly I realized the point was different. Estimation is more like planning because it forces you to think about what the task actually includes before you start.

My estimates were based on comparison and risk. If an issue looked similar to something we already did, I used that as historical data and started from that baseline. For example, if we already built one page with a certain layout and later needed another page that reused those same component patterns, I estimated lower because the setup and styling decisions were already solved. If the issue involved something unfamiliar, like a new library, a database schema change, authentication behavior, or tricky UI state, I estimated higher because I knew it would include debugging and extra verification time. For larger issues, I also broke the work down mentally into UI work, data wiring, validation, testing, and polish, then added those up to get a total estimate.

## Benefits of Estimating in Advance

Even when my estimates were off, estimating in advance still helped. The biggest benefit was planning and prioritizing. When a milestone board had a lot of issues, estimates helped me see which tasks were quick wins and which ones were risky or likely to block other work. That made it easier to choose what to start first.

Estimating also helped me catch scope creep sooner. Some issues started as one simple goal, but once I got into the code, they turned into multiple connected problems that all needed to be solved together. When that happened, the estimate stopped matching reality fast, and that was a signal to split the issue, simplify the approach, or communicate to the team that the task was larger than expected before it became a last minute scramble.

## Was Tracking Actual Effort Useful

Tracking actual effort was honestly the most useful part. After a few issues, I had real data on how long certain types of work actually took in our codebase, not just how long I thought they would take. That made later estimates more grounded.

It also helped explain why progress sometimes felt slow. Even when I was working consistently, time would get eaten by research, planning, debugging, and testing. Seeing that effort recorded made it easier to adjust expectations and make better decisions about how much we could realistically take on for the milestone.

## How I Tracked Effort and How Accurate It Was

I tracked my effort by timing my work with my phone. When I started working on an issue, I started a timer. When I stopped, I stopped the timer. I did my best not to count breaks, distractions, or time where I was not actually working.

For coding effort, I counted time spent writing code, iterating on solutions, debugging, running tests, refactoring, and integrating changes. For non coding effort, I also used my phone timer but tracked it separately, counting time spent on requirements analysis, design planning, research, documentation, and communication with teammates.

Since this was manual timing, I think my tracking was reasonably accurate, but not perfect. The biggest source of error was context switching, like answering a message or jumping between tasks and forgetting to stop the timer immediately. Even with that, I still trust the data because I was consistent and focused on keeping it honest.

## What I Would Change Next Time

If I had to do this again, I would improve the process in a few ways. First, I would split issues earlier when they contain multiple deliverables. An issue that includes UI, database changes, validation, and tests is basically multiple tasks, and combining them makes both estimating and tracking messy.

Second, I would standardize non coding logging a little more, even if it is just a quick note of start time, stop time, and what I did. That would make the non coding numbers easier to justify later.

Third, I would do a mid milestone review where I compare total estimated effort versus total actual effort so far. That would help adjust scope and priorities earlier instead of learning the lesson at the end.

## AI Use and How I Accounted for It

AI assistance was part of my workflow, and I tried to account for it accurately. I used ChatGPT by OpenAI, model GPT 5.2 Thinking. I mainly used it for breaking issues into subtasks, getting unstuck when I hit an error, and sanity checking approaches.

When I used AI during implementation, I counted that time as coding effort because it still involved prompt writing, iterating, reading outputs, verifying correctness, and integrating changes into the codebase.

Representative prompts I used were things like break this issue into subtasks and estimate minutes, here is an error and the relevant code what should I check, and suggest a clean way to implement a feature while keeping the code readable.

The parts I could accept quickly were usually higher level checklists, debugging ideas, or small isolated logic. The parts that required manual edits were anything tied to our specific schema, naming conventions, file structure, or UI behavior. I always verified by testing and making sure the solution actually fit our project. For AI time specifically, I counted minutes spent on prompt writing, generation, verification, and integration as part of the same timed work session using my phone timer.

## Closing Reflection

By the end of the project, effort estimation stopped feeling like paperwork and started feeling like a real management skill. The point was never to be perfect. The point was to plan before building, track what actually happened, and use that information to make smarter decisions as the project grows. Honest data beats perfect guesses every time.
