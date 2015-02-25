Reproducible and Collaborative Statistical Data Science


Overview and Course Description
Statistics 157 is a project-based course that introduces you to reproducible and collaborative statistical research, applied to a real scientific question. You will gain experience acquiring, cleaning, and curating data; formulating scientific questions statistically; developing appropriate statistical methods to analyze the data to answer the scientific questions; implementing those methods in robust, testable, reusable, extensible software; applying the methods; visualizing the results; interpreting the results; and communicating the results to others. And you will learn to do this in a way that is computationally reproducible, which is increasingly recognized as key to scientific progress.


As if you were working in a scientific research group or in industry, you will be given a set of tools (a “software stack”) and practices you are required to master and use. As if you were working in a scientific research group or in industry, you will be pointed to resources to help you learn the tools, and it is your responsibility to ensure that you have mastered them, which will require a substantial amount of time outside class. And, as if you were working in a scientific research group or in industry, you will be required to collaborate and to take responsibility for your role in the collaboration. 


But the point is not merely to master the tools or to learn to collaborate effectively.  Rather, the point is to do sound computational science, and to do it in a way that others can verify the data and statistical techniques behind your analysis, can verify that your code does what it’s supposed to do, can run the code using the data and parameters you used, can verify that they get the same results you do, and can build on what you have done to advance science even further. 
Format
3 hours of class per week in two 90-minute sessions, plus two hours of labwork. Class sessions are divided between lecture and collaborative work. To a large extent, the class is “flipped,” meaning that you are responsible for watching video lectures and working through online tutorial materials—outside class—as well as collaborating with your team outside class, so that a substantial amount of class time can be devoted to group work on the project, including frequent in-class presentations by students, code reviews, brainstorming, etc. Students are expected to work at least 8 hours per week outside class, making this a 4-unit course (12 hours of effort per week).


Prerequisites
At least one upper-division course in statistics and at least one upper-division course that requires programming or data analysis.  Statistics 133 fulfills both requirements.
Grading
Undergraduate versions (Statistics and Computer Science): participation, code review, weekly quizzes, a group term project (with self- and peer-evaluation), lightning oral presentation (backed by a reproducible code/data archive), poster presentation.


Graduate versions (IEOR, INFO, IB): participation, code review, a group term project (with self- and peer-evaluation), mentoring undergraduates, lightning oral presentation (backed by a reproducible code/data archive), poster presentation, written report.


All homework will be submitted by issuing pull requests to a git repository. You are expected to make consistent contributions. Procrastination is not rewarded.
Textbook
W. McKinney, 2012. Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython, O’Reilly Press. Available as an e-book and a print book.
Syllabus


Week 1: Introduction and Course Overview. What is reproducibility? What is the difference between reproducibility, replicability, verifiability, and auditability? Why is reproducibility important to the scientific method? Why are most scientific publications not reproducible? What is the impact of that? Vignettes of reproducibility successes: WaveLab, BioConductor, Reproducibility Project.  Open publication and open science. 


Reading: 
* http://www.nature.com/nature/focus/reproducibility/
* http://www.sciencemag.org/content/343/6168/229.summary 
* G. Johnson, 2014. New Truths That Only One Can See http://www.nytimes.com/2014/01/21/science/new-truths-that-only-one-can-see.html?ref=todayspaper&_r=0
* D. Donoho, 2013: http://biostatistics.oxfordjournals.org/content/11/3/385.full 
* V. Stodden, 2013: http://bulletin.imstat.org/2013/11/resolving-irreproducibility-in-empirical-and-computational-research/ 
* Reproducibility PI manifesto: http://figshare.com/articles/Reproducibility_PI_Manifesto/104539 
* M. Eisen, 2013: http://www.michaeleisen.org/blog/?p=1346
* Setting the Default to Reproducible: Reproducibility in Computational and Experimental Mathematics, Developed collaboratively by the ICERM workshop participants, compiled and edited by the Organizers: V. Stodden, D. H. Bailey, J. Borwein, R. J. LeVeque, W. Rider, and W. Stein, February, 2013. http://faculty.washington.edu/rjl/pubs/icerm2012/index.html 
* R.J. LeVeque and I. Mitchell and V. Stodden, 2012. Reproducible Research for Scientific Computing: Tools and Strategies for Changing the Culture, Computing in Sci. and Eng. 14, 13-17. http://faculty.washington.edu/rjl/pubs/cise12/index.html 
* Millman, K.J. and F. Perez, 2014. Developing open source scientiﬁc practice. In Implementing Reproducible Research (Chapman & Hall/CRC The R Series), Stodden, Leisch, and Peng, eds.
* Reproducibility project: https://openscienceframework.org/project/EZcUj/wiki/home/  
* Button, K. S., Ioannidis, J. P. A., Mokrysz, C., Nosek, B. A., Flint, J., Robinson, E. S. J., and Munafo, M. R. (2013). Power failure: Why small sample size undermines the reliability of neuroscience. Nature Reviews Neuroscience, 14, 1-12. doi:10.1038/nrn3475


