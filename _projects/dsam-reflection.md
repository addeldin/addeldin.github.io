---
layout: page
title: DSAM Capstone Reflection
description: reflective writing on my work across the core courses in the Digital Studies & Methods certificate at the University of Pittsburgh
img:
importance: 1
category: coursework
---

## Introduction
The theme across my projects done for the core courses in the Digital Studies & Methods certificate is examining digital pedagogy and my relationship to it. For each one, I focused on a different element of pedagogy:

1. For the DSAM Seminar in 2020, I read the assigned content of various digital studies syllabi to understand the kinds of content assigned.
2. For the DSAM Practicum in 2021, I built an asynchronous educational resource for understanding the historical role of the ENIAC in the history of computing.
3. For the DSAM Capstone in 2023, where my initial goals and the final product most closely aligned, I designed open educational resources hosted on GitHub and linked to from a personal website that acts as an academic portfolio.

Interestingly to me, I used a variety of digital tools and programming/markup langauges for the projects (e.g. Palladio, Python, Excel, HTML, CSS, Markdown, Twine, Anaconda, and Jekyll themes for GitHub Pages), but in each case the tools used proved secondary to the goals of the project—and, in some cases, unnecessary or outright counterproductive. In part, this arose from just trying to get something done that fit the course expectations, but rather than being a sequence of abandoned projects, I think that each contributed to an ongoing conversation with myself mediated by the projects, my classmates, and the course instructors. The conversation had a central premise that eluded me until stated concisely by Prof. Alison Langmead at the end of the Capstone project: what kind of teacher do I want to be?

The following sections will provide an abridged walk through the coursework that led to my awareness of that underlying conversation, and the best answer to that question that I can provide here in the first half of 2023.

