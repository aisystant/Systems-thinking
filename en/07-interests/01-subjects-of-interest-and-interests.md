---
title: Items of Interest and Interests
---

In systems thinking, reasoning usually follows the systems mantra,
which has many different formulations, but it all comes down to
first considering the working target system in its environment (concept of
operation), then — what to make it of (system concept) and what methods can be used to create this system (engineering methods), then — who could
carry out these methods (creators-engineers), then — who could create
these creators (creators-organizers of engineers), and so on
down the creation graph. In any case, at some point in determining
important objects of attention in the project, its participants::roles are driven by
cultural conditioning on which objects are most likely
to change their state during the project--- based on knowledge of
how the typical engineering method of creation is arranged for those types
of systems. In fact, all our courses talk about the fact that a
systems thinker enters a project not with zero knowledge about
what happens in the project (which he has not yet properly seen) and what could
happen there at all.

For example, it is assumed that at each stage of growing the functionality
of the developing system (continuous development implies not a one-time
creation of the system, but the creation and development of the system with gradual
accumulation of its functionality), the possibility of creating
the next increment of the system is realized, it will be described in the concept
of operation, the system concept will be corrected, then the system
concept will be detailed in the project/design with enough precision for
manufacturing the increment, then parts of the new
increment will be manufactured, the system will be assembled and debugged “in the physical”, tested, and put into operation with the new increment, if problems are found, taken out of operation reverting to the previous version, operated
(operator's work, monitoring), and so on--- for each type of system
it will be something similar, although the terminology may differ significantly
(for example, the term “manufacturing of mastery” won't be used, but
there will be talk of “training to mastery”).

In any case, in the project, some set of objects is expected to change their states in the course of the project. This change of states
is carried out by some working methods. For example, the system concept
is developed with the participation of developers (their subject of interest is the functional
decomposition and set of constructs as affordances for subsystems
as functional objects) and architects (their interest is that
the system is built from constructs with optimal autonomy, because
this affects numerous architectural characteristics--- and this often
contradicts the proposals of some development groups). The interest
of developers is usually --- quick introduction of new functionality now
("quick and dirty solution"), the interest of architects--- quick introduction
of new functionality in the future (minimizing
technical/architectural debt). This is discussed in more detail in the course
"Systems Engineering." Still, it is important now that there are working methods
for development and working methods for making architectural decisions, which move the object "system concept" through states
in a coordinated manner, and this movement occurs throughout the project, considering
the continuous development of the system and the release of new and
new increments that implement new functionality.

The movement through the states of some objects changing during the project, as well as methods of modeling this movement, will be considered in
the methodology course. Which objects and how exactly they move through
states--- this will be considered in engineering courses (systems
engineering, personal engineering, systems management). In these
engineering courses, the roles that carry out engineering
(managerial, educational, promotional, etc.) work methods will also be considered. Each of
these work methods forces an agent performing the corresponding
role to pursue some interests.

Ultimately, we are interested not in the roles themselves, but in their working methods
(including methods of thinking/reasoning) and important/key characteristics
of some systems (concerns, systems/roles/works/activities
items of interest, "concerns"). Important characteristics --- these are
the characteristics of the system that are interesting to the roles in connection with their working methods. The values of these characteristics are changed by the roles
by their method/way, realizing their interest/preference in the values of these important
characteristics. Several related important characteristics are sometimes collected into
an area of interest, area of concern, the areas of objects of attention of roles in
a project.

For example, for the role of the architect in modern architecture, the characteristics that the architect must monitor are clearly
indicated (leading items of interest of the role are explicitly selected and documented in the project), and even guidelines are given on which metrics are better to use for
tracking these characteristics. For example, to track the
satisfaction of developers' interest in supporting the principle of "continuous everything" by developers::roles and "internal production platform engineers"::roles, four key metrics (Four Keys of DevOps, proposed in the book "Accelerate: The Science of Lean Software and DevOps" by Nicole Forsgren, Jez Humble, and Gene Kim) are offered to architects::roles:

- Deployment frequency
- Lead time for changes
- Change failure rate
- Time to restore service

Apart from these characteristics/concerns, architects are interested in (their items of interest) operational (i.e., operational/usage time) characteristics: availability, continuity, performance, recoverability, reliability, security, sustainability, and scalability. And also creation time characteristics: configurability, extendability, installability, reuse, localization, maintainability, portability, supportability, upgradability.

Common to all systems, these key architectural characteristics (also--- architectural interests, expressed by a variety of metrics) are not related to functionality, thus the unfortunate names were non-functional requirements, quality requirements. They are well known to systems engineers as --ilities, and it was understood that achieving acceptable values of these characteristics can be obtained by changing the design of the system, i.e., using different system assembly options from constructs/modules and different options for organizing interactions
between modules through interfaces.

These characteristics and possible metrics for them are continuously discussed
by the architectural community, in each engineering organization these
characteristics have their own variants, in each project, the architect
pays attention to only a small part of these characteristics. But agents
performing the role of architects are trained to uphold their interests in
achieving these or similar characteristics. The list of these
characteristics --- is a good starting point for training architects on what
should be the subject of their close attention.

A similar set of items of interest and some ideas on acceptable
values of achieved metrics for these items of interest is also available to
all other roles; in light of the vast variety of types of systems,
this set of "key characteristics"/"items of interest" is enormous, and
a huge number of roles participate in the project, performing work
by various methodologies, hence affecting, willingly or unwillingly, others'
items of interest: there is continuous collective discussion of
such decisions regarding the target system and all other systems in the creation graphs,
which leads to the project's success: if almost all interests are met, then the system being created and
developed by the project is successful. The project of its creation and development is successful.

An item of interest can be anything. Thus, ISO 42010:2022 gives
the following (also absolutely incomplete) approximate list of these items
of interest for the architect, and requires the architect to identify and
document them explicitly: suitability of the architecture for achieving
the objectives for the entity of interest, enterprise capability and capacity to implement the entity of interest, the feasibility of realizing and operating the entity of interest, the potential risks and impacts of the entity of interest to its stakeholders throughout its life cycle, added value to the stakeholder(s), reuse of known architectures, resilience, extensibility, adaptability, latency, resource utilization, effectiveness, operability, usefulness, usability, interoperability, complexity, sustainability and evolvability of the entity of interest, environmental impacts of the development, use, and disposal of the entity of interest.

In the previous version ISO 42010:2019 instead of the entity of interest it was the system of interest, in the current version the word "system" was replaced with a more general term. In ISO 15288:2023, when referring to ISO 42010:2022, the word entity is replaced by system, so we will follow this example. It's also interesting that the approximate list of architectural characteristics in ISO 42010:2022 differs from that provided in the previous paragraphs based on the latest discussions on the subject of systems architecture in the era of "continuous everything." Discussions among architects about what constitutes their item of interest are ongoing, and each architect is expected to have their opinion on what their role's item of interest (architectural characteristic) is, and what their role's interest (what value of the architectural characteristic they need to achieve) is in each specific project, with the architect's priority interests potentially changing throughout the project. This is exactly what's indicated now in textbooks for architects: you cannot satisfy all possible architectural interests, so choose only a few main items of interest (architectural characteristics), list them explicitly --- and professionally optimize metrics only for them, while keeping the rest at a "hygiene" level, that is, maintaining them at a minimally acceptable level to avoid remarks.

Items of interest determine the questions of some roles to other roles: they are interested in the forecast of the situation regarding the realization/observance of their preferences in the values of these important characteristics. These are not questions from performers/agents, these are questions from professional/occupational roles/“actors.” These are not questions from John Doe, these are questions from his role as Prince Hamlet. Important characteristics and preferences are role-based, needed for performing the work of this role by the working method of this role.

An agent/actor performing an assigned role may use means to satisfy their role's interest, far beyond merely performing the work by the assigned role's methodology. For example, actor-1 may unexpectedly for actor-2, who is playing a role with a different preference than the role of actor-1, call their friend, and this friend's boss actor-2. Actor-1 then asks the friend to "pressure" the performer to realize his preference/interest, instead of the preference/interest of actor-2's role. The result may be not a rational argumentation in favor of changing the opinion of actor-2's role, but a banal blackmail: a threat not to the role, but to the actor himself (a managerial threat from the theater director to deprive John Doe of a bonus if he insists on saying "to be or not to be" while playing Hamlet --- and let him solve it as he wishes with Shakespeare, the director, the audience, theatrical critics).

This is all sheer improvisation by actor-1, but no one said that people will realize their preferences just by stating them at meetings with other roles. No, people/actors are very inventive when realizing their role's preferences, they may change roles two or three times to realize these intentions, and hire other people to perform missing roles. Working methods, items of interest, and interests of roles, that is, actors, not performers/actors!

The performers/actors themselves, as roles of agents (it can also be considered this way: the actor's work is also work! Entering the role, playing the play, arriving on time for performances/games, not mixing up words) want to get paid, sleep well before going to work, be entertained and develop to take on more interesting roles. John Doe or Jane Smith are not particularly distinguished, they usually do not have their own preferences in current projects, but when they start playing their roles, that is, performing the artist’s work (playing Prince Hamlet to the audience), engineer (developing CAD models), manager (negotiating the project plan regarding resources and timing), marketer (assessing market volume) --- this is where initiative and inventiveness awaken.

This is an “active entrepreneurial attitude”/enterprise/initiative/inquisitiveness and creativity, but not a specific role, but an actor, supported by intellect and further the entire set of skills of performing work according to applied methods available to the agent.

The actor develops a strategy (**strategy** --- is a specialized method for obtaining results in a specific situation), based on which plans his work (clarifies the availability of resources), and then
acts, strategizing on the move (re-evaluating the strategy) and replanning the work based on the changed circumstances.

Why does the actor act? He simply believes that investing in
additional actions of role-playing through additional working methods “here and now” will bring him benefits in the future, “there and then.” He acts absolutely engineeringly, that is, in the process of strategization based on his model of the world, he generates many alternatives for some methods of achieving his goals in the interests of the role, assesses the benefit of these actions by comparing the investments in them and the resulting imagined picture of the future world (the classic role of the entrepreneur according to Joseph Schumpeter), and then plans actions/work based on available resources according to the developed strategy --- and acts, continuously clarifying the state of affairs with satisfying the interest of his core role and changing the situation with the readiness of agents playing other roles to yielding to his pressure.

A systems thinker, as an actor, needs to be able to maintain a conversation on the topics of items of interest in the project (many roles may have the same items of interest, but different interests --- and this requires reconciliation of interests), to give each role sufficient answers about their items of interest so that each team and external role could assess the feasibility of their preferences/interests.

In the project, it is important to document descriptions of common areas of interest to facilitate the achievement of agreements. For example, if the item of interest is the price of a unique system, then some version of the estimate, or protocol on the agreed price, or expert assessment of similar open-market sales prices, or some other variant of description is needed. One needs to choose the description that will allow reaching an agreement. This documented description of the price::"key/important characteristic" will be studied by both the seller::role and the buyer::role. The price description will be their main communication tool for reaching an agreement
on their completely different preferences in price as an important characteristic.
And this price description will be of interest not only to the seller and
buyer, it may be needed for many other roles to agree on their preferences.
For example, the operational manager may be interested in the price when evaluating the maximum possible set of
resources for performing work on the project: he must have the maximum
resources, but no more than what the agreed price between the buyer and
seller will allow.

If you meet a person without a clearly expressed interest (interested in everything, or not interested at all, not having clearly expressed preferences, although they seem to declare some item of interest) --- this means this is not a role performer in the project, but just someone “curious”, “from extras”, an “onlooker passing by”, a spectator accidentally entering the stage during a play, a non-player who accidentally wandered into the role-playing game. Do not waste time on him until he shows his item of interest and preferences! But after you understand what he will do::method with the information obtained about his items of interest in the project, on the contrary, you should spend time on him, agree with him on decisions taken, however much you would like to ignore him. **Creation of systems ---** **is a continuous search for agreements regarding the project. A successful project ---** **is when everyone has agreed, and the systems thinker must ensure that everyone around him agrees!**

If a role (Prince Hamlet, not John Doe) discusses something that is not a part of his occupational interest, then at this moment you are talking to an actor (possibly playing some other role at the moment, which you are not aware of), not to a character in your "play", your
activity. **To reliably distinguish people in their various roles and determine** **their** **working methods, items** **of interest** **and** **preferences, one needs to have a** **work** **perspective ---** **in general terms to understand how human activities are organized with** **division of labor** **in its various forms** **into very different** **working methods, what** **types/variants of methods** **exist in each** **category** **of methods** **(for example, in** **systems engineering** **they immediately recommend paying attention to such** **working methods of different roles as** **visioning, development, architectural activities, production platform engineering, and in management it is business, organizing, organizational-architectural activities, administration),** **with what types of systems these** **methods** **work,** **what** **items of interest of these** **working methods,** **what preferences in these items.** In the previous section about methods and roles, we have already discussed this, but here we add that the perspective includes understanding the items of interest of typical roles. In the project, it will not be enough to recognize the working method and find out the culturally conditioned role performing the method. One also needs to understand what the role's interests are, what it will strive for!