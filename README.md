
# **_Interactive Urinal Device Project_**

**_Author： Zhentao Lu_**

**_02/2015-03/2016_**

**_Copyright belongs to the author_**
***
# Contents
# [[Preface|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#preface-1]]
# 1. [[Define the problem|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#1-define-the-problem-1]]
## a) [[Define the project|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#a-define-the-project-1]]
### i. [[Select the project|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#i-select-the-project-1]]
### ii. [[Sketch the concept|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#ii-sketch-the-concept-1]]
### iii. [[Define and tailor the process|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#iii-define-and-tailor-the-process-1]]
### iv. [[Define the owner, the customer and the user|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#iv-collect-customer-comments-1]]
### v. [[Write a mission statement|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#v-write-a-mission-statement-1]]
## b) [[Define the context|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#b-define-the-context-1]]
### i. [[Define the system boundary|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#i-define-the-system-boundary-1]]
### ii. [[Document the context of the system|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#ii-document-the-context-of-the-system-1]]
### iii. [[Study the current context|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#iii-study-the-current-context-1]]
### iv. [[Collect customer comments|https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/wiki#iv-collect-customer-comments-1]]
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
| | The system shows the result |
| The adult male leaves | |
| | The system displays messages indicating the adult male to leave |

**End state: the system is idle and displays ad** 

The flow diagram designed by using IBM Rational Rhapsody is shown below

# `picture to be added`

The details of use cases are illustrated in the background matrix table below

| Is related to | Adult male | Gaming device | Body detector | Sound detector | Fluid detector | Result of the game |
| --- | --- | --- | --- | --- | --- | --- |
| Adult male | | use | is detected by | is detected by | is detected by | sees |
| Gaming device | `is used by` | | `includes` | `includes` | `includes` | `includes` |
| Body detector | `detects` | `is inside` | | | | |
| Sound detector | `detects` | `is inside` | | | | |
| Fluid detector | `detects` | `is inside` | | | | |
| Result of the game | `is seen by` | `is inside` | | | | |

Body, fluid and sound detections are different components of the system. They are here just for description purpose, which may not exist in the actual design.

Cells marked with shadow indicates actions within the system, which can be designed. The rests are out of control of the system.

Similarly we can work out the rest of use cases. System behaviours that have been analyzed will be neglected.

**Name: When the toilet is occupied for too long, the game shall cease and a message shall be displayed on the screen to suggest that the user shall finish using the toilet as soon as possible **

**Initial state: the system shows the result of the game**

| Operator | System |
| --- | --- | 
| An adult is using the toilet | Interactive urinal device |
| The adult male continues occupying the toilet after finish using it | |
| | The system detects that the same person occupying the toilet |
| | The system displays displays a message that suggests the adult male should leave |

**End state: the system is idle and displays ad** 

If new information appears during the analysis, it should be added in the background matrix table. For our case, it remains the same. 

### iv. Summarize functional requirements from use cases	

Based on the analysis, system function requirements are listed below

* The device can display ad when idling
* The device can receive the ad to be displayed
* The device can detect approaching human being
* The device can display game instructions
* The device can detect the sound of human being
* The device can count down to start the game
* The device can detect fluid
* The device can interact with the user based on the pressure and direction of the fluid
* The device can calculate and display the result of the game
* The device can display the message to suggest that the user shall finish using the toilet as soon as possible

### v. Repeat for secondary use cases

We have analyzed primary use cases. Secondary use cases, such as the system is overused or malfunctioning shall be analyzed and added in the table.

| Use case | Priority |
| --- | --- |
| Primary use case | |
| An adult male plays the game | High |
| A technician installs the device on the toilet | Low |
| A cleaner cleans the toilet | Low |
| A shopping mall staff displays advertisements | Medium |
| When the toilet is occupied for too long, the game shall cease and a message shall be displayed on the screen to suggest that the user shall finish using the toilet as soon as possible | High |
| A technician fixes the device | Medium |
| Secondary use case | |
| The system switches to a power saving mode during night | High |
| The system can wake up automatically in the morning | High |

### vi. Finalize requirements	

Based on the analysis of major and minor use cases, function requirements of the system are listed in the table below

| No. | Requirements | Function name |
| --- | --- | --- |
| OR1 | The device can display ad when idling | Ad display |
| OR2 | The device can receive the ad to be displayed | Message receiving |
| OR3 | The device can detect approaching human being | Body detection |
| OR4 | The device can display game instructions | Instruction display |
| OR5 | The device can detect the sound of human being | Sound detection |
| OR6 | The device can count down to start the game | Counting Down |
| OR7 | The device can detect fluid | Fluid detection |
| OR8 | The device can interact with the user based on the pressure and direction of the fluid | Pressure and direction detection |
| OR9 | The device can calculate and display the result of the game | Result display |
| OR10 | The device can display the message to suggest that the user shall finish using the toilet as soon as possible | Leaving message display |
| OR11 | The system switches to a power saving mode during night | Power saving mode |
| OR12 | The system can wake up automatically in the morning | Automatically waking up |

# 2. Measurement the need and set targets	

In this stage, based on the previous analysis, such as customer's feedback, we need to
* measure how well the product satisfying the requirements
* measure the importance of each requirement for the customer
* set technical targets for the product, which can make it more competitive than similar products in the market

## a) Measure the need	

Measure of effectiveness is to evaluate how much the product satisfies the targets. In practice, methods can be used for the evaluation are quantifying customer's requirements, sorting them in order according to their priorities, and developing measurement graph.

### i. Determine measure of effectiveness	

There are many ways to collect data, such as costumer survey. But quantitatively measure the effectiveness is not easy, we use Goal-Question-Metric (GQM) method for gathering the information.

### ii. Apply the Goal-Question-Metric method

#### 1. Identify the goals of the measurement	

To identify the goals of the measurement, we need to work out the following subjects
* the project or procedure to be measured
* the goal of the measurement, such as to understand, control, design or improve 
* the measurement quality of the project or procedure
* the perspective of the measurement
* the context of the measurement

Based on the feedback of customers, the goals for our gaming device are summarized as follows
* the modification to the existing toilet shall not be very large
* the device shall be sensitive
* the game shall be interesting 
* the device shall be waterproof
* it shall be easy to clean the device
* the device shall display the message to suggest that the user shall finish using the toilet as soon as possible 
* the device shall be able to switch to power saving mode and wake up automatically
* it shall be easy to maintain the device

Finally, we get the table below

| | Analysis (the project or procedure to be measured) | the goal of the measurement (understand, control, design or improve) | Is related to (Measure the quality of the product) | Perspective (the personal to evaluate the quality or measure the goals) | Context |
| --- | --- | --- | --- | --- | --- |
| the modification to the existing toilet | the interactive urinal device | control | structure | installation personal | men's toilet |
| the device shall be sensitive | the interactive urinal device | design | sensitivity | user (adult male) | men's toilet |
| the game shall be interesting  | the interactive urinal device | design | interest | user (adult male) | men's toilet |
| the device shall be waterproof | the interactive urinal device | control | waterproof | installation personal | men's toilet |
| it shall be easy to clean the device | the interactive urinal device | control | cleaning | cleaner | men's toilet |
| the device shall display the message to suggest that the user shall finish using the toilet as soon as possible | the interactive urinal device | control | usage rate | user (adult male) | men's toilet |
| the device shall be able to switch to power saving mode and wake up automatically | the interactive urinal device | design | power saving | customer | men's toilet |
| it shall be easy to maintain the device | the interactive urinal device | design | structure | customer | men's toilet |

#### 2. Refine the goals with questions	

Here we interpret the targets into specific questions. In this way it's very helpful to get a feeling on the mission to be accomplished. 

| Targets | Questions |
| --- | --- |
| the modification to the existing toilet | Does the installation require drilling holes on the wall or other mechanical modifications on the existing structure? <br /> How many holes to be drilled? <br /> How big is the affected area? |
| the device shall be sensitive | When someone approaching the toilet, how long it takes the devices to show instructions? <br /> When someone is interacting with the device, how quick will the device react? <br /> After the game is over, how long it takes to show the result? |
| the game shall be interesting | Does the user enjoy the game? <br /> Does he want to play it again? |
| the device shall be waterproof | How long can the device stay in the water while functioning? |
| it shall be easy to clean the device | How long it takes to clean the device? <br /> Will cleaning agents damage the device? |
| the device shall display the message to suggest that the user shall finish using the toilet as soon as possible | the interactive urinal device | Generally, how long will a user occupies the toilet? |
| the device shall be able to switch to power saving mode and wake up automatically | When shall the device switch to power saving mode? <br /> When shall the device wake up? |
| it shall be easy to maintain the device | How long it takes to fix the device? |

