This document is written as an assignment for the course Open Source (IS-213) at the University of Agder. The purpose of the document is to answer the question as to *Why people contribute to open source projects.*

**Abstract**  
In this document we will first outline how most open source projects are structured, and how their communities work. Then we will look at how an individual can be integrated into one of these communities. Last but not least we will look at why people would want to be integrated into such a community.

**Introduction**  
"What motivates an individual to devote their efforts to the development of free software?" is a question i often see arund the WWW. It is puzzling to see a proffessional developer spend their free time doing "work" without monetary compensation. Understanding the motivation that lies behind these individuals is a key step to understanding how the F/OSS model has managed to succeed.


**What is motivation**
The topic of human motivation is divided into two types those that are intrinsic (activity valued for its own sake) and extrinsic (indirectly being rewarded for doing the task at hand) [16].

**Intrinsic Motivation**
Quoting Ryan and Deci in [16] *"Intrinsic motivation is defined as the doing of an activity for its inherent satisfactions rather than for some separable consequence. When intrinsically motivated, a person is moved to act for the fun or challenge entailed rather than because of external prods, pressures, or rewards".* A central part of intrinsic motivation is the human need for competence and self-determination. Intrinsic motivation is usually divided into two categories: enjoyment-based and obligation/community-based.

**Enjoyment based intrinsic motivation**
Enjoying an activity is the core concept of intrinsic motivation [16]. Mihali Csikszentmihalyi in his book "flow" emphasized that certain activities were pursued for the sake of the enjoyment derived from carrying them out. He suggested a state called "flow" where enjoyment was maximized, characterized by intese focus and concentration. 

**Extrinsic Motivation**


**Motivation in an open source context**
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

And this is important, as a project that does not appear invitational will be less motivating towards a possible project. And a project is depedant on its users. *"First, the success of a project appears to be highly correlated with its size: projects that fail to attract and, more importantly, to retain new contributors rarely get beyond a name and a few lines of code stored on Sourceforge".* [1] this quote very well explains the issue at hand.

This is a major problem for open source projects. Several empirical studies have found that, in a large majority of cases, a single small group is often responsible for a large portion of the accomplished work. On the contrary, a very large group of participants are responsible for the remaining work [3]. The success of a project also seems to be highly correlated to its own size. Projects that fail to attract and retain net contributors very rarely grow larger than a name and some lines of code [1]. As you can imagine this would be detrimental to a project. If the project cannot attract users it will not survive, and if it does not market itself it will not gain participants.

**Why people participate**    
So what makes the individual want to participate to a project aside from the marketing? According to Eric Raymond [11] there are three main categories for motvation in open source projects: Social, Cultural, Economical [14]. These  categories each present different reasons within them as to where people get their motivation from.

**Cultural**    
In the cultural aspect it is said that people get their motivation from the importance of their work [14]. The open source community governs several important projects around the web. For instance the Apache foundation, which governs ex. The apache web server [12]. The apache web server is, according to statistics from w3techs, the most used web server in the world with a 46,4% market share [13] as can be seen in Figure 3 below.

![Apache web server](https://i.imgur.com/CRawaBt.png)   
*Figure 3*

Because of this it is apparent that Apache has an important place in the internet of today. If key members were to leave the project because of their lost motivation the project would eventually falter. This makes the influx of new members essential for the long-term survival of an open source project. Many people are motivated by this fact that they are contributing to something valuable and worthy of protection [14].


**Social**    
In the modern societies of today we live in an *exchange economy*. This means that social status is determined by having control over things to use for trade [1]. For us this is completely normal, and our goods are usually in the form of money. There is however also a form of society named *the gift culture* [1]. In the gift culture your social status is not determinet by what you have to trade, but by what you have to give away [1]. This ties into the software developer community very well, as the resources like computing power, bandwith and disk space are in abundance, whiole software is a more scarce and valuable resource [14]. Because of this a software developer might have his motivation come from the fact that his social status increases, seeing as he has the ability to give away his time in the form of free software.


**Economical**    
Some programmers will choose to look at open source projects from an economical perspective. If they feel that the benefit from contributing will be greater than the cost of participating, they might protive their time and expertise [14]. The primary cost of participating come at the expensve of expected income from working on something else [14]. The rewards considering the economical approach need not nescessarily be directly connected to money. According to Lerner and Tirole [15] the benefits fall in the categories of immediate and delayed. The immediate benefits come from the increase of personal satisfaction. The delayed benefits involve recognition as well as rewards from employers, either current or future, in the form of higher wages, more attractive jobs, stock options, etc [14].


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
* [11] https://en.wikipedia.org/wiki/Eric_S._Raymond
* [12] https://www.apache.org/
* [13] https://w3techs.com/technologies/overview/web_server/all
* [14] https://pdfs.semanticscholar.org/953d/9faa84cca23a9f3bc07d23eaba83acdb25fa.pdf
* [15] http://www.nber.org/papers/w7600.pdf
* [16] https://papers.ssrn.com/sol3/papers.cfm?abstract_id=443040
