# Correct at Construction

*A Philosophy for Experience Developers*

"And after all, we were tool makers." Howard Aiken, 1973, page 33.
[Smithsonian oral history transcript](https://mads.si.edu/mads/id/NMAH-AC0196_aike73027).

The experience comes first.

We are experience developers. Everything is built around the experience of the person using the software, and that experience should not be degraded.

We build software, but software is not the purpose of our work. What matters is the experience it makes possible.

And that experience does not begin when someone launches an application. It begins with the people building it, the tools they use, the systems they depend on, and the processes through which their work becomes something others can experience.

It includes everyone involved: developers, users, players, and increasingly, intelligent agents.

A frame-time hitch interrupts a player. A slow compilation interrupts a developer. Missing information forces an agent to search for something that it shouldn't need to search for. An ambiguous process introduces mistakes that could have been prevented.

Each represents unnecessary friction between intelligence and what it is trying to accomplish.

Everything within our control should be directed toward improving that experience.

This creates a self-reinforcing process. Faster tools enable more experimentation. More experimentation produces greater understanding. Greater understanding produces better tools, which make further improvements possible.

We should build systems in which every improvement makes the next one easier.

## We Are Toolmakers

Computers are tools. Software is a tool. The purpose of both is to extend what people can accomplish.

In 1973, Howard Aiken, the physicist who led the creation of the Harvard Mark I, reflected on the role of the people who built the first computing machines:

> "And after all, we were tool makers."

Aiken was explaining why he had opposed the creation of a separate scientific society devoted to computing. He saw computation as a general capability that could serve every field, rather than something whose value existed independently of its applications.

I believe this distinction remains fundamental.

Our responsibility is not merely to construct increasingly sophisticated software. It is to make the capabilities of computing available to the people and systems that can put them to use.

The value of our work is ultimately measured by what it enables.

## Correct at Construction

Much of software engineering is devoted to managing complexity after we have introduced it.

We write code, discover mistakes, establish conventions, add tests, introduce reviews, and construct increasingly elaborate processes to prevent those mistakes from recurring.

These practices have value. But they also raise a more fundamental question:

**Why was the mistake possible in the first place?**

If a system can know that an operation is invalid before it happens, why should we depend on someone remembering not to perform it?

If a dependency can be established automatically, why should someone maintain it by hand?

If the correct next action can be determined from information the system already possesses, why should a person or agent have to rediscover it?

Correct at construction means moving responsibility for preventable mistakes into the design of the system itself.

Correctness by Construction is an established idea in software engineering. My interest extends beyond functional correctness to the entire experience of constructing and using software, including performance, information, human time, and the environments in which intelligent agents operate.

The goal is not to verify increasingly complicated systems indefinitely. It is to reduce unnecessary complexity at its source.

We should make constraints explicit, relationships discoverable, and invalid constructions impossible wherever practical.

This does not mean every behavior can be known before execution. Some properties can only be established through measurement, and some questions cannot be decided in general.

But those limitations should define the boundaries of our guarantees, not discourage us from establishing everything that can be known.

**What can be guaranteed should be guaranteed. What must be measured should be measured. What remains unknown should be explicit.**

## Intelligence and the Responsibility of Systems

People do not make decisions in isolation.

They operate within environments that determine what information is available, how quickly feedback arrives, what actions are possible, and how much unnecessary work stands between them and their objectives.

When someone makes a mistake, we should examine those conditions before concluding that the individual was the problem.

Was the necessary information available? Was it accurate? Could the process have been simpler? Could the mistake have been prevented entirely?

At a sufficient level of intelligence, repeated and preventable failures should increasingly be understood as failures of the environment and processes surrounding that intelligence.

I believe modern intelligent agents have already reached a level of capability where this principle becomes especially important.

An agent may produce incorrect code or make a poor decision. But it should not have to independently reconstruct the architecture, discover undocumented constraints, determine which checks are required, or interpret failures that the system could explain directly.

Those responsibilities belong to the system.

This reveals a deeper problem.

Many difficulties we treat as technical limitations are actually problems of information, process, and time.

Missing information produces uncertainty. Uncertainty produces unnecessary decisions. Those decisions introduce opportunities for error. Errors create rework, which consumes more time and resources.

We can improve the intelligence performing the work, but we can also improve the environment in which that intelligence operates, to the point where the agent never has to search for anything. The system simply gives it exactly what it needs to pursue the goal the human set for it.

This benefits every capable participant, human or artificial.

**Intelligence should be spent solving new problems, not repeatedly overcoming deficiencies in the systems surrounding it.**

This is not an argument for eliminating judgment or responsibility. It is an argument for directing them toward the problems that genuinely require them.

## Tokens and Time

Tokens are a proxy for intelligent work done.

I believe the progress our species makes from here will be, in large part, a function of how many tokens are spent and how well they are spent. So we need to make sure they are spent well. That means making as many things as deterministic as possible, which reduces the tokens needed to complete a task. Wasted tokens are wasted time, compute, and money.

Time is the most valuable thing humans have. But it is something agents do not necessarily care about. We have to impose the time constraint ourselves.

I think all of technology can be reduced to the human time required to complete some goal.

## Speed Is Part of the Experience

Time is the resource we cannot recover.

Every unnecessary operation, every repeated mistake, every avoidable delay consumes time that could have been spent creating, learning, or experiencing something meaningful.

Performance is therefore not merely a technical characteristic of software. It is part of the experience itself.

This applies as much to development as it does to the finished product.

A game should not interrupt its player with avoidable hitches. A compiler should not interrupt its developer with unnecessary work. An agent should not spend its context and computation rediscovering information that could have been provided directly.

The principles are the same.

Our tools should account for their costs, eliminate redundant work, and provide feedback as quickly as the underlying problem allows.

Speed also changes what becomes possible.

When an experiment takes minutes instead of hours, we can perform more experiments. When feedback is immediate, ideas can be tested while they are still forming. When unnecessary work disappears, more resources become available for the work that matters.

**Performance is not separate from correctness or usability. Each should reinforce the others.**

## The Machine Is the Limit

Hardware provides the physical resources with which we work. Software determines how effectively we use them.

I want to approach engineering with the awareness of a chip designer: understanding how information moves, where work takes place, and what each operation costs.

The machine does not care whether we call something animation, physics, rendering, or simulation.

Those are useful abstractions for us, but they need not dictate how the underlying work is organized.

If two operations depend on the same data, perhaps they should execute together. If information can remain on the GPU, perhaps it should never be transferred back to the CPU. If multiple implementations are possible, we should be able to measure and select the one best suited to the available hardware.

We should not mistake the structure of our source code for the structure of the problem itself.

Our goal is to minimize the distance between the work that must be done and the physical capabilities of the machine performing it.

That requires measurement, experimentation, and a willingness to reconsider abstractions when they impose unnecessary costs.

**The machine establishes the limits. Our engineering should strive to approach them.**

## Carry What We Learn

We will make mistakes.

**Correct at construction does not mean correct on the first attempt. It means that what we learn becomes part of how the next attempt is constructed.**

We will build things that turn out to be unnecessarily complicated, discover better representations, and occasionally find that an entire implementation should be replaced.

That is part of learning.

What matters is that the knowledge survives.

A failure that teaches us something should change how the system is constructed. A recurring mistake should become a constraint, a better interface, or an improvement to the process that allowed it.

Documentation is useful, but knowledge that exists only in documentation can be forgotten, misunderstood, or become outdated.

Where possible, the system should embody what we have learned.

An agent arriving tomorrow should benefit from mistakes made yesterday without needing to read the entire history of the project.

A developer should be able to ask why a constraint exists and receive an answer grounded in the decision or measurement that established it.

And when an implementation is rewritten, the lessons that justified its design should not disappear with the code.

**The purpose of learning is not simply to remember our mistakes. It is to build systems that no longer require us to repeat them. This is what creates institutionalized and deterministic knowledge: knowledge that can be swapped out, retired, or improved without ambiguity. Ambiguity is wasteful.**

## What We Are Working Toward

I want to build systems that make intelligence more effective.

Systems that expose what they know, acknowledge what they do not, and make their constraints understandable.

Systems that prevent avoidable mistakes rather than continually correcting them.

Systems that treat the time and experience of everyone involved as something worth protecting.

Systems that allow developers and agents to focus less on managing complexity and more on creating what they envision.

This is the philosophy behind Correct at Construction.

It is also the foundation on which I am building CreationOS.

I believe the greatest opportunity in computing is not simply to make machines faster or intelligence more capable. It is to eliminate the unnecessary work that stands between that intelligence and what we want to accomplish.

Every mistake we can prevent, every piece of knowledge we can preserve, and every process we can make deterministic gives us back time that would otherwise be lost.

And those improvements should accumulate. What we learn today should make tomorrow's work easier, not leave us solving the same problems again.

We finally have a chance to do software right, from the ground up, from first principles. We have all of human knowledge at our fingertips, and each of us now has access to an intelligence that can help build almost anything.

Once you can build almost anything, the question is what to build.

**But more importantly, how should we build it? What is the correct way to build something when the experience of everyone involved, from its construction to its use, is part of what we are responsible for? That is our job as tool makers.**
