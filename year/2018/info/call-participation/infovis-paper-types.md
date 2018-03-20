---
title: IEEE InfoVis 2018 - Topics and Paper Types
layout: main-2018
permalink: /year/2018/info/call-participation/infovis-paper-types
---

The **IEEE Information Visualization (InfoVis)** conference solicits original research papers on a diverse set of topics related to information visualization.  Broadly defined, information visualization covers human visual data exploration, analysis, and communication within displays that flexibly encode data in perceptually effective ways.

We encourage papers from novel research areas that pertain to information visualization. Papers may contribute new or improved visual encoding or interaction techniques, evaluations of InfoVis techniques and tools, models or theories related to InfoVis, systems that support visual data analysis, or applications of information visualization to domain-specific problems. This list is not prescriptive; in fact, many successful papers combine two contribution types, and some of the very best papers often combine several.

The submission guidelines can be found here: http://ieeevis.org/year/2018/info/call-participation/paper-submission-guidelines


## Topics

Research contributions are welcomed across a range of topics including, but not limited to:

*Information visualization techniques for*

* causality and uncertainty data
* collaboration support (both co-located and distributed)
* combinations of abstract and spatial data
* graphs (networks), trees (hierarchies), and other relational data
* heterogeneous data
* high-dimensional data and dimensionality reduction
* multivariate data
* non-expert audiences
* non-numeric data (categorical data, nominal data, etc.)
* personal or social data (health, energy, finance, fitness, email, etc.)
* spatial data, particularly visualized with a new spatial mapping
* streaming or time-varying data
* text and documents (e.g. using Natural Language Processing techniques)
* time-series & temporal event data
* machine-learning approaches
* very large datasets

*Interaction techniques for visualizations or for supporting the data analysis process, including* 

* recordkeeping and sensemaking
* storytelling
* integration of visualization with other software tools
* post-WIMP interactions (pen, touch, speech, gestures, mixed reality, etc.)
* focus + context and overview + detail methods
* zooming, navigation, and distortion techniques
* brushing and linking
* coordinated multiple views
* data labeling, editing, and annotation
* visual data mining and visual knowledge discovery 


*Integration of visualizations into the context of use, including*

* minimal attention contexts (e.g. ambient displays, second screens)
* mobile and ubiquitous applications
* public environments
* situated visualization (e.g. augmented reality)


*Information visualization fundamentals and methodologies:*

* cognition and perception  
* visual design and aesthetics
* novel algorithms, mathematics, machine learning or optimisation techniques that solve problems related to abstract data visualization
* taxonomies and models
* research methodology, discussions, and frameworks


*Evaluation:*

* task and requirements analysis
* metrics and benchmarks
* qualitative and quantitative evaluation
* laboratory and field studies
* novel evaluation methods
* usability studies and focus groups
* case studies (involving real users)
* replications of past studies that validate or contradict key findings


*Applied information visualization:*

* reports of information visualization in domains where it has impact
* using information visualization for education and teaching
* design studies
* visualization toolkit design

Please note that topics primarily involving encodings where the spatial layout is given by the dataset (such as scalar, vector and tensor fields) might be a better match for the "[IEEE SciVis Conference at IEEE VIS](http://staging.ieeevis.org/year/2018/info/call-participation/scivis-paper-types)". Similarly, topics that clearly focus on visual analytics, e.g., an integration of data analysis algorithms and visual interfaces to support analysis, might be a better match for the IEEE VAST Conference, also at IEEE VIS. The papers co-chairs reserve the right to move papers between these three conferences based on topic and perceived fit.

## Paper Types

