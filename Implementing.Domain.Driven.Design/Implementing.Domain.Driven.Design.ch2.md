Chapter 2. Domains, Subdomains, and Bounded Contexts
======

There are three things you are going to have to understand very clearly:
- What your **Domain** is
- What your **SubDomains** are
- What your Bounded Contexts are

To succeed in implementing DDD, you have to get these right.

---
###Road Map to This Chapter###
- Grasp the big pcture of DDD by understanding Domains, Subdomains, and Bounded Contexts.
- Learn why strategic design is so essential, and why designing without it hurts.
- Consider a practical real-world Domain with multiple Subdomains.
- Make sense of Bounded Contexts, both conceptually and technically.
----

######  Big Picture  #####

###### Subdomains and Bounded Contexts at Work ########

###### Focus on the Core Domain  #####

###### Why Strategic Design Is So Incredibly Essential ######


---

### Naming a Bounded Context ######

>  Did you notice the name *Collaboration Context* used here? This is the way we name a Bounded Context, which is in the form *Name-of-Model* Context. In this casewe use *Collaboration Context* because it is the Bounded Context that contains the domain model of the Cooaboration project. We also have *Identity and Access Context* for the Bounded Context that contains the model of the Identity and Access project, and *Agile Project Management (PM) Context* for the Bounded Context that holds the model of the Agile Project Management project.

----
### Collaboration Context ###


### Real-World Domains and Subdomains ###############

- Problem Space
- Solution space

##### Problem Space ##################

>  The problem space is the parts of the Domain that need to be developed to deliver a new Core Domain. Assessing the problem space involves examining Subdomains that *already exist and those that are needed.* Thus, your problem space is the combination of the Core Domain and the Subdomains it must use. The Subdomains in the problem space are usually different from project to project since they are used to explore a current strategic business problem.


##### Solution Space ##################

>  The solution space is one or more Bounded contexts, a set of specific software models. That's because the Bounded Context *is a specific solution,* a *realization view,* once developed. The Bounded Context is used to realize a solution as software.



##### Here are some questions that should be answered in order to steer your project in the right direction:
- What is the name of and vision for teh strategic Core Domain?
- What concepts should be considered part of the strategic Core Domain?
- What are the necessary Supporting Subdomains and the Generic Subdomains?
- Who should do the work in each area of the domain?
- Can the right teams be assembled?

---

>Whiteboard Time
>```
Take a moment to look at your whiteboard work and consider: What is your problem space? Recall that it is the combination of the strategic Core Domain and the Subdomains supporting it.
```

---
