---
title: "Developing a baseline schedule"
icon: "Baseline"
---


A construction project requires careful planning and execution. The Critical Path Method (CPM) baseline schedule lists all necessary tasks and ensures the project is completed on time, within budget, and to quality standards. However, a high-quality schedule is more than just correct durations and structure; it’s a reactive, dynamic document that shows impacts and aligns with the project’s intended build.

Listing all tasks, assigning durations, and establishing relationships create a logical order. Superimposing this information on a calendar yields a readable plan. Prioritizing tasks based on sensitivity to delaying the project end date determines the critical path, which ensures certain areas are done on time

Understanding the critical path and sensitive tasks allows project managers to prioritize work and ensure timely completion. Accuracy is crucial; all logic, durations, and best practices must be followed for effective management. Strict attention to detail and honesty are essential to avoid scheduling failures.

## What is Schedule Quality?

Schedule quality refers to the structural integrity of the schedule or the level at which best practices have been incorporated into the CPM scheduling program when developing and updating the schedule.

Robins & Morton has developed an internal Schedule Quality System you can use to validate your schedule's quality. Reach out to Daniel Soliman for more information.

### **Best Practices for Building a High-Quality Schedule**

For a schedule to be of high quality, you must establish three things within the schedule:

* Sufficient detail
* All necessary logic
* Accurate durations

Note: durations are not static and are subject to change.

The whole concept behind the critical path is that whenever you see a critical path activity, you have to hit that duration, or you will be delayed. Note that critical paths, like durations, are not static.

Regardless of whether your durations or critical path shift throughout the job, critical path activities produce a benchmark explaining the activities that require resources or they will impact the end of the job.

Essentially, schedule quality must be nearly “perfect” for schedules to be effective because, without quality, the critical path is likely wrong–making the schedule misleading. This process might take more planning than you have done in the past. However, proper scheduling is a process of continuous improvement: Plan→ Schedule→ Optimize.

## Baseline Schedules: Planning vs. Scheduling


To maximize project scheduling effectiveness, remember that schedules demand continuous planning and optimization. Each phase contributes to creating quality.

Follow a strategic process: first plan thoroughly by examining drawings, mapping sequences, understanding job details, and conceptualizing organizational structures before building the schedule. Don't rush into scheduling without comprehensive preparation.

Optimization is crucial. Review your schedule multiple times to ensure:

* Contract alignment
* Critical path activity duration validity
* Complete logical connections
* Overall schedule integrity

Analyze and tweak the schedule, making necessary adjustments to achieve an optimal baseline. Commit to continuous improvement throughout the scheduling process.

### **Step 1: How to Set Up a Baseline Schedule**

You first need to choose a scheduling program, the unofficial standard at Robins and Morton is Oracle's Primavera Cloud. The main point of OPC[^1]  it is designed to give you a float value so you can understand critical path sensitivity and quickly visualize your schedule so you do not have to think about how to draw it out.

### **Step 2: Working Sessions**

Conducting collaborative working sessions is crucial for project planning. Gather project managers, superintendents, site teams, and subcontractors to map out the project plan and schedule. Encourage comprehensive input and collective brainstorming by discussing critical questions like site clearance sequence and optimal work order.

### **Step 3: Map Organizational Structure**

Next, take all the information from your working session to develop an organizational structure. Mapping your organizational structure, also known as activity codes or work breakdown structures (WBS), allows for clean-cut and understandable schedule data.

Organizing activities into buckets is vital as the process tells you something intuitively by breaking your schedule into components. What does this activity fall into (structural, design, interior, exterior, etc.)?  Then break down activities by area or location. If you skip over this step, you have a waterfall of activities not organized by location, area, or trade. Without organizational structures, the schedule becomes confusing.


In the schedule above, there is no order. There is just a hodgepodge of activities that bounce all over the place.


Now, you can view the schedule the way you think about it in your head. The program lists activities over a calendar in a specific order. You want your schedule to speak to you and your project team to mirror your plan and have a structured order.

### **Step 4: List Activities and Set Durations in Your CPM Tool**

