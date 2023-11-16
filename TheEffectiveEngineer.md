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


### Chapter 5: Measure what you want to improve
(pg.86-87)
- Measuring progress and performance might seem to fall within your manager's purview, but it's actually a powerful tool for assessing your own effectiveness and prioritizing your work. As Peter Drucker points out in 'The Effective Executive', "If you can't measure it, you can't improve it". In product development, it's not uncommone for a manager to conceive of some new feature, for engineers to build and ship it, and for the team to celebrate - all without implementing any mechanism to measure whether the feature actually improved the product experience.
- Good metrics... help you focus on the right things... confirm that the product changes achieve your objectives.
- Only way to be consistently confident when answering questions like these is to define a metric associated with your goal.
- When visualised over time, good metrics help guard against future regressions.
- Engineers know the value of writing a regression test while fixing bugs: it confirms that a patch actually fixes a bug and detects if the bug resurfaces in the future.
- Good metrics can drive forward progress.
- A good metric lets you measure your effectiveness over time and compare the leverage of what you're doing against other activities you could be doing instead.

(pg.88-89)
- Is there some way to measure the progress of what I'm doing?
- If a task I'm working on doesn't move a core metric, is it worth doing? Or is there a missing key metric?
- Ultimately attempting to increase output by increasing hours worked per week is unsustainable. It is much more reasonable to align your metric with productivity per week, where productivity in your focus area is measured by factors like product quality, site speed, or user growth.

(pg.90)
- Tracking the number of outstanding bugs instead of bugs fixed would have de-incentivized this behaviour [writing sloppy code to have more easy bugs to fix]
- Measure the fraction of users who are still weekly actives the nth week after signing up, and track how that number changes over time. This metric provides more actionable insight into how product changes have affected the engagement of newer cohorts of users as compared to older ones.

(pg.92-93)
- When deciding which metrics to use, choose ones that maximise impact, are actionable, and are responsive yet robust.
- Look for a metric that, when optimised, maximises impact for the team.
- ...what differentiates great companies from good companies is that they align all employees along a single core metric... the economic denominator. The economic denominator answers the question "If you could pick one and only one ratio - profit per x... - to systematically increase over time, what x would have the greatest and most sustainable impact on your economic engine?" In the context of engineering, the core metric should be the one that, when systematically increased over time, leads you and the rest of your team to make the greatest and most sustainable impact. Having a single, unifying metric ... enables you to compare the output of disparate projects and helps your team decide how to handle externalities.
- An actionable metric is one whose movements can be causally explained by the team's efforts.
- Increases in vanity metrics [e.g. page views per month. total registered users, total paying customers] may imply forward product progress, but they don't necessarily reflect the actual quality of the team's work.
- A responsive metric updates quickly enough to give feedback about whether a given change was positive or negative, so that your team can learn where to apply future efforts. It is a leading indicator of how your team is currently doing.
- Dedicate the time to pick the right metric, whether it's just for yourself or for your team.

(pg.94)
- When we don't have visibility into our software, all we can do is guess at what's wrong.

(pg.96)
- Adopting a mindset of instrumentation means ensuring we have a set of dashboards that surface key health metrics and that enable us to drill down to the relevant data.
- Therefore we need to build flexible tools and abstractions that make it easy to track additional metrics.
- Measure anything, measure everything.
- By graphically correlating these metrics with the times of code deployments, ... able to quickly spot when a certain deployment goes awry.
- Successful technology companies build the quivalent of a pilot's flight instruments, making it wasy for engineers to measure, monitor, and visualise system behaviour. The more quickly that teams can identify the root cause of certain behaviours, the more rapidly they can address issues and make progress.

(pg.98)
- ... you don't need accurate numbers to make effective decisions; you just need ones that are in the right ballpark. Ensuring you have access to a few useful numbers to approximate your progress and benchmark your performance is a high-leverage investment: they provide the benefits of metrics at a much lower cost.

