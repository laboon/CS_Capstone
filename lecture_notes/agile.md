# Agile/Scrum and Requirements Elicitation

## Agile / Scrum

* What do we mean by Agile?
  * Individuals and interactions over processes and tools
  * Working software over comprehensive documentation
  * Customer collaboration over contract negotiation
  * Responding to change over following a plan

* The main goal for agile software - develop software in an environment of change
  * At the beginning of the project, that is when you know the _least_ about the project
  * So why restrict yourself to what you know then?
  * Be _flexible_ while also be _prepared_
  * Agile does not mean "cowboy coding"!
  * Testing, documentation, design are still all necessary

* How do we prepare for change?
  * Adaptive planning
  * "Evolution" of a system instead of "culmination" in a particular version
  * Deliver early and often (_always_ have working software!)
  * Kaizen - "continuous improvement"

* Scrum is a particular agile methology with a heavy focus on being iterative and incremental
  * There are many others! (e.g. XP, DSDM)
  * Scrum comes from Rugby - team of people who work together to move forward
  * Been around since 1995
  * Scrum is very popular
  * Slightly more heavyweight than some other agile methodologies, but still a relatively lightweight process

* The "atomic unit" in Scrum is the User Story
  * User stories are kind of like requirements, but focused from the user perspective
  * Connextra template
    * As a ROLE
    * I want FEATURE
    * So that RESULT
  * Allows us to not only see what they want, but __why__
  * Gives us further flexibility if what they say they want is difficult/impossible, but can do something else that gives them the same result

* First, develop the Product Backlog
  * User stories that you want in the final system
  * Should be prioritized
  * Note - other items may be added to the product backlog (such as "defect fixes") later!  "Items" belong in the product backlog, not just user stories.  However, we should usually start with all user stories (and that is what I would like to see)

* Project divided into sprints, subdivided into days
  * Usually 2 - 3 weeks long (ours will be 2)
  * At beginning, take user stories from product backlog you want to get accomplished this sprint, put in the sprint backlog (Sprint planning).
    * Apply points - usually 1-2-4-8-16, where 16 is the entire sprint for one developer or pair of developers, 1 is tiny (typo fix)
    * However, assume all tasks will take at least four hours
    * However, try to avoid very large point user stories (if you have a 16-point story, in most cases you should break up the user story)
    * Developers work in tandem with QA to write/test/release(merge)
  * After the sprints, you have a sprint "retrospective", to think about what you've done right and wrong, and how you can do it better (kaizen - "continuous improvement")
  * Standups - usually daily and very short
    * What have I done in the last 24 hours?
    * What do I plan to do in the next 24 hours?
    * Do I need any help or have any blockers?
    * You can probably do this 3x/week or something, probably not necessary for every day
  * At the end of which, you have __complete__ software
  * Complete means tested, documented, integrated... that user story is done!
  * __Definition of Done__ - what does it mean to say that we're done?

## Eliciting Requirements

* Figuring out users' wants and needs and converting them into requirements (or in our case, user stories)

* Sometimes called 'requirements gathering'
  * I prefer eliciting because you need to draw them out, they're not just sitting around waiting to be picked up

* All sorts of ways to get them
  * Questionnaires
  * User observation
  * Workshops
  * Brainstorming
  * Role Playing
  * Prototyping
  * Interviews

* We will focus on the last two.  These are proven effective and if you have few customers, much better than spending time on a survey.

* Interview
  * Determine the actual business need
  * Identify people to talk to
  * Determine technical environment
  * Determine domain constraints
  * Avoid ambiguity
  * Try to get interviewee to say "obvious" things - you as a non-domain-expert may not know about them
  * User scenarios - if I do X, what do you want to happen?
  * Be sure to get functional and non-functional aspects of the system
  * Prioritization - what's important?  What's a "nice-to-have"?  What's superfluous?

* Requirements will change.  Bet on it.  Communication is difficult, especially cross-domain.

* Paper prototyping - using drawings as the UI and humans as the "interface"

## Your Goal

Your goal for the first part of this assignment is figure out what the user/customer _wants_ and _needs_.  Your software can be great, but it is worthless if it is not what the customer needs!
