# Scheduling 101

## Getting Started with CPM

This guide is intended as an introduction to the Critical Path Method as a process to develop schedules for project management. The Critical Path Method is a systematic approach to project planning which can provide significant benefits in cost and completion time of many projects. The concepts were first developed at Dupont, and refined by the United States Navy in the development of the Polaris Missile. They can be applied to various projects, from manufacturing and production, to surgeries and conventions. CPM has found extensive use in the construction industry, where cost and time overruns and frequently experienced. The proper use of CPM scheduling techniques can help you avoid such issues on your own projects. &#x20;

## The CPM Concept <a href="#page_title_text" id="page_title_text"></a>

### Quick Glossary

**Task -** A task (also called an "Activity") is a specific part of a project that has an easily identified start and finish, and will take a certain amount of time (duration). A task may or may not have a dependency that must be satisfied before the task can occur. Examples of tasks are framing a wall, changing a light bulb, and printing a report. Multiple small tasks can be combined into a single task, if they are expected to be performed at the same time, but this can make tracking the performance of those tasks more difficult.&#x20;

**Task Duration -** A task will have a duration, which represents the amount of time required to complete the task, from start to finish. Durations can be calculated in many different units (hours, days, weeks, months) but the most commonly used unit is days. The duration of some tasks may be difficult to estimate, and you will need to use experience, industry guidelines, and input from subcontractors or other people upon whom the work relies in order to arrive at the best possible estimate for a task. Unforeseen circumstances such as weather delays, difficulties in obtaining funding or manpower, or variations in performance of the work can cause the duration to increase or decrease, but a good starting estimate will make your schedule much more valuable over the life of the project.&#x20;

**Task Dependency -** Dependencies between tasks show how the individual parts of the project are related to each other, and where progress on a certain task will effect the others. Most tasks in a project will require another task to either start or finish before it can take place. These dependencies are shown in CPM as Relationships (sometimes also called "Ties" or "Restraints"). A CPM relationship specifically defines two tasks, and the dependency that one has upon the other. Relationships will be covered in detail in the Relationship section of this guide. &#x20;

## How is CPM Different From What I'm Doing Now?

The Critical Path Method (CPM) is a scheduling strategy that uses task details, durations, and dependencies to create an efficient project timeline. It calculates the minimum time needed for project completion and identifies tasks critical to meeting deadlines.  The method's key feature is identifying the "Critical Path"—tasks that, if delayed, impact the project's finish date.

## How does it compare to other planning methods?

### CPM vs To-Do List (Task List)

A To-Do List outlines tasks needed for a project, typically in planned order, but lacks detailed info on durations or dependencies. It's quick for a basic sequence overview but may omit critical tasks due to missing dependency insights. While time estimates can be included, connecting durations for a total project timeline isn’t feasible.

### CPM vs Work Calendar

This type of planning expands on the To-Do List by incorporating expected work days for each task, and plotting them against a calendar. These types of schedules are commonly used to avoid crew or equipment scheduling conflicts, by illustrating what work is being performed on a given day. Weather delays and production issues can cause the expected work days to change, which requires manually estimating the new work days, and applying them to the calendar.

### Critical Path Method

The critical path method starts in the same place as all other planning, creating a list of Tasks to be performed for the project. Rather than try to assign specific work days to a activity, a task duration is estimated, based on experience and industry standards, and the CPM is used to calculate what the earliest date we can start and finish a task is. Once the Tasks have been identified, the Dependencies between tasks have to be explored, and defined as Relationships. This processes of exploring dependencies will frequently uncover Tasks that were not previously identified, and possibly lead to revision of Task descriptions, work Durations, and creation of additional Relationships. This exhaustive examination of the work process is the foundation of a good schedule.The Tasks and Relationships are then entered into the Critical Path Method software, and the mathematical algorithms that CPM is based on are run on the provided date. This will then produce an earliest project completion date, early and late start and finish dates for each task to achieve this finish date, and a Critical Path, that identifies the work that is most likely to affect the completion date.

## Advantages of the Critical Path Method

A major advantage of this planning is that changes to the schedule can be mathematically evaluated using CPM software or by hand to determine their total effect on the project. It recalculates start and finish dates for individual tasks to ensure dependencies are satisfied before the planned start and finish. This can cause a new critical path to emerge, requiring a project shift in focus to stay on track. While the Critical Path Method requires additional work and research for a thorough schedule, it remains a useful tool throughout the project, even with significant changes.

### Tasks & Activities

The first step in developing a schedule is listing the tasks required to complete the project. Consider the level of detail needed for the schedule’s effectiveness. The purpose and intended audience may dictate a high-level summary or a specific work plan.

With your desired level of detail in mind, list the tasks. Resources include previous schedules, project specifications, and input from subcontractors. You can also mentally or physically note each task. The task list doesn’t have to be complete, but the more accurate it is, the less time you’ll spend revising it.

