---
layout: page
title: Syllabus
description: >-
    Course policies and information.
---

# Syllabus
{:.no_toc}

## COMP 152-06: Explainable Artificial Intelligence (XAI)
{:.no_toc}
Department of Computer Science, Tufts University, Spring 2021

** Note: this syllabus is subject to change.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
# Course Overview

As machine learning systems are increasingly being considered for employments in contexts where their decisions can have real (positive and negative) impacts on people's lives, scholars and activists have increasingly raised concerns about the transparency and accountability of such systems and their designers. The field of explainable artificial intelligence (XAI) has sprung up in recent years to address some of these concerns by developing systems which can explain the reasons behind their decisions and outputs to users.  In this course, we explore this up-and-coming subfield of AI by learning the basic concepts and ideas, and then discussing recent research papers in the field.  We will study both the central ideas and concrete systems constructed using these ideas. We will also think more broadly about the assumptions underlying the field of XAI and the ethical debates within the field.

Topics to be discussed include: explanation in comparison to interpretability, accountability, and transparency; causal inference and its relation to explainability; explanation in social science; explanation of black-box models; explainable planning; explainable reinforcement learning; and ongoing ethical and methodological debates within the field of XAI.


# Objectives

Upon completing this course, students will be able to:

* Understand the concepts behind XAI and participate in its debates;
* Read and critique recent papers in the XAI literature; and
* Identify gaps and opportunities for fruitful research in XAI.

# Prerequisites

This course is an XAI course, not a general introduction to AI. As such, a basic understanding of some approaches to AI (especially neural networks, classical planning, and reinforcement learning) is highly recommended, though not strictly required as a prerequisite.

