<h1 align="center">The Solo Developers Manifesto    </h1>

<p align="center">
  <img width="460" height="300" src="https://github.com/fawazahmed0/the-solo-developers-manifesto/raw/main/agile.png">
</p>

### Credits:
All credits goes to experienced software developers on different internet forums, who have shared their invaluable experience on how we can code better.
I have collected all this information from different places on internet and have written it into a nicely formatted guide for my personal use.

---

_This guide will help solo developers achieve what could be achieved by teams by God's mercy_

### Phases:

Each Phase should be timeboxed

#### 1. Planning:

- Define objectives/ from users perspective (what user problem it solves, what user wants etc) and not from Devs perspective (Extra features, fancy looking etc), also write basic user acceptance test
- Start this Phase ASAP to avoid going beyond deadline
- Good Research for best simplest design (Includes learning new things)
- Good upfront design (avoids future blocking issues)
- Divide this phase into subphases i.e. Research, Designing, Estimation and timebox each one
- Subdivide the work recursively till you get the smallest task unit, this helps in proper estimation
- Story -> Features -> Task -> Sub Task
- Add the tasks in backlog & group tasks into meaningful group & Sort the group by priority/MoSCoW (Must have, should have, could have, and Won't have, use users POV during prioritization) & story points (Reprioritization/Re-estimation/Redo Dead lining if new feature is added to backlog)
- Timebox each Sub Task and keep daily tasks to do list (Tasks completable in 8-9 hours)

##### 1.1 Designing :

- complicated user interactions/simple requirements interaction with simple use case design (draw.io)
- simple UI design (MS paint), use tested UI design patterns (e.g. Want to add search bar? use Google search bar design)
- Spike solution (small experiment/program to research the answer to a problem)
- simplest design (no fancy features etc, don't worry about future requirements)
- worse is better, Software that is limited, but simple to use is better, than buggy or complex software with complex features (less features, more quality)
- Don't program features until they are actually needed (YAGNI)
- Write programs that do one thing and do it well and work with other programs
- complete design: The design must cover as many important situations as is practical. All reasonably expected cases must be covered. Simplicity is not allowed to overly reduce completeness.
- Use software standards for everything (e.g. semantic versioning etc)

##### 1.2 Estimation:

- 10-30% buffer time while estimating deadline (E.g. 1-day buffer means, release date 29th-30th) (avoids stress & frustrations)
- overestimation-Parkinson's law, underestimation-no work/feature get done
- Proper estimation is very important for highest productivity (No time limit/deadline - Low productivity)

#### 2. Implementation:

- Make sure I am following the manifesto properly
- Start day by observing/tracking yesterday's task and deadline, things TODO today, and any blocking issue to fix it
- Track the work daily to meet deadline (GitHub Projects - Kanban boards) & correct productivity/blocking issue if any and prioritize accordingly
- Use pomodoro Timer Technique for Time Management -> work for n tasks for x mins(30-90mins,depending on estimated time), small break(3-5mins) if fewer than n task completed else large break(10-15mins), pomodoro is indivisible and cannot be interrupted, other things should be done after pomodoro or else abandon pomodoro. After task completion any remaining time used for Reviewing the work and also seeing from learning POV (What I learned? What could be done better etc)
- Use Test-driven development (TDD) during coding:
  - Convert software feature/requirement -> test case (concise, note it down for future unit testing),
  - run test and see it fail,
  - write code to only pass the test (No refactoring)
  - run test and see it pass (the code should not break any existing feature) (if it's gotten hard to pass the above code, then revert the above code to avoid excessive debugging) & commit,
  - refactor the new code and the whole code & commit (deepcode/standardjs --fix)

##### 2.1 Testing:

- Unit Test, Total feature test, acceptance test (users POV), stability test(stressing)

##### 2.2 Documentation & PR:

- Minimal documentation for users and also about how the code works (for myself & future Devs) (Code comments, unit test cases above function, etc)
- PR/Marketing (Write Medium/dev.to/LinkedIn Article, Reddit, Product Hunt, Answering SO, Quora, SEO keywords [etc](https://github.com/trekhleb/promote-your-next-startup), 4P's-Price, Product, Place, Promotion, Market Targeting/Segmentation message with differentiation & positioning) (Refer similar software to make marketing message), use good Graphics(pixabay), Test Market(get feedback)

#### 3. Measurement:

- Measure & document the estimated time vs actual time taken for subtask, to help in future estimation using my historical values (by seeing time taken previously for similar subtask) and also for retrospective to make things better
- Google Timer to measure task and then use Google stopwatch to measure extra time taken (This helps in future estimation by comparing estimated time vs actual time)

#### 4. Retrospective:

- Happens at end of sprint, involves looking back at how the sprint went
- what things I can use? where I can make things better?
- See why I am taking more time than estimated time for different task etc
- Try Sheets/Excel Charts to analyse my historical data
- Plot estimation vs actual time for task on a graph to see your personal time estimate accuracy trend
- Learn from mistakes (Unnecessarily complex solutions, being perfectionist, using unstable libraries effects quality/stability)
- Learn from customer question/feedback? Why is customer/user asking/saying that, is there a lacking doc/feature

### Rules:

- Time/Deadline & quality (no compromise)
- Scope (features etc, high impact features first), cost (overtime, etc)
- Shorter Sprint (1-2 weeks) release product

### Things to Remember:

- Eliminate waste (partial work, multitasking, task switching, bugs, extra features, relearning, unnecessarily complex solution, unnecessary stress, building wrong feature, rework, waiting)
- Concentrate and work on single task at a time
- Implement new learnings
- Decide as late as possible (so that to know more about problem and not waste time on things that's not required)
- Deliver ASAP
- Prepare about work & deadline mentally(by thinking about it  before starting the work or when free or idle)
- During major blocking issue during operations use stop the line technique -> stop everything (Give importance/resources to issue), assess the issue, and resolve the issue, and learn how to prevent it
- Don't beg for help, learn & do things yourself
- If stuck somewhere, then google search in Stack Overflow (& its sister sites) and GitHub issue
- If stuck, Explain the problem out loud to someone (I prefer God)
- Consider asking question at Stack Overflow as last resort (Not advisable)
- commits on one main branch to avoid merge hell (don't keep multiple feature branch)
- Start your day with most difficult/time-consuming task
- When a bug is found, tests are created before the bug is addressed (a bug is not an error in logic; it is a test that was not written)
- embrace change (new features etc)
- During sprint you might have personal ideas (Urge to Google search something), project related ideas (new features), just write those into personal notes/to-do list(or somwhere else) to refer it back in personal/work time. This will reduce stress and help us to be focused (GTD Method)
- Reread this manifesto, when you are at low productivity
- Automated testing (unit etc), CI/CD is great for software which have to be maintained for long time/always and not for small GitHub hobby projects which are onetime thing
- High cohesion in function (only does one simple task) and low coupling (low dependency on other function)
- Take break/nap(~30mins) when no longer productive/frustrated, if doesn't work, then do the work next day
- Batch Check everything one time daily (emails, messages, SMS, calls, news, sites etc) (Don't check again & again) and mark imp emails to reply at end of work time
- Headphones (inc conc.mp3) to avoid distraction

### Productivity Tools:

- G Suite (Calendar, sheets etc), VS Code (Code Completion), GitHub Copilot
- Code Time (Time tracker metrics)
- Prowritingaid, Hemingwayapp (Documentation/Marketing message simplification)
- GitHub Projects (Agile Project Management, Kanban boards)
- GitHub Actions (CI/CD)
- DeepCode/SynkCode(code review), StandardJS(Consistent code style)

### Why Solo is Great:

- Be humble & happy & be thankful to God for being solo developer, as you are saved from idiocracies of a team
- No Difference of opinion
- No rework due to communication gap
- No need to show off work to someone
- No status updates
- No conflicts
- No junk office timings
- No begging for your rights
- No need to compete
- No rules you make the rules,
- No waste time travelling
- Great work/life balance being solo
- Your God is your boss

### Daily Routine:

Prophet Muhammad (May God's Peace be on him) has been guiding example for this daily routine.

Divide your daily routine into three different parts

- Work Time
- Personal Time
- Family/Social Time

You should give equal importance to each. Some people work whole day without giving time to themselves or their family/Other people. Use this manifesto or Note-Taking app (Google keep-TODO List) or Kanban boards (Asana) to manage personal & Social Time

#### Work Time:

- This is the time you work
- 9 Hours/Daily(incl breaks) (Note down work starting time, to track how many hrs worked)
- Prefer working after waking up (Start with work, rather than checking emails, messages, SMS, calls, news, sites etc to avoid distractions)
- 1-day rest after every iteration/sprint/release
- Take 15-30min nap 6-7 hrs after waking up (Increases Productivity)
- Have ergonomics Computer chair & table(keep back posture straight) and take 20sec break every 15mins (Use stretchly, stand up and move during break & stretch your body) (Prevents Computer related injuries)

#### Personal Time:

- This is the time you give to yourself, for example looking your health, clothes, hygiene, ID renewal etc (For example torn shoes, repair it or get it repaired from cobbler or buy new one)
- Exercise weekly twice (e.g.: Rope skipping/Burpees 10mins for healthy heart)(Sat,Tue Fixed Date)
- Be physically active by performing household chores
- Eat moderately (avoids laziness)
- Start working on tasks in here after work time

#### Family/Social Time:

- This is the time you give to your family and other people, such as bringing grocery for family, giving time to wife, parents etc, taking family member to doctor when they are sick, helping in household chores etc
- Start working on tasks in here after work time

---


### Manifesto Implementation:

The [Free Currency Exchange API](https://github.com/fawazahmed0/currency-api) was made by following this manifesto by a single developer in 2 days time

Please Star this repo by clicking on [:star: button](#) above [:arrow_upper_right:](#)

<br>
<br>
<br>

[:pencil2:*Improve this page*](https://github.com/fawazahmed0/the-solo-developers-manifesto/edit/main/README.md)