In step three, you gave your schedule an organizational structure that intelligently houses information. Step four entails listing all the activities and durations you need to fill your schedule.

#### **Listing Activities

As you list them, the activities will be assigned an activity ID. However, you want to understand the activity and assign it to a Work Breakdown Structure (WBS), then give it a name and a duration. You can write these down in Excel and then transfer them over or build them into the scheduling program.

#### **Setting Durations**

The human mind is wired toward the best-case scenario or [planning fallacy](https://nesslabs.com/planning-fallacy).

Time and time again, I have seen schedules created without considering unforeseen circumstances. Knowing that, on average, unforeseen circumstances pop up around every corner throughout the project lifecycle (material delays, rain, change orders, RFIs, etc.), schedulers should set durations with risk in mind.

Not factoring potential risks into durations is a massive contributor to projects being delayed and over budget. So, get buy-in from your team when setting durations to ensure they are feasible and have room for the unexpected.

You must also be mindful of long-duration activities (any activity lasting longer than 20 days). Suppose you think about an activity that will last an entire month. In that case, it can be broad, making the statusing and estimating the percent completion of that activity rather tricky. And while the DCMA recommends not having activities longer than two months, my experience tells me that two months is much too long. I suggest keeping most construction activities between five to 20 days or one to four weeks (_note: procurement activities, etc., can be longer).

### **Step 5: Apply Necessary Relationships to Activities**

CPM tools function on activity relationships or logic ties. These logic ties establish how activities flow throughout the job.

Schedulers can tie activities together in the following ways:

* Finish-to-Start: a tie denoting that a Successor can start after its Predecessor finishes.
* Start-to-Start: a tie denoting that a Successor can start after its Predecessor starts.
* Finish-to-Finish: a tie denoting that a Successor can finish after its Predecessor finishes.
* Start-to-Finish: a tie denoting that a Successor can finish after its Predecessor has started.
* Lag: an additional time component assigned to relationships.

#### **Finish-to-Start, Lag 0**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/finish-to-start-lag-0.png)

Finish-to-Start (F-S) relationships are logical ties denoting that a successor (B) can start after its predecessor (A) is complete. F-S connections are considered a best practice because Crew A can clear out once Activity A finishes, and Crew B can begin working on Activity B. The example above shows zero lag, meaning activity B starts immediately after activity A finishes.

#### **Finish-to-Start, Lag 2**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/baseline-schedule-fs-lag-2.png)

This F-S tie indicates you are going to start Activity B two days after Activity A. For example, the curing of concrete is a common place where lag is used because you need to wait for the concrete to dry. So, you tell the program not to start the successor until two days after the predecessor finishes.

#### **Finish-to-Start, Lag – 2**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/finish-to-start-lag-neg-2.png)

Another way to show Finish-to-Start is negative lag. Negative lag is frowned upon, but it is okay as long as you do not have giant lag numbers. The risk is that the predecessor is not going to be completely done before you start the next activity.

#### **Start-to-Start, Lag 0**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/start-to-start-1.png)



Start-to-Start (S-S), lag zero, ties indicate you are going to start both activities on the same day. For example, fire sprinklers and plumbing could begin on the same day.

#### **Start-to-Start, Lag 2**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/start-to-start-lag-2.png)



S-S, lag 2 ties allow you to stagger a little. For example, you can have the mechanical work start and the electrical work begin two days later. You can put the lag of two days to stagger the start dates consistently with what you anticipate, which is generally the most common way to do this.

#### **Start-to-Start, Lag – 2**

![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/start-to-start-lag-negative.png)

S-S, lag – 2 means you are going to start activity B two days before activity A. If that is the case, you should generally just switch the two. So, this logic tie is generally not recommended.

#### **Finish-to-Finish, Lag 0**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/finish-to-finish.png)



Finish-to-Finish (F-F), lag zero, says that activity A will begin with activity B starting halfway through activity A, allowing them both to finish on the same day. This logic tie allows you to time the completion of things perfectly. For example, you may want drywall to start before mud and tape but have them finish on the same day.

**Finish-to-Finish, Lag 2**

![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/finish-to-finish-lag-2.png)



F-F, lag 2 allows activity A to finish two days before activity B finishes. For example, you plan to finish drywall and finish mud and tape two days later.

**Finish-to-Finish, Lag – 2**

![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/finish-to-finish-negative-lag.png)



As the previous examples show, negative lag is unreasonable. It tells the program you will finish your successor (activity B) before your predecessor (activity A). If so, you should flip the two and have them as positive lag.

### **Step 6: Apply Necessary Constraints (Date, Crew, Calendar, etc.)**

![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/schedule-analysis-triangle-cycle.png)



Until now, you’ve listed activities and organizational structures and refined your logic. However, the first pass of logic is usually incomplete, meaning you still need to sort through what is possible versus what is ideal.

For instance, you cannot install drywall until you’ve hung up your framing. You also need to consider other things that come into play, like holidays, crew logic, number of crews. I once worked on a job in Augusta that was happening during the Masters. They incorporated that into the schedule because they could not work the entire week during the golf tournament.

You need to be aware of start date issues and have a plan for the days that certain trades can’t work. To account for these items, you can put in constraints, set up calendars, and put crew logic into the schedule.



## **What is Hard and Crew Logic?**



Both hard and crew logic are required for useful schedules.

Hard logic represents logic that cannot happen any other way, i.e., mechanical, electrical, and plumbing (MEP) can’t begin until the structure is complete.



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/hard-and-crew-logic.png)