#### 3. Specify the metrics	

Considering the trade off between the quality of the information and the required efforts for collecting the data, we have two kinds of metrics for the above questions, the ideal metrics and the practical metrics. The ideal metrics are the results from directly answering the questions based on the collected data. When that is not possible (due to time, cost, or other issues), practical metrics can be applied. Due to the cost, time and viability, sometimes we use rough metrics. 

| Targets | Questions | Ideal metrics | Rough metrics | 
| --- | --- | --- | --- |
| the modification to the existing toilet | Does the installation require drilling holes on the wall or other mechanical modifications on the existing structure? <br /> How big is the affected area? | The number of holes to be drilled <br /> The size of the affected area | <br /> The contact area between the device and the toilet |
| the device shall be sensitive | When someone approaching the toilet, how long it takes the devices to show instructions? <br /> When someone is interacting with the device, how quick will the device react? <br /> After the game is over, how long it takes to show the result? | The time between an adult stands in front of the toilet and the device displays gaming instructions <br /> The time between liquid flowing in the toilet and the corresponding reaction on the screen <br /> The time between the interaction stops and the device shows the result | |
| the game shall be interesting | Does the user want to play it again? | The times a user plays the game | The average times 3-5 users play the game |
| the device shall be waterproof | How long can the device stay in the water while functioning? | The time the device can stay in water while functioning | |
| it shall be easy to clean the device | How long it takes to clean the device? <br /> Will cleaning agents damage the device? | The time it takes to clean the device <br /> The amount of cleaning agents that may damage the device | |
| the device shall display the message to suggest that the user shall finish using the toilet as soon as possible | the interactive urinal device | Generally, how long will a user occupies the toilet? | The average time a user occupies the toilet during a day | The average time of 3-5 users occupy the toilet |
| the device shall be able to switch to power saving mode and wake up automatically | When shall the device switch to power saving mode? <br /> When shall the device wake up? | The time the device switches to power saving mode <br /> The time the device wakes up | |
| it shall be easy to maintain the device | How long it takes to fix the device? | The time it takes to fix the device | The time it take to fix mechanical failures <br /> The time it takes to fix electronic failures |

#### 4. Develop Data collection methods	

According to the target-question-metric method, the last step is to develop data collection methods. If it is difficult to collect data, we might consider repeat the previous step and redesign the rough metrics. There are two ways to collect date: for general questions we use costumer survey; and for data requires repeatedly observation, we use the data collection table.

| Targets | Questions | Ideal metrics | Rough metrics | Data collection method |
| --- | --- | --- | --- | --- |
| the modification to the existing toilet | Does the installation require drilling holes on the wall or other mechanical modifications on the existing structure? <br /> How big is the affected area? | The number of holes to be drilled <br /> The size of the affected area | <br /> The contact area between the device and the toilet | Estimated from the design <br /> Estimated from the design <br /> Estimated from the design |
| the device shall be sensitive | When someone approaching the toilet, how long it takes the devices to show instructions? <br /> When someone is interacting with the device, how quick will the device react? <br /> After the game is over, how long it takes to show the result? | The time between an adult stands in front of the toilet and the device displays gaming instructions <br /> The time between liquid flowing in the toilet and the corresponding reaction on the screen <br /> The time between the interaction stops and the device shows the result | | Customer survey <br /> Customer survey <br /> Customer survey |
| the game shall be interesting | Does the user want to play it again? | The times a user plays the game | The average times 3-5 users play the game | | Customer survey |
| the device shall be waterproof | How long can the device stay in the water while functioning? | The time the device can stay in water while functioning | | Data collection table |
| it shall be easy to clean the device | How long it takes to clean the device? <br /> Will cleaning agents damage the device? | The time it takes to clean the device <br /> The amount of cleaning agents that may damage the device | | Customer survey <br /> Estimated from the design |
| the device shall display the message to suggest that the user shall finish using the toilet as soon as possible | the interactive urinal device | Generally, how long will a user occupies the toilet? | The average time a user occupies the toilet during a day | The average time of 3-5 users occupy the toilet | Data collection table |
| the device shall be able to switch to power saving mode and wake up automatically | When shall the device switch to power saving mode? <br /> When shall the device wake up? | The time the device switches to power saving mode <br /> The time the device wakes up | | Customer survey <br /> Customer survey |
| it shall be easy to maintain the device | How long it takes to fix the device? | The time it takes to fix the device | The time it take to fix mechanical failures <br /> The time it takes to fix electronic failures | Estimated from the design <br /> Estimated from the design |

When testing the waterproofness of the device, data collected at different time may be listed in the data collection table below,

* Product name:
* Observer's name:
* Time: from _ till _
* Location: 

| No. | Time | Result | Remark |
| --- | --- | --- | --- |
| 1 | | | |
| 2 | | | |
| 3 | | | |

### iii. Weigh the product objectives	

Now it's time to figure out which properties are the most important for customers. As we haven't developed a specific design of the product yet, only the qualitative analysis can be provided at the moment, while the quantitative analysis will be conducted later. When sorting out the product objectives based on their priorities, following issues need to be concerned,

* Is it useful to sort out the product objectives based on their priorities? Is it possible to reach the final decision if results based on quantitative analysis are available?
* Who will perform the sorting? Base on the perspective of which group? The owner? The customer? The user?
* Some of the comparisons are contradictory. Is it necessary to perform comparison based on safety and cost-effectiveness?
* How accurate does the survey reflect the preferences of the respondents? Are the preferences of the respondents in accordance to the product objectives developed by the team? 

The procedure consist of four steps: 
1. Sort the product objectives to different categories according to their similarities
2. Render each category with a weighing factor; The summed weighing factors of each category is 1; The higher the value, the more important the product objective
3. Multiply the priority with the weighing factor
4. Sort the result according to descending order

For our project, there is no similarity between different product objectives, therefore each goal takes its own category

| Modification to the existing structure | Sensitivity | Fun | Waterproof | Easy to clean | Alert message | Power saving | Easy to maintain |
| --- | --- | --- | --- | --- | --- | --- | --- |
| The degree of modification to the existing structure | The device is sensitive and may respond to instructions promptly | The game is fun to play | The device is waterproof | The device is easy to clean | The device may display message to suggest that the user shall finish using the toilet as soon as possible | The device can switch to power-saving mode and wake up automatically | The device is easy to maintain |


| 1 | Modification to the existing structure | Sensitivity | Fun | Waterproof | Easy to clean | Alert message | Power saving | Easy to maintain |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | 0.15 | 0.25 | 0.1 | 0.2 | 0.1 | 0.1 | 0.05 | 0.05 |

| 2 | The area of modification to the existing structure | The effort required to modify the structure | Pregame sensitivity | During the game sensitivity | Postgame sensitivity | Game is fun to play | Waterproof | The time it takes to clean the device | The robustness of the device against cleaning agents | Display alert message when the game is over | Switch to power saving mode during the night automatically | Wake up during the day automatically | Easy to maintain |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | 0.333 | 0.667 | | | | | | | | | | | |
| | | | 0.3 | 0.4 | 0.3 | | | | | | | | |
| | | | | | | 1 | | | | | | | |
| | | | | | | | 1 | | | | | | |
| | | | | | | | | 0.6 | 0.4 | | | | |
| | | | | | | | | | | 1 | | | |
| | | | | | | | | | | | 0.5 | 0.5 | |
| | | | | | | | | | | | | | 1 |
| 3 | 0.15*0.333=0.05 | 0.15*0.667=0.1 | 0.25*0.3=0.075 | 0.25*0.4=0.1 | 0.25*0.3=0.075 | 0.1*1=0.1 | 0.2*1=0.2 | 0.1*0.6=0.06 | 0.1*0.4=0.04 | 0.1*1=0.1 | 0.05*0.5=0.025 | 0.05*0.5=0.025 | 0.05*1=0.05 |

The sorted product targets are

| Product target | Priority | Level |
| --- | --- | --- |
| Waterproof | 0.2 | 1 |
| The effort required to modify the structure | 0.1 | 2 |
| During the game sensitivity | 0.1 | 2 |
| It's fun to play the game | 0.1 | 2 | 
| Display alert message when the game is over | 0.1 | 2 | 
| Pregame sensitivity | 0.075 | 6 | 
| Postgame sensitivity | 0.075 | 6 |
| The time it takes to clean the device | 0.06 | 8 | 
| The area of modification to the existing structure | 0.05 | 9 |
| Easy to maintain | 0.05 | 9 |
| The robustness of the device against cleaning agents | 0.04 | 11 |
| Switch to power saving mode during the night automatically | 0.025 | 12 |
| Wake up during the day automatically | 0.025 | 12 |

