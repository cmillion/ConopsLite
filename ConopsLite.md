####ConOps Lite: a quick tool for small software project definition

#####Abstract
This document describes a simplified version of the formal engineering product known as a Concept of Operations (ConOps) document that is appropriate for small, academic projects at the level of individual researchers and small research groups. A ConOps is a formal project management document that describes an existing system, justifies the need for a new or modified system, and outlines the proposed features and deployment environment of the new or modified system.

Creation of the ConOps is an important and critical step in large and industrial projects. It provides a common mechanism through which all project participants agree on the scope, goals, and feasibility of the planned work. The ConOps serves as a record of the project objectives and required features of a new system as well as their priority, so it provides a record by which to compare the capabilities of the final product against the initial goals. It is a living document that can and should change over the course of a project and serve as a record of new or changing requirements, false leads in development, or reassessments of feasibility. The creation of a ConOps early in the lifetime of a project of any size has the potential to dramatically reduce the amount of effort wasted by researchers and developers in building useless, unnecessary, or unwanted tools and features.

The IEEE formally defines the format and content of a ConOps for software development in IEEE Std 1362™-1998 (R2007) titled “IEEE Guide for Information Technology—System Definition—Concept of Operations (ConOps) Document.” IEEE Std 1362 is a generalized industry standard targeted to a broad range of project types and sizes. Its language does not necessarily require that you are working on a large, well funded team of professional developers, but it does kind of _assume_ that. Parts of the formal ConOps specification are rarely if ever applicable to work by an individual researcher or small group, and the inclusion of these details can make the official standard especially impenetrable and difficult to use.

This is a shame because a small amount of effort put into project definition early on can save huge amounts of wasted effort later in the project. While project sizes and time scales are often smaller in academia, effort is still wasted because of poor scope definition. If there were a simple template for defining the scope of small research software projects early on, perhaps this wasted effort could be reduced or eliminated.

#####Outline
Before you start a new project, you should take the time to go through all of these elements and compose (actually write down) responses to each. Make sure that everyone associated with the project (advisors, collaborators, other potential users or at least a representative sample of potential users) has a pass at the document and approves it before you start writing code.

1. Define what exists. (If anything.)
  * Who wrote it? When? What does it do?
  * How is it written?
  * Which features are useful? Which are not?
  * What features don’t exist but are needed?
2. Define what is needed.
  * What does it need to do? (Don’t bother with how just yet.)
  * List features. Be specific. Rank them by priority.
  * Identify the list of minimum features to meet the objective.
  * If there are specific performance requirements, list them.
  * Avoid the urge to define requirements too strictly. Write down the minimum that will meet the objectives.
  * What is the expected lifetime of the tool. (That is, it will probably be around for a long time. You will probably need to use it again in the future, and other people will probably need to use it.)
3. How much effort will it take to do?
  * For each feature, estimate level of effort (LoE). Be conservative (i.e. Assume it will take much longer than you think. If you have more experience, you will be better at estimating LoE, but you will still probably guess too low.)
  * Break each task down into its smallest elements as individual tasks. I.e. “Create an image from data.” “Display the image.” “Allow the user to click the image to create a histogram.” This will help you make a better estimate of time and will also serve as a useful checklist during development.
4. [Assess feasibility.]
  * Given the amount of time available.
  * Given the amount of money available.
  * Given the experience and skills of the developer(s).
  * Given the state of the existing software.
  * What can you reuse? (Both developed by you or your group and others).

#####Citations
IEEE Std 1362™-1998 (R2007)
