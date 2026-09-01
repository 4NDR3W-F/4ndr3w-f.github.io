---
title: Everything you need to know about the EPR paradox
date: 2026-09-01 09:00:00 +0300
categories: [quantum_interpretations]
tags: [entanglement,epr,copenhagen's_interpretation]
description: A deep dive on the most influential paper for quantum interpretations

image:
  path: /assets/img/einstein_bohr.jpg
  alt: Does God play dice?

math: true
---

# Introduction

The Einstein-Podolsky-Rosen (EPR) paradox is arguably the most discussed topic related to the interpretations of Quantum Mechanics (QM). The paper behind this paradox (Can Quantum-Mechanical Description of Reality Be Considered Complete?) is so monumental and influential that it has been ranked among the top ten papers **ever published** in _Physical Review_ journals. And for very good reasons: This paper brought to the forefront the concept of non-locality and entanglement, parts of QM that were already known but weren't fully understood until then. It also served as the banner for the group of physicists who criticized the standard interpretation of QM (the Copenhagen Interpretation) as it was forming. Even today, it is part of the zeitgeist that Einstein, a synonym for intelligence for many, wasn't the biggest fan of QM.

And Einstein was probably the one who had the biggest "right to protest" against the implications of the Copenhagen Interpretation (CI). His Special Relativity (SR) was still a "newborn" when Bohr, the frontliner of the CI, published his paper about complementarity. SR, now, allowed only local interactions, put a "speed limit" on everything (that has some form of energy), and introduced causality, limiting all the possible effects of an event to its future light cone and vice versa.

How exactly SR's locality may seem at odds with QM is easy to show, because QM is inherently "non-local", even without conjuring the EPR thought experiment. Suppose a particle is described by a wavefunction that is spread out over an enormous distance, light-years away. Measuring it somewhere is like "sucking up" the probability of the particle being found anywhere in that distance, something that happens instantly. So that "sucking up" surely must violate special relativity's universal speed limit (spoiler: it does not).

Even more importantly, though, SR was deterministic (as the rest of physics up to that point). And that very determinism is what the CI challenged. It supports the idea that the nature of quantum probabilities is innate and not a result of lack of information, as is the case with classical probabilities. Phenomena like when exactly an excited atom will fall to its ground state or what exact measurement of a qubit in a superposition of up and down will give are things that QM fundamentally doesn't have exact predictions for. Such a claim, i.e. that nature is not deterministic on a deeper level, of course ruffled some feathers, since physics predicted (with perfect accuracy, if you had enough information) a vast plethora of natural events, and that arguably was one of the most alluring characteristics of the field. Determinism provides a certain comfort to the human psyche.

So a fierce response from grand physicists of the time, and Einstein especially, was just a matter of time. And thus, the infamous EPR paper was born.

# Analysis of the EPR arguments:

## Definitions and context:

My objective is to present as fairly as possible the arguments raised by EPR, even though we know by now (thanks to Bell, but that is a story for another time) that the concerns of EPR regarding QM were false alarms. At first, I will present and analyze the arguments of Bohm, which are logically equivalent to the EPR arguments, except that Bohm's version is awfully simpler. Then, I will give an account of the original version of the argument, exactly as it is in the EPR paper, and lastly I will entertain Einstein's further arguments, since he himself was not very satisfied with the way the EPR paper turned out.

(Disclaimer: In my effort to present the other side of the argument justly, I will need to play devil's advocate, so I need to state that I do not claim as my own anything in this section.)

EPR tried to show that QM is incomplete. The first step is to define completeness:

> "Every element of physical reality must have a counterpart in the physical theory"

In other words, the theory is complete if every element of physical reality has a counterpart in the physical theory. This criterion seems logical, since it doesn't concern itself with the experimental and verification processes of said theory, but only with the expressive power of its formalism. I.e., being able to describe all the elements of reality theoretically and make sure not to include elements of reality that don't exist. These are merely the two contrapositive forms of the criterion:

>If a theory doesn't have a counterpart for every element of reality, the theory is incomplete.

or

>If the theory has elements that don't have a counterpart in reality, the theory is incomplete.

But the above criterion doesn't amount to much if we don't define what is considered as reality, at least as far as the QM incompleteness argument is concerned. Here is the Criterion of Reality, as it is found in the EPR paper:

>"If, without in any way disturbing the system, with certainty (probability = 1) the value of a physical quantity, then there exists an element of reality corresponding to that quantity."

This criterion gets especially interesting if we consider how one might get probability = 1 in the context of QM. QM supports that this may hold for a measurement only if the state at hand is an eigenstate of the measured observable. That means that we can claim elements of reality only for eigenstates. It is important to note, though, that even if the state at hand is not an eigenstate of the measured observable, the measurement itself will change the state into an eigenstate of the observable. This is because a measurement gives a certain result, and measuring again in succession must give the same result, so the state changes in such a way that after a measurement it will be in the eigenstate that gives that result. So, if a measurement indeed took place, the probability of getting the same result after the first measurement is 100%, meaning that we can claim there is an element of reality for the measured observable.

This is a very short description of the collapse of the wavefunction and the measuring problem, a topic I plan to analyze in great detail in the future. For now, though, accept it as part of the QM formalism that is being scrutinized.

## EPR thought experiment step by step:

### Step 1:

Introduce the singlet spin state. This state can be created by the splitting of a particle with total spin S=0 into two 1/2 particles, and more specifically, their antisymmetric combination. In Dirac notation:

$\ket{S}= \frac{1}{\sqrt{ 2 }}(\ket{\uparrow}\ket{\downarrow}-\ket{\downarrow} \ket{\uparrow} )$

This means that the two 1/2 particles are in an entangled state. I won't go into detail here about what entanglement is, but only about how it manifests in this case. This state tells us that if the first particle is found in the spin-up state, then the second particle will be in the spin-down state, and vice versa. They can never be found in both spin-up or both spin-down. This is important because the total angular momentum is zero and it is conserved in this system, so it should remain zero even when each 1/2 particle is measured separately.

This is described exactly by the math: Each of the two terms of the singlet state is a tensor product of eigenstates for the two observables $(\sigma_{i,z}\ket{\uparrow}=\ket{\uparrow})$, because if the state ended up being either one of the terms, we would know with certainty for both if they are up or down. But now we are in a superposition of eigenstates, and such a superposition cannot be written as a product state (A state that is a tensor product between all the possible eigenstates of the first part times all the possible eigenstates of the second part). That is why the state is an entangled one (and in fact, a state of max entanglement, but I digress)

Trying to add terms to the above state that it may be written in a tensor product of the two subsystems helps build intuition: why are they entangled? What would it take not to be entangled? Can the entangled or the non-entangled state be projected to classical systems?

Suppose now that these two 1/2 particles travel in opposite directions (because the total momentum is zero) and that each lands on a Stern-Gerlach (SG) magnet (which is a spin-measuring device). These two magnets are considered to be placed far away from each other, say one controlled by Alice and the other by Bob, in a way that they are spatially separated. That means that they are so far away that even light can't travel between the two SG locations during the time between the two measurements. This is to ensure that no communication between Alice and Bob, and no local interaction between the two 1/2 particles, can occur.

### Step 2:

Alice measures first the spin 1/2 particle that arrives at her. That means that Alice now knows that the particle she received is either up or down with certainty; say, for simplicity, that she measured it as spin up. That means that it can be predicted with certainty that Bob will receive a spin-down particle. But Bob hasn't measured his particle, and according to him the particle is in an entangled state (remember, there is no communication between Alice and Bob), so its state should not be able to be predicted with certainty (the entangled state is not a spin eigenstate). That means that the result QM gives, the entangled state, must miss something from the description of reality, since Bob's spin can be considered an element of reality (predicted with certainty) and the QM description doesn't express it. As such, QM is incomplete.

### Step 3:

It gets worse: Suppose Alice and Bob measure two different orientations of spin. (Important background knowledge is that the singlet state is axially symmetric; the results would be the same whether the measurement devices measure the x, y, or z components of the spin-1/2 particles.) But what if they measure different orientations?

Suppose Alice measures the direction along x. Instantly, we know that Bob's particle has an element of reality in the x direction of spin, and in fact opposite to the one measured on the first wing. But we choose to measure the second spin in the y direction. So for the second spin we have an element of reality for both x and y directions of spin, even though the related operators do not commute. To make matters worse, since Bob measured the y direction of spin, Alice's spin must have an element of reality for the y-direction of spin. Heisenberg's uncertainty principle has been violated, and there are elements of reality that QM cannot explain. QM is incomplete.

Comments:

1. Heisenberg's uncertainty principle states that we cannot know with certainty at the same time the values of two non-commuting operators. The most popular form of this principle concerns the position and momentum of a single particle, and it is formulated as: $\Delta x\cdot \Delta p \geq \frac{\hbar}{2}$. A similar inequality can be written for any two non-commuting operators, like the different orientations of spin. The inequality is connected to the result of the commutator - for example, for x and p:
 ![Commutator+Uncertainty](/assets/img/img1.jpg){: w="700"}{: .normal }

_Connection between commutator and Heisenberg's Uncertainty principle for x and p_

2. For those who will say: "A violation of Heisenberg's equation surely is a hit to QM, but it doesn't directly show incompleteness", yes, it doesn't show it directly, but it infers it. There are two ways to define completeness:

- Ordinary completeness: If a theory is complete, it does not leave out any relevant details about a system.
- Bijective completeness: Only one quantum state should correspond to any given real state. This only refers to truly distinct quantum states, i.e., states that ascribe different values to the same elements.

Those are connected:

If bijective completeness fails, that means that two distinct possible cases of reality exist. The one misses what the other gets. Both miss something. Incomplete in the ordinary sense.

If not bijective -> not ordinary <=> if yes ordinary -> yes bijective. (contrapositively)

That means that ordinary completeness implies bijectivity (Ordinary => bijective)

The opposite isn't true: If indeed the bijective completeness holds (i.e. only one q. state corresponds to a real state), that doesn't necessarily mean that this unique q. state doesn't miss something.

## Saving QM:

The theoretical integrity of QM really seems to be cornered and threatened - but don't fret, dear reader, because the answer is quite simple; otherwise QM would be dead years ago (the EPR paper was published in 1935!). It all starts with the definition of the criterion of reality, which silently assumes _locality_, Einstein's worldview and QM's mortal enemy. This silent assumption of locality and the blending of locality+realism has given ground for ample criticism against the EPR paper, because it obscures the logical structure of their argument.

But what is locality? There are multiple ways to define locality, but the one relevant to this debate is the following:

"Elements of reality about one system cannot be affected by measurements performed at a distance on another system".

That is the reason why the reality (i.e., the answer to "is it considered real or not?") of the spin of the particle that travels towards Bob cannot change because somewhere, spatially separated, a measurement occurred. Before that distant measurement, Bob's spin was not an element of reality, so it cannot suddenly be an element of reality after the distant measurement.

This part of the EPR argument (i.e. the assumption of locality) is eclipsed even further by the complete absence of "time" in the EPR argument. This seemingly innocent detail makes it very difficult to see how QM survives. So, let's define the criterion of reality with explicit mentions of time:

If we can predict with certainty (probability = 1) the value of an observable at time t_{1}, then at all times t\geq t_{1} there is an element of reality that corresponds to this element of the theory.

 ![Projection](/assets/img/projection.jpg){: w="700"}{: .normal }

_Locality allows the projection of the element of reality of the 2nd spin for times before the measurement_

Now, if we do not enforce locality and make specific mentions of times, "saving" QM is straightforward: Let's say that Alice measures the spin $s_{1}$ of the first particle at $t_{1}$. That means for times $t_{2}> t_{1}$ we can predict with certainty that a measurement of the second particle, $s_{2}$, will be the opposite of the first. Also, it means that the wavefunction is now reduced to either one of the two parts it had before. Suppose the first measurement yields $\ket{\uparrow}$ so the second would yield upon a measurement $\ket{\downarrow}$, thus the state is collapsed to:

$\ket{S'}= \ket{\uparrow}\ket{\downarrow}$

Of course, this state is an eigenstate for both observables, so both observables are elements of reality for $t_{2}>t_{1}$.

What EPR achieves by assuming locality is being able to project the element of reality of $s_{2}$ that exists after Alice's measurement to times $t_{3}< t_{1}$, where the system is described by an entangled state, which doesn't predict either particle's spin to be considered an element of reality.

What about the expansion of the argument? The one that violated Heisenberg's uncertainty principle? I got you. _When_ do you consider something an element of reality? Explicit mention of time breaks the argument once more: The moment the measurement on the first wing is made (suppose we measure their spin-up), we have the x-spin component as an element of reality for both particles. The state collapses to the one that gives spin-up in the x direction for the first wing and spin-down in the x direction for the second wing. At this point, the measurement on the second wing would be a measurement of the spin-down in the x direction measured in the y direction, which has a 50% probability of giving either up or down. Or in math:

After the first measurement:

$$\ket{S}= \frac{1}{\sqrt{ 2 }}(\ket{\uparrow}\ket{\downarrow}-\ket{\downarrow} \ket{\uparrow} ) \rightarrow \ket{S'}=\ket{\uparrow}_{x} \ket{\downarrow}_{x}$$

Where the first ket of each ket tensor product represents the state of Alice's particle (first to be measured) and the second ket refers to the state of Bob's particle. So, measuring in the y direction on Bob's particle: $\bra{\downarrow}_{x}\sigma_{y}\ket{\downarrow}_{x}$. In the z basis, this is:

$$\begin{bmatrix}
 1 & -1

\end{bmatrix} 

\begin{bmatrix}
0&-i \\ i&0 
\end{bmatrix}

\begin{bmatrix}
1 \\\ -1 
\end{bmatrix}
 =
\begin{bmatrix}
1 & -1 
\end{bmatrix}
\begin{bmatrix}
i \\ i 
\end{bmatrix} =0$$

which is a very intuitive result that tells us that the $\sigma_{y}$ observable doesn't have a preference for the y-up or the y-down state when it is in the $\ket{\downarrow}_{x}$ state; in fact, this expectation value is zero exactly because that state gives a 50% chance of giving either y-eigenstate, as promised.

So, you still cannot "break" the uncertainty principle if you can't measure simultaneously. That was true for a spatially localized quantum state, and it stays true even for spatially separated states. QM is saved...

#### Original x-p argument:

An EPR analysis would not be complete without mentioning the original setup. EPR arguments didn't have to do with spins but with the position and momentum operators (x and p). This makes the argument a little more abstract, but the core ideas are intact.

First, assume that two quantum systems (named I and II) interact (for times t=0 to t=T) in such a way that we cannot know the state of the individual systems after the interaction (which is to say they are entangled), even though we know the overall state through Schrödinger's equation. Also, no interaction between them is allowed for $t>T$.

Then, they consider an observable A pertaining system I with eigenvalues $a_{1}, a_{2},\dots, a_{i}$ and respective eigenstates $u_{1}(x_{1}), u_{2}(x_{1}),\dots,u_{i}(x_{1})$, where $x_{1}$ refers to all the variables used to describe the I system.

A's eigenstates can be used as a basis-state set to analyze the wavefunction:

$$\Psi(x_{1}, x_{2})=\sum_{n=1}^{\infty} \psi_{n}(x_{2})u_{n}(x_{1})$$

Where the coefficients for each eigenfunction must be dependent on $x_{2}$, which refers to all the variables used to describe system II.

Of course, this is also entangled (since it cannot be written as a product), and a measurement of A, yielding $a_{i}$ on I, would collapse the wavefunction from the infinite terms to 1, the one corresponding to the measurement result: $\psi_{i}(x_{2})u_{i}(x_{1})$.

Then, it is stated that if one chooses a different observable to use as a basis state to analyze \psi and measure, one would end up in a different state after the measurement. It is also pointed out that the measurements all happen on system I, and it is system II that is left in different states. For that reason, they consider that the same reality (system II after the interaction with I) can be assigned two different wavefunctions.

Having read the analysis above, it is probably easy to see that the problem is the assumption of locality. The systems are entangled, and the entanglement is non-local. You cannot infer the existence of an element of reality at a time before the distant measurement. Or simpler: A distant measurement affects the system.

Assigning different wavefunctions to "the same reality" is not the end of the EPR argument, of course. It is then argued that these two different wavefunctions can be eigenfunctions of two non-commuting operators. Of course, that is possible, and it really would be a problem for QM if these two wavefunctions were assigned to the same reality, because that would mean that we can know with certainty two non-commuting observables, violating the corresponding Heisenberg uncertainty. Then, they use math to prove that such a case is indeed possible, and in fact, with the two non-commuting observables being q and p (the position and linear momentum operators), to make the "violation" of the Heisenberg uncertainty principle even more stark. But such an analysis isn't necessary, because the problem with their argument is not in the math, but in the assumption that two "clashing" wavefunctions refer to the same reality.

They end the paper by considering the other side of the argument and saying that if their criterion of reality is considered not "restrictive enough", one will get different results if one needed the two non-commuting observables to be measured simultaneously. That is a step towards the right direction because then locality wouldn't be needed, even though truly simultaneous measurements aren't possible. But for them, "no reasonable definition of reality could be expected to permit this".

But, it is not that we need a more restrictive criterion of reality; we just need to let go of locality. And it's easy to see why something like that wouldn't seem "reasonable", especially when all of science up to that point was local, but basing science on what each of us considers reasonable can't be a good practice.

#### Einstein's position:

As I mentioned previously, Einstein wasn't very happy with how the arguments in the EPR paper were structured. He thought that math "smothered" the argument. Indeed, in his writing on the topic, like his correspondence with Schrödinger, he used very little, if any, math. Here is a quote from these letters:

"It is … characteristic of … physical objects that they are thought of as arranged in a space-time continuum. An essential aspect of this arrangement … is that they lay claim, at a certain time, to an existence independent of one another, provided these objects “are situated in different parts of space”. … The following idea characterizes the relative independence of objects (A and B) far apart in space: external influence on A has no direct influence on B. (Born, 1971, pp. 170–71).

What Einstein is talking about is ascribing independent real states to spatially separated objects. That is what the classical intuition wants us to assume. But something happens to A and B if they are governed by an entangled state according to QM, which makes them unable to be described separately, no matter how far apart they are. This highlights how entanglement is inherently non-local.

Einstein understood that it came down to locality (in contrast to the EPR paper that doesn't mention locality once, even though they assume it), but could not accept that nature is non-local, especially since SR did not allow non-local phenomena.
$$
F \land L = I
$$
Meaning that QM's **formalism,** according to Bohr, along with **L**ocality, means that QM is incomplete.
$$
\lnot I = \lnot F \lor \lnot L \Rightarrow \lnot I \land L = \lnot F \lor \lnot L \land L \Rightarrow

\lnot F = \lnot (I \lor \lnot L) \Rightarrow F= I \lor \lnot L \lnot I \land L = \lnot F \lor 1
$$

which is known as Einstein's dilemma. It says, either give up locality or completeness of the QM formalism.

Einstein stuck with locality to the point that he tried his own luck with coming up with a QM interpretation, even though it is said that he gave up the paper he was writing, probably because he found out his version allowed non-locality too, as I narrate [here](/posts/The-Philosophical-debate-to-quantum-technological-revolution-pipeline.md/). Locality was so crucial to him that his main problem with the EPR paper was that it didn't point out how QM violated locality.

But what did the fiercest supporter and main figure of the Copenhagen interpretation, Niels Bohr himself, have to say about Einstein's arguments?

#### Bohr's position:

It's simple: he said that QM violated locality without violating special relativity. That is because QM's non-local phenomena do not, in fact, transmit any physical effects. Einstein's speed upper limit applies to anything that includes the transfer of mass/energy at said speeds. But the "sucking up" of the wavefunction refers to probabilities, not something physical, and as such SR is not violated. The same applies to the EPR setup, where the "instantaneous" effect, the "knowing" of the result of the state far away, doesn't amount to any transmission of energy.

And this is where the "paradox" breaks. Suppose that Alice measures spin up. Then, Alice knows that Bob, under a measurement, will get a result of spin down. They know that with certainty, but only the scientists at the first wing know that. From the perspective of the second wing, the spin measurement result is still 50% spin up and 50% spin down. And since they are spatially separated, there can be no communication between the two wings, so that the second wing could know the result before the measurement. So the argument about an element of reality being there that QM doesn't predict does not hold.

## QM and Causality/ QM-SR compatibility

There is one last argument in favour of locality, and that is the need for causality. Causality in physics is yet another concept of SR, and it says that the cause of an effect must be in the "past event light cone" of the effect and vice versa. I.e., the cause and effect must be two events that are not connected superluminally. One result of causality is the prohibition of superluminal communication. And at first glance, the EPR experiment could be grounds to assume that QM violates causality.

How exactly is that? The whole issue would arise if Bob (the second measurement) could use the result of the first measurement to change his result. We claim that the wavefunction collapses instantaneously after the first measurement, so Bob probably could change the orientation of his SG magnet to catch the already collapsed spin, to get the correct result 100% of the time. That is practically an element of reality which QM says should not exist, but even if Bob misses some and gets an overall correct result of ~75%, this would be as bad. QM predicts that Bob must have a 50% chance of getting the correct answer. And he does, because QM's standard interpretation does not allow signalling, i.e., transfer of useful information, between the two parties. The collapse of the wavefunction after Alice's measurement is knowledge that Bob does not receive upon the first measurement. For all that matters, for Bob, the wavefunction is as good as not collapsed. He doesn't know the result of Alice's measurement, and there is no way to know it; as such, he has a 50% chance of measuring up or down.

One could argue, though, that Bob's reason for not knowing is not inherent, but a result of incomplete knowledge. That is an argument against QM's claims that quantum probabilities are inherent, right? Wrong, because as long as SR is part of our best explanation of our world, we have to respect the limitations of causality, and thus accept that it is not that it is Bob's fault that he doesn't know Alice's result, but that it is literally prohibited for him to know. If SR holds, there is no way for Bob to know Alice's measurement before his measurement. So, in a sense, SR protects QM.

# EPR and the burden of proof

QM survived EPR's criticism. QM is non-local in a way that doesn't violate SR physically (upper speed limit) or semantically (causality). A careful analysis of the QM formalism, in addition to conscious choices of assumptions, shows how QM is not inherently inconsistent; it is just incompatible with the assumption of locality.

But who can say what is right to assume and what is not? This is the problem with the nature of this debate; it is philosophical. It is not based on experimental data. The "experiment" was a thought experiment, but one could argue that this is an example of taking the scientific procedure backwards: "I have a conclusion (nature is local + QM is non-local = QM is incomplete); how can I prove it?" That was more or less the way EPR approached this. And I am not saying that QM shouldn't receive criticism, but if Einstein et al. wrote a paper where they found experimentally these supposed elements of reality that QM can't explain, we would have a very different story. They did not do that. So they claimed there must be a better explanation for QM without providing said explanation. They, at the end of the day, have the burden of proof.

What is the burden of proof, you may ask? It is incredibly hard to prove that something doesn't exist. I can claim that there exist unicorns and you can say that makes no sense biologically, but that is not a proof that they truly do not exist. But it is not your burden to find a proof that what I claim is wrong. It is my burden to provide proof that what I claim is right.

Of course, Bohr could not reply to the metaphysical question of "is there a better explanation?" What he did was debunk the claims that QM has inherent inconsistencies. But that does not mean that there is not a better explanation out there. That led to a stalemate where either could be the case...Until Bell came along and turned this metaphysical debate into a testable, physical one. But that is a story for another time.

# Appendix A: Addressing common questions/concerns

It is inevitable for those newly introduced to the concepts above to resist them and question them. This reaction is common and crucial for deeper understanding. It signifies a true scientific way of thinking to challenge these ideas, and the most productive way to truly grasp the material is by entertaining these concerns and by holding the given explanation up to the light. To play a role in that, I will try to recall my concerns from when I came into contact with this material and give an answer to those concerns.

Feel free to comment with your questions on this subject. I think I will be able to address most of them. That way, we will be able to help someone else who may have the same question.

The first question I can think of has to do with the intricate workings of wavefunctions and how "insane" it sounds to have two wildly different descriptions of the setup (entangled / product wavefunction) that are not connected by a physical law/process but instead are the before and after of a measurement.

"If the two wings are not spatially separated and a communication channel is allowed so that Bob knows Alice's result before he measures, does that mean that there is an element of reality that QM cannot explain, therefore it is incomplete?"

Not really. You suggest that Bob uses the pre-collapse wavefunction to describe the reality of the second-to-be-measured particle, even if he has info about the collapse? There is an "incompleteness" to information here, but it is not QM to blame. Not using the data of the first measurement to adapt the wavefunction you use to describe your system is the reason you have an incomplete description. QM is dependent on the measurements. What difference does it make if you make the measurement or someone else does?

"This cannot be the most accurate description we have! What does it mean to 'adapt' the wavefunction by hand? Reality cannot depend on my understanding of it! What if I do a measurement, but miss the result on the measuring device? Is then the system in a superposition of spin up and down or not?"

We are getting to the heart of things. Wavefunctions are just a tool for us to describe something that we cannot comprehend otherwise. They are not physical; they hold information, like bookkeeping. So, yes, they change if you gain new information, no matter whether you measured (i.e., disturbed) the system or someone else did. As for the "missing the result" that leads to a bigger question.

# Appendix B: Lessons on Entanglement by EPR

One of the reasons that made the EPR paper so popular is the fact that it showcased the stark difference between quantum entanglement and anything classical. The EPR state is truly the 2-part state with maximum entanglement between the two parts.

Entanglement makes the two systems act like one. I mentioned before that you cannot fully describe a system that is entangled with another system without mentioning the entanglement. Formally, this is described by the fact that such a system is described by a mixed state rather than a pure state, which means that you don't have full knowledge of the system you are trying to describe.

But, apart from the formalism that highlights how they aren't independent, the two systems act like one for all intents and purposes. Let's go back to the argument against QM, which stated that the two parties could measure different orientations of spin so that at least one party has perfect knowledge of two orientations of spin simultaneously. The way this argument was debunked is by highlighting that the first measurement collapses the wavefunction, destroying the in-between entanglement, making the two measurements independent. What would be a problem for QM is if Alice and Bob made the two measurements on different orientations of spin simultaneously. But truly simultaneous measurements are not possible, which is what "saves" the uncertainty principles in single systems too. That analogy makes the EPR system just a spatially expanded single system. They truly are like one until a measurement collapses their collective state.

# Appendix C: Fun facts about the EPR paper

- It was published in 1935! Almost a century ago! Isn't that insane? If you truly die once someone says your name for the last time, Einstein is bound to live forever.
- It is widely hated. Even by Einstein himself. Yes, it was written and published in such a haste that Einstein himself didn't even read it before publishing!! The person everyone thinks about when they think about this paper hated it. I haven't read a single analysis of that paper that endorsed the way it was written (and I dug a lot). And there are very good reasons for anyone to hate it, no matter which side of the argument you are standing on.
- Einstein said that the math smothered the argument.
- Everyone studying it in retrospect, from philosophers to physicists, never mentions the original x-p entanglement, and everyone prefers Bohm's spin singlet version.
- The arguments made don't specify the order of certain events or the notion of time in general, and after the presentation of the argument, including time, it is easy to point out a weak point of the argument.
- Even philosophers who have invested in the logical structure, logical dissection of the arguments, and the back-and-forth of this debate think that the language used isn't doing a favor to the argument being made. Specifically, it is often pointed out that the assumptions made by the EPR paper aren't stated explicitly (locality and separability), which obscures their argument and makes a deeper analysis of the text necessary before any logical response could be attributed/ arguments countered.
- Lastly, it is common to change the wording, even the reality criterion itself, which is very central to the paper, to make it clearer whenever someone analyzes the EPR argument.