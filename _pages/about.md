---
permalink: /
title: "General Information"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I studied at the [University of Rome Tor Vergata](https://ing.uniroma2.it/), in the Faculty of Computer
Engineering, with a specialization in *"Software and Web."* 

During my academic journey, I gained solid expertise in operating systems and machine language, with a particular focus on *x86
assembly*.

I had the opportunity to collaborate as a visitor at the [National Research Council (C.N.R.)](https://www.cnr.it/), where I
developed skills in using [LabVIEW](https://www.ni.com/en/shop/labview.html) to create programs for data acquisition and analysis, process control, report generation, and software design in industrial settings for a solar simulator.


I worked at [AlmavivA](https://www.almaviva.it/it_IT) as a database administrator and web application developer in
C#, integrating Microsoft 365 and SharePoint. 
Specifically, I managed projects for the [Italian Ministry of Defense]([Italian Ministry of Defense](https://www.difesa.it/)), focusing on the implementation of digital signature systems.

I am deeply passionate about distributed programming on servers, particularly in Linux
environments. 
I use [Apache Tomcat](https://tomcat.apache.org/) to configure LAMP (Linux, Apache, MySQL, PHP) stacks on
Raspberry Pi, creating local mini servers for experimental projects.

Among my personal projects currently in development is [RouteX](https://github.com/SimoneRemoli/RouteX_Shortest_Path.git), a Java-based application
designed to help citizens of large metropolitan areas use subway networks eﬃciently and
intuitively.

My passion for programming began at the age of 15 when I started studying C++ while attending
a technical IT institute. Over time, I developed a particular interest in algorithm design, combining
computer science with combinatorial elements such as [graphs](https://en.wikipedia.org/wiki/Graph_(topology)) to solve complex problems and
optimize solutions. Click [here](https://github.com/SimoneRemoli/Dijkstra-s-algorithm_New/blob/main/Dijkstra_How_to_Implement.pdf) for the explanation of recursive Dijkstra's algorithm on graphs in Italian.

Theoretical Computer Science
======
One of the fields I am most passionate about is *theoretical computer science*. I deeply enjoy studying the [complexity of algorithms](https://en.wikipedia.org/wiki/Computational_complexity_theory) and exploring the distinction between polynomial and non-polynomial solutions, considering that problems in the NP class can be solved by a nondeterministic Turing machine in polynomial time.
![P_np_np-complete_np-hard svg](https://github.com/user-attachments/assets/15705430-cd52-429c-96c1-0c32b192c906)



Passion for Graph Theory in Computer Science
======
[Graph theory](https://en.wikipedia.org/wiki/Graph_theory) represents one of the most fascinating areas of computer science for me, where logic, mathematics, and creativity converge to solve complex problems. I am particularly interested in studying graph structures, which find applications in numerous fields, from optimizing paths to designing computer networks.

I enjoy analyzing algorithms such as [Dijkstra](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm), [Prim](https://en.wikipedia.org/wiki/Prim%27s_algorithm), and [Kruskal](https://en.wikipedia.org/wiki/Kruskal%27s_algorithm) to uncover the most efficient ways to navigate graphs, whether they represent transportation networks, social connections, or technological infrastructures. 
![Petersen_double_cover svg](https://github.com/user-attachments/assets/84ec2b52-26a4-4293-8967-595e83b49173)

I love exploring the mysteries and applications of graph theory, from the magic of [**degrees of separation**](https://en.wikipedia.org/wiki/Six_degrees_of_separation) and the [**Small World Theory**](https://en.wikipedia.org/wiki/Small-world_experiment), which reveal hidden connections in apparent chaos, to the logical challenges of the [**Three Utilities Problem**](https://en.wikipedia.org/wiki/Three_utilities_problem). I’m fascinated by concepts like [**Maximum Flow and Minimum Cut**](https://en.wikipedia.org/wiki/Maximum_flow_problem), which optimize networks and resources, and the [**Dominating Set**](https://en.wikipedia.org/wiki/Dominating_set), which captures efficiency in controlling graphs. Finally, the enigma of the [**Cycle Double Cover**](https://en.wikipedia.org/wiki/Cycle_double_cover), a conjecture that embodies the beauty of unanswered questions, deeply inspires me. For me, graph theory is an endless journey through logic, creativity, and real-world applications.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