## DSAM Seminar
In the seminar, I worked with a set of syllabi that fell under the loose categorization of `digital studies`, which is phrase I use to basically mean lowercase `digital humanities` while trying to avoid the stale baggage the phrase carries. The 35 syllabi all came from the [Humanities Commons CORE Repository](https://hcommons.org/core/) and included 16 universities, even more professors professors, and a mix of departments, but all focused on digital culture, studies, or history.

I knew I wanted to do something with these syllabi, but my approach in hindsight was more utilitarian than purposeful and effective. Basically, I knew that I wanted to see how content that was more about learning how to use tools, software, or methods (what I'll refer to as `technical learning`) or the history of digital technology was represented in the syllabi's assigned materials. I looked to digital methods I'd learned up to that point, and felt that network analysis would be the best way to interrelate the metadata *about* the syllabi and the assigned content *within* them.

The choice of tool wasn't per se wrong, but the focus on tools misguided me from the start. To help make this point, I'm going to compare the thesis I started with, and the conclusion I drew at the end of term.

First, the thesis:
>Syllabi, as structuring documents for a course, can indicate how humanities courses oriented around digital humanities, culture, or history are or are not engaging with computer history through the pieces they cite. My preliminary hypothesis is in particular that these syllabi do not include much from computer/digital histories, particularly anything technical/methodological, and that as a result, the understanding of what computers are/can be is being limited by a sense that technical understanding and historical understanding could limit or frustrate students rather than empower them in their humanistic inquiry.

There's a pretty strong argument present in the preliminary hypothesis, and that points away from the means by which I'd test the hypothesis (a pretty informal use of network analysis), and toward what my actual interest was. I wanted to see if the syllabi had the kind of assigned content I was interested in seeing more of. The best way to do that wasn't any of the tools I was looking at.

Here's the conclusion:

>Where I’m at right now is that I have a sense of what is there and what isn’t, but not necessarily how contingent factors of the syllabus and its author might be relevant. I think that technical/methodological pieces and texts outside of recent academia are being generally overlooked, but I do not have evidence from the networks or timelines themselves of this, which is the next step. That all said, I think that the most interesting part to me is where this will leave me off. That is, when I said in my thesis above that I want to see how I fit into all this, that’s going to be a reflection rather than something the tools tell me. I want to see what’s there, and if my suspicion is correct, because then I can learn what might be included in citations that I didn’t think of or consider, and what I know from my own studies, thus turning this exploratory project into context from which I think critically about my own pedagogical practices and future syllabi.

That is, the best method for what I wanted was close reading, which the spreadsheets (or more specifically, the process by which I converted the syllabi into spreadsheets) facilitated. The data-making process was what actually helped; the network analysis was a way to make it feel more relevant to the goals of the course. It's worth noting, though, that the spreadsheet creation process was itself a use of digital tools to help do interpretive work. The choice to represent over 700 readings in a spreadsheet meant having to systematically read the syllabi's content, which enabled the interpretive understanding I needed through giving me a way to work with each syllabus via a consistent method.

In addition, feedback from others  helped guide me toward some underlying questions and premises that would make that interpretive work more focused. Early on, I received feedback from Jane and Alysha about what factors might influence a syllabus's contents, e.g. the academic title of the professor, and further, to what extent syllabi consistently reflect the content of a course. I ended up with three questions that guided the rest of the work to come:

1. What do I think syllabi are "about"/what do they represent about the class based on my own experience making them?
2. How do I make my categories capture things that influence syllabi like teacher position, department, and field of the course?
3. What can syllabi tell me about the presence of computer history and technical learning in digitally-oriented humanities courses?

And that's the story of my long journey to not make effective use of Palladio. The real lesson was the spreadsheets made along the way.
 
## DSAM Practicum
In Practicum, at least as much as I can remember reading through years-old notes, I had a bit more self-awareness. I knew what I wanted to do: research the ENIAC further. I did not know how it worked at a fundamental level, and its role in early computer history seemed like a useful starting point for building out my more general understanding of that history and how it relates to computers and our understanding of them in the present. The readings I ended up utilizing at the end of the term are available in Appendix A.

I decided to design an asynchronous lesson plan around the ENIAC so that I could work in [Twine](https://twinery.org/), designing interactivity into the lesson plan directly rather than indicating points of interactivity in a more standard presentated lesson plan. But the route I took at building out the lesson plan was prone to sudden shifts rather than a clear, well, plan. After determining the six key sections (`The ENIAC, Today`, `The ENIAC, Then`, `Functions`, `Tables & Computation`, `Programming the ENIAC`, and `Simulating the ENIAC`), I started by building out a skeleton of the structure and got lost in a forest of menu- and ease-of-use-focused design. A functioning, hyperlink table of contents; a stable return function from the works referenced that could be clicked to from many different pages; and convenient design for clicking to and returning from diversions without losing on-page progress all took up more time than designing the actual lesson, which led to a pivot.

From there, I focused on getting a basic text write up with minimal interactivity in the form of reflective questions for the early, more text-heavy sections, then moved to the middle sections focused on the mathematics behind the ENIAC. Here, I got lost in explaining the math at a level that seemed reasonably understandable for an audience that might not have taken math since high school, and maybe even taken those courses to meet curricular requirements. I leaned on my previous experience designing digital math lessons for high school students, which was a nice change of pace from the headier academic work, but proved to be another potential time sink at the expense of some kind of full, rough draft of the lesson plan.

I'm talking about this lesson plan and not linking to it because I did not get a full draft completed. Revisiting it two years later, I do have some desire to rework and finish it, but I don't think it's worth releasing even for an example in its current state. That said, the focus on lesson planning was useful in its own right, as it led into the Capstone project despite the time gap. And, well, the research I did at that time led me to more useful subjects and readings than I could've imagined at the time. Those subjects, and the subjects I generally interacted with over the Seminar and Practicum, are the subject of the next section.

## Relevant Fields

## DSAM Capstone

## Conclusion

## Appendix
### A: Works Cited in Practicum Project
* Bullynck, Maarten and Liesbeth De Mol. "Setting-up Early Computer Programs: D. H. Lehmer’s ENIAC Computation." *Archive for Mathematical Logic*, vol. 49, no. 2, 2010, pp. 123-146, Academic Search Premier, doi:10.1007/s00153-009-0169-8.
* De Mol, Liesbeth. "‘A pretence of What Is Not’? A study of Simulation(S) from the ENIAC Perspective." *NTM Zeitschrift für Geschichte der Wissenschaften, Technik und Medizin*, vol. 27, no. 4, 2019, pp. 443-478, doi:10.1007/s00048-019-00226-7.
* De Mol, Liesbeth and Giuseppe Primiero. "When Logic Meets Engineering: Introduction to Logical Issues in the History and Philosophy of Computer Science." *History and Philosophy of Logic*, vol. 36, no. 3, 2015, pp. 195-204, doi:10.1080/01445340.2015.1084183.
* "ENIAC computer, programmers." Penn Archives Digital Image Collection, Digital Image Number UARC20011120004, 1946, http://dla.library.upenn.edu/dla/archives/detail.html?id=ARCHIVES_20011120004.
* Goldstine, A. "Part I: Technical Description of the ENIAC." *Report on the ENIAC*, edited by Moore School of Electrical Engineering, Moore School of Electrical Engineering, 1946.
* Goldstine, H. H. and A. Goldstine. "The Electronic Numerical Integrator and Computer (ENIAC)." *IEEE Annals of the History of Computing*, vol. 18, no. 1, 1996, pp. 10-16, doi:10.1109/85.476557.
* Greengard, Samuel. “ENIAC Turns 75.” *Communications of the ACM*, ACM, 11 Feb. 2021, cacm.acm.org/news/250485-eniac-turns-75/fulltext.
* Haigh, Thomas. "Introducing the Early Digital." *Exploring the Early Digital*, edited by Thomas Haigh, Springer International Publishing, 2019, pp. 1-18. https://doi.org/10.1007/978-3-030-02152-8_1.
* Kline, Ronald R. "Inventing an Analog Past and a Digital Future in Computing." *Exploring the Early Digital*, edited by Thomas Haigh, Springer International Publishing, 2019, pp. 19-39. https://doi.org/10.1007/978-3-030-02152-8_2.
* Polachek, H. "Before the Eniac [Weapons Firing Table Calculations]." *IEEE Annals of the History of Computing*, vol. 19, no. 2, 1997, pp. 25-30, doi:10.1109/85.586069.
* Priestley, Mark and Thomas Haigh. "The Media of Programming." *Exploring the Early Digital*, edited by Thomas Haigh, Springer International Publishing, 2019, pp. 135-158. https://doi.org/10.1007/978-3-030-02152-8_8.
* Stuart, B. L. "Simulating the Eniac [Scanning Our Past]." *Proceedings of the IEEE*, vol. 106, no. 4, 2018, pp. 761-772, doi:10.1109/JPROC.2018.2813678.
* Zoppke, Till. *Simulating the ENIAC as a Java Applet*. 2004. Free University of Berlin, Diploma thesis. ENIAC simulation, http://kinnla.github.io/eniac/doc/eniac_simulation_thesis.pdf