Crew logic represents logic that is 100% based on crew restraints, i.e., site teams cannot begin MEP on the second floor until it is completed on the first floor.

With crew logic, impacts become clear, and crew restraints are reflected in the plan, making the schedule reactive and allowing the site teams to see the potential consequences of delay.



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/crew-logic-impact.png)



_For more information on crew logic, visit our blog post:_ [_Missing Crew Logic: The Silent Killer of Construction Scheduling_](https://smartpm.com/blog/missing-crew-logic/).



## **Schedule Optimization**



Now it’s time to stand back and look at the overall schedule to A) ensure it is in alignment with the contract and B) see if your critical path makes sense. I suggest getting a couple of eyes on it to ensure it passes the gut check and that you did not forget anything.



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/baseline-schedule-optimization-example.png)



The most important thing to check is schedule quality. As mentioned above, there is an industry “gold standard” for gauging schedule quality called the DCMA 14-point check. It looks at things like the frequency of missing logic, the existence of negative lag, high float, and high durations.



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/dcma-14-schedule-quality.png)



Within these indicators, three areas are most important regarding quality: missing logic, constraints, and high-duration activities. These driving indicators are typically at the root of all other schedule-quality issues.

For instance, missing logic and constraints drive float. High-duration activities can alter the critical path. If you have a lot of high-duration activities, you likely have a lot of start-to-start and finish-to-finish ties. All these things are generally interrelated, and they contribute to an abundance of risk:

* Missing logic makes your schedule non-reactive and misleading.
* Too many constraints permit user-determined start dates instead of letting the program dictate through logic ties.
* High-duration activities are hard to status, putting the critical path at risk.

Again, all these factors drive each other.



### **Schedule Quality Cheat Sheet**



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/schedule-quality-cheat-sheet.png)



The DCMA methodology is a pass-fail type situation. You fail if more than 5% of your activities have missing logic. If more than 5% of your schedule has constraints, you fail. You fail if more than 5-10% of your schedule is start-to-start or finish-to-finish. I disagree with that.

I think construction projects vary. There are linear, horizontal, small, and mega projects. So, above is a grading rubric that you can adjust along with about 20 more items that help you gauge best practices in your schedule, but you decide the thresholds.



#### **Total Relationship Ratio**



I like to look at the ratio of logic to activities. For instance, how many logic ties we have compared to how many activities greater than 1.5 tells me that, on average, every activity potentially has up to two successors. This tells me that there is hard _and_ crew logic present. Once you are over that 1.5 range, it shows evidence of true logic.

#### **Logic Ties**

Next is the number of finish-to-start ties, the number of start-to-start ties, the number of finish-to-finish ties, and the number of start-to-finish ties, which should be 0%. Generally speaking, 80% of logic ties should be finish-to-start, including hard and crew logic. In addition, 10% of both finish-to-start and start-to-start is a good indicator. But, once you get to the 15% range, there might be an issue with high levels of compression, lack of detail, or long-duration activities.

