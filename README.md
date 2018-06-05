# **_Interactive Urinal Device Project_**

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
### iii. Study the current context
### iv. Collect customer comments
### v. Summarize the project (product) objectives
## c) Define functional requirements	
### i. Collect use cases	
### ii. Prioritize use cases	
### iii. Describe use case behaviors	
### iv. Summarize functional requirements from use cases	
### v. Repeat for secondary use cases	
### vi. Finalize requirements	
# 2. Measurement the need and set targets	
## a) Measure the need	
### i. Determine measure of effectiveness	
### ii. Apply the Goal-Question-Metric method
#### 1. Identify the goals of the measurement	
#### 2. Refine the goals with questions	
#### 3. Specify the metrics	
#### 4. Develop Data collection methods	
### iii. Weigh the product objectives	
### iv. Benchmark competition on measures of effectiveness	
## b) Translate to technical requirements	
### i. The house of quality	
#### 1. Identify engineering characteristics	
#### 2. Map engineering characteristics to customer attributes	
#### 3. Document engineering interrelationships	
#### 4. Identify units of measure and benchmark competitions	
#### 5. Determine target technical performance measure	
### ii. Collect and rationalize system-level requirements	
## c) Identify the customer value proposition	
# 3. Explore the design space	
## a) Discover concepts	
### i. Clarify the problem and decompose the functions	
### ii. Brainstorm and research	
### iii. Organize concept fragments	
### iv. Prune and expand	
## b) Explore concepts	
### i. Combine concept fragments	
### ii. Generate integrated concepts	
## c) Identify subsystem	
# 4. Optimize design choices	
## a) Select concepts	
### i. Identify alternatives	
### ii. Identify attributes	
### iii. Screen the alternatives	
### iv. Rate alternatives	
### v. Weigh the attributes	
### vi. Calculate weight and sort	
### vii. Score and select alternatives	
## b) Optimize parameters	
### i. Define the product family	
# 5. Develop the architecture	
## a) Design the behavior	
### i. Review use cases, context, and functional requirements	
### ii. Map behaviors to subsystems	
### iii. Identify messages, triggers, and interfaces	
### iv. Identify system states	
### v. Set targets for behavior	
### vi. Extract functional requirements to originating requirements	
### vii. Trace-derived requirements to originating requirements	
### viii. The centrality of the operational description template	
## b) Design the flow and control	
### i. Identify functional relationships	
### ii. Summarize state changes	
## c) Design the structure	
### i. Identify interfaces and finalize subsystems	
### ii. Document links	
### iii. Identify emergent interactions	
### iv. Sketch a design concept	
### v. Create a rough-cut bill of materials	
### vi. Create a rough-cut reliability estimate	
### vii. Allocate target technical performance measure to subsystem	
# 6. Validate the design	
## a) Verify requirements	
### i. Conduct design reviews	
#### 1. Determine if entry criteria are met	
#### 2. Schedule the review meeting	
#### 3. Present the design	
#### 4. Collect review panel comments	
#### 5. Use exit criteria to assess whether the review was passed	
#### 6. Reschedule if the review did not pass	
### ii. Develop the test plan	
#### 1. Identify behavioural test sequence	
#### 2. Develop behavioural test methodology	
#### 3. Repeat for nonbehavioural tests	
#### 4. Map test activities to system requirements	
## b) Manage risks	
### i. Conduct failure modes and effects analysis	
#### 1. Select functions	
#### 2. identify failure modes	
#### 3. assess potential impact of failure	
#### 4. brainstorm possible causes	
#### 5. suggest corrective actions	
#### 6. rate the severity of impact	
#### 7. Rate the likelihood of causal occurrence	
#### 8. Assess the risks	
#### 9. Prioritize the action	
# 7. Execute the design	
## a) Schedule the project and track progress	
### i. Develop the task list (work breakdown structure)	
### ii. Estimate durations	
### iii. Task percent complete	
### iv. Identify task inputs, outputs, and deliverables	
### v. Establish task precedence relationships	
### vi. Schedule the project	
### vii. Display a Gantt chart	
### viii. Adjust the schedule for team availability	
## b) Conduct management reviews	
# 8. Iterate the design process	
## a) Iterate until feasible	
### i. Backtracking strategies	
## b) Iterate with improvement	
## c) Iterate by level	
### i. Level-by-level decomposition: the Vee diagram	
#### 1. Detail functions into behaviours	
#### 2. Allocate nonbehavioural requirements: linked houses of quality	
#### 3. Maintain hierarchies and traceabilities	
## d) Dive and surface: a system view	
### Appendix 1 IBM Rational Rhapsody - Design black box system model	
### Appendix 2 IBM Rational Rhapsody - Design white box system model

