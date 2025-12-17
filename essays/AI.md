---
layout: essay
type: essay
title: "AI Was My Tutor, Not My Shortcut"
date: 2025-12-16
published: true
labels:
  - AI
  - ICS 314
  - Software Engineering
---

## Introduction

AI is showing up everywhere in education now, but in Software Engineering it feels especially relevant because the work is already tool heavy. In ICS 314, a lot of the learning is not just concepts, it is also workflows: reading docs, debugging weird errors, writing clean code, and communicating with a team. For me, AI became like a fast helper in that process.

The main AI tool I used was ChatGPT. I used it for everything from explaining concepts (like risk management) to debugging ESLint issues, to brainstorming how to structure an essay in the format that works in my GitHub portfolio. I learned pretty quickly that AI is best when I treat it like a tutor and a rubber duck, not like a magic answer generator.

## Personal Experience with AI

Below is the exact list from the prompt, and how I used AI for each one, with specific examples and the tradeoffs I noticed.

## Experience WODs

I used AI the most on Experience WODs because those are usually solo and time boxed, and getting stuck early can waste the whole session. For the functional programming style WODs, I asked things like, “Write a function using underscore to implement the following instructions” and then I pasted the WOD instructions. This was useful for getting a starting structure and seeing what underscore functions were even relevant. The cost was that the first answer was often close but not correct for the exact WOD constraints, so I still had to do trial and error, and sometimes it took longer because I had to debug AI mistakes.

## In class Practice WODs

During practice WODs, I used AI more like a hint system instead of asking for full solutions. A typical prompt was, “I am stuck on this step. What is the next small thing I should check. Here is my code and the error.” This worked well because practice WODs are where I wanted to actually learn, not just finish. The downside is that AI can over explain or suggest extra refactors that do not match how the instructor wants it done.

## In class WODs

I used AI less during in class WODs because of the pace and because it can be risky to copy a suggestion without fully understanding it. When I did use it, it was usually for a quick sanity check like, “Does this approach match the requirement of not using loops and using underscore methods.” AI was helpful for confirming direction, but it was not worth it when the question was something I could solve by just reading the instructions again carefully.

## Essays

AI helped me a lot on essays, mainly with structure and formatting. I used it to organize sections, tighten wording, and make sure I was following the required layout for the course. A typical prompt for me was something like, “Here is my draft. Can you help me improve clarity and flow, and also format it with the correct front matter for my portfolio.” This saved time and helped me avoid spending forever on formatting details, but the cost is that I still had to make sure the final writing sounded like me and matched what I actually did in the course.

## Final project

For the final project, AI was most useful for debugging and for small design decisions. For example, when working with a participants table and sorting logic, a prompt would look like, “Here is my ParticipantsTable component. I added sorting by wins and losses. How can I test that the change actually works, and what test data should I try.” This was helpful because it pushed me to think about edge cases. The cost is that AI sometimes suggests a testing approach that does not fit the actual project setup, so I still had to adapt it.

## Learning a concept or tutorial

AI was great for explain it like I am new moments. A prompt I used was, “Why is risk management important for software development projects. Explain it in a practical way with examples.” This helped a lot with comprehension because I could ask follow ups immediately. The downside is that AI explanations can make something feel simpler than it really is, so I still needed to connect it back to class examples and readings.

## Answering a question in class or in Discord

I sometimes used AI to help me respond clearly when someone asked a question and I knew the idea but not the best wording. A prompt would be, “Help me explain this error in simple terms and suggest what they should try first.” The benefit is faster, clearer communication. The cost is I had to avoid posting AI sounding answers that look like I did not really understand it.

## Asking or answering a smart question

AI helped me turn “I am confused” into a smart question that includes context. A prompt I used was, “Rewrite my question so it includes what I tried, what I expected, what happened, and the exact error message.” This honestly made my questions better and got me better help. The risk is if I rely on AI too much, I might stop practicing writing clear technical questions myself, so I tried to use it as a template and then edit.

## Coding example (for example “give an example of using Underscore .pluck”)

This is where AI is perfect. I asked, “Give me an example of using underscore pluck on an array of objects. Show input and output.” Super useful, low risk, and it saves a ton of time compared to digging through docs. The only cost is that sometimes the example is not in the exact style our course expects, so I still adjust it.

## Explaining code