#### **Missing Logic**

For missing logic, the general rule of thumb is that every activity–except the first and the last–should have a predecessor and a successor.

You want to do your best to ensure nothing alters the critical path. Otherwise, you will have a non-reactive schedule because if nothing is following an activity when something is supposed to, the program will not know to push out a successor if the predecessor is delayed.

#### **Positive and Negative Lag**

It is the same for negative and positive lag. These indicate a schedule with a lack of detail or one that is overly compressed, resulting in an inaccurate critical path.

#### **Constraints**

Activities need to have drivers, not an arbitrarily chosen start and end date because delays happen. I have often seen finish constraints put into a schedule for a gauge of delays. However, this tends to be done in multiple activities. Too many constraints result in a non-reactive schedule with a flawed critical path. So, when delays happen, float becomes negative, more activities become red, and you lose sight of the critical path.

#### **High Float Activities**

High-float activities tell you there is missing logic or missing crew logic. If 80% of your activities have more than two months of total float, that’s basically saying 80% of your job can be delayed by two months, which is not possible. You want to know when delays happen so you can adjust. If you cannot see them in your schedule because it is poorly built with missing logic and with a ton of float, you will not know when delays happen and will end up shooting yourself in the foot.

#### **High Duration Activities**

High-duration activities show a schedule that lacks detail or is overly compressed and, again, has an inaccurate critical path.

### **Example Schedule**



![](images/baseline-schedule-example-negative-float.webp)

Here is an example of a poorly planned schedule. At first glance, it looks okay. There is an order from floor to floor. However, why is everything critical? Why is pre-construction critical? Why are the foundations, underpinning, structure, enclosure, and interiors also critical?

This shows me a schedule with too much critical path; over 30% of this schedule is critical. So, what do you see? Negative float, which means there are finish constraints. If you remove the finish constraints, you end up with the following:



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/baseline-schedule-example-finish-constraints.png)

Now, you have a solid critical path that goes through the structure, into the enclosure, to the top floor, and ultimately to close out. You now have very few activities on the critical path by making that one change to finish constraints. However, the top floor is the most critical, but every other floor has room for delay. As you go down each floor, float decreases over time from area to area, indicating missing crew logic.

Furthermore, a minimal critical path in the interiors shows incomplete logic. However, when you add crew logic, it creates a critical path that makes sense. Yes, the critical path is in the structure for a while, it gets into the enclosures and the drywall, but with crew logic, impacts are **evident.**

#### **The Negative Impact of High-Duration Activities**

![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/baseline-schedule-example-high-durations.png)

This schedule has elevators on the critical path and lists them as a three-month-long activity. However, adding more details to the elevator and breaking up the activity into smaller bits will give you a more accurate, useful critical path.



![](https://cdn-ilaggnj.nitrocdn.com/VQHQpMDJLInBLJSFwsKUBgyoSXHHkgif/assets/images/optimized/rev-af1596b/smartpm.com/wp-content/uploads/2023/03/baseline-schedule-high-durations-2.png)

The critical path is now in more than just one area of the job. It shows where and how the crews will be moving through the job.

## **How to Minimize Schedule Quality Risks**

1. Every activity needs at least one predecessor and successor (except project start and completion milestones).
2. Start constraints should be minimal, and there should be no finish constraints.
3. No activity should have longer than a 20-day duration.
4. Crew logic must be present in major trades.
5. If something seems “off” with the schedule, it probably is.

If you incorporate these guidelines every time you build a schedule, you will be set up for success. A schedule worthy of managing a job means it is trustworthy, accurate, and effective. A schedule not worthy of managing a job means that you do not have best practices built into your schedule. Therefore, your project is at risk of not having an accurate critical path. Inaccurate critical paths result in not knowing which activities are driving the end date of a job; which activities are a high priority for resource constraints; and, ultimately, results in your project delivery being late, over budget, and potentially headed to court.

[^1]: Oracle Primavera Cloud
