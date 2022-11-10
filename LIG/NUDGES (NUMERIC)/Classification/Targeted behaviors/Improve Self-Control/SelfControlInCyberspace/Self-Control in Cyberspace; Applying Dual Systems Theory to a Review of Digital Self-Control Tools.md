
[Paper link.](https://sci-hub.st/https://dl.acm.org/doi/10.1145/3290605.3300361)

# Description

This paper offer an analysis of a set of applications and browser extensions (N=367) to identify **common core design features** and **intervention strategies** afforded by *current tools* for digital self-control. 

>[!QUOTE] 
>This paper aim to help the design of better tools in two ways: (i) by **identifying how**, through a well-established model of self-regulation, current tools **overlap and differ** in how they support self-control; and (ii) by using the model to **reveal under-explored cognitive mechanisms** that could aid the design of new tools.

## Digital Self-Control Tools

They identified 17 HCI papers which have either built **novel design intervention** or **evaluated existing interventions** to support self-control over digital device use. For each of these, they examined which self regulation theories were applied to guide tool development (if designing new interventions) and/or to evaluate effects

| Paper | Summary                                                                                                                                              | Self regulation theory                                                                     |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
|       | Firefox extension which classifies URLs as work or non-work, then makes non-work tabs less prominent and displays time spent                         | Multitasking, inhibitory brain function                                                    |
|       | **AppDetox**, an Android app which let users voluntarily create rules intended to keep them from certain apps                                        | *None*                                                                                     |
|       | **RescueTime**, a commercial Windows/Mac application which provides visualisations of how much time is spent in different applications               | Cognitive Load theory                                                                      |
|       | **SAMS**, an Android app for tracking smartphone usage and setting time limits for app use                                                           | Relapse prevention model, clinical guidelines for internet addiction                       |
|       | **NUGU**, a smartphone app which let users set goals for limiting usage, then share performance with friends and receive encouragement               | Social Cognitive Theory                                                                    |
|       | **Menthal**, a smartphone app displaying the ’MScore’, a single number summarising overall phone usage, as well as a series of main usage measures   | *None*                                                                                     |
|       | **[[MyTime]]**, an Android app showing time spent in apps (and whether a daily limit was hit) plus a daily prompt asking what the user wished to achieve | *None*                                                                                     |
|       | **TimeAware**, an ambient Windows and Mac widget which presents time spent in ’distracting’ or ’productive’ applications                             | Framing effects                                                                            |
|       | **[[Lock n’ LoL]]**, a smartphone app which lets users as a group set their phones in a lock mode in which notifications are muted and usage restricted  | *None*                                                                                     |
|       | **PreventDark**, an Android app which detects phone use in the dark and notifies the user that they should put it away                               | *None*                                                                                     |
|       | **MeTime**, a computer application providing a floating visualisation of time spent in different applications within the last 30 mins                | *None*                                                                                     |
|       | Let’s **FOCUS**, an Android and iOS app letting users enter a ’virtual room’ where notifications and apps are blocked; links to location or time     | *None*                                                                                     |
|       | **[[PomodoLock]]**, a PC and Android application plus Chrome extension which blocks  distracting apps and websites during 25 minute focus sessions       | Strength model of self-control                                                             |
|       | **Freedom**, a commercial Windows/Mac/Android/iOS app which blocks access to distracting parts of the web or the internet altogether                 | Rational choice, ’self-commitment’                                                         |
|       | **HabitLab**, a Chrome extension in which the user sets time limit goals for specific  sites, then tries a range of interventions to reach the goal  | Numerous, including goal setting theory, operant conditioning, and self-consistency theory |
|       | **Freedom**, described above                                                                                                                         | Attentional resources, Big 5                                                               |
|       | Android app nudging users to close Facebook when a usage limit has been hit, using pulsing vibrations that stop when the user leaves the site        | Nudge theory, negative reinforcement                                                |
|       |                                                                                                                                                      |                                                                                            |

## Motivations

>[!QUOTE] Digital Behaviour Change Interventions (DBCIs)
>A large body of HCI work exists on how digital tools can **assist behaviour change** in general. Since digital self-control tools **can be seen as a subset of DBCIs**, understanding how self-regulation theory has been applied within this research area is relevant for the present paper.


### Self-regulation and self-control

#### The dual system model of self-regulation

The authors used the dual system model of self-regulation to classify and evaluate the efficiency of the applications.

This model define two different system control. The first one correspond to immediate reaction when the second one describe the conscious decisions.
![[Screenshot from 2022-10-15 18-02-52.png|400]]


The authors divided the app functionalities in 4 groups:
 + **Block/Removal**
	 + Feature minimization
	 + Block
	 + Can't be stopped when on
	 + Irrelevant effortful task to override
	 + Time limit
	 + Time lag to override
	 + Uninstall prevention
	 + Auto-reply during block
	 + Time lag before launch
	 + Launch limit
	 + Pay to override
 + **Self-Tracking**
	 + Record history
	 + Visualize usage
	 + Display a timer
 + **Goal-advancement**
	 + Concrete goal reminder
	 + Value/General goal reminder
	 + Set concrete time goal/s
	 + Motivational quotes
	 + Redirect activity
	 + Set activity goals
	 + Compare behavior with goals
 + **Reward/Punish**
	 + Gain points/streak
	 + Praise/Blame/Please/Annoy
	 + Social sharing/leader-boards
	 + Unlock achievements
	 + Points represented as lifeforms
	 + Lose points/streaks
	 + Real world punishment

![[FrequencyTools.png]]

The authors then **mapped** those functionalities to their dual system.

## Observations

The authors have observed that few applications had functionalities in each groups but rather one or two.
![[mapping.png]]

![[categories.png]]


