---
layout: page
title: Resume
permalink: /resume/
---

<a href="{{ site.url }}/assets/CodyJGilbertResume.pdf" style="color:white" class="myButton">PDF Version</a>

This page contains an extended version of my resume to provide additional information. Click one of the links below to learn more.

* [Education](#education)
	* [Graduate](#graduate)
	* [Undergraduate](#undergraduate)
* [Programming Languages](#programming_languages)
* [Work Experience](#work_experience)
* [Selected Projects](#projects)

### [Education]({{ site.url }}/resume/education/) (click for details) <a name="education"></a>

#### Graduate <a name="graduate"></a>

* **Degree:** Master of Science - Computer Science
* **Dates:** May 2018 to May 2020
* **School:** [New York University, Courant Institute of Mathematical Sciences]( https://cs.nyu.edu/home/index.html )
* **Location:** New York, New York
* **GPA:** 3.8/4.0
* **Relevant Coursework:** Algorithms, Programming Languages, Operating Systems, Probability Theory, Database Systems, Artificial Intelligence, Big Data Application Development, Big Data Analytics, Statistical Natural Language Processing, Predictive Analytics, Blockchain & its Applications, High-Performance Machine Learning

#### Undergraduate <a name="undergraduate"></a>

* **Degree:** Bachelor of Science - Nuclear Engineering
* **School:** [North Carolina State University, College of Engineering]( https://www.ncsu.edu/ )
* **Location:** Raleigh, North Carolina
* **GPA:** 4.0/4.0
* **Honors and Activities:** Valedictorian, Summa Cum Laude, Senior Design Team Leader, Dean's List (x6), [University Scholars Program]( https://scholars.dasa.ncsu.edu/ ), [American Nuclear Society Student Member]( http://www.ans.org/ )
* **Scholarships:** [American Nuclear Society Robert G. Lacy Scholarship]( http://www.ans.org/honors/scholarships/programs/ ), [CASL Undergraduate Scholar]( https://www.casl.gov/ ), [American Nuclear Society Operations and Power Division Scholarship]( http://www.ans.org/honors/scholarships/programs/ ), [American Nuclear Society National Sophomore Scholarship]( http://www.ans.org/honors/scholarships/programs/ ), [Nuclear Engineering University Program Scholarship]( https://neup.inl.gov/SitePages/Home.aspx ), [Rotary Scholarship]( https://www.rotary.org/en/our-programs/scholarships ), Troop 566 Eagle Scout Scholarship
***

### [Programming Languages]({{ site.url }}/resume/prog_languages/) (click for details)  <a name="programming_languages"></a>

* Development Languages
	* Python
	* C++
	* Scala
	* OCaml
	* Fortran
	* Go
* Analysis Languages
	* Matlab
	* R
	* SQL
* Applications
	* RapidMiner
	* PostgreSQL
	* Flask
	* Dash
	* Hadoop
	* Spark
	* LaTeX
	* Framatome MICROBURN-B2 and POWERPLEX

***

### [Work Experience]({{ site.url }}/resume/work_experience/) (click for details) <a name="work_experience"></a>


#### Data Analyst Intern

* **Organization:** [Betterfin]( https://betterfin.com/ )
* **Location:** Brooklyn, NY
* **Dates:** Aug 2019 - Present
* **Description:** This internship focused on implementing APIs with Python to connect disparate data sources (external CRM databases, US Census open source APIs, internal PostgreSQL servers, etc.) to a common data lake, and to perform data analysis on the aggregated records.
These analyses focused on providing actionable information to small businesses seeking additional capital, such as:
	* Finding yearly trends Startup Early Survival Rate for a given US region using data extracted from the Kauffman Indicators of Entrepreneurship to determine what industries within that region have the highest chances of long-term success
	* Evaluating small business owner sentiment on acquiring additional funding using US Census Annual Business Survey (ABS) data
	* Finding average employee payroll and wages for a given US region and industry using U.S. Bureau of Labor Statistics data, which small business owners can use to evaluate their standing in comparison to their peers.
This position also included several development projects:
	* Creating tools to interface local Python applications to external PostgreSQL databases
	* Building interactive visual dashboards using Flask and Dash.
	* Creating a fuzzy-search method within a moderately-large database (>30 million records) using a combination of PostgreSQL trigram indexing and machine learning to estimate the match likelihood of two vectors of business identifying information

#### Research Assistant

* **Organization:** [New York University]( https://cims.nyu.edu/ )
* **Location:** New York, NY
* **Dates:** Jan 2019 - July 2019
* **Description:** I worked as a research assistant under Professor Benjamin Peherstorfer in model reduction methods. This role involved applying model reduction methods including Proper Orthogonal Decomposition (POD), Discrete Empirical Interpolation Method (DEIM), and Adaptive Discrete Empirical Interpolation Method (ADEIM) on a simulated rocket combustion model to accelerate the computation of approximate state solutions. All methods were created using Matlab.

#### Recitation Leader

* **Organization:** [New York University]( https://cims.nyu.edu/ )
* **Location:** New York, NY
* **Dates:** Jan 2019 - May 2019
* **Description:** I worked as a recitation leader for a Fluid Dynamics course during the Spring 2019 semester. This role involved working with Professor Antoine Cerfon to give weekly supplementary fluid dynamics instruction to a class of 15-20 students. Curriculum included vector calculus, thermodynamics, Euler equations and associated solutions, the Navier-Stokes equations and approximations, and other mechanical principles.

#### Nuclear Fuel Engineer (Nuclear Engineer II)

* **Organization:** [Duke Energy]( https://www.duke-energy.com/home )
* **Location:** Charlotte, NC
* **Dates:** June 2015 - Jan 2018
* **Description:** I worked as a nuclear fuel engineer for the Duke Energy utility company in supporting the operations and refueling campaigns of the Brunswick Nuclear Plant. My duties included:
	* Supporting periodic plant operations by preparing power and safety margin projections using core simulation software (Framatome MICROBURN-B2 and POWERPLEX)
	* Creating design calculations to support biannual core reload that verified core shuffle sub-criticality, control blade material integrity, and startup operation safety margins
	* Provided emergent issue support, including the creation of high-quality engineering designs under tight time constraints
	* Generated short-term and long-term power and core operation predictions using core modeling software

***

### [Selected Projects]({{ site.url }}/projects/) (click for details) <a name="projects"></a>

#### Python Tutorial Writing

* **Status:** Active
* [Python Tutorials Page]({{ site.url }}/projects/python_tutorials/)
* **Skills:** Python, Markdown, HTML, Informative Writing
* **Description:** Python, being my favorite dynamically-typed object-oriented language, has been my standard tool for analysis and development. To share the insights I've collected over the years using, I've written dozens of tutorials for both beginners and power users of the language. These tutorials have been published by the software consulting service [rwells.com]( https://wellsr.com/python ).

#### HMDA Data Exploration with Spark

* **Status:** Complete
* [Github Repository]( https://github.com/cody-joe-gilbert/SU19SparkClass )
* [Paper]( https://github.com/cody-joe-gilbert/SU19SparkClass/blob/master/presentation/paper/HMDA_Paper.pdf )
* **Skills:** Spark, Scala, Distributed Programming, Machine Learning, Team Collaboration, Big Data Applications, Big Data Analysis
* **Description:** This project seeks to find patterns of discriminatory lending using data provided by the Consumer Financial Protection Bureau (CFPB) as part of the Home Mortage Disclosure Act (HMDA). The goal of the project was to create a machine learning model from the HMDA data that would indicate differences in loan approval rate between members of a given race, ethnicity, or gender. As a school project limited over the course of a month, the final model and webapp is not perfect by any means, but the project served to learn Spark, distributed computing, creating application with big data, and machine learning with big data.

#### Finding Napa

* **Status:** Complete
* [Github Repository]( https://github.com/cody-joe-gilbert/SU19Hadoop )
* [Paper]( https://github.com/cody-joe-gilbert/SU19Hadoop/blob/master/TeamPaper.pdf )
* **Skills:** Hadoop, Hive, Distributed Programming, Team Collaboration, Big Data Applications, Big Data Analysis
* **Description:** The time-tested traditional methods of wine production have begun to be impacted with the advent of rapid climate change. This analysis seeks to quantify and predict those changes to allow grapevine and wine stakeholders to find new regions for growing grapes in a climate-altered future that best replicate the current conditions of the Napa Valley region. This analysis aggregates weather, soil, and sunlight data over a set of US geographic regions and time periods to select areas that best replicate those of Napa Valley given a trend of climate change. This project used Hadoop tools including MapReduce, Hive, and HDFS to process big data for analysis.