The pie chart of the results

# `pic to be added`

### iv. Benchmark competition on measures of effectiveness	

Next we study the existing product in the market. The product developed by SEGA, by companies in India and London are displayed,

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/three%20product.jpg)

In the table below an evaluation of the three products are presented

| | SEGA | India | London |
| --- | --- | --- | --- |
| Price | Hardware 140,000 Yen <br /> Sotware 10,000 Yen | Unknown | Unknown |
| Recommended user age | Older than 10 years | Adult | Adult |
| Material | Ceramic | Ceramic | Ceramic | 
| Touch control | Single point | Half urinal | Multiple points |
| Game | 2D games | Unknown | 2D and 3D games | 
| Date of the report released | Oct 2011 | Jan 2014 | Nov 2011 |

Evaluation of the three products (1-5, higher score represents better performance)

| | SEGA | India | London |
| --- | --- | --- | --- |
| Appearance | 4 | 2 | 4 |
| Touch control | 3 | 5 | 4 |
| Game | 3 | 2 | 4 |
| Modification to the existing structure | 4 | 2 | 3 |
| Price | 4 | 3 | 2 |

Displayed in chart

# `pic to be added`

## b) Translate to technical requirements	

The next step is to translate the product objectives to engineering characteristics, and set norms to evaluate those characteristics. As there might be mismatches between the perspective of customers and engineers, extensive communication is more than important. 

### i. The house of quality	

One way to facilitate effective communication is use the house of quality. It is a matrix which determines the relation between customer's anticipations and engineering characteristics. This matrix reveals all the questions that worth to be discussed by designers and engineers.

# `matrix to be added`

The aim of using house of quality is to determine target technical performance measure rather than set targets or make decisions. The goal is to make sure that the product objectives matches customer anticipations. 

It is constructed through the following steps:
1. Identify and classify the product objectives
2. Weigh the product objectives from customers perspective
3. Benchmark competition on measures of effectiveness
4. Identify engineering characteristics	
5. Map engineering characteristics to customer attributes	
6. Document engineering interrelationships	
7. Identify units of measure, cost, difficulties and other engineering characteristics
8. Benchmark competitions on engineering characteristics
9. Determine target technical performance measure	

As the first three steps have been done, we will continue with the fourth step.

#### 1. Identify engineering characteristics	

The purpose of identifying engineering characteristics is to figure out measurable product attributes, which are directly related to customer attributes. This step requires some engineering knowledge. It's important that designers and engineers communicate extensively.

For our project, the identified characteristics are,

* The choices of waterproof materials and the related techniques to process them
* The choices of materials around the region of detectors
* The effective area of the detectors
* The maximum amount of detectors required
* The maximum sound volume required for activating the device
* The maximum time it takes for starting the game
* The time it takes to display the result of the game
* The time between displaying the result of the game and displaying the alarm message to indicate the user should leave
* The times a player willing to play the same game
* The integration of all the components of the device
* The time for automatically switching off and turning on the device

#### 2. Map engineering characteristics to customer attributes	

Below is the house of quality. The columns are the identified engineering characteristics, the rows are the customer attributes. Here we can clearly see how the engineering characteristics influence the customer attributes. If a engineering characteristic has no influence on customer attributes, it should not be listed in the table.

| | | | Waterproof materials and the related processing techniques | The effective area of the detectors | The maximum amount of detectors required | The maximum sound volume required for activating the device | The maximum time it takes for starting the game | The time it takes to display the result of the game | The times a player willing to play the same game | The choices of materials around the region of detectors | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave | The integration of all the components of the device | The time for automatically switching off and turning on the device |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | | | &#x2191; | &#x2191; | &#x2191; | &#x2193; | &#x2193; | &#x2193; | &#x2191; | &#x2191; | &#x2193; | &#x2191; | &#x2191; |
| Modification to the existing structure | Modification to the existing structure | 0.05 | XX | XX | XX | | | | | | | &#x2713;&#x2713; | |
| | The effort required to modify the structure | 0.1 | XX | XX | XX | | | | | | | &#x2713; | |
| Sensitivity | Pregame | 0.075 | | | | &#x2713;&#x2713; | &#x2713;&#x2713; |  | | | | | |
| | During the game | 0.1 | | &#x2713;&#x2713; |&#x2713;&#x2713; | | | | | | | | |
| | Post game | 0.075 | | | | | | &#x2713;&#x2713; | | | | | |
| Fun to play | Fun to play | 0.1 | | | &#x2713;&#x2713;| | | | &#x2713;&#x2713; | | | | |
| Waterproof | Waterproof | 0.2 | &#x2713;&#x2713; | XX | | | | | | &#x2713;&#x2713; | | | |
| Easy to clean | Time required for cleaning | 0.06 | | X | XX | | | | | &#x2713; | | | |
| | Robustness -- The resistance to cleaning agents | 0.04 | | | | | | | | &#x2713;&#x2713; | | | |
| Display message to indicate the user should leave | 0.1 | | | | | | | | | &#x2713;&#x2713; | | |
| Easy to maintain | Easy to maintain | 0.05 | | | | | | | | | | &#x2713;&#x2713; | |
| Power saving | Switch off during the night | 0.025 | | | | | | | | | | | &#x2713;&#x2713; |
| | Turn on during the day | 0.025 | | | | | | | | | | | &#x2713;&#x2713; |

&#x2713;&#x2713; stands for strong relevance; &#x2713; stands for relevance; X stands for weak relevance; XX stands for no relevance; &#x2191; stands for ascend; &#x2193; stands for descend. 

For example, the more detectors are implemented, the larger the effective area, hence the higher the sensitivity of the device. However, this requires an additional work for modifying the existing structure. It is more difficult to manufacture, reduces the waterproofness and requires more effort for cleaning after installed in the toilet.

#### 3. Document engineering interrelationships	

As the engineering characteristics may influence each other as well, we present their relationships in the table below,

| | | | | | | | | | | | Waterproof material and related processing techniques |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| &#x2713;&#x2713; | | | | | | | | | | | The effective area of the detectors |
| &#x2713;&#x2713; | &#x2713;&#x2713; | | | | | | | | | | The maximum amount of detectors required |
| | | | | | | | | | | | The maximum sound volume required for activating the device |
| | | | XX | | | | | | | | The maximum time it takes for starting the game |
| | XX | &#x2713;&#x2713; | | | | | | | | | The time it takes to display the result of the game |
| | | &#x2713; | X | X | X | | | | | | The times a player willing to play the same game |
| &#x2713;&#x2713; | | | | | | | | | | | The choices of materials around the region of detectors |
| | | | | | | | | | | | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave |
| &#x2713;&#x2713; | | | | | | | | | | | The integration of all the components of the device |
| | | | | | | | | | | | The time for automatically switching off and turning on the device |
| Waterproof material and related processing techniques | The effective area of the detectors | The maximum amount of detectors required | The maximum sound volume required for activating the device | The maximum time it takes for starting the game | The time it takes to display the result of the game | The times a player willing to play the same game | The choices of materials around the region of detectors | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave | The integration of all the components of the device | The time for automatically switching off and turning on the device | |
| &#x2191; | &#x2191; | &#x2191; | &#x2193; | &#x2193; | &#x2193; | &#x2191; | &#x2191; | &#x2193; | &#x2191; | &#x2191; | |

&#x2713;&#x2713; stands for strong relevance; &#x2713; stands for relevance; X stands for weak relevance; XX stands for no relevance; &#x2191; stands for ascend; &#x2193; stands for descend. 

For example, if the area for detection is increased, more detector can be installed, the waiting time can be reduced.

#### 4. Identify units of measure and benchmark competitions	

In the bottom of the house of quality, detailed product measures from different vendors are presented. First we identify units of measure, then analyze the product from each competitor. It is worth noting that none of the three products is superior than the other two in all measured features. 

