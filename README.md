
# **_Mens Toilet Interactive Device Project_**

**_Author： Zhentao Lu_**

**_02/2015-03/2016_**

**_Copyright belongs to the author_**
***
# Contents
# Preface
# 1. Define the problem
## a) Define the project
### i. Select the project
### ii. Sketch the concept
### iii. Define and tailor the process
### iv. Define the owner, the customer and the user
### v. Write a mission statement
## b) Define the context
### i. Define the system boundary
### ii. Document the context of the system
### iii. Study the current coDocument the context of the system
### iv. Collect customer comments
### v. Summarize the project (product) objectives
## c) Define functional requirements	
### i.Collect use cases	
### ii.Prioritize use cases	
### iii.Describe use case behaviours	
### iv.Summarize functional requirements from use cases	
### v.Repeat for secondary use cases	
### vi.Finalize requirements	
# 2.Measurement the need and set targets	
## a)Measure the need	
### i.Determine measure of effectiveness	
#### 1.Identify the goals of the measurement	
#### 2.Refine the goals with questions	
#### 3.Specify the metrics	
#### 4.Develop Data collection methods	
### ii.Repeat for secondary goals	
### iii.Weight the product objectives	
### iv.Benchmark competition on measures of effectiveness	
## b)Translate to technical requirements	
### i.The house of quality	
#### 1.Identify engineering characteristics	
#### 2.Map engineering characteristics to customer attributes	
#### 3.Document engineering interrelationships	
#### 4.Identify units of measure and benchmark competitions	
#### 5.Determine target technical performance measure	
### ii.Collect and rationalize system-level requirements	
## c)Identify the customer value proposition	
# 3.Explore the design space	
## a)Discover concepts	
### i.Clarify the problem and decompose the functions	
### ii.Brainstorm and research	
### iii.Organize concept fragments	
### iv.Prune and expand	
## b)Explore concepts	
### i.Combine concept fragments	
### ii.Generate integrated concepts	
## c)Identify subsystem	
# 4.Optimize design choices	
## a)Select concepts	
### i.Identify alternatives	
### ii.Identify attributes	
### iii.Screen the alternatives	
### iv.Rate alternatives	
### v.Weight the attributes	
### vi.Calculate weight and sort	
### vii.Score and select alternatives	
## b)Optimize parameters	
### i.Define the product family	
# 5.Develop the architecture	
## a)Design the behaviour	
### i.Review use cases, context, and functional requirements	
### ii.Map behaviours to subsystems	
### iii.Identify messages, triggers, and interfaces	
### iv.Identify system states	
### v.Set targets for behaviour	
### vi.Extract functional requirements to originating requirements	
### vii.Trace-derived requirements to originating requirements	
### viii.The centrality of the operational description template	
## b)Design the flow and control	
### i.Identify functional relationships	
### ii.Summarize state changes	
## c)Design the structure	
### i.Identify interfaces and finalize subsystems	
### ii.Document links	
### iii.Identify emergent interactions	
### iv.Sketch a design concept	
### v.Create a rough-cut bill of materials	
### vi.Create a rough-cut reliability estimate	
### vii.Allocate target technical performance measure to subsystem	
# 6.Validate the design	
## a)Verify requirements	
### i.Conduct design reviews	
#### 1.Determine if entry criteria are met	
#### 2.Schedule the review meeting	
#### 3.Present the design	
#### 4.Collect review panel comments	
#### 5.Use exit criteria to assess whether the review was passed	
#### 6.Reschedule if the review did not pass	
### ii.Develop the test plan	
#### 1.Identify behavioural test sequence	
#### 2.Develop behavioural test methodology	
#### 3.Repeat for nonbehavioural tests	
#### 4.Map test activities to system requirements	
## b)Manage risks	
### i.Conduct failure modes and effects analysis	
#### 1.Select functions	
#### 2.identify failure modes	
#### 3.assess potential impact of failure	
#### 4.brainstorm possible causes	
#### 5.suggest corrective actions	
#### 6.rate the severity of impact	
#### 7.Rate the likelihood of causal occurrence	
#### 8.Assess the risks	
#### 9.Prioritize the action	
# 7.Execute the design	
## a)Schedule the project and track progress	
### i.Develop the task list (work breakdown structure)	
### ii.Estimate durations	
### iii.Task percent complete	
### iv.Identify task inputs, outputs, and deliverables	
### v.Establish task precedence relationships	
### vi.Schedule the project	
### vii.Display a Gantt chart	
### viii.Adjust the schedule for team availability	
## b)Conduct management reviews	
# 8.Iterate the design process	
## a)Iterate until feasible	
### i.Backtracking strategies	
## b)Iterate with improvement	
## c)Iterate by level	
### i.Level-by-level decomposition: the Vee diagram	
#### 1.Detail functions into behaviours	
#### 2.Allocate nonbehavioural requirements: linked houses of quality	
#### 3.Maintain hierarchies and traceabilities	
## d)Dive and surface: a system view	
### Appendix 1 IBM Rational Rhapsody - Design black box system model	
### Appendix 2 IBM Rational Rhapsody - Design white box system model