Assignment: 
* Install BCE, the Berkeley Common Environment
* Test the installation by running the test suite
* For those without prior python experience, complete the self-study with Code Academy: http://www.codecademy.com/tracks/python 


Week 2: Introduction to the scientific problem for the semester (the substantive scientific question the class will address will vary by semester) and the data sources for the project. Example topics[a][b]: recidivism in Federal prisons, earthquake prediction, effect of packstock use on the Yosemite Toad population.


Reading (these will be assigned each semester based on the chosen topic):
* Scientific articles on the topic
* Documentation for the data sources


Assignment:
* Summarize the scientific problem in your own words
* Identify at least one source of data that bears on the problem
* Find, read, and summarize a scientific article about the problem


Week 3: Pros and cons of virtual machines[c] and executable documents for computational reproducibility.Overview of the course software stack: BCE (http://collaboratool.berkeley.edu/)--virtual machines and environments, git, IPython, numpy, scipy, pandas, matplotlib, statmodels, R, mySQL, LaTeX. Collaborative tools for help[d]: GitHub issue tracker, StackOverflow, Assembla (https://www.assembla.com/home)




Reading:
* Git tutorial http://git-scm.com/docs/gittutorial 
* Python bootcamp https://github.com/profjsb/python-bootcamp
* Introduction to Python http://nbviewer.ipython.org/urls/raw.github.com/ehmatthes/intro_programming/master/notebooks/contents.ipynb
* A Crash Course in Python for Scientists http://nbviewer.ipython.org/5920182
* Scientific Computing with Python http://nbviewer.ipython.org/url/atwallab.cshl.edu/teaching/QBbootcamp3.ipynb
* Learn Pandas https://bitbucket.org/hrojas/learn-pandas
* Interesting IPython notebooks:  https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks


Assignment:
* Find, read, and summarize two more scientific articles about the problem




Week 4: Revision control systems. Why not just use Box/Dropbox/Google Drive? Distributed RCSs versus client-server RCSs. Introduction to git. Branches, directed acyclic graphs, hash functions. Getting started in git. The basic commands. Cloning, remotes, branching, pull requests.


Reading:
* Fernando Perez, lectures on reproducible science and modern scientific software https://github.com/fperez/reprosw


Assignment:
* Clone the class git repository onto your own computer
* Edit the class roster in the repository to add your name and email address
* Commit the change and submit a pull request


Week 5: Team building. Horizontal and vertical groups.  Organize class into teams consisting of (one each) of Data Curators, Analyzers, Visualizers, Presenters. Select technical leads. Discuss roles, skills, responsibilities.  Set milestones. Set up the issue tracker. Construct the “class dashboard” on GitHub to track progress within and across teams. 


Reading:
* GitHub documentation


Assignment:
* Construct a dashboard for your team


Week 6: Starting in week 6, the pattern of class will alternate weekly between producing and presenting and checking. There will be a week of science, code development, and occasional new material, followed by a week in which students make 5-minute student presentations about what their team did on Tuesday, and then a cross-team code review and check for reproducibility on Thursday. 


Tuesday--presentation about dashboard development and introduction to LaTeX. Thursday--introduction to software testing and test-driven development; effective code review.


Reading:
* nose tutorial by C. Titus Brown: http://ivory.idyll.org/articles/nose-intro.html
* Effective code review: http://stackoverflow.com/questions/310813/how-do-you-perform-code-reviews
* LaTeX tutorial: http://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf 


Assignment:
* If you used a language other than LaTeX to submit your writing assignments for weeks 1 through 6, translate those assignments to LaTeX
* Submit LaTeX source for all previous writing assignments


Week 7: Back to the science and the Statistics. Refresher on the scientific problem and the statistical issues it raises. Estimation, prediction, hypothesis testing, confidence sets, robustness, nonparametrics, abstract permutation tests, Monte Carlo, pseudo-random number generation. Framing the scientific question as a quantitative statistical question.


Reading:
* Ioannidis, 2005: http://www.plosmedicine.org/article/info:doi/10.1371/journal.pmed.0020124
* Computational companion to these issues: http://nbviewer.ipython.org/urls/raw.github.com/matthew-brett/sketch-books/mark-lab-meeting/ioannidis_2005.ipynb


Assignment:
* Identify the data source(s) for the project.
* Sketch the analysis and the steps you anticipate will be required; submit the sketch in pdf, along with LaTeX source.


Week 8: Data structures and databases. An introduction to databases using SQLite (note advantages of production systems such as mySQL, MariaDB, and PostgreSQL). Structured formats for large-scale scientific data: HDF5.  


Distribute tasks among and within groups. 


Reading. Python SQLite tutorials:
* http://www.tutorialspoint.com/sqlite/sqlite_python.htm
* http://www.pythoncentral.io/series/python-sqlite-database-tutorial/
* http://www.pythoncentral.io/introduction-to-sqlite-in-python/


Assignment:
* Acquire the data for the term project, begin data cleaning. 
* Sketch the statistical analysis planned to solve the scientific problem; identify potential conceptual, scientific, statistical, and computational bottlenecks
* Begin building the software to analyze the data.




Week 9: Tuesday--present progress. Introduction to Hadoop and MapReduce. Thursday--code review and reproducibility review.


Reading:
* Introduction to Hadoop [ADD LINK]
* Introduction to MapReduce [ADD LINK]


Assignment:
* Complete data cleaning.
* Continue developing the statistical approach and the software to analyze the data.


Week 10: Discussion of bottlenecks. Refine scientific and statistical vision. Outline analysis strategy. Mini-lectures on statistical and computational tools needed to complete the project.


Assignment:
* Submit outline of the reports and presentations.
* Write the data cleaning section of the report (in LaTeX).




Week 11:Tuesday--present progress. Thursday--code review and reproducibility review.


Assignment:
* Clean, transform, and archive the data
* Write the first pass of the description of the planned statistical analysis
* Write the first pass of the data analysis software


Week 12: Tips on giving good talks and posters; examples of bad talks and posters.


Reading:
* http://www.ted.com/playlists/130/the_dark_side_of_data.html


Assignment: 
* Write three sentences summarizing each of the 11 TED talks on the playlist
* Finalize the analysis and the description/documentation of the analysis
* Write the first pass of the interpretation of the results
* Write the first pass of the presentation of the results, including any graphics or interactive elements


Week 13: Tuesday--present progress. Thursday--code review and reproducibility review.


Reading:
* None


Assignment:
* Refine and finalize the interpretation
* Refine and finalize the presentation


Week 14: Tuesday--Lightning talks in class. Each group makes a 5-minute oral presentation. Thursday--feedback on the talks.


Week 15: Tuesday--polish poster presentations. Thursday-- 3-hour session of public poster presentations[e][f][g].












Last modified 4 February 2015 by PB Stark
[a]You might want to ping Victoria S. for ideas on this, I know she's been teaching at Columbia on this topic and may have other good examples.
[b]Definitely. Brian Nosek might also be able to provide some data/code for the papers his reproducibility project is replicating
[c]check out this coolness:https://olivearchive.org/origins/
[d]see also Assembla for code dev management https://www.assembla.com/home
[e]a general comment - any interest in touching on scalable algorithm implementation at some point, possibly after the Week 8: Data structures and databases module? I'm thinking hadoop and mapreduce
[f]definitely worth doing; just a question of the finiteness of time, and priorities.  I'll put it in week 9.
[g]Any links to tutorials, etc., you have handy?
