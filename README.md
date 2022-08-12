# Animal-Expert-System

## Knowledge Representation

One of the important concepts in Symbolic AI is knowledge. It is important to differentiate knowledge from information or data. For example, one can say that books contain knowledge, because one can study books and become an expert. However, what books contain is actually called data, and by reading books and integrating this data into our world model we convert this data to knowledge.

Most often, we do not strictly define knowledge, but we align it with other related concepts using DIKW Pyramid. It contains the following concepts:

* `Data` is something represented in physical media, such as written text or spoken words.Data exists independently of human beings and can be passed between people.

* `Information` is how we interpret data in our head. For example, when we hear the word computer, we have some understanding of what it is.

* `Knowledge` is information being integrated into our world model. For example, once we learn what a computer is, we start having some ideas about how it works, how much it costs, and what it can be used for. This network of interrelated concepts forms our knowledge.

* `Wisdom` is yet one more level of our understanding of the world, and it represents meta-knowledge, eg. some notion on how and when the knowledge should be used.

![image](https://user-images.githubusercontent.com/64821137/184442022-4408d7dc-1e1a-4922-8c0b-ba3b2bcef7ff.png)

## Expert Systems

One of the early successes of symbolic AI were so-called expert systems - computer systems that were designed to act as an expert in some limited problem domain. They were based on a knowledge base extracted from one or more human experts, and they contained an inference engine that performed some reasoning on top of it.

![image](https://user-images.githubusercontent.com/64821137/184442153-ecaa90a8-08c9-4acd-968c-a807fcfd3fc6.png)

Expert systems are built like the human reasoning system, which contains short-term memory and long-term memory. Similarly, in knowledge-based systems we distinguish the following components:

* `Problem memory`: contains the knowledge about the problem being currently solved, i.e. the temperature or blood pressure of a patient, whether he has inflammation or not, etc. This knowledge is also called static knowledge, because it contains a snapshot of what we currently know about the problem - the so-called problem state.

* `Knowledge base`: represents long-term knowledge about a problem domain. It is extracted manually from human experts, and does not change from consultation to consultation. Because it allows us to navigate from one problem state to another, it is also called dynamic knowledge.

* `Inference engine`: orchestrates the whole process of searching in the problem state space, asking questions of the user when necessary. It is also responsible for finding the right rules to be applied to each state.

