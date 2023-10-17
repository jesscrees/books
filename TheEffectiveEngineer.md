# The Effective Engineer
*Edmond Lau*

[Available on Amazon](https://www.amazon.co.uk/Effective-Engineer-Engineering-Disproportionate-Meaningful/dp/0996128107/)


## Highlights

### Chapter 1: Focus on high-leverage activities
(pg.18)
- Use leverage to measure your engineering effectiveness
  - Focus on what generates the highest return on investment for your time spent.
- Systematically increase the leverage of your time.
  - Find ways to get an activity done more quickly, to increase the impact of an activity, or to shift to activities with higher leverage.
- Focus your effort on leverage points.
  - Time is your most limited asset. Identify the habits that produce disproportionately high impact for the time you invest.


### Chapter 2: Optimise for learning
(pg.23)
- Those with growth mindsets are willing to take steps to better themselves, whereas those with fixed mindsets are not.


### Chapter 3: Prioritize regularly
(pg.42-43)
- Regular prioritization is a high-leverage activity, because it determines the leverage of the rest of your time.
- [those who follow checklists] eliminate large classes of avoidable errors simply by writing steps down and tracking what needs to be done.

(pg.44-45)
- the human brain is optimized for processing and not for storage.
- The goal isn't to establish a total ordering of all your priorities, since any ordering you make will be based on imperfect information; instead, it's to continuously shift your top priorities toward the ones with the highest leverage, given the information you have.

(pg.46-47)
- When you get important things right, the small things often don't matter.
- After you ship a change that produces value, find the next task that will produce value. Prioritise the ones that produce the most value with the least amount of effort. Once you do this a few times, it becomes easier to recognise which tasks are the most valuable.
- Don't treat every invitation to do something as an obligation. Explain how the meeting, bug, or project will detract from your other tasks, and discuss whether it should have higher priority. If not, you probably shouldn't be spending your time on it. Don't try to get everything done. Focus on what matters - and what matters is what produces value.

(pg.49)
- Be wary if you're spending too much time on important and urgent activities. A high-priority bug or a pressing deadline for a project may be important and urgent, but assess whether you're simply addressing the symptoms of the problem and not its underlying cause. Oftentimes, the root cause is an underinvestment in a non-urgent important activity.
- Investing in non-urgent important activities can reduce urgent tasks and their associated causes.

(pg.50)
- Engineers needs longer and more contiguous blocks of time to be productive than many other professionals.


### Chapter 4: Invest in iteration speed
(pg.73)
- Find an area where a tool could save time, build it, and demonstrate its value. You'll earn leeway to explore more ambitious avenues, and you'll find the tools you build empowering you to be more effective on future tasks. Don't let the pressure to constantly ship new features cause the important but non-urgent task of building time-saving tools to fall by the wayside.

(pg.75)
- "Effective engineers have an obsessive ability to create tight feedback loops for what they're testing. They're the people who, if they're dealing with a bug ... have the instinct to spend 20 minutes to wire things up so that they can press a button and get to the exact state they want in the flow every time."
- The next time you find yourself repeatedly going through the same motions when you're fixing a bug or iterating on a feature, pause. Take a moment to think through whether you might be able to tighten that testing loop. It could save you time in the long run.

(pg.76-77)
- Get proficient with your favourite text editor or IDE.
- Each minute spent writing boilerplate code for a less productive language is a minute not spent tackling the meatier aspects of a problem.
- Learn basic commands like grep, sort, uniq, wc, awk, sed, xargs, and find, all of which piped together to execute arbitrarily powerful transformations.
- Prefer the keyboard over the mouse.

(pg.78-79)
- Automate your manual workflows. Developing the skills to automate takes time, whether they be using shell scripts, browser extensions, or something else. But the cost of mastering these skills gets smaller the more often you do it and the better you get at it. As a rule of thumb, once I've manually performed a task three or more times, I start thinking about whether it would be worthwhile to automate it.
- Make it fast and easy to run just the unit tests associated with your current changes. Use testing tools that run only the subset of tests affected by your code. Even better, integrate the tool with your text editor or IDE so that you can invoke them with a few keystrokes. In general, the faster that you can run your tests, both in terms of how long it takes to invoke the tests and how long they take to run, the more you'll use tests as a normal part of your development - and the more time you'll save.
- The sooner you acknowledge that you need to personally address the bottleneck, the more likely you'll be able to either adapt your goals or establish consensus on the functionality's priority.

(pg.80-81)
- Don't wait until after you've invested massive amounts of engineering time to seek final project approval. Prioritise building prototypes, collecting early data, conducting user studies.
- Explicitly ask the decision makers what they care about the most, so that you can make sure to get those details right.
- Don't defer approvals until the end.
- Plan ahead. Expend slightly more effort in coordination; it could make a significant dent in your iteration speed. Get the ball rolling on the requirements in your launch checklist, and don't wait until the last minute to schedule necessary reviews. Again, communication is key to ensure that review processes don't become bottlenecks.
- "Premature optimisation is the root of all evil."
- Find out where the biggest bottlenecks in your iteration cycle are, whether they're in the engineering tools, cross-team dependencies, approvals from decision-makers, or organisational processes. Then, work to optimise them.