| | | Waterproof material and related processing techniques | The effective area of the detectors | The maximum amount of detectors required | The maximum sound volume required for activating the device | The maximum time it takes for starting the game | The time it takes to display the result of the game | The times a player willing to play the same game | The choices of materials around the region of detectors | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave | The integration of all the components of the device | The time for automatically switching off and turning on the device |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | | &#x2191; | &#x2191; | &#x2191; | &#x2193; | &#x2193; | &#x2193; | &#x2191; | &#x2191; | &#x2193; | &#x2191; | &#x2191; |
| target measurement | Units of measure | mm<sup>2</sup> | mm<sup>2</sup> | Piece | dB | second | second | times | material | second | box | time |
| | Sega | Unknown | 28.27 | 1 | None | Unknown | 0.1 | Unknown | Plastic | Unknown | Unknown | Unknown | 
| | Indian | Unknown | 603.19 | 192 | None | Unknown | Unknown | Unknown | Plastic | Unknown | Unknown | Unknown | 
| | London | Unknown | 51.41 | 3 | None | Unknown | 0.1 | Unknown | Metal | Unknown | Unknown | Unknown | 

#### 5. Determine target technical performance measure	

Before determining target technical performance measure, it's necessary to add three rows in the bottom of the house of quality: technical viability, evaluated value, evaluated cost. Technical viability is a subjective estimation of how difficult it is to realize the designed device features; Evaluated cost is also a subjective estimation, which is related to technical viability; Evaluated value represents how important are the designed features for customers. This evaluation is achieved from the following analysis, 

    Evaluated value = product objective X identification (√√) + product objective X identification (XX)

After the analysis, target technical performance measure can be determined. Note that the house of quality is just a tool for collecting information. The final decisions should be made by the team after extensive discussions. Note that the contents of the house of quality are interrelated in different dimensions, special attention should be paid on not falling into endless iterated discussions. 

| | | Waterproof material and related processing techniques | The effective area of the detectors | The maximum amount of detectors required | The maximum sound volume required for activating the device | The maximum time it takes for starting the game | The time it takes to display the result of the game | The times a player willing to play the same game | The choices of materials around the region of detectors | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave | The integration of all the components of the device | The time for automatically switching off and turning on the device |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | | &#x2191; | &#x2191; | &#x2191; | &#x2193; | &#x2193; | &#x2193; | &#x2191; | &#x2191; | &#x2193; | &#x2191; | &#x2191; |
| target measurement | Units of measure | mm<sup>2</sup> | mm<sup>2</sup> | Piece | dB | second | second | times | material | second | box | time |
| | Sega | Unknown | 28.27 | 1 | None | Unknown | 0.1 | Unknown | Plastic | Unknown | Unknown | Unknown | 
| | Indian | Unknown | 603.19 | 192 | None | Unknown | Unknown | Unknown | Plastic | Unknown | Unknown | Unknown | 
| | London | Unknown | 51.41 | 3 | None | Unknown | 0.1 | Unknown | Metal | Unknown | Unknown | Unknown | 
| Technical difficulties (1-lowest, 5-highest) | | 4 | 3 | 3 | 2 | 4 | 5 | 3 | 2 | 2 | 2 | 1 | 
| Estimated values (%) | | 70% | 96% | 56% | 15% | 15% | 35% | 20% | 54% | 20% | 30% | 10% | 
| Estimated cost (1-lowest, 5-highest) | | 5 | 3 | 3 | 2 | 4 | 4 | 3 | 4 | 2 | 2 | 1 |
| Target | | 50 | 120 | 5 | 40 | 3 | 0.1 | 3 | Plastic | 8 | 3 | 7:00 AM <br /> 1:00 AM | 




The complete house of quality for our project is shown below

| | | | | | | | | | | | | | | Waterproof material and related processing techniques |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| | | | &#x2713;&#x2713; | | | | | | | | | | | The effective area of the detectors |
| | | | &#x2713;&#x2713; | &#x2713;&#x2713; | | | | | | | | | | The maximum amount of detectors required |
| | | | | | | | | | | | | | | The maximum sound volume required for activating the device |
| | | | | | | XX | | | | | | | | The maximum time it takes for starting the game |
| | | | | XX | &#x2713;&#x2713; | | | | | | | | | The time it takes to display the result of the game |
| | | | | | &#x2713; | X | X | X | | | | | | The times a player willing to play the same game |
| | | | &#x2713;&#x2713; | | | | | | | | | | | The choices of materials around the region of detectors |
| | | | | | | | | | | | | | | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave |
| | | | &#x2713;&#x2713; | | | | | | | | | | | The integration of all the components of the device |
| | | | | | | | | | | | | | | The time for automatically switching off and turning on the device |
| | | | Waterproof material and related processing techniques | The effective area of the detectors | The maximum amount of detectors required | The maximum sound volume required for activating the device | The maximum time it takes for starting the game | The time it takes to display the result of the game | The times a player willing to play the same game | The choices of materials around the region of detectors | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave | The integration of all the components of the device | The time for automatically switching off and turning on the device | |
| | | | &#x2191; | &#x2191; | &#x2191; | &#x2193; | &#x2193; | &#x2193; | &#x2191; | &#x2191; | &#x2193; | &#x2191; | &#x2191; | |
| target measurement | Units of measure | mm<sup>2</sup> | mm<sup>2</sup> | Piece | dB | second | second | times | material | second | box | time |
| | Sega | Unknown | 28.27 | 1 | None | Unknown | 0.1 | Unknown | Plastic | Unknown | Unknown | Unknown | | |
| | Indian | Unknown | 603.19 | 192 | None | Unknown | Unknown | Unknown | Plastic | Unknown | Unknown | Unknown | | |
| | London | Unknown | 51.41 | 3 | None | Unknown | 0.1 | Unknown | Metal | Unknown | Unknown | Unknown | | |
| Technical difficulties (1-lowest, 5-highest) | | 4 | 3 | 3 | 2 | 4 | 5 | 3 | 2 | 2 | 2 | 1 | | |
| Estimated values (%) | | 70% | 96% | 56% | 15% | 15% | 35% | 20% | 54% | 20% | 30% | 10% | | |
| Estimated cost (1-lowest, 5-highest) | | 5 | 3 | 3 | 2 | 4 | 4 | 3 | 4 | 2 | 2 | 1 | | |
| Target | | 50 | 120 | 5 | 40 | 3 | 0.1 | 3 | Plastic | 8 | 3 | 7:00 AM <br /> 1:00 AM | | |

After analyzing the house of quality, the resulting primary requirements are listed in the table below

| | |
| --- | --- |
| OR13 | The area of the waterproof material should not exceed 80mm<sup>2</sup> |
| OR14 | The effective area of the detectors should be at least 120mm<sup>2</sup> |
| OR15 | The maximum number of detectors should be at least 5 |
| OR16 | The maximum sound volume required for activating the device should be at most 40dB |
| OR17 | The maximum time it takes for starting the game should be no more than 3 seconds |
| OR18 | The time it takes to display the result of the game should be at most 0.1 second | 
| OR19 | The times a player willing to play the same game is 3 | 
| OR20 | The material around the region of detectors should be plastic |
| OR21 | The time between displaying the result of the game and displaying the alarm message to indicate the user should leave should be 8 seconds |
| OR22 | The integrated components of the device should be no more than 3 boxes |
| OR23 | The device should automatically switch off at 1 AM and turn on at 7 AM |





### ii. Collect and rationalize system-level requirements	

Through the analysis of the use case, we get the functional requirements. Through the analysis of the house of quality, we get the primary requirements. Now is time to combine the two. Requirements that are duplicated, unclear or limits the design should be removed from the final list. The result is showing below

# `table to be added`

Requirement 11, 12 and 23 are duplicated, requirement 20 limits the design, they are removed from the list.

## c) Identify the customer value proposition	

The next step is to reinspect the product from the perspective of customers. It is similar to the analysis of task list. Customer proposals are more than a simple list of system characteristics. They clearly indicate the advantage of the to be designed product over the existing products on the market. If no advantage can be established, the project should be stopped. The product concept, functional requirements and technical performance measure should be redone. The customer proposal for our project is,

#### Customer proposal for toilet interactive gaming project
* Comparing to SEGA, we will implement more detectors, design the device with a larger effective area, hence improve the user experience. 
* Comparing to the Indian vendor, we will implement less detectors to reduce the difficulty for manufacture. 
* Comparing to the British vendor, the functions are similar. However, we will choose different material with a different appearance. 
What's more, our product aims to provide better user experience, such as more interesting games, better waterproofness, better responsibility and possible voice recognition.
Note that till now we haven't estimated the cost. As the quantity of the tailored product is small, the cost can be estimated after receiving customer's orders.

# 3. Explore the design space	

