---
layout: essay
type: essay
title: Interns for Interns
# All dates must be YYYY-MM-DD format!
date: 2020-05-19
labels:
  - InternBit
  - Artificial Intelligence
  - RadGrad
---

Finding suitable internships is a challenge that too many college students face on a regular basis. Why is it so hard? Simply googling “internship” will show you how easy it is to become overwhelmed by the sheer number of choices available. Sites such as indeed.com, internships.com, linkedin.com, occasionally provide some opportunities, but their selection is so massive that it’s sometimes difficult to find anything relevant. 

<img class="ui medium floated rounded image" src="../images/internship.png">

Looking particularly at internships.com, using “computer science” as a keyword and setting the location restraint to “Honolulu, HI” within 5 mi. radius, the first few results are all remote work, with one particular outlier in Virginia - to see internships that are located in Hawaii, we need to scroll a little further to find… just one internship in the area. In addition, the interface of the selection of internships can make it challenging to discern immediate information about the job - such as experience/skills required. It can be a frustrating battle to use these massive internship sites, as it’s not only difficult to find something that could be a good fit, but also time consuming to filter through internships that seem like a possible match, but upon further inspection, end up being something that doesn’t fit with your interest or skill set. 

This is where <a href="https://radgrad.github.io/docs/internbit/goals">InternBit</a> comes in. InternBit is an upcoming internship recommendation system set to be integrated with <a href="https://www.radgrad.org/">RadGrad</a>, a system for University of Hawaii Computer Science students that not only acts as a degree planner, but also allows students to explore opportunities in computer science available to them. Through the successful implementation of InternBit, students will have easier access to find and apply for internships that both fit their current skill set and are of interest to them.

The following few paragraphs will focus on a review of initial resources provided for the InternBit project.

##“Building an internship recommendation system”

<img class="ui medium floated rounded image" src="../images/recommend.jpg">

In <a href="https://medium.com/@ishannangia/building-an-internship-recommendation-system-i-introduction-8ab428131483">“Building an internship recommendation system,” </a> Ishan Nangia documents the process of creating his internship recommendation system, as he details his methods for scraping and cleaning internship data collected as well as creating the overall recommendation system. Nangia uses a mix between knowledge-based and content-based recommendation models to create a basis for his system. In the knowledge-based model, users receive recommendations based on preferences inputted by the users. In the context of an internship recommendation system, this would be based on details such as their major, preferred working field, and current skill set.  The content-based model selects recommendations based on the similarity of an item currently selected. In regards to internships, this would be similar to selecting an internship, and then getting recommendations for other internships based on the employer/job title/skill set required for the current internship. 

##Applications to InternBit

Nangia’s internship recommendation system provides a great starting point for the development of InternBit’s recommendation system. Nangia’s discussion regarding the different types of recommendation models gives foundation for InternBit’s model, as we can apply knowledge-based, collaborative, and content-based models based on the user information that RadGrad already has. His documentation on his internship crawler provides InternBit with a basis to create our own crawler, although ideally, InternBit would crawl through multiple internship websites, rather than just one. This would allow InternBit to access a greater number of internships, which in turn, could provide better internship recommendations. 

In addition, we can take note of some of the problems that Nangia documented throughout his process of developing the system, such as the issue of being unable to navigate past the first page of internship websites and the consequences of neglecting to add exceptions in his code. This could help prevent us from running into the same issues and/or provide us with a way to circumvent the problems entirely.

###Improvements by Integrating RadGrad

There are multiple improvements that could be made to Nangia’s system by integrating RadGrad, including enhancements to the knowledge-based and content-based recommendations, as well as the possible addition of collaborative recommendations. Because RadGrad already collects data from students, such as GPA, grade level, skill set, and past school/work experience, InternBit can use this data to better tailor its recommendations. For example, an internship that lists experience with Java or C as a requirement could be matched with a student who has completed ICS 111/211/212, courses that provide students with skills in Java and C. Collaborative recommendations, which base recommendations on a user’s similarity to another user, are another possible addition to make InternBit’s recommendations stronger. The aforementioned data collected by RadGrad can be used to compare students’ skill sets/experience to other students, which will give us the ability to use this type of recommendation model.

In addition, because RadGrad has an existing user base, we have a stronger way to evaluate InternBit’s recommendation system. Rather than trying to test the system on our own, we could use Nangia’s suggestion of creating two test groups, one that is given random recommendations and another given recommendations from InternBit. Then we could compare the clicks on each recommendation to see which group engaged more with the recommended internships.

As such, while Nangia’s recommendation system provides a great starting model, integrating RadGrad can offer many improvements for the purposes of InternBit.

##“An AI-based recommendation system for internship placements”
<img class="ui medium floated rounded image" src="../images/artificial-intelligence.jpg">
In <a href="https://techxplore.com/news/2019-03-ai-based-internship-placements.html">“An AI-based recommendation system for internship placements,”</a> Ingrid Fadelli reports on the use of artificial intelligence to recommend internships for students. The main process is as follows: students take a test that allows them to provide their “skills, grades, aspirations, and interests” as well as a questionnaire, known as the “Inventory Personal Survey,” to assess their behavior and attitudes. Then, the Elman neural network analyzes the results to provide a fitting recommendation for each student. This system appears to have great potential, as in the initial tests, in which it tested students who were currently applying for internships, it was able to successfully identify the internship placements of students with 95% accuracy.

###Potential of AI in InternBit?

As shown by the successful tests of this AI-based recommendation system, the use of artificial intelligence appears to have promising potential for recommending internships that are likely to be a good fit for the students matched with the internship. If we are able to implement artificial intelligence into InternBit, this could mean higher-quality internship recommendations - in the sense that students are more likely to be interested in the internships that InternBit recommends. 

If it is possible to implement this AI-based recommendation system into InternBit, there are a few advantages through integration with RadGrad. The initial test regarding students’ skillset and aspirations may not be necessary, as most of this information is already present within RadGrad. In addition, the information from RadGrad might be more accurate and more extensive than the self-reported test used in the AI-based recommendation. This could be used to craft recommendations that are better suited for students, as it will have more detailed information to analyze. 

##InternBit = Internships, Bit by Bit
<img class="ui medium floated rounded image" src="../images/jigsaw.png">

These resources all provide InternBit with a decent basis for development, from an example of a small-scale recommendation system to the noteworthy potential for artificial intelligence to be integrated within the system. InternBit can take “bits” from each of these resources to mold its internship recommendation system. In addition, with RadGrad integration, InternBit will have much more data to analyze within its system to better craft recommendations. Careful review of these resources can ensure steady, successful development of InternBit.