# Preface
This project is based on the process described in the book - Getting Design Right. The author of the book, Dr. Peter L. Jackson, is the professor in School of Operations Research and Information Engineering in Cornell University. This project uses similar terminology as in the book. Readers should focus on the essence of the design, rather than specific terms. 

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/preface.jpg)

This project involves eight stages – define, measurement, explore, optimize, develop, validate, execute and iterate.

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/8steps.jpg)

The presented template shows the process of product design and management. As an example, it may not represent a delicate engineering design. Instead, it’s focusing on pre-engineering design and post-engineering test. The traditional “Vee” model clearly indicates two parts of the procedure, the design stage, the manufacture stage, and the assembly and test stage. According to the Vee model, while the project is progressing from the upper left towards the bottom, the design becomes optimized with its details completed. When it progressing further from the bottom towards the upper right, tests are preformed to verify the design at different stages.

# 1. Define the problem
## a) Define the project
### i. Select the project

Starting with an idea. That could be a problem you want to solve. It will lead you to look for possible solutions. The idea can be a solution as well. Then you should think about the problem that the solution can solve, and think about other possible solutions. Alternatively, it can be an idea of making something interesting. In this case, appealing is the feature to be considered through the process. 

To illustrate the procedure with an example, here we develop a Interactive urinal device. 

### ii. Sketch the concept

The best way to show your idea is to present it with a schematic drawing. It may be scratched on one piece of paper, which does not contain much details and can be presented conveniently.

The gaming device we are designing can be installed in toilets in shopping malls. Game will start when a costumer is using the urinal. Advertisement will be displayed when it is idle. 

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/Toilet.jpg)

### iii. Define and tailor the process

Depending on your time and budget, you need to find the balance between how much resource spending on scheduling, and how much on performing. You may consider skipping part of the procedure presented here, but please note that it should be done with caution. This procedure is developed by many professionals based on decades of practice. Therefore tailoring the procedure requires extensive experience.

### iv. Define the owner, the customer and the user

Base on the relation to the system, there are three type of roles: owner, customer and user. Sometimes these three roles can be represented by the same person, but generally they are different. 
    Owner: sets design goals and authorizes major design decision.
    Customer: purchases the system and prepares for the usage.
    User: actually uses the system.

In our case, the gaming device will be installed in shopping malls,
    Owner: the vendor
    Customer: shopping malls
    User: male adults

### v. Write a mission statement

As the project may be complicated, involving many subsystems, at the beginning it's necessary to write a mission statement to describe the goal of the project. The statement should be expressed in the view of the owner. It should be concise and formal. 

The goal of our project is to design a gaming device installed in toilets in shopping malls for gaming and advertising purpose. 

## b) Define the context

### i. Define the system boundary

Different persons may have different views on the same project, especially the designers. For a project developed by a team, effective communications are essential. For a project developed by many teams, communications may become more difficult. Therefore system boundaries should be defined at the beginning of the process. Within the boundary are internal issues which can be handled by the team; Outside the boundary are external issues which are out of control of the team. If an external issue is related to the project, the team should evaluate its impact; otherwise the team should neglect the issue. When a new event appears, it is necessary to determine whether it is internal, external irrelevant, or external relevant.

For our project the gaming device is installed in toilets. The design is focused on the gaming device. Any toilet related modification is not considered here. 

### ii. Document the context of the system

Now it’s time to think about the relationships between the system we are going to design and the external entities.

#### 1. Context diagram

Using context diagram is a concise way to show the relation between the system and the surroundings. 

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/Context%20diagram.png)

The system we are going to design is placed in the center of the drawing. It is surrounded by external entities. Those external entities are linked to the center by lines. Along the line, a sentence is formed by combining the words in the external entity with those in the system. The sentence expresses the relation between the external entity and the system.

#### 2. Context matrices

The sentences generated in the previous section are presented in the table below.