During the design stage, there are many pitfalls the team may encounter. For example, the team only has one backup plan, the design is dominated by the most confident person in the team, only one or two members participate in the design while the rest are excluded from the process, can't find other useful concept, failed to scrutinize the solution as a whole subject, failed to integrate plans that are promising. In a nutshell, these pitfalls appeared because not all the team members participated in the process, to be creative, to complete the whole design concept.

The key point here is that the team should spend enough time on a variety of possible designs, with all the members involved in the process. 

## a) Discover concepts	

### i. Clarify the problem and decompose the functions	

Before being creative on looking for solutions, first we need to analyze the problems. As we have already analyzed the main functions and come up with the functional requirements list, this will be a good point for starting the exploration. We should be careful not confusing main functions with constraints. Main functions are those the system should perform to accomplish the task. While constraints are requirements for how the system perform the main functions. Starting with the analysis of the behaviour description is proven to be a useful method. We copy the table of the behaviour description here. As time for development is limited, more efforts should be spend on being creative and satisfying customer's requirements. 

# `table to be added`

Now we specify the table base on the user's behaviour. Sentences with bold letters indicates where we can potentially be creative. 

# `table to be added`

### ii. Brainstorm and research	

Now the team should look for backup plans. As far as a problem can be solved by a backup plan, it doesn't matter if the plan has defect or not practically viable. The team should be more creative than being realistic. The team can try different methods such as brainstorm, looking for opinions from experts, web search, patent search etc. The team should look for as many solutions as possible. Table below presents possible solutions for our project.

# `table to be added`

### iii. Organize concept fragments	

The next step is to sort out the solutions, prepare them in order and form a concept category tree. Here we present the tree using the table below

# `table to be added`

### iv. Prune and expand	

One advantage of using the tree structure is that the categories can be extended or cut off. For example, if a category is not environmentally friendly, it can be considered removed from the tree. The resulting table is listed below

# `table to be added`

We cut off the following elements in the table:
- the motion detection device, because it is too expensive. 
- gravity sensitive device, because it is difficult to install.
- photoelectric sensor, because its sensitivity will be largely reduced when blocking by other objects.
- 3D multiple points detector, because it is difficult to manufacture due to its special shape.
- acceleration detector, because it is not commercially available at the moment.
- temperature detector, because its responding time is too long, and it is subject to the environment.
- CRT display, because it is out of date.
- normal PC, because it is not easy to control the hardware.
- embed system, because it's video capability is not good enough.
- Java, because no java programmer in the company.

## b) Explore concepts	

### i. Combine concept fragments	

Through the above analysis we get possible resolutions through combinations of the remaining elements in the table.
We list some of the combinations in the table below.

### ii. Generate integrated concepts	

From the above combinations, we can choose the best solution to complete the design. The choices for each module are presented below.

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/detect%20people.jpg)

Body detectors: Ultrasonic transducer and Passive infrared sensor

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/ultrasonic%20and%20infrared.jpg)

Microphone and voice recognition module

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/microphone%20and%20voice%20.jpg)

Liquid detectors 

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/liquid%20detector.jpg)

Liquid pressure sensors

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/liquid%20pressure%20sensor.jpg)

Liquid volume detectors

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/liquid%20volumn%20detector.jpg)

Liquid speed detector

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/%E8%B6%85%E5%A3%B0%E6%B3%A2%E6%B6%B2%E4%BD%93%E6%B5%81%E9%80%9F%E4%BC%A0%E6%84%9F%E5%99%A8TCF1M-20TR2.jpg)

LCD

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/8%E5%AF%B8%E5%BD%A9%E8%89%B2%E6%B6%B2%E6%99%B6%E6%98%BE%E7%A4%BA%E5%99%A8L8008.jpg)

Data processing unit: Raspberry Pi, Pcduino, Arduino + PC