After identifying a task, define its duration, the expected time for performance. This is usually in work days, which may differ from calendar days. Developing accurate task durations is challenging and requires resources like experience, industry guidelines, publications, and subcontractor input.

A common approach is to determine the total quantity of items to be installed. Then, identify a quantity per hour, week, day, etc. and divide the total by this number to get a reasonable and sound duration. Not every task is quantifiable, but many have a quantity that can be isolated for estimating.&#x20;

**Example Task List - Making a Sandwich:**

* Select Bread
* Select Meat
* Select Condiments
* Select Cheese
* Slice the Bread
* Place Bottom Slice of Bread on Work Surface
* Apply and Spread Condiments
* Apply Meat
* Slice Cheese
* Apply Cheese
* Place Top Slice of Bread on Sandwich
* Cut sandwich in half

**Example Duration Calculation - Building a Fence:**

* The length of the fence to be installed is 120 feet.
* The driving factor in construction of the fence is the installation of fenceposts, which are spaced 8 feet apart.
* It takes 20 minutes to install a single fencepost, so fenceposts can be installed at a rate of 3 per hour.

120 feet of fencing with 8 Feet between each fencepost requires 16 Fenceposts. 16 Fenceposts at 3 Fenceposts per hour is 5.3 hours for the installation of all fenceposts. Thus, the duration for the task of fencepost installation is 5.3 hours. If scheduling in days, the task would have a duration of 1 day. &#x20;

### Relationships & Dependencies <a href="#page_title_text" id="page_title_text"></a>

Once you’ve identified your schedule tasks, create relationships showing dependencies between them. To do this, identify two tasks with a dependency and determine the appropriate relationship type. The most common type is Finish-to-Start, or FS, where one task start depends on the completion of another. For instance, finishing putting on pants precedes putting on shoes, creating a Finish-to-Start relationship between them.

<Frame><img src="https://www.phoenixcpm.com/archive/wp-content/uploads/2013/03/finishtostartnetwork.png" alt="" /> </Frame>

This basic relationship type (FS) is straightforward and can describe nearly all dependencies encountered in project planning. Although there are a few special cases where other relationship types may be appropriate, you can rely exclusively on Finish-to-Start relationships for developing your schedules until you become more familiar with project scheduling.

<Frame><img src="https://www.phoenixcpm.com/archive/wp-content/uploads/2013/03/constraint.png" alt="" /> </Frame>

The example schedule above consists entirely of Finish-to-Start relationships. Typically, a schedule has a single start and a single finish. However, some tasks may have no predecessor tasks and are instead influenced by external factors that dictate their start or end dates. To position these tasks correctly in the schedule, a constraint can be applied. A constraint is an artificial limitation on an activity that impacts its start or finish, independent of the schedule's typical task and relationship logic.

<Frame><img src="https://www.phoenixcpm.com/archive/wp-content/uploads/2013/03/finishtostart.png" alt="" /> </Frame>

### Scheduling with the CPM Calculation

Scheduling, or calculating the schedule, involves running Tasks, Durations, and Relationships through the Critical Path Method to identify Starts, Finishes, Float, and the Critical Path. While understanding the process isn’t necessary, a brief overview can enhance comprehension of the Critical Path Method.

Calculating a CPM schedule is a three-step process: the Forward Pass.

<Frame>
<img src="https://www.phoenixcpm.com/archive/wp-content/uploads/2013/03/forwardpass.png" alt="" />
 </Frame>

The Forward Pass calculates the earliest start and finish dates for each task based on its dependencies, defined by relationships. These dates, called Early Start and Early Finish dates, are commonly used as “planned” project dates. Working against these dates maximizes task float in case of delays. This step also identifies the project’s completion date, which is the Early Finish of the last task. This date forms the basis for the next step in CPM, the Backward Pass.

<Frame>
<img src="https://www.phoenixcpm.com/archive/wp-content/uploads/2013/03/backwardpass.png" alt="" />
 </Frame>

The Backwards Pass step calculates the Late Start and Late Finish for each Task, which are the latest dates a Task may start or finish without impacting the Project Completion date. If the start or finish of a Task does occur after these Late dates, then either the Project Completion will occur later, or the schedule needs to be revisited to mitigate the delay. Once the Early Dates and Late Dates are known, the third step of the CPM process is the Float Calculation for each Task. Float is the number of days that an activity can be delayed before it will impact the completion date of the project. Activities with no float are called Critical Activities, and are part of the Critical Path.

<Frame><img src="https://www.phoenixcpm.com/archive/wp-content/uploads/2013/03/floatcalc.png" alt="" /> </Frame>

The Critical Path identifies which activities will cause your project completion to slip if they are delayed even a single day. There are also activities which are not critical, because they have at least one day of float, but can still have an impact if they experience multiple days of delay. Activities with very small amounts of float are considered "Near Critical" and are important to watch, as they can quickly become Critical Path items if they are delayed.