# Preface
This project is based on the process described in the book - Getting Design Right. The author of the book is Dr. Peter L. Jackson, who is a professor in School of Operations Research and Information Engineering in Cornell University. 
This project uses similar terminology as  in the book. Readers should focus on the essence of the design, in stead of specific terms. In the book many tables are made by using Excel for analysis purpose. Here some diagrams are made by using IBM Rational Rhapsody and Microsoft Project. 

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/preface.jpg)

This project process involves eight stages – define, measurement, explore, optimize, develop, validate, execute and iterate.

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/8steps.jpg)

The presented template shows the process of product design and project management. As an example, it may not represent a delicate engineering design. Instead, it’s focusing on pre-engineering design and post-engineering test. As indicated in the traditional “Vee” model clearly indicates two parts of the procedure, the design stage and manufacturing stage and the assembly and test stage. According to the Vee model, when the project is moving from the upper left towards the bottom, the design becomes optimized with its details completed. When moving from the bottom towards the upper right, tests are preformed to verify the design at different stages.

# 1. Define the problem
## a) Define the project
### i. Select the project

Starting with an idea. That could be a problem you want to solve. This will lead you to look for possible solutions. The idea can be a solution as well. Then you should think about the problem that the solution can solve, and think about other possible solutions. Alternatively, it can be an idea of making something interesting. In this case, appealing is the issue to be considered through the process.

### ii. Sketch the concept

The best way to show your idea is to present it with a schematic drawing. It does not need to contain much details. It may be scratched on one piece of paper, which can be presented conveniently.

As an example, here we present a design of a gaming device install in toilet of shopping malls. Users can play games, such as angry birds through the touch screen. Advertisement is displayed while idle. 

# `picture to be added`

### iii. Define and tailor the process

Depending on your budget of time and money, you need to find a balance way between how much resource spending on scheduling and how much spending on performing. You may consider skipping part of the procedure presented here, but please note that this should be done with caution, as the procedure is a result based on many professionals' decades of practice. Therefore tailoring the procedure requires extensive experience.

### iv. Define the owner, the customer and the user

Sometimes all these three roles can be represented one, but most of the time they are different. 
    Owner: sets design goals and authorizes major design decision.
    Customer: purchases the system and prepares for the usage.
    User: actually uses the system.

In our case, the gaming device will be installed in shopping malls,
    Owner: the vendor
    Customer: shopping malls
    User: male adults

### v. Write a mission statement

Write a mission statement to describe the goal of the project. The statement is expressed by the view of the owner. It should be concise and formal. 

The goal of the above mentioned project is to design a gaming device which is installed in toilets in shopping malls for gaming and advertising purpose. 

## b) Define the context

### i. Define the system boundary

