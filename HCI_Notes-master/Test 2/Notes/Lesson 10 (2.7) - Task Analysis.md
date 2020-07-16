# Lesson 10

In this lesson, we will look into two methods for task analysis:

1. Human information processor models - Especially GOMS Model, Input to user and output from user (Processor model)
2. Cognitive task analysis - A way to get inside users hedad (predictor model)

- Task is at the heart of the HCI. Look at the task, restructure tasks.
- Two Methods: 
	- GOMS Model (human information processor models) and 
	- Cognitive Task Analysis (A way of trying to get inside the users head instead of focusing just on the input and the output)

## GOMS Model

A human information processor model; it builds off the processor model of the human's role in a system. There are four categories in the GOMS model:

1. Goals - users goals
2. Operators - user operations to carry out method
3. Methods - user can use to complete (Methods - Operator 1---n)
4. Selection rules - which to select methods

- This model proposes that a human interact has a set of goals and methods they can choose from to accomplish those goals. 
- User starts with some initial situation/scenario. 
- Each method is comprised of a series of operators which help carry out that method. 
- Lastly, they use some set of selection rules to help decide what method to choose from.
- Once they've chosen a method, they execute that series of operators and makes that goal a reality

Ex - Transfer information to coworkers - Email, chat, In person, etc.

## Strengths And Weaknesses Of GOMS

Weaknesses of GOMS model:

1. Does not (automatically) address complexity - There are many methods and submethods for addressing a goal. 
The standard GOMS model leaves those kinds of things out, although there are augmented versions that have been created to deal with this kind of complexity, like CMN-GOMS and NGOMSL.
2. Assumes user is an expert - GOMS doesnt account for novices and user errors. 
GOMS model assumes the user already has the methods in mind. eg. I dont know highway in USA.

Strengths of GOMS model:

1. Formalize user interaction:
- The strength of GOMS is its ability to formalize user interaction into steps that we can actually use to make predictions. 
- We can measure how long each of these operators takes, and so we can predict the overall efficiency of using a certain interface.
- Helps to narrow down the time for each steps. 
- Find areas of improvement. 
Example: Count time for each operator, easy to get keychain while holding something in hand.


### Types of GOMS
KLM - GOMS -> Keystroke level model
	- Is the simplest of GOMS model
    - Lists sequence of operators & execution time for the operators
	- Must specify Method used for the operators
	- here operator + execution time - efficiency determination
	- 6 types of operators 
	- (K-press key,P-point,H-home,D-draw,M-mentally prepare action,R-response time)
	- Wont work on modern ideas. we would need some new ones to cover touch screens and other novel interfaces.

Card, Moran and Newell GOMS *CMN GOMS*  (***Hierarchy***)
    - CMN-GOMS is an extension of GOMS that features sub methods and conditions in a strict GOAL hierarchy.
	- Hierarchical Goals and choose multiple goals
	- Goals go all the way to Very-low-level (moving text,delete phrases)
	- Find place which we can cut out complexity
	- Modeling how long each individual GOMS to take

N GOMSL - Natural GOMS language
	- is a natural language form of GOMS that lends itself to human interpretation
	- the user is being asked to carry a lot of information in working memory
	- lends itself for human interpretation.

## 5 Tips: Developing GOMS Models

1. Focus on small goals
	- GOMS was really designed to work in the context of very small goals
	- GOMS shud be small (moment to moment goals), abstract up from there.
	- Example - Navigating end of doc.
2. Nest goals, not operators
	- GOMS of Navigation
	- we could develop it further and break the overall task of navigating down to smaller goals
		- eg. GOMS for changing lanes and plotting routes
		- Operators are smallest atoms of GOMS models. Dont breakdown further
3. Differentiate descriptive *What people do* and prescriptive *what you want them to do*
	- You can build goal model of what people should do with your interface. They will not do that?
4. Assign costs to operators
	- predictions about how long certain methods will take
	- Measurement of how long individual operators will take.
5. Use GOMS to trim waste
	- Use GOMS to cut cost by reducing unncessary operators.
	- Use GOMS to identify places where the number of operators required can be simplified by the interface

## GOMS to Cognitive Task Analysis

The GOMS model assumes the human is an input-output machine (processor model). However, human reasoning may be too nuanced and complex to be so simplified 

***Get more intomWhat goes inside human's head***
Cognitive task analysis is another way of examining tasks but it puts a much higher emphasis on things like memory, attention, and cognitive load (predictor model).

- Behaviorism vs Cognitivism
	- Observable of things
	- Get into mind.
- Behaviorism: Emphasizes behavior as a product of stimuli & environment
- Cognitism: Emphasizes internal thought process 

## Cognitive Task Analysis

Its collection of methods focus on what we cant see.

Cognitive task analysis are concerned with the underlying thought process associated with performing a task. Most methods follow a particular common sequence:

1. Collecting preliminary knowledge
	- No experts needed, but need some familiarity
2. Identify knowledge representations
	- what kinds of things does the user need to know to complete their task
	- Ex: Ordering of tasks/ Memorization etc.
	- eg. For navigation, monitoring and sequence of actions.
3. Apply focused knowledge elicitation methods
	- we start to recognize what the user actually knows
	- Identify task, knowledge by thinkout loud about it.
	- We do this by applying focused knowledge elicitation methods
	- Get user to tell us what's going on in their head or what's going on in their environment.
	- What changed their approach, what did they do in prior and what they do after change.
4. Analyze and verify data acquired
	- Confirming if understanding is correct.
5. Format results for intend application
	- We take results and models user.

Result looks like a flow chart, with various tasks in each box.

**limitations:**
- Challenge. large tasks are actually composed of many multiple smaller tasks. These smaller tasks could then be used in different contexts
-  These tasks are so high-level that it’s almost useless to describe them

## Hierarchical Task Analysis

Tasks could be broken and small tasks could be reused. 

This form of task analysis helps us understand what tools might already be available to accomplish certain portions of our task, or how we might design certain things to transfer between different tasks and different contexts.

Hierarchical task analysis process:

1. Abstracting out unnecessary details for a certain level of abstraction
2. Modularizing designs or principles so that they can be transferred between different tasks or different contexts
3. Organizing the cognitive task analysis in a way that makes it easier to understand and reason over

## Cognitive Task Analysis Strengths And Weaknesses

Like the GOMS model, cognitive task analysis also have strengths and weaknesses.

Strengths:

1. Emphasizes mental processes
	- Unlike GOMS, emphasis on whats goes on users head
2. Formal enough to for interface design
	- for comparison in mode alternatives and more
	- Easy to communicate
Weaknesses:

1. Time-intensive - They involve talking to multiple experts and systemtic analysis of data
2. May deemphasize context - Role of artifacts and deemphasize details that are in world
3. Ill-suited for novices 
	- Whos try to use an interface.
	- It's well suited to expert users who have very strong models of the way they work and clearly understand their own mental thought processes


### Other task analysis

**Human information**

- KLM - Keystroke level model
- TLM - Touch leve model
- MLP - Model human processor
all 3  capture even finer grain actions for estimating performance speed
- CPM-GOMS: focuses on Parallel tasks. 
- NGOMSL: Natural language.

**Cognitive Models**

- CDM - Critical decision model: focus on places where critical decisions occur.
- TKS - Task knowledge structures: Focus on nature of human's knownledge.
- CFM - Cognitive function model - Focus on complexity
- Appplied CTA
- Skilled CTA
ACTA and Skill-Based CTA are two ways of gathering the information necessary to create a cognitive model