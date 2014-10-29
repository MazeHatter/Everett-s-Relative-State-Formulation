Everett's Relative State Formulation of Quantum Mechanics

overview: 

On page 9 of 1956's the _The Relative State Formulation of Quantum Mechanics_[1],  Hugh Everett presents the requirements to be satisfied to say an observation has taken place in a mathematical model. After receiving his PhD, Everett went on to do more work with computers than theoretical physics. Though it would not have been remotely possible in Everett's life time, his description of an observer in a mathematical model resembles a set of software requirements. This project explores ways to write an algorithm that satisfies those requirements and how such a model helps us understand measurement in physics, as well as  what such a model quantitatively predicts.

I. Background

It is well known that when an object is measured in quantum mechanics, it changes. Hugh Everett goes further. He says that when an object is measured in quantum mechanics, that the observer also changes, since the observer is a physical system having a physical interaction with another physical system.

>For this purpose it is necessary to formulate abstract models for observers that can be treated within the theory itself as physical systems, to consider isolated systems containing such model observers in interaction with other subsystems, **to deduce the changes that occur in an observer as a consequence of interaction with the surrounding subsystems**.
[1, p. 4]

What does this mean? It means that when you and I make a measurement, we gain a memory containing the outcome of that measurement. Is Everett actually suggesting that we make a model that contains a machine that makes measurements and record them in a memory? And that we look at the content's of an observer's memory to figure out how the model looks from the inside?

Yes, that's what he says alright:

>We have the task of making deductions about the appearance of phenomena to observers which are considered as purely physical systems and are treated within the theory. ...

>It will suffice for our purposes to consider the observers to possess memories (i.e., parts of a relatively permanent nature whose states are in correspondence with past experience of the observers). In order to make deductions about the past experience of an observer it is sufficient to **deduce the present contents of the memory as it appears within the mathematical model.**

>As models for observers we can, if we wish, consider **automatically functioning machines, possessing sensory apparatus and coupled to recording devices capable of registering past sensory data and machine configurations.**
[1, p. 9]

In the first and much longer version of his thesis, which was called _The Universal Wave Function_, he sums all this up:

>We shall be able to Introduce into the theory systems which represent observers. Such systems can be conceived as automatically functioning machines (servomechanisms) possessing recording devices (memory) and which are capable of responding to their environment. The behavior of these observers shall always be treated within the framework of wave mechanics. Furthermore, we shall deduce the probabilistic assertions of Process 1 as subjective appearances to such observers, thus placing the theory in correspondence with experience.
[2, p. 9]

This is actually a novel way of making predictions from a mathematical model. Rather than looking at the model from the outside, we try to find out how it looks from the inside. This isn't just a model of an object, but, in Everett's words, models a **"composite system: observer + object-system"**. We model the object we want to examine plus a physical observer to examine it. Then find out what the observer has learned. Put yet another way, this isn't simply a model of the things we measure, this is a model of measurement itself.

II. Enter modern technology

To implement Everett's Relative State Formulation we need a model with an observer in it. For an observer, we’ll use a measurement-making nanocomputer, (MMNC). Since observers are, according to Everett, *"automatically functioning machines, possessing sensory apparatus and coupled to recording devices"*, a MMNC is a nanocomputer that has a nano-camera or other instrument and records the measurements it makes to a hard drive, or RAM, or screen or paper print out if it’s appropriate.

Keep in mind the idea here isn't to actually build these measurement-making nanocomputers to go around measuring things in the real world. That would be kind of creepy.  The idea is to make mathematical models that contain an MMNC and other things for the MMNC to look at; through them, we can see the models from the inside rather than outside. 

Everett had very strict rules about how you could add an observer to the model. It had to be "purely" physical, a point he emphasized over and over. What does that mean?

It means you don't add any rule to the model that allows a measurement to happen. It must occur through the basic physical interactions of nature. It means, in order to have a purely physical observer, you first model the individual electrons and nucleons and photons involved and their interactions. With only those ingredients, you model atoms and molecules. From those, you construct the components of the MMNC, and of course from those construct the MMNC itself. In the model, the MMNC is purely physical and can have purely physical interactions with other objects in the model. Even the photons that bounce off of (or are emitted from) the object being measured, into the MMNC’s camera are present in the model. These are processed into a measurement and recorded.

As you might imagine, that's going to require a lot of particles in the model. That's why computers in Everett's time didn't stand a chance at getting the job done. That's also why today, our observer is a nanocomputer. Smaller means fewer material, which means fewer elementary particles, which means less work for the computer or computers running the model.

III. What's the point?

Imagine we've built a particle simulation. And imagine the particles in the model arranged into physical systems including a billiard ball, an MMNC, as well as some free electrons. The MMNC is directed to make measurements, such as the size of the billiard ball. So it does. Maybe it sticks a ruler next to it, and the it reads the markings on the ruler. The measurement is recorded on the MMNC's nanodrive. 

Next, ask the MMNC to measure the position and the momentum of a free electron. The MMNC's first measurement will require an interaction with the electron that imparts some force and changes it's properties. 

For this reason, it seems to me, measurements made in Everett's model will never violate the uncertainty principle, which is falsifiable. It can be falsified by building a model that satisfied Everett's requirement yet violates the uncertainty princple. A dilligent researcher in this case should attempt to falsify their conjectures. 

IV. The Beef

The plan is to use this open source project to keep track of models that show promise in satisfying Everett's requirements. The first step seems to me to be make a model of particle physics that holds electrons and neutron and protons into different atoms, hydrogen and carbon, ect.

All are welcome to join in. For the most part I've been playing with Javascript and Python models as of late. But I think all languages and approaches are welcomed toward satisfying Everett's requirement.


[1] http://philosophyfaculty.ucsd.edu/faculty/wuthrich/PhilPhys/EverettHugh1957PhDThesis_BarrettComments.pdf

[2] http://www-tc.pbs.org/wgbh/nova/manyworlds/pdf/dissertation.pdf
(note, this is a larger collection of papers of which the Universal Wave Function is simply the first.)