![](https://github.com/lvzt/Mens-toilet-interactive-device-project-EN/blob/master/Image/computer.jpg)

## c) Identify subsystem	

Now we have done enough analysis to generate a complete solution. Before that, we shall summarize all the remaining solutions. Here subsystems are identified by grouping components with same functions together (See the table below). Note that if we had done this at an early stage, we might be limited on the first design when doing the analysis. Now we have produced enough possible solutions, we can combine different components to see if we can get creative results. 

# `table to be added`

The subsystems are identified as follows

- Body detection
- Sound detection
- Liquid detection
- Display
- Data processing
- Game

# 4. Optimize design choices	

The team shall decide on the final design. As there are many influencing factors, it's common that the discussion falling into a circle, plan A is better than plan B, plan B is better than plan C, plan C is better than plan A. Considering all the factors at the same time is rather difficult.

Weighing analysis is an effective way, as it combine different factors to find the optimal solution based on convincible reasons. Problem illustration and primary data table can be used as input for setting the baseline for choosing the optimum design. The progress of the weighing analysis should be documented, therefore the plan can be modified when environment or situation changes.

## a) Select concepts	

### i. Identify alternatives	

First we copy the table of all possible solutions here.

### ii. Identify attributes	

Base on the product objectives we obtained previously, we can start the weighing analysis. Product objectives are product decision attributes. Not all the product objectives will be covered by the final complete design. 

When qualifying either of the two conditions, the product attribute can be neglected.

* the product attribute is the same in different possible solutions.

* the product attribute is different in different possible solutions, but it is strongly related to other product attributes.

Below is the table of product attributes we developed previously. 

# `table to be added`

First we remove the product objectives that are not related to the design, such as the game is fun to play (it is the objective of game design, which can be considered later), send out an alarm to tell the user who occupy the device for too long (this is strongly related to other functions such as the sensitivity of the device), combine the before and post game sensitivity as one - game sensitivity, combine auto-switch off during night and auto-switch on during the day as one - energy saving, and energy saving is removed because it is not among the primary objectives which will be added at a later stage. After the modification, the remaining product objectives are,

* Waterproof
* Easiness to manufacture
* Game sensitivity
* Modification to the environment
* Easiness to clean
* Robustness
* Easiness to maintain 

### iii. Screen the alternatives	

As we have many different solutions for the final design, we are in the selection phase. The selection is based on the value assignment and comparing method. First an arbitrary solution is chosen as reference, with its value setting as 0. Solutions are marked as + if they are better than reference, - if they are worse, 0 if they are comparable with the reference. The result for our project is presented in the table below

# `table to be added`

From the analysis we conclude that, the performance of ultrasonic and infrared detectors are comparable; flat multiple-points detector is better in the following aspects: waterproof, ease of manufacture, ease of cleaning, robustness, but is less sensitive and less easy to maintain comparing to the ball shape detector; over all liquid pressure sensor are better than liquid speed detector and liquid volume detector; mini PC is better to maintain comparing to Arduino + PC; games designed by using Unity3D has a better quality, but usually they require more resource and hence less sensitive, therefore C# or Python will be selected in this stage. 

### iv. Rate alternatives	

After the rough selection in the previous step, now we will perform more elaborated analysis. Here we evaluate the alternatives with a score system: score 5 indicates that the alternative is much better than the reference, score 3 represents the same, score 1 indicates that the alternative is much worse than the reference. The results are presented in the table below

# `table to be added`

### v. Weigh the attributes	

First we copy the results from the second chapter to here. As we can see, the sum of the factors does not equal to 100%, because they are just part of the over all project targets. We adjust the results a bit by combining the during game sensitivity and after game sensitivity to one subject, game sensitivity. 

### vi. Calculate weight and sort	

Finally, we place the weighed attributes and alternatives in one table to form a matrix, evaluate every alternatives according to each attributes, which results in the final scores of each alternative. The advantage of using this matrix is that it facilitates the discussion among team members. What's more, the document records the process of decision making, which can be displayed to the outsiders. The matrix after evaluation is shown below

# `table to be added`

After analyzing the above matrix, we conclude that, we will choose the flat multi-point detector over the ball shape multi-point detector; choosing between ultra-sonic and infrared detector requires more analysis, or maybe we will try them both; choosing between mini pc and Arduino + pc also requires more analysis; we choose python over C# because python is more flexible. 

### vii. Score and select alternatives	

# vi and vii need to be fixed!!

## b) Optimize parameters	

Usually this step is performed in the design revision circle. Because our project here is relatively simple, instead of using discrete analysis like before, we analyze the alternatives continuously, i.e., for each alternative we study the design for every engineering characteristics and optimize the parameters. In chapter 2 we already worked out the technical requirements,

# `table to be added`

From the house of quality we get the system variable and place them together with the subsystem variable in the new house of quality matrix. The new matrix has the same column vector as the old one, but the row vector consist of all the alternatives, instead of the technical performance measure. Same as before, √√ represents the two elements are strongly positively related, √ positively related, X negatively related, XX strongly negatively related. For our project, as the selection sound detector has been fixed with no other alternatives, the requirements 16, 21 and 23 are removed from the knew house of quality matrix. The results are in the table below

# `table to be added` 

Now is time to discuss with experts extensively on specific designs, such as 3D modeling, finite element method analysis, estimating the amount of code to be written by developers. When the prospected value during design (the design variable) is lager than the value of requirement, the difference between the two is called design freedom. Therefore, when setting one design variable, other design variables can be adjusted correspondingly according to time, cost etc. What's more, it's necessary to optimize different design variables according to certain constraints or limits. For some demos can be built to test the viability and extent of the design.

For our project, comparing to a mini PC, a normal PC has better performance. In the case of designing the game using an advanced game engine, normal PC is a better choice. On the other hand, there are many highly developed python libraries for gaming development. 

### i. Define the product family	

Now we have collected many alternatives. Through the previous optimization steps, we get different combinations which composite the product family. Different product in the product family suits different market. They are all originated from the same platform, share many components, facilities and even producing process. For our product the setup can provide simple games for children, or more complicated games for adults.

# 5. Develop the architecture	

For a simple project whole designing task can be finished by one person. While for a complicated project with multiple people or even multiple teams involved in the task, communication between different parties is more than important. This chapter will focus on describing the system language, i.e., separate the product into subsystem and comprehensively describe the relation between them. The most important part is the interface of the subsystems. Here we use the behaviour-function-structure method. 

## a) Design the behavior	

The analysis performed previously is mainly focused on the system structure. Now we will describe the system behavior, because function analysis, control and verification are all rely on the system behavior. 

### i. Review use cases, context, and functional requirements	

The use cases summarized in the first chapter is presented below

# `table to be added`

The context has also been analyzed in the first chapter, which contains the relation between the system and the context, the system range, and the interface between the system and context. The table is presented below

# `table to be added`

What's more, in the first chapter we have worked out the functional requirements too. The table is presented below. Note that it is necessary to satisfy the requirements, but that is not adequate. Even if all the requirements are satisfied, it is not guaranteed that the project will be successful. It's important to combine all the features, run the system and check its behavior. 

# `table to be added`

Through the analysis of the house of quality we obtained technical performance measures. They are neglected here, because they have no influence on the description of system behavior. In chapter three we have figured out all the subsystems, which are listed below,

- Body detection
- Sound detection
- Liquid detection
- Display
- Data processing
- Game

Till now we have gathered all we need for the next step.

### ii. Map behaviors to subsystems	

The first step of behavior design is to describe behaviors at the system level. As we have analyzed behaviors in chapter 1, here we perform more detailed analysis. We use running description template to describe the system behavior, from the beginning of the interaction between the user and the device to the end state of the system. The input information generate from the user is listed on the left of the template, the response of the device system is on the right. If the interaction process involves more than one subsystem, it will be analyzed one by one according to the signal flow. The template contains three parts: initial state, behavior analysis, end state. 

# `table to be added`

### iii. Identify messages, triggers, and interfaces	

Different subsystems are response for different functions, which are triggered by different activities or events, therefore we add interfaces (between a subsystem and the context, or different subsystems) in the above template. All the interfaces are marked as grey in the template. The updated template is presented below.

# `table to be added`

To prevent the interaction device fall in deadlock, two extra functions are added in the above table, which are marked yellow:
* After repeatedly displaying the hint message without getting any response, the interaction device will quit the current process and show the advertisement.
* If no liquid is detected in a certain time span, the interaction device will quit the current process and show the advertisement.

Below is a graph produced using IBM Rational Rhapsody,

# `graph to be added`

More related graphs are in the supplementary 

### iv. Identify system states	

Another way to analyze system behavior is to identify system states. When transfering from one state to another, we keep track how the system changes. This step is useful for finding unstable states during the process. The result is shown in the table below

# `table to be added`

The corresponding graph made by using IBM Rational Rhapsody is presented below

# `graph to be added`

### v. Set targets for behavior	

The template is also useful for collecting other information, for example time related events or actions. It is updated and shown below

# `table to be added`

### vi. Extract functional requirements to originating requirements	

The running description template may help the team focus on the whole system, instead of a single subsystem. We made different templates for different use cases. After combining all the templates, we get function requirements. The requirements are goal-oriented, as each of them corresponds to one or multiple functions. The summarized function requirements are listed in the table below.

# `table to be added`

### vii. Trace derived requirements to original requirements	

Through the previously analysis, we have a better understanding of the requirements. During this process, many derived requirements may appear. Here we trace the derived requirements to original requirements, check if there are conflicts and solve them by modifying the functional requirements. The result is listed in the table below

# `table to be added (only one is enough)`

Base on the table above, we can construct the tracing matrix

#  `table to be added`

From the matrix above we can find the original requirements that do no have a corresponding derived requirement. They are converted directly to derived requirements and listed in the table below

# `table to be added`

### viii. The centrality of the operational description template	

Now we switch back to the running description template. On the left side is the user. Based on the user behavior we can define the norm for the user interface, which can be used for editing the user manual. Base on the behavior description of each subsystem, the requirement norm for each subsystem are defined. What's more, through analyzing the template, norm for test and interface requirement can also be defined.

# `table to be added`

## b) Design the flow and control	

To avoid lost in details during function analysis, here we perform two different method, one based on functions, the other based on state changes. 

### i. Identify functional relationships	

System behaviors can be seen as interactions between different subsystems to realize different functions. We describe the behaviors using the function matrix, which is generated from function requirements. 

# `table to be added`

Note that entries below the diagonal are empty, otherwise the device will fall in deadlock.

### ii. Summarize state changes	

Here we focus on state changes and event triggers. Through analyzing the function matrix, we have a good understanding of system behaviors. Through the analysis of state change matrix, we can double-check if any system states are omitted in the previous step. As we can see from the table below, there are non-empty entries below the diagonal, which suggests that the system might be in abnormal states. 

# `table to be added`

In the table above a deadlock state is marked with bold borders. Below is the state change graph. Within the square is the system state. Lines represent paths, with events indicated above them. 

## c) Design the structure	

### i. Identify interfaces and finalize subsystems	

Here we use interface matrix to identify and analyze interfaces. Outside entities and inside components are listed in the top row and left column of the matrix. The other units are interfaces, which describe messages or events transferred between subsystems. The identified interfaces are recorded in the interface control document. 

# `table to be added`

If we remove outside entities from the above matrix, we will get design structure matrix. This is very useful for multiple teams to cooperate and accomplish the task. Usually different team works on different subsystem. It's very important that all the teams have the same definition for every interface. 

# `table to be added`

The above matrix is arranged to have most of the contents above the diagonal, and most of the messages or events are in the column of data processing system. The matrix suggest that game system, data processing system and display system are closely related. To reduce system errors, it's better to develop these three systems at the same time. Therefore, we combine them as one, namely display, game and data processing system.

### ii. Document links	

This step is to analyze the way that different subsystems communicate and interact with each other through their interfaces. Here links may refer to RS232, Ethernet, Wi-Fi, USB etc.

# `table to be added`

### iii. Identify emergent interactions	

We use matrix to display all kinds of relationships. These analysis are follow the procedure from use cases to function analysis. Now we need to consider some unexpected side-effects which might rise from different subsystems. These emergent interactions may occur due to friction, vibration, heat, etc., which are common among mechanical systems but rare among software systems. We use interaction matrix to analyze these side-effects. Afterwards, we may consider to add new requirements or even subsystems to control the side-effects. 

# `table to be added`

### iv. Sketch a design concept	

Before substantiating the design of subsystems, we will sketch a design concept, which will be very useful later on. 

### v. Create a rough-cut bill of materials	

From the design concept we can estimate types and quantities of raw materials we need, and their cost. We list them in an table, in the order of descending system or subsystem levels. Note that this step is necessary for estimating the cost, however, it does not mean that the design is fixed. Estimating the total cost at an early stage is rather important. A large part of the cost is from the materials. 

# `table to be added`

From the table above, we present the cost in the table below. The viability analysis and professional knowledge are omitted here. 

# `table to be added`

### vi. Allocate target technical performance measure to subsystem	

Through analyzing the house of quality we have gotten the initial requirements, including cost and liability. These targets should be allocated to subsystems, hence to guarantee that the requirements are satisfied in the end. Correspondingly, target technical performance measure should also be allocated to each subsystem. If the estimated cost is higher than expectation, the cutting of the cost of each subsystem should be calculated. Here we skip this step. 

# 6. Validate the design	

As suggested by the V-model, design and test are related. Here we do not focus on the design-manufacture-test procedure, but on the steps before and after.

## a) Verify requirements	

### i. Conduct design reviews	

There are two types of requirements verifications: customer verification and internal verification. Through customer verification we can make sure the product is designed as customer requested, in the mean time, ambiguities in the requirements may be clarified during the discussion. These requirements are mainly behaviour related. The purpose of the verification is to figure out how to fabricate the product. It should satisfy customer's requirement but not violate any regulation. The regulation related requirements are generally non-behaviour related. Anyway, the focus of the verification should be on behaviours, instead of structures.

For systems that are very complecated, there will be more than one verifications, some for sub-systems, some for the whole system. Different verifications emphasis on different aspects. The status of design are also different at different stages. One thing for sure, the previous behaviour description template will be the main tool for verifications.

#### 1. Determine if entry criteria are met	

To avoid wasting participants' time, evaluation on design works should be done before the verification, to decide if entry criteria are met. Listed below are criteria for evaluation.

# `table to be added` 

#### 2. Schedule the review meeting	

For internal verifications, invitations should be sent out to experts in the field. For customer verifications, it's necessary to find customer deputies to form a group. They can present customer opinions properly. 
 
#### 3. Present the design	

Product design can be described from high to low levels, i.e., integrated product concept → function interaction matrix → status exchange matrix → interface, connection and interaction matrix. To guide the verification group to express their opinions effectively, it's better to present them the running description too, therefore they could have a better understanding of the task procedure.

#### 4. Collect review panel comments	

Collect opinions of the verification group on different parts of the design, such as on the function requirements or the procedure. After processing, they can be written in the verification reports. 

#### 5. Use exit criteria to assess whether the review was passed	

Before the verification meeting, exit criteria should be distributed to group members. It includes: the satisfaction of the customer requirements; the technical viability of the design; the risk of the project etc. As a result, group members can assess whether the review is passed. 

#### 6. Reschedule if the review did not pass	

If the review does not pass the verification, it can be modified based on the advices in the report, and reschedule the time for the next verification. 

### ii. Develop the test plan	

Usually the test plan will be worked out at a rather late stage. In that case, the content of the test plan will be based on the product design instead of requirements. On the other hand, if the test plan is worked out at an early stage, original requirements won't be omitted during the test.#### 1. Identify behavioural test sequence	

For test, running description template is very useful tool for designing test procedure. Two columns should be added in the template: the expected result and the real result. The real result should be filled in by the test engineer.  What's more, the template should also involve the special set-ups required for the test, such as equipments, costumes.

For our project, the test procedure is as follows,

# `table to be added`
# `table to be added`
# `table to be added`

#### 2. Develop behavioural test methodology	

Through behaviour analysis we have gotten the original requirements. There should be a test plan for every system behaviour. Usually test plans are presented in tables, listed with test schedules, test equipments, entrance and exit conditions. Entrance condition infers the requirements to be satisfied before the test; exit condition is the minimum requirements for passing the test. 

For some tests it's not necessary to wait until the prototype system is fully developed, if only certain parts are required. The earlier a test is started, the earlier defects in the design can be detected and fixed. The test stage can easily become the bottleneck of the project. It's better to start tests at an earlier stage, to avoid accumulating too many test tasks and cause a delay.

The exit conditions should have much flexibility. They should be approved by customers, owners and rule makers. Tests should be repeated and analysed using statistics methods. When developing the test plan, a requirements list with complete structures, clear descriptions can be very beneficial. For the ideal case, test plans should be drawn out from the requirements list. Therefore, test plans should be considered during the preparation of the requirements. 

For our project, behaviour test plan is analysed as follows,

# `table to be added`

#### 3. Repeat for non-behavioural tests	

Most of the non-behavioural request are obtained during the analysis of the quality house. The rest are usually from the review. Test are required for every request. 

For our project, non-behavioural tests are listed in the table below,

# `table to be added`

After finishing the plan for non-behavioural tests, a table for real test should be designed based on statistic methods. For example, after 10 tests, based on six sigma the average value and standard deviance can be used for evaluating if the design has passed the test or not.

#### 4. Map test activities to system requirements	

After finishing all the tests, it's important to check if they are complete. Now we should map test activities to system requirements, to make sure that there is a test activity for every original request. The result will be presented in a reference matrix. Any omitted tests should be added now.

For our project, the result of checking the test plan for behavioural requests is presented in the table below,

# `table to be added`

The result of checking the test plan for non-behavioural requests is presented in the table below

# 'table to be added'

Develop the reference matrix to check the completeness of the tests.

# 'table to be added'

Here we figured that OR2 (the interactive device should be able to receive instructions and display commercials) hasn't scheduled for test, which should be added.

# `table to be added`

## b) Manage risks	

Risk management is of great importance and has been considered during the preparation of the quality house. There are two ways to manage risks: one is from bottom to top -- the failure mode and effects analysis(FMEA); the other is from top to bottom -- fault tree analysis(FTA). For our project, we choose FMEA. Behaviours that minimize risks are called rectification behaviours, aiming to reduce probabilities of malfunctions, or the damage caused by it if malfunctions occur. 

### i. Conduct failure modes and effects analysis	

#### 1. Select functions	

As mentioned above, the FMEA procedure is to preform analysis from bottom to top, starting with basic components or subsystems. Note that analysis start with functions may discover same risks. For our project we start with subsystem.

# `table to be added`

#### 2. identify failure modes	

Here we identified failure modes for every subsystem. Note some subsystems may have more than one failure modes.

# `table to be added`

#### 3. assess potential impact of failure	

According to their impact, failure modes are classified in three levels, 1. local -- direct impacts caused by the malfunction; 2. system -- the damage on the whole system; 3. task -- the impact on the environment and surrounding people. 

# `table to be added`

#### 4. brainstorm possible causes	

Now is time to analyse every failure mode and find out the reason. There are many different causes. Most of them fall into four categories: human, machine(such as components failure), method(such as software error), and material. 

# `table to be added`

#### 5. suggest corrective actions	

After finding out the causes of failures, it's time to look for corrective actions to reduce the chance of malfunctions occur. It's important to consider the timing for corrective actions. The three windows are: during design, manufacture and running. 

# `table to be added`

Although we have gotten the result of the analysis, it doesn't mean the related systems have to be modified. We need to estimate the cost and evaluate the benefit of the modifications.

#### 6. rate the severity of impact	

Next we need to estimate the probabilities of the failures occur and the damage they may cause. The table below shows the rate of the severity of impact.

# `table to be added`

#### 7. Rate the likelihood of causal occurrence	

To rate the likelihood of causal occurrence, we use the table below. Here MTTF is mean time between failures. 

# `table to be added`

#### 8. Assess the risks	

For a simple project, risks can be analysed using using a two dimensional table, one dimensional corresponds to likelihood; the other corresponds to severity. To assess the risks, simply multiply the values along the two axis gives the risk priority number(RPN), i.e., likelihood * severity = RPN.

# `table to be added` 

#### 9. Prioritize the action	

The last step is to prioritize the action. It's better to find solutions for risks with high priorities as quickly as possible. It worth to note that some risks may cause severe damage, but it is very unlikely to occur. Therefore, it has a very low RPN. Such ricks should be re-evaluated as derived requirements. 

For our project, the priorities are listed in the table below

# `table to be added`

# 7. Execute the design	

From now on, we will shift the focus towards project managements. In reality, no matter how perfect the design is, there will be many unexpected obstacles appear in practice. It's important to have a well organised team that can react to the changing of the environment promptly. It's necessary to carefully ponder the interaction between different subjects base on the view of the whole system.

## a) Schedule the project and track progress	
### i. Develop the task list (work breakdown structure)	

The main task of the project manager is to define the project category, and identify all the tasks to be done within the category. If the estimated cost exceeds the budget, it's necessary to find a way to reduce the cost, or negotiate with the investor to increase the budget. 

Here the first step is to develop a task list for all tasks within the category. Tasks can be decomposed and sorted base on their ranks. 

# `table to be added`

We list all the low rank activities in a new table and give each of them a number.

# `table to be added`

### ii. Estimate durations	

To work out the schedule, it's necessary to estimate the time for each task. This estimation is based on experience, which can be modified during the action. For our project the estimation is listed in the table below.

# `table to be added`

### iii. Task percent complete	

The project manager should follow each task and make sure none of them is overdue. If the project requires collaboration of different teams, leaders of the teams should report to the project manager about their progress. These informations are added in the same table.

# `table to be added`

### iv. Identify task inputs, outputs, and deliverables	

It's important to be aware of the relation between different tasks. This relation can be presented in a task input-output matrix, which describe the order of design, manufacture and test of all tasks. 

For our project, the matrix is composed of 26 design and manufacture activities, and 14 test activities. For simplicity here we show part of the matrix as an example. The complete matrix can be found in the excel file "task input-output matrix". For example, the A.01 subsystem requirement will define the interfaces, norms and requirements of the body and sound detection subsystems, which should be worked out before purchase. 

# `table to be added`

The summary of the task input-output matrix

# `table to be added`

### v. Establish task precedence relationships	

After working out the task input-output matrix, it's easy to generate the establish the task precedence matrix. Each cell marked as "1" in the matrix indicates that the task labelled in the row should be finished prior to that labelled in the column. For our project, only part of the matrix is presented here. The complete matrix can be found in the excel file -- "task precedence matrix".

# `table to be added`

In the above matrix, some of the cells under the diagonal are labelled as "1", indicating that the order of the tasks should be adjusted. This work can be done by using computer programs. The adjusted tasks are listed in the table below based on their priorities. 

# `table to be added`

### vi. Schedule the project	

The next step is to work out the schedule, which presents the start and end time of each task. 

# `table to be added`

Note that the start time is assigned as the earliest time the task may be started. For example, the activity A.21 "integrate the body detection system and the data processing system" can be started after the accomplishment of A.04 "test body detection system" and A.14 "test data processing system". Therefore, the start time of A.21 should be the later time between the end times of A.04 and A.14.   

### vii. Display a Gantt chart	

The schedule can be visualized using Gantt chart. Here we use MS Project to produce the Gantt chart. 

# `ms project to be added`

Note that many tasks are parallel. Here we do not consider the competition of resources. For example, we only have one data process system. The integration of the data process system with other systems, such as body detection system, sound detection system, liquid detection system, etc, has to be done one by one. Therefore, the schedule should be adjusted according to the availability of resources.

### viii. Adjust the schedule for team availability	

For a small project, adjustment of the schedule can be done by using the test for error method and add delay in the schedule. For big projects, this step can be done by using computer programs. For our project, the result of the adjustment is displayed in the table below.

# `ms project to be added`

In the previous MS project table, a column of "Levelling Delay" is added. Next, we need to assign tasks to each team member, based on his/her availability. 

# `table` to be added
# `ms project` to be added

Team members are added in the Gantt chart. We should go through each member  and check if there is any time conflict between different tasks. If yes, a delay should be added in schedule. 

## b) Conduct management reviews	

By conducting management reviews, we can check if the project progresses according to the schedule. In this step, all the team leaders should report to the project manager. For efficiency, normally the report is presented in one A4 paper, which contains the following contents:

- achievements; works have been done since last review
- plan; works should be done before next review
- metric; a practical and objective way to evaluate the result
- obstacles; problems the teams encountered, which may cause delay or cost exceeds budget

For our project, the result is presented in the table below

# `table to be added`

During the review, based on the information from all the team leaders, the project manager should judge the situation and draw following conclusions if necessary,

- stop the project. If the target is not reachable, stop the project may save cost
- allocate more resources. This may help the project progress faster
- modify the target or the requirements. If the cost is too high, it's better to negotiate with the customer and see if it's possible to reduce the quality or cut some functions, and therefore reduce the total cost

# 8. Iterate the design process	

## a) Iterate until feasible	

All the above mentioned steps are in the same mode, from one start point, going through all the analysis steps, and reach the end. However, when errors occur during the development process, or it turns out that the design cannot satisfy all the requirements, or some components fail the tests, it's necessary to backtrack and iterate the design process.

### i. Backtracking strategies	

- terminate or modify the project
- modify the requirements, narrow down the project, or increase the investment
- lower the exit standards. If some modules cannot pass the test, it might be OK to consider to lower the standard for acceptance 
- improve the quality of the related components or subsystems. Sometimes it is due to the quality, not the design.
- adjust the parameters. Maybe the design is viable, but the parameters are far from optimized. 
- backtrack to the selection phase, try the second solution, evaluate the viability. 
- backtrack to the concept category tree and look for other possible solutions. 
- merge functions. Sometimes extending functions of one component may make other components with similar functions redundant. 
- describe functions or problems more abstractly. Maybe there are too much restrictions on descriptions. Redefining them during the abstraction may be helpful for finding new solutions. 
- add new functions, tasks or parameters. Maybe the current design does not have enough freedom to satisfy all the requirements. Adding new sub-functions may provide more design freedom.
 
For our project, the backtracking strategy is shown in the table below

# `table to be added`

## b) Iterate with improvement	

This document follows the procedure described in the book -- Getting Design Right, which combines the constantly improving concept in quality management with system engineering. Among the eight steps we mentioned above, the first six steps (define, measure, explore, optimize, develop, validate) are corresponding to three steps (plan, perform and check) in quality management. Data collected during validation in one iteration can be used during measurement in the next iteration. In this case, the last two steps (execute and iterate) are corresponding to the action step in quality management. 

Not all iterations result successful. It's important to learn and improve during each iteration. 

- tailor the procedure. Before starting to iterate, it's important to have a clear idea on the fundamental of the design, the actions to be taken, how far you should go along the path etc.
- develop standards for effectiveness measurements and competitions. 
- track the performance, be clear about the time consuming activities, have a better estimation on timing. 
- collect feedback, communication with each team, discuss the result of the iteration, weigh the pros and cons, improve the performance. 

## c) Iterate by level	

Iteration by level is in the nested form, which is different from the previous analysis. 

### i. Level-by-level decomposition: the Vee diagram	

According to system engineering, we describe a system through its context, behaviour and subsystems. The whole system is decomposed into many subsystems, which can be divided again and again, forms V shape design procedure -- the system engineering procedure. The above mentioned eight steps are applied to different levels. 

# `V shape pic to be added`

The left side of the V-model focus on the sort out all the requirements, identify subsystems, specify their functions, work out performance requirements, setup standards for interfaces. The design-manufacture at the bottom of the V-model relates to many different subjects. The final solution should be worked out by experts in the field. It should satisfy all the requirements. The right side of the V-model is focus on the design, which starts from the verification of whether all the components satisfy their requirements. After testing all the components, the next step will be the integration and verification of all subsystems. The last step is the integration and verification of the whole system, which eventually will be tested by the market and costumers. 

During the process, we should pay attention to the following three aspects, detail functions into behaviours; allocate nonbehavioural requirements; maintain hierarchies and traceabilities. 

#### 1. Detail functions into behaviours	

Similar to the procedure discussed in chapter 5, use case behaviours can be described through functions realized by corresponding subsystems. Running description template can be used for describing behaviour, subsystem function responsibility and interface requirement. 

According to the system engineering procedure, functions should be assigned to low level subsystems. The procedure should be iterated until enough evidence suggests the subsystems can be designed, manufactured and tested. 

#### 2. Allocate nonbehavioural requirements: linked houses of quality	

Just like the behavioural requirements, nonbehavioural requirements should be allocated on subsystems as well. Some engineering characteristics, such as weight, should be allocated on every subsystem levels; other engineering characteristics, such as velocity, should be presented on the interactions between different subsystems. The process of allocation is preformed by connecting related quality houses. 

# 'pic to be added'

Here we only show three levels of quality house. Ideally it should be applied on every subsystem level, and every procedure, such as manufacture, installation, running, uninstallation etc.

#### 3. Maintain hierarchies and traceabilities	

Previously we have used simple templates to illustrate systems and their relations. For a more complicated system, it's necessary to keep track of the data, such as,

- requirement traceability (trace the requirements in different system levels)
- material manifest (including subsystem, components, module etc)
- from behaviour to function and vice versa
- the physical relation between subsystems
- data and data stream
- test plan
- decomposed work structure
- work schedule

Listed above are mostly datum with level structures. For example, through the material manifest we can find out a component belongs to which module in which subsystem. 

## d) Dive and surface: a system view	

Dive is to analyze the questions in details, while surface is to summarize those details. During surface, we should focus on analyzing the questions and environments in the system level. To determine the viability of the analysis, we should switch to dive and be more specific. The following table is used for the analysis.

# `table to be added`

### Appendix 1 IBM Rational Rhapsody - Design black box system model	
### Appendix 2 IBM Rational Rhapsody - Design white box system model
