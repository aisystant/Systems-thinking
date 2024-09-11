---
title: Continuous everything in engineering as techno-evolution
---

The limitation of the **waterfall model**^[Waterfall model,
<https://en.wikipedia.org/wiki/Waterfall_model>] was the
idea of a one-time unidirectional traversal by creators of the life
cycle as a set of works conducted according to practices, while the target system
was viewed as passively undergoing this one-time creation.
Therefore, **agile approaches** developed in engineering, overcoming
the concept of a "waterfall" life cycle, and in 2001 the Manifesto
for Agile Software Development^[Manifesto for Agile
Software Development, <https://agilemanifesto.org/>] appeared.
In 2017, the idea of **evolvability** as a key **architectural
property** reflecting the idea of **"continuous everything"**
firmly established itself not only in advanced engineering practice but also
in literature^[Neal Ford, Rebecca Parsons,
Patrick Kua, Building Evolutionary Architectures, 2017,
<https://www.oreilly.com/library/view/building-evolutionary-architectures/9781491986356/>],
and **architecture** finally differentiated itself from **development** into a separate
subject area, as literature began to reflect the inevitable
"productive conflicts" between architects and developers. Architecture
worked on slicing the system into minimally interacting
**constructs/modules** to maintain **stability** of the whole in
**evolutionary timescale** (well-known to engineers
**-ilities** turned out to be architectural characteristics), while
developers cared about maximizing functionality, which could lead to
temporary deterioration of architectural characteristics as the accumulation of
**technical debt** (tasks aimed at supporting selected
architectural solutions but not directly affecting functionality),
which turned out to be an **architectural debt**.

Ideas of **techno-evolution** came to engineering, but they differed from the idea of
**biological evolution** in that the **meme** as an analogue
of the **biological genome** was not located in the manufactured system itself,
but was stored in **digital** (meaning exact replication without accumulating analog error) form somewhere in the
systems-creators. This allowed for a significant acceleration of evolution, as
for some technocrab it wasn't necessary to wait until a whole crab
died to replace a failed claw variant through
**mutations** forming the claws' phenotype genes only together with the crab. Instead, it was possible to
use **smart** **mutations**, obtaining results, i.e.,
**in real life** only testing claw variants that showed success during modeling in the
**virtual world**— and changing only the claw, but not the entire crab. This provided high speed of techno-evolution and
its results, unachievable by just a one-time offer of a new set of
**features** (a one-time traversal of the "waterfall" for one instance of the system)
or only evolution with random mutations^[Joel
Lehman, Jonathan Gordon, Shawn Jain, Kamal Ndousse, Cathy Yeh, Kenneth
O. Stanley, Evolution through Large Models, 2022,
<https://arxiv.org/abs/2206.08896>]. To understand
how successful a system is in operation, system modeling for operational time appeared—**digital twin**, reflecting not only
the current state of the meme but also the state of the system's **phenome**. So,
it turned out that ontologies oriented on two times (1. operation and 2.
creating one **increment/feature**) were insufficient.
Nor were modeling tools for an entire **group of systems**
(**product lines**^[Software Product Lines mature into
the next generation of Systems and Software Product Line Engineering,
<https://www.softwareproductlines.com/>], sometimes **system
families**) as different variants of the system coexisting at the same time.

The solution was found in the idea of **continuous everything**^[The Continuous Everything (CE) concept
defined,
<https://en.itpedia.nl/2021/06/02/het-continuous-everything-ce-concept-gedefinieerd/>]
as an infinitely ongoing development with **continuous delivery**
of new **versions** of the target system with ever-new changes, wherein the pace of development is not slowed down
despite the increasing complexity of the target system, supported by both
an evolving architecture and evolving **teams** that carry out the development
(using the **reverse Conway maneuver**^[Nicole Forsgren, Jez Humble, Gene Kim,
Accelerate, 2018,
<https://www.oreilly.com/library/view/accelerate/9781457191435/>]).
In software engineering, this idea developed within the framework of the
DevOps/SRE/platform engineering (internal **production platform
engineering**)^[Aeris Stewart, How Is Platform Engineering
Different from DevOps and SRE?, 2022
<https://thenewstack.io/how-is-platform-engineering-different-from-devops-and-sre/>],
in "iron" engineering this idea is currently discussed in traditional
Systems engineering examples like aerospace, where **testing** of engines
of the next version starts before the tested engines of the previous version in the
rocket fly in their first flight, and each new instance of the rocket has new
features and/or improved design compared to the previous instance. But already in this way not only aerospace but also
automakers and roboticists work.
"Continuous everything" signifies a transition for engineering to techno-evolution projects, meaning smart (non-random) mutational/evolutionary
changes to the meme (**informational project model/design of the system**), and
not just changes to the phenome as "finetuning with a file"
of a system instance. During evolution, the system is considered not as
an instance (perhaps an industrial series with identical instances), but as a species— where the configuration of each instance can be unique,
continuously discussing **smart**
**mutations**^[<https://arxiv.org/abs/2206.08896>]**,
most likely leading to system success (in Darwinian evolution—these are random mutations during replication) and even unlike natural selection
industrial A|B testing is conducted, (and even more so, as not only two options are tested, but multiple options in many subsystems simultaneously) as a directed selection of such mutations.
**Evolving system** development attempts to make it as close to infinite
as possible, very long adjusting the system to inevitable changes both in the environment and in itself, as well as in
creation systems. In biology and life sciences, similar problems
of approaching infinity in time are discussed as
**open-endedness**^[Kenneth O.
Stanley, Joel Lehman and Lisa Soros, Open-endedness: The last grand
challenge you've never heard of, 2017,
<https://www.oreilly.com/radar/open-endedness-the-last-grand-challenge-youve-never-heard-of/>].

Thus, ontology ideas of evolution appeared and began to be developed within the ***
third generation of the systems approach**,
which not only considers systems creation from agents in their different
project/activity roles but also explicitly considers three times: system operation as a phenome, increment creation of the phenome
from the meme (**design** and **implementation**),
and meme change (evolution, continuous everything).