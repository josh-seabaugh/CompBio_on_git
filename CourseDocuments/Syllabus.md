# Syllabus and Course Policies for EBIO 4420/5420 Computational Biology

**STUDENTS:** Contents of this repository will change often during the semester.  Please check  back at least weekly ("pull" updates).

## Aims and Scope
This is a course for scientists who want to learn basic tools of modern computing.  Students with in-depth experience in computer science/programming will probably NOT find sufficient challenge from this course.

#### What the course is:
This course's main learning goals are for students to: 

1. Discover and implement computational tools for making their own professional work efficient, reproducible, transparent, shareable, maintainable, and robust.
2. Learn and use tools of programming at a basic level, including but not limited to writing programs and scripts in R, using the `git` version control system, and using GitHub to share and publicly archive projects.
3. Learn and apply tools for handling data (filtering, manipulating, subsetting, concatenating, re-formatting)
4. Learn how to learn new tools; learn how to find out how to use new tools; become more self-sufficient as a scientist and problem solver
5. If time allows and if there is sufficient interest, we may optionally: Learn and apply tools for simulating biological systems to generate pseudo-data and test hypotheses, including difference-time models, stochastic models, and ordinary differential equations models.


#### What the course is not:
This course is intended to give you tools that should help you in other courses focused on topics like "genomics," "bioinformatics," and "statistics," but this is NOT a course that will teach you those subject areas.

#### Why is this an upper division / grad course? 
Even though this course provides introductory material in computer programming, I expect you to know some fundamentals of organismal biology (like you would learn in 2000- and 3000- level Ecology and Evolution courses).  I also expect you to engage with your own critical thinking abilities, independent problem solving abilities, and independent research abilities.

______________________________

## Logistics and Contact Info

### Zoom Meetings for Class