For project developed by a team, effective communication is essential. System boundary should be defined at the beginning of the process, which defines 
1. internal issues, the issues can be handled within the team.
2. external issues, the issues are not controllable. 
When a new encounter appears, it is necessary to determine whether it is internal or external. If it is not relevant, then it can be ignored.

Here, the gaming device is installed in toilets. The design is focused on gaming device. Any toilet related modification is not considered here. 

### ii. Document the context of the system

Now it’s time to think about the relationships between the system we are going to design and the external entities.

#### 1. Context diagram



#`the diagram is to be added`



The system we are going to design is placed in the center of the drawing and it is surrounded by external entities. Those external entities are linked to the center by lines. Due to their external attribute, there are few things we can do about them. As indicated in the diagram, a sentence can be formed by combining the words in the external entity, on the line, in the system. The sentence expresses the relationship between the external entity and the system.

#### 2. Context matrices



#`table to be added`



The sentences generated in the previous section are presented in the table above. For convenience, here we use capital letters such as A, B, C to represent different external entities.

### iii. Study the current context

It is necessary to consider the system in the context in which it will be used. So it's necessary to visit the customer, examine the environment, and collect information. When studying the environment, the operator should act as the following roles: observer, apprentice and partner. An observer is to watch the process without changing anything. An apprentice is to learn the current process and think about the reason of doing it. Sometimes an apprentice can transfer into a questioner. A partner is to get involved in the process a little deeper and look for alternative ways to complete the same task in the process. Note that the collected information should be processed afterwards, so that redundant information can be removed.

The environment in our case is shopping malls. Things worth noticed are
* Children that are under-age may used the toilet.
* People tends to ware more clothes in winter while less in summer.

### iv. Collect customer comments

The product you are going to design may be an ideal one and there is no similar product in the market. Customer comments may be a good source of information. The comments can be obtained from surveys, error logs, warranty claim of relevant products, even distributing the prototype of your design and getting feedback.

Here, customers may concern 
* if the game is fun
* measures can be take to prevent users playing the game for too long
* if the device is robust 
* may receive and display advertisements properly

### v. Summarize the project(product) objectives

After collecting many comments from customers, it’s necessary to extract a statement of project objectives. The way of extracting can be diving and surfacing. Diving means developing the details of the system. Surfacing means developing an abstract idea of the system. More practice way to apply the concept is separated into two steps. The first one is to put relevant comments in one group. Then write down a name or sentence above those comments.

#`pic to be added`

Finally, the result of summary should be a table showing all concerns from customers.

Here, the goal of our project is to design a gaming device installed in toilets in shopping malls, with minimum modification to the environment during the installation. The game should be fun to play. The device should be robust, water-proof, easy to clean and maintenance. Measures can be taken to prevent long time occupation of the toilet.

## c) Define functional requirements

Now it’s time to list functional requirements of the system. The list shows what kind of functions the system should have. The requirements should be stated using “shall” instead of “should”. When writing requirements, pay more attention to not restricting the design. At the same time, try not to miss important requirements. “Diving-and-surfacing” method is especially useful for the people who don’t have much experience on writing requirements.

### i. Collect use cases

Use case represents examples of different users interacting with the system. Different perspective results in different use cases. Some of them are very obvious but some are not. It's a good time for the team to brainstorm more practical use cases

For our project, some of the use cases are listed below,
* Adult male playing the game
* Technician installing the device in the toilet
* Cleaner cleaning the toilet
* Stuff from the shopping mall displaying advertisements 
* When the toilet is occupied too long, the game shall cease and a message shall be displayed on the screen to suggest that the user shall finish using the toilet as soon as possible
* Technician fixing the device

#`picture shall be added`

### ii. Prioritize use cases

Normally the team will have collected many use cases by now. It's important to prioritize the use cases according to three levels: high, medium, low. For use cases with high priority, it is necessary to describe the interaction between the user and the system. 