VIS papers often fall into one or many of five main categories: technique, system, design study, evaluation, or model. We briefly discuss these categories below. Although your main paper type has to be specified during the paper submission process, papers can include elements of more than one of these categories; in fact, successful papers sometimes combine elements from several paper types. Please see
"[Process and Pitfalls in Writing Information Visualization Research
Papers](https://www.cs.ubc.ca/labs/imager/tr/2008/pitfalls/)" by Tamara Munzner for more detailed discussion on how to write a successful VIS paper.

The paper types below include several example papers demonstrating each respective paper type. All of these example papers are selected from Best Papers or Honorable Mentions at past InfoVis conferences.

### Paper Type: Technique 

Technique papers introduce novel techniques or algorithms that have not previously appeared in the literature, or that significantly extend known techniques or algorithms, for example by scaling to datasets of much larger size than before or by generalizing a technique to a larger class of uses. The technique or algorithm description provided in the paper should be complete enough that a competent graduate student in visualization could implement the work, and the authors should create a prototype implementation of the methods. Relevant previous work must be referenced, and the advantage of the new methods over it should be clearly demonstrated. There should be a discussion of the tasks and datasets for which this new method is appropriate, as well as its limitations. Evaluation is likely to strengthen technique papers.

Examples:

* Steve Kieffer, Tim Dwyer, Kim Marriott, Michael Wybrow. HOLA: Human-like Orthogonal Network Layout. IEEE *Transactions on Visualization & Computer Graphics*, 22(1):349-358, 2016. ([DOI](http://ieeexplore.ieee.org/abstract/document/7192690/))
* Ali K. Al-Awami, Johanna Beyer, Hendrik Strobelt, Narayanan Kasthuri, Jeff W. Lichtman, Hanspeter Pfister, Markus Hadwiger. NeuroLines: A Subway Map Metaphor for Visualizing Nanoscale Neuronal Connectivity. IEEE *Transactions on Visualization & Computer Graphics*, 20(12):2369-2378, 2014. ([DOI](http://ieeexplore.ieee.org/abstract/document/6875935/))
* Samuel Gratzl, Nils Gehlenborg, Alexander Lex, Hanspeter Pfister, Marc Streit. Domino: Extracting, Comparing, and Manipulating Subsets across Multiple Tabular Datasets. IEEE *Transactions on Visualization & Computer Graphics*, 20(12):2023-2032, 2014. ([DOI](http://ieeexplore.ieee.org/document/6875920/))
* Michael J. McGuffin, Igor Jurisica. Interaction Techniques for Selecting and Manipulating Subgraphs in Network Visualizations. IEEE *Transactions on Visualization & Computer Graphics*, 15(6):937-944, 2009. ([DOI](http://ieeexplore.ieee.org/abstract/document/5290697/))

### Paper Type: System

System papers present a blend of algorithms, technical requirements, user requirements, and design that solves a major problem. The system that is described is both novel and important, and has been implemented. The rationale for significant design decisions is provided, design alternatives and final design choices are discussed, and the system is compared to documented, best-of-breed systems already in use. The comparison includes specific discussion of how the described system differs from and is, in some significant respects, superior to those systems. For example, the described system may offer substantial advancements in the performance or usability of visualization systems, or novel capabilities. Every effort should be made to eliminate external factors (such as advances in processor performance, memory sizes or operating system features) that would affect this comparison. For further suggestions, please review “How (and How Not) to Write a Good Systems Paper” by Roy Levin and David Redell, and “Empirical Methods in CS and AI” by Toby Walsh.

Examples:

* Arvind Satyanarayan, Dominik Moritz, Kanit Wongsuphasawat, Jeffrey Heer. Vega-Lite: A Grammar of Interactive Graphics. IEEE *Transactions on Visualization & Computer Graphics*, 23(1):341-350, 2017. ([DOI](http://ieeexplore.ieee.org/document/7539624/))
* Lauro Lins, James T. Klosowski, Carlos Scheidegger. Nanocubes for Real-Time Exploration of Spatiotemporal Datasets. IEEE *Transactions on Visualization & Computer Graphics*, 19(12):2456-2465, 2013. ([DOI](http://ieeexplore.ieee.org/document/6634137/))

### Paper Type: Application/Design Study 

Application/Design Study papers explore the choices made when applying visualization and visual analytics techniques in an application area, for example relating the visual encodings and interaction techniques to the requirements of the target task. In addition, Application/Design Study papers have been the norm when researchers describe the use of visualization techniques to glean insights from problems in engineering and science. Although a significant amount of application domain background information can be useful to provide a framing context in which to discuss the specifics of the target task, the primary focus of the case study must be on the use of visualization in this domain. The results of the Application/Design Study, including insights generated in the application domain, should be clearly conveyed. Describing new techniques and algorithms developed to solve the target problem will strengthen a Design Study paper, but the requirements for novelty are less stringent than in a Technique paper. Where necessary, the identification of the underlying parametric space and its efficient search must be aptly described. The work will be judged by the design lessons learned or insights gleaned for visualization research, on which future contributors can build. We invite submissions on any application area.

Examples:

* Cydney B. Nielsen, Shaun D. Jackman, Inanc Birol, Steven J. M. Jones. ABySS-Explorer: Visualizing Genome Sequence
  Assemblies. IEEE *Transactions on Visualization & Computer Graphics*, 15(6):881-888, 2009. ([DOI](http://ieeexplore.ieee.org/document/5290690/))
* Miriah Meyer, Tamara Munzner, and Hanspeter Pfister. MizBee: A Multiscale Synteny Browser. IEEE *Transactions on Visualization & Computer Graphics*, 15(6):897-904, 2009. ([DOI](http://ieeexplore.ieee.org/document/5290692/))
* Zhicheng Liu, John Stasko, Timothy Sullivan. SellTrend: Inter-Attribute Visual Analysis of Temporal Transaction Data. IEEE *Transactions on Visualization & Computer Graphics*, 15(6):1025-1032, 2009. ([DOI](http://ieeexplore.ieee.org/abstract/document/5290708/))

### Paper Type: Evaluation

Evaluation papers explore the usage of visualization and visual analytics by human users, and typically present an empirical study, either qualitative or quantitative,  of visualization techniques or systems. Authors are not necessarily expected to implement the systems used in these studies themselves; the research contribution will be judged on the validity and importance of the results as opposed to the novelty of the systems or techniques under study. The conference committee appreciates the difficulty and importance of designing and performing rigorous evaluation, including where appropriate, the definition of hypotheses, tasks, data sets, the rigorous collection and examination/analysis/coding of data, the  selection of subjects and cases, as well as  validation, discussion and conclusions. The goal of evaluation papers is often to better understand data analysis by analyzing how humans use or perceive particular visual representations within specific analysis environments.

Carpendale (2008) provides excellent advice to guide research in InfoVis evaluation:

* Empirical methodology must be chosen sensitively as a good fit to
  the research question, the situation and the research goals.
* Studies must be conducted with appropriate rigor as dictated by the
  selected methodology. Trying to fit the rigor from one methodology
  onto another is rarely appropriate.
* Sufficient details should be published so that the reader can fully
  understand the processes and reproduce processes and results if
  appropriate. We welcome supplementary materials that address this
  need.
* Claims that are made should be appropriate to the strengths of the
  chosen methodology and evaluation design. For example, if a given
  methodology or research data set does not generalize well, then
  generalizations should not be drawn from the results.

Examples:

* Evanthia Dimara, Anastasia Bezerianos, Pierre Dragicevic. The
  Attraction Effect in Information Visualization. IEEE *Transactions on Visualization & Computer Graphics*, 23(1):471-480, 2017. ([DOI](http://ieeexplore.ieee.org/document/7539348/))
* Yalong Yang, Tim Dwyer, Sarah Goodwin, Kim Marriott. Many-to-Many
  Geographically-Embedded Flow Visualisation: An Evaluation. IEEE
  *Transactions on Visualization & Computer Graphics*, 23(1):411-420, 2017. ([DOI](http://ieeexplore.ieee.org/document/7539669/))
* Roger Beecham, Jason Dykes, Wouter Meulemans, Aidan Slingsby,
  Cagatay Turkay, Jo Wood. Map LineUps: effects of spatial structure
  on graphical inference. IEEE *Transactions on Visualization & Computer Graphics*, 23(1):391-400, 2017. ([DOI](http://ieeexplore.ieee.org/document/7539286/))
* Matthew Kay, Jeffrey Heer. Beyond Weber’s Law: A Second Look at
  Ranking Visualizations of Correlation. IEEE *Transactions on Visualization & Computer Graphics*, 22(1):469-478, 2016. ([DOI](http://ieeexplore.ieee.org/document/7192661/))

### Paper Type: Theory/Model

Theory/Model papers present new interpretations of the foundational theory of visualization and visual analytics, including models, typologies or taxonomies of the design, development, or use of visualization in particular contexts. Implementations are usually not relevant for papers in this category. Papers should focus on basic advancement in our understanding of how visualization techniques complement and exploit properties of human vision and cognition.

Examples:

* Gordon Kindlmann, Carlos Scheidegger. An Algebraic Process for
  Visualization Design. IEEE *Transactions on Visualization & Computer Graphics*, 20(12):2181-2190, 2014. ([DOI](http://ieeexplore.ieee.org/abstract/document/6875930/))
* Michael Sedlmair, Miriah Meyer, Tamara Munzner. Design Study
  Methodology: Reflections from the Trenches and the Stacks. IEEE
  *Transactions on Visualization & Computer Graphics*, 18(12):2431-2440, 2012. ([DOI](http://ieeexplore.ieee.org/document/6327248/))
* Jarke J. van Wijk. The value of visualization. In Proceedings of the
  IEEE Conference on Visualization, pp. 79-86, 2005. ([DOI](http://ieeexplore.ieee.org/document/1532781/))

### Papers Co-Chairs

* Tim Dwyer, *Monash University, Australia*
* Steven Franconeri, *Northwestern University, USA*
* Petra Isenberg, *Inria, France*


Email: [infovis_papers@ieeevis.org](mailto:infovis_papers@ieeevis.org).