(pg.102-103)
- Using data to support your arguments is powerful. The right metric can slice through office politics, philosophical biases, and product arguments, quickly resolving discussions. Unfortunately, the wrong metric can do the same thing - with disastrous results. And that means we have to be careful how we use data.
- When it comes to metrics, compare the numbers with your intuition to see if they align. Try to arrive at the same data from a different direction and see if the metrics still make sense. If a metric implies some other property, try to measure the other property to make sure the conclusions are consistent.

(pg.104-105)
- Log data liberally, in case it turns out to be useful later on.
- Build tools to iterate on data accuracy sooner.
- Cross-validate data accuracy by computing the same metric in multiple ways.
- When a number does look off, dig into it early. Understand what's going on. Figure out whether the discrepancy is due to a bug, a misinterpretation, or something else.
- Make sure your data is reliable. The only thing worse than having no data is the illusion of having the right data.


### Chapter 6: Validate your ideas early and often
(pg.110-111)
- Iterative approaches lead to fewer costly errors and give us opportunities between each iteration to collect data and correct our course. The shorter each iteration cycle, the more quickly we can learn from our mistakes. COnversely, the longer the iteration cycle, the more likely it is that incorrect assumptions and errors will compound. These cause us to veer off course and waste our time and effort.
- The sooner that er gain a better understanding of a risky issue that impedes our progress, the earlier we can either address it to increase our chances of success, or change course to a more promising avenue.
- "What's the scariest part of this project? That's the part with the most unknowns and the most risk. Do that part first."
- ...defines the MVP as "that version of a new product which allows a team to collect the maximum amount of validated learning about customers with the least effort."

(pg.114-115)
- Before investing time into fixing it [a bug], you can use data from logs to validate whether the bug actually is affecting a sufficient number of users to justify spending your resources.
- An A/B test doesn't help you decide which variation to launch. Even if you were absolutely convinced that a certain change would improve metrics, an A/B test tells you how much better that variation actually is. Quantifying that improvement informs whether it makes sense to keep investing in the same area.

(pg.118)
- Initially, it's tricky to determine what's practically significant, but as you run more experiments, you'll be able to prioritise better and determine which tests might give large payoffs.

(pg.121-123)
- View feedback and criticism not as personal attacks but as opportunities for improvement.
- Focus on making iterative progress, and use those iterative commits as forcing functions for soliciting feedback. Don't be the person who sends out the ginormous code review.
- It's better to get harsh feedback from a teammate early on than to get it from users later when something doesn't work.
- The most direct path to getting feedback is to request it.
- Research shows that explaining an idea to another person is one of the best ways of learning it yourself; moreover, your explanation might reveal holes in your own understanding.
- Prepare beforehand. Make sure that you can articulate the problem that you're trying to solve and the approaches that you've already tried. After the discussion, reciprocate with an offer to be a sounding board for their ideas.
- Design the interface or API of a new system first. After your interface is designed, prototype what the client code would look like if your feature were built. Creating a concrete picture of the interactions will surface poor assumptions of missing requirements, saving you time in the long run.
- The [design] document doesn't have to be particularly formal - it could just be a detailed email - but it should be comprehensive enough for your reader to understand what you're trying to do and be able to ask clarifying questions.
- ...structure ongoing projects so that there is some shared context with your teammates. Rather than working on a separate project in parallel with your teammates, consider working together on the same project and tackling the other project together afterwards. Or, consider working in the same focus area as your teammates. This creates a shared context, in turn, reduces the friction in discussions and code reviews. Serialising team projects to increase collaboration rather than doing them independently and in parallel can provide learning benefits as well: each project takes a shorter amount of calendar time to complete, so within a given timeframe, you can be exposed to a larger diversity of project areas.
- Solicit buy-in for controversial features before investing too much time. This might mean floating the idea in conversations and building a prototype to help convince relevant stakeholders. Sometimes, engineers misconstrue or dismiss this type of selling and marketing as office politics, but it's a fairly logical decision from the viewpoint of leverage.
- If a conversation to get feedback only takes a few hours but an implementation takes weeks, the shorter path to earlier feedback is extremely valuable. Failing to get buy-in from those who understand the domain might mean you're on the wrong path.
- ... creating a feedback loop is necessary for all aspects of a job. "It applies to recruiting. It applies to team design. It applies to how you build your culture. It applies to your compensation structure"
