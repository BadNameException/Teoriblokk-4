This document is written as an assignment for the course Open Source (IS-213) at the University of Agder. The purpose of the document is to answer the question as to *Why people contribute to open source projects.*

**Abstract**  
In this document we will first outline how most open source projects are structured, and how their communities work. Then we will look at how an individual can be integrated into one of these communities. Last but not least we will look at why people would want to be integrated into such a community.

**Introduction**  
The topic of motivation is a difficult one to describe concretely. People are motivated by distinctly different rewards. While some people refuse to do a job without payment in the form of money, a different person might do the same job for the enjoyment of it, while yet another might do it just for the challenge.

Before we take a look the reasons why people are motivated to commit their time to open source projects we will first look at how most open source projects are structured.

**Communities**   
Like every type of project, be it software, hardware, or anything really, a place to gather all contributions is essential. Be it a lab for hardware, or a garage for cars. In the case of software it is almost always hosted on some kind of web platform. You also need some kind of way to document what has been done so that it can be used later on, either for proof/leverage, or as learning material for later projects. In the case of software this is present in the for of "versioning systems" [4]. These systems track changes in the form of: who did them, what was done and when it was done.

**Platforms**   
In the market today there is a clear leader when it comes to versioning systems, spcifically Git [5]. Git allows you to merge together code from multiple users into what is called a "repository". This *repository* has to be hosted in a central location where it is reachable for multiple users. and functions as a folder to hold all source-files for a project. It is normal practice to use a web-based platform for this. The leader in this part of the market is GitHub [6]. GitHub allows you to host your projects for free, as long as it remains open to the public. They also offer a version they call *"GitHub Enterprise"*, which allows for private repositories, albeit costing money.

Since GitHub [6] has become the *"standard"* location for hosting open source projects, it is the perfect platform to market your project for new users. This is very important for open source projects as they are dependant on an influx of developers for the project to continue its existence [3]. Just like in commercial closed-source projects there is a clear hierarchy within an open source project. A project usually starts out with a group of people with an idea for a project. These are known as the *"core developers"* [3]. Figure 1 describes a traditional hierarchy very well. At the core we have the starting developers, and as the project grows, so does the hierarchy.

![Figure 1 ](https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/9e13b0df8c772d05019d54c453a51942151938ca/3-Figure1-1.png)

*Figure 1*    

**Hierarchy**   
The next role we see added is the role of the "Maintainers". Their roles are, as the name suggests, to maintain parts of the system [3]. The part they maintain is usually a piece of software they have been developing through large degrees of their lifetime [3]. Maintainers usually have rights to contribute via the versioning system without going through the core developers.

The next role is that of the patcher. The job of a patcher is to fix bugs in the system [3]. Bugs are really anything that does something it is not supposed to do, example a link that is supposed to redirect to The University of Agder, but in reality redirects to The University of Nebraska Omaha [8]. The next role of bug reporter is heavily tied in with the patcher. The bug reporter is the one responsible for finding and reporting bugs. This role is one of the two entry points into the project. If we look at the project *"Django"* [9], which is a web framework written in python, we can see that there is an ability to create a *"new pull request"*. This means that we can suggest a change to the project, without any prior affiliation. It is though wise to learn more about the project and make sure that you create the request so that it follows the guidelines for the project.

Last but certainly not least we have the role of the documenters. Their role is to make sure the documentation is as available as possible, that it is gramatically correct, and that it is always updated [10].

A very good example of this is the Golang project on GitHub as can be seen in Figure 2.

![GoLang Github](https://i.imgur.com/PlJwhfp.png)

*Figure 2*

Here they have done a good job of structuring the project so that it looks inviting, but still has all of the relevant information available immediately. They also have a file called *CONTRIBUTING.md* which is a guide on how to commit your changes according to their guidelines.


**Sources**
* [1] https://pdfs.semanticscholar.org/98a6/c566a7e28a48facb664c8689607a52c57a5d.pdf
* [2] https://poseidon01.ssrn.com/delivery.php?ID=525111031127091070095092104098091124024042028006019024112092090106011101100062121039107127028116101098024089008118069058086006104073087082008027119077000073065061067083072121077095009025122075069066111067094076086002065113099107126023015110126&EXT=pdf
* [3] http://users.ece.utexas.edu/~perry/education/382v-s08/papers/ducheneaut.pdf
* [4] https://en.wikipedia.org/wiki/Git
* [5] https://git-scm.com/
* [6] https://github.com/
* [7] https://enterprise.github.com/home
* [8] https://en.wikipedia.org/wiki/Software_bug
* [9] https://github.com/django/django/pulls?q=is%3Apr+is%3Aclosed
* [10] http://oss-watch.ac.uk/resources/rolesinopensource