That said, I do expect students to have at least a rudimentary understanding of the following before taking this course:
* Probability theory (Bayes' theorem, etc.)
* Linear algebra (matrices, vectors)
* Differential calculus (namely, how to take derivatives of functions)

With instructor permission, diligent students who are lacking in a few of these areas will hopefully be able to catch-up on core concepts via self-study and thus still be able to complete the course effectively.

# Format
The class is synchronous and fully virtual. Class sessions are over Zoom, **Mondays** and **Wednesdays** from **10:30-11:45am EST**.

# Instructor
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

**Contact**: My email address is listed above; however, any questions that are not of a personal nature should be directed to Piazza, for the edification of all.  Please preface the subject line of any course-related emails (including submission of deliverables) with "[COMP152]" or "[COMP152XAI]" or something similar.

# Resources
* The schedule, final project description, and syllabus can be found at [https://www.cs.tufts.edu/comp/152XAI/2021s/](https://www.cs.tufts.edu/comp/152XAI/2021s/).
* We will be using Piazza for collaborative class discussion. The Piazza link can be found at [https://www.piazza.com/tufts/spring2021/comp15206](https://www.piazza.com/tufts/spring2021/comp15206).

# Assignments and Grading

Students' grades will be calculated as follows:

* **Reading responses on Piazza** (**20%** of grade): by 9:00 PM the night before each class, students will submit (on a central Piazza thread, non-anonymously) a brief response to that class's readings, consisting of some combination of clarification and discussion questions, interesting takeaways, and critiques of the paper. Students are encouraged to read and engage with each other's responses.  Meaningfully engaging with another student's response (either by expanding on the ideas, answering questions, etc) will count as a response in itself.

* **Final Project**: (**80%** of grade): students will form groups of 1-3 (individual projects are permitted) to complete a final group project. The project will be (a) a literature review; (b) a position paper in the field of XAI (convincingly making a novel argument); or (c) a paper presenting original XAI research. The goal will be to do work that the student could potentially submit to an academic conference or journal. The deliverables of this project are as follows:
  * *Topic list* (5%): By February 22nd, students will have formed groups (feel free to use Piazza for group formation and brainstorming) and assembled a list of potential topics, and will submit the list of group members and potential topics to the instructor. The instructor will provide feedback on the ideas in a timely fashion. Groups are encouraged to meet with the instructor prior to February 22nd to discuss ideas.
  * *Outline* (10%): By March 15th, students will submit an outline of their intended paper, consisting of a detailed description of:
    - What is known about the topic
    - What remains unknown about the topic
    - Why the topic is important
    - What the unique contributions of the paper will be with respect to the topic
  * *Presentation* (15%): Within their groups, students are expected to present the current state of their final projects. Presentations should be roughly 15 minutes total (12 minutes, plus 3 for questions), and should have slides. Presentations are expected to occur on April 12th and 14th. While papers need not be finished by presentation time, the presentations should demonstrate that substantial progress on the project has been made.
  * *Paper* (50%): The final outcome of the project will be a paper. This paper will be written using the [ACM SIGCONF paper template](https://www.acm.org/publications/proceedings-template), 6 -- 10 pages excluding references. The paper will be submitted no later than Sunday, May 9th, 2021.  Along with the paper, any groups of 2 or more should submit, as a separate document, a brief summary of all group members' contributions (ideas, work, etc) to the paper and the project as a whole.

All assignments are due 11:59PM EST unless otherwise specified. All deliverables for the final project are to be emailed to the instructor.

# Late Work Policy

Individual work (namely, Piazza reading responses) will receive half-credit if submitted after 9:00PM the night before class but before class start time (10:30AM). Responses submitted after the class in question will not receive credit.

For the final project, each group will have a total of 72 total late hours (3 late days) to divide between the topic list, outline, and final paper. Provided these late hours are not used up, groups will receive full credit on late deliverables. The time of submission will be measured as the time that the email containing the deliverable is delivered to my email address. Late time is rounded up to the nearest hour (so, submitting an assignment a half-hour late uses one late hour).  Beyond your allowance of 72 late hours, zero credit will be awarded except in exceptional circumstances (e.g., family/medical emergency).

# Collaboration Policy

Academic research can be a highly collaborative process. Group collaboration in this course is encouraged, particularly in the final project, in which group members with different backgrounds can each contribute uniquely and meaningfully to the research process. Students are further encouraged to discuss issues related to the course over Piazza.

Two common-sense principles apply here:

* **Give credit where credit is due**: If you receive help or inspiration from classmates, acknowledge it. This is especially true with final projects: if anyone outside of your group contributes to your project in any meaningful way, include a short "acknowledgments" section in your paper in which you briefly mention how they helped and thank them for it. This is good practice for anyone in a research field.
* **Contribute and engage**: I expect that each student in the class is interested in engaging with the ideas presented. Actually read the readings, and provide responses that reflect your engagement with them, rather than simply reading someone else's post and paraphrasing it. Similarly, I expect final projects to contribute to the XAI field in a meaningful way, rather than simply paraphrase or summarize existing papers (this is true even for literature reviews).

# Academic Integrity Policy

This course will strictly follow the Academic Integrity Policy of Tufts University. Students are expected to finish course work independently when instructed, and to acknowledge all collaborators appropriately when group work is allowed. Submitted work should truthfully represent the time and effort applied.

Please refer to the Academic Integrity Policy at the following URL: [https://students.tufts.edu/student-affairs/student-life-policies/academic-integrity-policy](https://students.tufts.edu/student-affairs/student-life-policies/academic-integrity-policy)

# Academic support at the StAAR Center

The StAAR Center (formerly the Academic Resource Center and Student Accessibility Services) offers a variety of resources to all students (both undergraduate and graduate) in the Schools of Arts and Sciences, and Engineering, the SMFA, and The Fletcher School; services are free to all enrolled students. Students may make an appointment to work on any writing-related project or assignment, attend subject tutoring in a variety of disciplines, or meet with an academic coach to hone fundamental academic skills like time management or overcoming procrastination. Students can make an appointment for any of these services by visiting [go.tufts.edu/TutorFinder](go.tufts.edu/TutorFinder), or by visiting [go.tufts.edu/StAARCenter](go.tufts.edu/TutorFinder).

# Accommodations for students with disabilities
Tufts University values the diversity of our body of students, staff, and faculty and recognizes the important contribution each student makes to our unique community. Tufts is committed to providing equal access and support to all qualified students through the provision of reasonable accommodations so that each student may fully participate in the Tufts experience.

If a student has a disability that requires reasonable accommodations, they should please contact the StAAR Center (formerly Student Accessibility Services) at [StaarCenter@tufts.edu](StaarCenter@tufts.edu) or 617-627-4539 to make an appointment with an accessibility representative to determine appropriate accommodations. Please be aware that accommodations cannot be enacted retroactively, making timeliness a critical aspect for their provision.

Please see the detailed accessibility policy at the following URL: [https://students.tufts.edu/staar-center/accessibility-services](https://students.tufts.edu/staar-center/accessibility-services). 

# Feedback
Tufts and the instructor of this course strive to create a learning environment that is welcoming to students of all backgrounds.

Your thoughts and concerns are important. You are encouraged to give feedback to the instructor throughout the term. If you feel uncomfortable talking to the instructor, consider reaching out to your academic advisor, department chair, or dean.