I used AI as a code explainer a lot when I understood what but not why. A prompt I used was, “Explain what this function is doing step by step and what the key idea is. Here is the code.” This helped me build real understanding, especially with React state logic and sorting. The risk is that AI can hallucinate intent, so I always checked the explanation against the actual code behavior.

## Writing code

I did use AI to write code sometimes, but usually only as a starting draft. A prompt looked like, “Write a React component that displays a table of participants and supports sorting by seed and record.” The benefit is speed and getting unstuck. The cost is big: the code can be wrong, too complex, or not match course constraints. Also, relying on AI too much can weaken your own problem solving, so I tried to use it like generate a rough idea, then I wrote the final version myself.

## Documenting code

AI helped with documentation because it can summarize patterns quickly. I used prompts like, “Write a short README section explaining how to run this project locally and what the main features are. Keep it student project level.” This was helpful, but I still had to verify commands and avoid fake steps. Documentation is only useful if it is accurate.

## Quality assurance (for example “What’s wrong with this code” or “Fix the ESLint errors in <code here>”)

This was one of my biggest use cases. A prompt I used was, “Fix the ESLint errors in this file without changing behavior. Here is the code and the lint output.” AI was helpful at spotting small issues fast. The cost is that it might fix by rewriting logic, which is not always what I want. I learned to be super specific, like only change formatting and typing, do not change logic.

## Other uses in ICS 314 not listed

I used AI for small but real things like generating test cases, writing better commit messages, or debugging tool issues. For example, when Playwright commands failed, I asked, “I ran this Playwright command and got connection refused. What are the most likely causes and what should I check first.” This was useful because it gave me a checklist, but I still had to do the actual investigation.

## Impact on Learning and Understanding

Overall, AI improved my learning when I used it in a disciplined way. It boosted my comprehension because I could ask unlimited follow up questions without feeling judged. It also helped my problem solving because it encouraged a more systematic debugging approach, like check config, check environment, check assumptions.

At the same time, AI can challenge learning if I use it lazily. If I copy a solution without understanding, I might finish the assignment but not actually gain skill. The biggest positive change for me was learning how to prompt better, because that forced me to be clear about what I knew, what I tried, and what I needed next.

## Practical Applications

Outside ICS 314, AI already matches real world software engineering. In real projects, people constantly search docs, ask teammates, and use tools to speed up work. AI fits into that same workflow, especially for code review style feedback, documentation drafting, and debugging checklists. Even in collaborative environments, it can help you communicate better by making clearer bug reports and smarter questions.

The effectiveness depends on honesty and verification. In real world settings, shipping wrong code is expensive, so AI is only helpful if you validate what it gives you.

## Challenges and Opportunities

The biggest limitations I saw were accuracy and overconfidence. AI will sometimes give a confident answer that is slightly wrong, or it will suggest a solution that violates constraints. Another challenge is academic integrity. It is easy to cross the line from help into doing the work for you, so I had to constantly check myself and make sure I was still learning.

The opportunity is teaching students how to use AI responsibly: how to prompt, how to verify, how to cite when needed, and how to use it to learn instead of replace learning.

## Comparative Analysis

Traditional teaching methods build strong fundamentals because you struggle through problems and that struggle teaches you. AI enhanced approaches make learning faster and more flexible because you get instant explanations and feedback.

For engagement, AI can make learning more interactive because you can turn confusion into a conversation. For retention, I think traditional struggle still matters, but AI can increase retention if you use it to understand, not to copy. For practical skill development, AI feels closer to the real world because real engineers use tools, search, and automation constantly.

## Future Considerations

I think AI will be a permanent part of software engineering education. The future challenge is making sure students still develop core skills: reading documentation, debugging, reasoning about code, and designing systems. Courses will probably need clearer rules and more emphasis on process, like showing your work, explaining your decisions, and reflecting on tradeoffs.

A big improvement area would be teaching AI literacy directly, like how to evaluate AI output, how to test what it suggests, and how to avoid hallucinations.

## Conclusion

In ICS 314, AI was a powerful tool that helped me learn faster, communicate better, and debug more efficiently, especially on WODs, essays, and the final project. The benefits were speed, clarity, and confidence when I was stuck. The costs were the risk of wrong answers, wasted time chasing bad suggestions, and the temptation to rely too much on it.

My main recommendation is to treat AI like a tutor, not a shortcut. If future courses build in guidance on responsible use, good prompting, and verification habits, AI can make software engineering education more realistic and more effective without sacrificing actual learning.