+ The following link is for ALL scheduled class meetings, MWF at 10:20 a.m. any day that class is held, including both lecture and lab.
[https://cuboulder.zoom.us/j/96646452340](https://cuboulder.zoom.us/j/96646452340)

+ NOTE:  You MUST be signed into Zoom with your CU Boulder credentials to be able to join that meeting. See this video or this help page from OIT for instructions.

 
 ### Contacting Sam and Office Hours:

+ **NOTE DIFFERENT ZOOM LINK FOR OFFICE HOURS (below).**

+ Cell Phone: _see [Canvas][CanvasContactLink]_

+ Email Address: [samuel.flaxman@colorado.edu](mailto:samuel.flaxman@colorado.edu) 

+ Office hours on Zoom:  Mondays 9:00 - 10:00 a.m. and Mondays 11:30 a.m. - 12:30 p.m. 

    + No appointment is needed for office hours.  You can simply join the Zoom meeting below.  Note that the "waiting room" feature will be used.  If you are in the waiting room for several minutes, it means that Sam is meeting with someone else.  Office hours are held on Mondays so that you can follow up on any remaining questions or challenges you have from labs (on Fridays).  Office hours will be held every Monday from January 25th - April 26th.

    + All one-on-one meetings and office hours meetings will take place using Zoom at the following link:  _see [Canvas][CanvasContactLink]_

### Information available on Canvas:

+ Please visit our course's [Canvas page][CanvasSiteLink] for grades, assignment deadlines, PowerPoint files, announcements, and more.



______________________________

## Required Materials and Participation in the age of COVID-19

The following are absolutely required for success in this class:

* A working computer that can run R and RStudio and Zoom simultaneously and at reasonable speed
* A webcam or camera built into your computer that can show your face
* A microphone or one built into your computer that can clearly transmit your voice
* A reliable, high-speed internet connection that has enough bandwidth for you to transmit Zoom sound, video, and screenshares
* Checking [Canvas][CanvasSiteLink] regularly
* The software requirements as detailed at [https://github.com/flaxmans/CompBio_on_git/blob/master/CourseDocuments/SoftwareRequirements.md](https://github.com/flaxmans/CompBio_on_git/blob/master/CourseDocuments/SoftwareRequirements.md)

If you have any difficulty obtaining any of the above, you MUST let Sam know ASAP so that he can help you rectify the situation.  Broken cameras, microphones, computers, etc. will not be accepted as excuses for consistently missing work or a consistent lack of participation.  Unreliable or slow internet will NOT be accepted as an excuse for repeated absences or a consistent lack of participation.  If you have any concerns about this, please talk to Sam ASAP.   Sam wants to help you succeed and can put you in touch with resources to surmount any challenges you may be facing that are impeding you in having the requirements above.  The University as well as State and local governments all have resources that we can tap into if there is a need.

You are responsible for finding a quiet, appropriate location with a reliable, fast internet connection from which to "attend" classes on Zoom.  If you need help with that, I am happy to help arrange a location for you on campus.   

I am expecting everyone to keep their cameras on all the time during class.  If this is an issue for you, please discuss with Sam ASAP.

______________________________

## Week-by-Week Agenda  
This is subject to change and frequent updating; note that the accompanying PowerPoint files are available on Canvas.
Please also note that all deadlines for assignments are found on [Canvas][CanvasSiteLink].



###### Week 1 (1/15 - 1/22): 
+ Topics
	+ Mutual expectations
	+ Implicit bias
	+ Logistics of course
	+ Pitfalls of computing: case in point: don't use Excel (see paper by Ziemann et al. 2016)
	+ UNIX Command Line  

+ Lab week 1: Doing stuff with the UNIX command line
	
###### Week 2 (1/25 - 1/29):
+ Topics
    + Git intro
    + Lab week 2: git
    + Important reminder: [Send your GitHub repo's URL to Sam](https://goo.gl/forms/PhPGZPvE7fP3vW3R2)

+ Want to see live demonstrations of the key steps related to using `git` basics?  Sam made these screencasts for that purpose:
    + [Global user configuration settings](https://youtu.be/jPAB9BW1yXc), i.e., `git config ...`
    + [Initialize a new repo and link it to GitHub](https://youtu.be/8Ln6pjFrdvw), i.e., `git init` and `git remote add origin ...`
    + [Make a README, `add`, `commit`, and `push`](https://youtu.be/YwzEhb4Tf-g)

###### Week 3 (2/1 - 2/5):
+ Topics
    + Follow up from lab: remaining uncertainties?
    + Best practices: git, files, comments, README
    + Intro to R and scripting with R

+ Lab week 3: some simple scripting (and of course using git with the script(s))

+ Some resources to prepare for using R: 
    + Please watch these three (short) YouTube videos if you are new to R, and follow along by doing everything the narrator does on your own computer:
        + [intro](https://youtu.be/TG77MVHfC8E)
        + [vectors pt 1](https://youtu.be/A2Sh7uBwQv0)
        + [vectors pt 2](https://youtu.be/lNZQnLu_AWM)
    + If you are new to R or just rusty at using it, check out `swirl`.  To do so, follow the steps at [https://swirlstats.com/students.html](https://swirlstats.com/students.html), and do the first module of the first “course” it offers ("`1. R Programming`" --> "`1. Basic Building Blocks`").
    + Obviously, if you want to do additional modules of `R Programming` within `swirl`, go for it!

+ Hints and help: 
    + If you are experiencing conflicts with git, check out [this screencast](https://youtu.be/jIV_toWa5Zc).

###### Week 4 (2/8 - 2/12)
+ Topics
    + More R and Scripting
    + Best practices for writing scripts and handling data
    + Lab week 4: looping with `for` and array indexing

+ Resources: 
    + Read the ["Best Practices" Guide][bestpracticeslink]
 
###### Week 5 (2/15 - 2/19)
+ More with loops
+ Vectorizing
+ Conditionals
+ Lab week 5: combining loops, vectors, and conditionals
+ Resources:
    + Check out this [guide to turning ideas into code][WordsToCodeLink] and let Sam know what you think of it.

 
###### Week 6 (2/22 - 2/26)
 + More with loops and conditionals
 + Lab week 6: finish up lab 5 
 + Action items: 
+ Read the [Words to Code guide][WordsToCodeLink] and let Sam know what you think.  You can comment directly on that doc if you wish.
+ **NOTE: Campus "Wellness day" (no classes) on Wednesday 2/24**
 
###### Week 7 (3/1 - 3/5)
 + Solving problems and writing functions
 + Lab week 7: writing functions, part 1 
 
    
###### Week 8 (3/8 - 3/12)
 + Documentation and reproducibility
    + Markdown
    + More about Functions
 + [Lab week 8][Lab8link]: Markdown and more functions
 + Resources:
    + Do the tutorial at [https://www.markdowntutorial.com/](https://www.markdowntutorial.com/)
    + Reading for NEXT week:
        + *Abstract only* (unless you want to read more) at [https://doi.org/10.1371/journal.pone.0126373](https://doi.org/10.1371/journal.pone.0126373)
        + Data "Description" at [https://doi.org/10.5061/dryad.br86d](https://doi.org/10.5061/dryad.br86d)

###### Week 9 (3/15 - 3/19)
 + Follow-up on labs from weeks 7 and 8
 + Putting it all together: working through data problems with real data
    + using previously learned tools and new tools
    + file exploration and parsing on the command line
    + data exploration in R
    + scripting basic analyses and descriptive visualizations 
 + [Lab week 9](https://github.com/flaxmans/CompBio_on_git/blob/master/Labs/Lab09/Lab09_ParsingData.md): data parsing problems (prep by doing reading listed below)
 + Resources:
    + see two paragraphs of reading listed in week 8
    + Read about parsing dates and times in R at [https://www.stat.berkeley.edu/~s133/dates.html](https://www.stat.berkeley.edu/~s133/dates.html)
    + Browse the Tidyverse's date-handling package, "lubridate", at [https://lubridate.tidyverse.org/](https://lubridate.tidyverse.org/)


###### Week 10 (3/22 - 3/26)
+ Continuation of last week's challenges
    + Putting it all together: working through data problems with real data
    + using previously learned tools and new tools
    + file exploration and parsing on the command line
    + data exploration in R
    + scripting basic analyses and descriptive visualizations 
+ Resource: please read (at least) through section 3.6 at the following guide to ggplot2: [https://r4ds.had.co.nz/data-visualisation.html](https://r4ds.had.co.nz/data-visualisation.html)
+ **"Pause Week"**
    + The week of March 22-26 will be used in this class as a “spring pause” to provide us all with a safe and supportive way to promote health, wellness and learning without leaving campus. During this week, we won’t have any exams or assignments due. We will still have class with interactive class activities that will require your attendance and be part of your final course grade. Attendance is still required for all class sessions. I wish we could take a regular spring break, but public-health concerns prevent us from doing so. I would like to emphasize that it is still important for you all to behave responsibly. Do not use the week to travel or engage in risky behavior that could result in an outbreak on campus.

 
 ###### Week 11 (3/29 - 4/2)
 + Topics:
    + Final projects announced and described (see also [Assignment 08][Assignment8link])
    + More fun with real data
    + Wrapping up work with the Cusack et al. dataset
+ Lab for Week 11: more practice filtering, subsetting, summarizing, and plotting data
+ Resources: 
    + Preview the data set we'll work on in lab this week:
        + Read the abstract of [the original publication](https://doi.org/10.1111/j.1461-0248.2009.01285.x)
        + Download the [data package from Dryad](https://doi.org/10.5061/dryad.234)
    + Get ahead for lab on Friday: 
        + Check out the `order()` function in base R
        + `install.packages("tidyverse")`
        + In the `dplyr` package, check out `arrange()` and `summarise()`
        + Play with `ggplot()`

###### Week 12 (4/5 - 4/9)
+ Topics:
    + More exploration of `ggplot()`
    + More work with the [tree density database](https://doi.org/10.5061/dryad.234)

    
###### Week 13 (4/12 - 4/16)
+ Topics:
    + Student presentations of work to each other! (see [Assignment 08][Assignment8link])
    + Reviewing problems from Labs 11 and 12 if needed
    + Working with `ggplot()` and [COVID-19 data from the Denver Post](https://github.com/flaxmans/CompBio_on_git/tree/master/Datasets/COVID-19/DenverPostPlot)
+ Resources:
    + Read this Tidyverse [vignette about "pivoting"](https://tidyr.tidyverse.org/articles/pivot.html)

    
###### Week 14 (4/19 - 4/23)
+ Topics:
    + Working with data sets comprising many files
    + Shell command line tools applied to big data
+ Resources:
    + Check out one or two of the [raw data files on COVID-19 provided by CDPHE][CDPHEdata]
    + Read this [guide on citing references][CitationLink] for doing Assignment 09
 
 ###### Week 15 (4/26 - 4/28)
 + Topics:
    + Working with data sets comprising many files
    + Methods for creating visual and quantitative summaries across multiple data files
+ Resources:
    + Read this [guide on citing references][CitationLink] for doing Assignment 09.
+ **No class on Friday 4/30, "Reading Day"**    

_____________________________

## Grading policies 
This is a full, 3-credit course. You should expect to work as hard for these three credits as you do for any other advanced class.  Your final grade will be based upon a combination of (1) in-class participation, (2) formal assignments, (3) an independent project, (4) a take-home final examination, and (5) demonstrating enthusiasm and sincere effort for the material and the assignments.

1. Watching pre-recorded lectures will count for 20% of your grade.  These assignments will be completed via Canvas and the embedded PlayPosit tool.  

2. In-class participation will constitute 15% of your overall grade.  It will be based partially on attendance (you can’t participate without being there, right?), but mostly upon your work with others and your presentations to the class. Presentations to the class that fall in the participation category are “reporting out” exercises where you share the results of group work, sometimes at the front of the room using your own computer and/or the document camera.  Participation will also include discussions in class and demonstrations of your reasoning and problem solving (on paper and/or on your computer).  For most class periods, I will grade your participation on a scale from 0 to 5, with the approximate meanings of each as follows:  <br>
0 = absent  <br>
1 = showed up but did not engage; very unprepared; very late  <br>
2 = late; engaged minimally; not fully prepared  <br>
3 = on time and paid attention, but didn't participate  <br>
4 = average preparation and participation  <br>
5 = made an excellent contribution to the day's class

3. Formal assignments and presentations will constitute 35% of your overall grade.  Assignments will include written homework problems, computer code, and written responses to readings and exercises.

4. An independent project will be announced just before or after spring break. This project will constitute 15% of your overall grade. The project will be built from a series of assignments during the semester.

5. A take-home final examination will be given out on the day of our final designated by the University. You will have 24 hours to complete it.  It will be open-book, but you must work alone.  This exam will constitute 10% of your final grade.

6. Enthusiasm. 5% of your grade will be based upon a subjective evaluation (by me) of your general enthusiasm and effort for participating in all aspects of the course.  This not only includes your attitude toward class participation, but also things like really cleaning up your code nicely, polishing the work you show/turn in, etc.

Please note that all grades will be posted on the Course's [Canvas site][CanvasSiteLink]

_____________________________

## Statements about General Policies and Expected Conduct of Students, Faculty, and Staff

#### Live the [Colorado Creed](http://www.colorado.edu/creed/)
From [http://www.colorado.edu/creed/](http://www.colorado.edu/creed/), accessed 1/2/17:  
"As a member of the Boulder community and the University of Colorado Boulder, I agree to:

* Act with honor, integrity and accountability in my interactions with students, faculty, staff and neighbors.
* Respect the rights of others and accept our differences.
* Contribute to the greater good of this community.

I will strive to uphold these principles in all aspects of my collegiate experience and beyond."

#### Diversity and Inclusion
Research in educational settings suggests that students in a course benefit from the presence of diversity in the viewpoints, identities, and experiences of students and instructors.  In order for all of us to benefit to the greatest extent possible, together we need to value and respect each other as individuals and as contributors.  For my part, I want you to know that my classroom and office are intended to be welcoming, safe spaces for all students, regardless of any dimension of your identity.  I am happy to address you by whatever preferred name and pronouns you wish to use.  I welcome your suggestions for how I can make myself and/or any of the course content more inclusive.  For your part, I expect you, at a bare minimum, to abide by all campus codes of conduct and to live the Colorado Creed.  I also encourage you to think of this classroom as a community, and to treat your fellow community members in ways that foster an atmosphere in which all of us feel comfortable talking and sharing with each other.  During discussions and collaborative activities, try to find ways to invite others to share their ideas and viewpoints, and look for ways to help others feel valued for their contributions.

#### Implicit biases
Research from the fields of psychology and sociology demonstrates that ALL of us, no matter what our identities, have implicit biases.  Having implicit biases doesn't mean that you are bigoted.  Rather, these biases are present in each of us, subconsciously, owing to stereotypes we have been *repeatedly* exposed to, over and over again in our lifetimes as human beings.  A very common implicit bias that is relevant to this class has to do with people's (often unconscious) assumptions about innate abilities in math and computer programming.  Many people hold an implicit bias that one gender is inherently better at math and computer programming than another.  Research shows that this implicit bias is *equally present in both men and women*.  The bad things about implicit bias are that it leads to (1) self-reinforcing perpetuation of stereotypes and the bias itself, and (2) underperformance in people who have an implicit bias against some part of their own identity.  The good thing is that it is fairly easy to overcome by simply explicitly acknowledging that the bias is there but is not justified.  

I do not believe that any of you are inherently "good" or "bad" at math or computers.  I believe we all need practice, and we all can contribute.  There is no evidence that people from a particular gender, race, culture, age group, or ethnicity are innately better than others at the things I will ask you to do in this class.  You can all do equally well, no matter your identity.

### REQUIRED SYLLABUS STATEMENTS: Campus Policies that Apply to all Courses at University of Colorado Boulder

#### CLASSROOM BEHAVIOR

Both students and faculty are responsible for maintaining an appropriate learning environment in all instructional settings, whether in person, remote or online. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy.  For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](https://www.colorado.edu/sccr/sites/default/files/attached-files/2020-2021_student_code_of_conduct_0.pdf). 

#### REQUIREMENTS FOR COVID-19

As a matter of public health and safety due to the pandemic, all members of the CU Boulder community and all visitors to campus must follow university, department and building requirements, and public health orders in place to reduce the risk of spreading infectious disease. Required safety measures at CU Boulder relevant to the classroom setting include:

* maintain 6-foot distancing when possible,
* wear a face covering in public indoor spaces and outdoors while on campus consistent with state and county health orders,
* clean local work area,
* practice hand hygiene,
* follow public health orders, and
* if sick and you live off campus, do not come onto campus (unless instructed by a CU Healthcare professional), or if you live on-campus, please alert [CU Boulder Medical Services](https://www.colorado.edu/healthcenter/coronavirus-updates/symptoms-and-what-do-if-you-feel-sick).

Students who fail to adhere to these requirements will be asked to leave class, and students who do not leave class when asked or who refuse to comply with these requirements will be referred to [Student Conduct and Conflict Resolution](https://www.colorado.edu/sccr/). For more information, see the policies on [COVID-19 Health and Safety](https://www.colorado.edu/policies/covid-19-health-and-safety-policy) and [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](http://www.colorado.edu/osccr/). If you require accommodation because a disability prevents you from fulfilling these safety measures, please see the “Accommodation for Disabilities” statement on this syllabus.

All students who are new to campus must complete the [COVID-19 Student Health and Expectations Course](https://www.colorado.edu/protect-our-herd/how#anchor1). Before coming to campus each day, all students are required to complete the [Buff Pass](https://pass.colorado.edu/login).
 
 Students who have tested positive for COVID-19, have symptoms of COVID-19, or have had close contact with someone who has tested positive for or had symptoms of COVID-19 must stay home. In this class, if you cannot attend class for any reason, a simple email to Sam is all that is required.  You do NOT need to send Sam any kind of doctor's note.

#### ACCOMMODATION FOR DISABILITIES

If you qualify for accommodations because of a disability, please submit your accommodation letter from [Disability Services](https://www.colorado.edu/disabilityservices/) to your faculty member in a timely manner so that your needs can be addressed.  Disability Services determines accommodations based on documented disabilities in the academic environment.  Information on requesting accommodations is located on the Disability Services website. Contact Disability Services at 303-492-8671 or [dsinfo@colorado.edu](mailto:dsinfo@colorado.edu) for further assistance.  If you have a temporary medical condition, see [Temporary Medical Conditions](http://www.colorado.edu/disabilityservices/students/temporary-medical-conditions) on the Disability Services website.

#### PREFERRED STUDENT NAMES AND PRONOUNS

CU Boulder recognizes that students' legal information doesn't always align with how they identify. Students may update their preferred names and pronouns via the student portal; those preferred names and pronouns are listed on instructors' class rosters. In the absence of such updates, the name that appears on the class roster is the student's legal name.

#### HONOR CODE

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the Honor Code. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access to academic materials, clicker fraud, submitting the same or similar work in more than one course without permission from all course instructors involved, and aiding academic dishonesty. All incidents of academic misconduct will be reported to the Honor Code ([honor@colorado.edu](mailto:honor@colorado.edu)); 303-492-5550). Students found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code as well as academic sanctions from the faculty member. Additional information regarding the Honor Code academic integrity policy can be found at the [Honor Code Office website](https://www.colorado.edu/osccr/honor-code).

#### SEXUAL MISCONDUCT, DISCRIMINATION, HARASSMENT AND/OR RELATED RETALIATION

The University of Colorado Boulder (CU Boulder) is committed to fostering an inclusive and welcoming learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct (harassment, exploitation, and assault), intimate partner violence (dating or domestic violence), stalking, or protected-class discrimination or harassment by members of our community. Individuals who believe they have been subject to misconduct or retaliatory actions for reporting a concern should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127 or [cureport@colorado.edu](cureport@colorado.edu). Information about the OIEC, university policies, [anonymous reporting](https://cuboulder.qualtrics.com/jfe/form/SV_0PnqVK4kkIJIZnf), and the campus resources can be found on the [OIEC website](http://www.colorado.edu/institutionalequity/).

Please know that faculty and graduate instructors have a responsibility to inform OIEC when made aware of incidents of sexual misconduct, dating and domestic violence, stalking, discrimination, harassment and/or related retaliation, to ensure that individuals impacted receive information about options for reporting and support resources.

#### RELIGIOUS HOLIDAYS

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required attendance.  In this class, please let Sam know at least a week in advance about any needs for accommodations.

See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.








 
 
 
 
[GoogleDriveLink]: https://drive.google.com/drive/folders/1NnbmchARUxPdU6N4hdoRcbW9Yn_dXbEi?usp=sharing
[bestpracticeslink]: https://github.com/flaxmans/CompBio_on_git/blob/master/CourseDocuments/BestPractices.md
[Assignment5link]: https://github.com/flaxmans/CompBio_on_git/blob/master/Assignments/05_TasksForWeek5.md
[Assignment6link]: https://github.com/flaxmans/CompBio_on_git/blob/master/Assignments/06_TasksForWeek7.md
[Assignment7link]: https://github.com/flaxmans/CompBio_on_git/blob/master/Assignments/07_TasksForWeek8.md
[Assignment8link]: https://github.com/flaxmans/CompBio_on_git/blob/master/Assignments/08_Independent_Project_Step1.md
[Assignment9link]: https://github.com/flaxmans/CompBio_on_git/blob/master/Assignments/09_Independent_Project_Step2.md

[Lab8link]: https://github.com/flaxmans/CompBio_on_git/blob/master/Labs/Lab08/Lab08_documentation_and_metadata.md

[CanvasSiteLink]: https://canvas.colorado.edu/courses/70214

[WordsToCodeLink]: https://docs.google.com/document/d/1jAa5_lQL5AMd6Qg2UZGkjI_z5a6xtIj9IUgzG2J10vg/edit?usp=sharing

[CitationLink]: https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html

[CDPHEdata]: https://github.com/flaxmans/CompBio_on_git/tree/master/Datasets/COVID-19/CDPHE_Data

[CanvasContactLink]: https://canvas.colorado.edu/courses/70214/pages/contact-information