| | Adult Male | Shopping mall | Interactive urinal device | Installation personnel | cleaner |
| --- | --- | --- | --- | --- | --- |
| Adult Male | | | use | | |
| Shopping mall | | | display ad on | | |
| Interactive urinal device | used by | ad displayed on | | installed by | cleaned by |
| Installation personnel | | | install | | |
| Cleaner | | | clean | | | 

### iii. Study the current context

It is important to consider the context in which the system will be used. Therefore it's necessary to visit customers, examine the environment, and collect information. When studying the environment, we should act as the following roles: observer, apprentice and partner. As an observer we just watch the process without changing anything. As an apprentice we should learn the current process and think about the reason of doing it. Sometimes an apprentice can transfer to a questioner. As a partner we need to get involved in the process a little deeper and look for alternative ways to complete the same task. Note that the collected information should be processed afterwards, so that redundant information can be removed.

In our case, the environment is shopping malls. Things worth noticing are
* Children that are under-age may used the toilet.
* People tends to ware more clothes in winter than in summer.

### iv. Collect customer comments

Customer comments may be a good source of information, which can be obtained from surveys, error logs, warranty clauses etc.

For our project customers may concern 
* does the device have good sensitivity?
* is the game fun to play?
* can measures be taken to prevent users playing the game for too long?
* is the device robust? Is it easy to maintenance? 
* can the device receive and display advertisements properly?

### v. Summarize the project(product) objectives

After receiving enough feedback from customers, it’s necessary to process the information and summarize the project objectives. The methods are diving and surfacing. To dive is to focus on details; To Surface is to summarize the details and form an abstract concept. In practice it's better to put related subjects together, combine and summarize them. 

The goal of our project is to design a gaming device installed on toilets in shopping malls, with minimum modification to the environment during the installation. The game should be fun to play. The device should be robust, water-proof, easy to clean and maintenance, having good sensitivity. Measures can be taken to prevent long time occupation of the toilet.

## c) Define functional requirements

Now it's time to document functional requirements of the system. Here we need to figure out what functions the system **shall have**. Note that the requirements are stated using “shall have” instead of “should have”. When defining requirements, we should pay attention not to restrict the design; On the other hand, we should not miss any requirements. “Diving-and-surfacing” method is especially useful here. Collecting low level requirements is not a waste of time, as they can be used in later stages. 

### i. Collect use cases

Use case are examples of different users interacting with the system. Different perspective results in different use cases. It's a good time for the team to brainstorm more use cases

For our project, use cases are listed below,
* an adult male plays the game
* a technician installs the device on the toilet
* a cleaner cleans the toilet
* a shopping mall staff displays advertisements 
* when the toilet is occupied for too long, the game shall cease and a message shall be displayed on the screen to suggest that the user shall finish using the toilet as soon as possible
* a technician fixes the device

#`picture to be added`

### ii. Prioritize use cases

Normally the team will collect many use cases. It's important to prioritize the use cases according to three levels: high: system behaviours should be described; medium: if time allows, system behaviours should be described; low: no description is necessary.

In our case, the use cases are summarized and sorted, listed in the table below

| Use cases | Priority |
| --- | --- |
| An adult male plays the game | High |
| A technician installs the device on the toilet | Low |
| A cleaner cleans the toilet | Low |
| A shopping mall staff displays advertisements | Medium |
| When the toilet is occupied for too long, the game shall cease and a message shall be displayed on the screen to suggest that the user shall finish using the toilet as soon as possible | High |
| A technician fixes the device | Medium |

### iii. Describe use case behaviours

The table describing use case behaviours contains five parts: name of use cases, initial state of the system, behaviour description, ending status and remarks. Behaviour description can be started from any stage of the system. Details shall be summarized to high level function requirements. The table may contain information about the inner structure of the system, which is only for description purpose. The structure in the actual design may be totally different.

**Name: an adult male plays the game**

**Initial state: the system is idle and displays ad**

| Operator | System |
| --- | --- | 
| An adult male will use the toilet | Interactive urinal device |
| The adult male approaches the toilet | |
| | The system detects human being nearby |
| | The system displays instructions |
| The adult male confirms readiness by sound | |
| | The system detects the sound |
| | The system counts down to start the game |
| The adult male starts to use the toilet | |
| | The system detects fluid |
| | The system starts the game, detects the pressure of the fluid, count the time |
| The adult male finishes using the toilet | |
| | The system shows the 
