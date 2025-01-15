## **Introduction**

**Meet Our Aspirants:**

**1\. Rafiq (The Fresh Graduate)**

* Just completed his Higher Secondary Certificate (HSC) and dreams of studying abroad for his undergraduate degree.  
* Ambitious, curious, and driven to explore new academic fields.  
* Wishes for clear guidance on scholarships, universities, and application requirements.

**2\. Ayesha (The Academic Achiever)**

* Recently finished her undergraduate degree and aspires to pursue a Master’s or Ph.D. abroad.  
* Focused on research opportunities and collaborations with professors.  
* Seeks funding and assistantships but feels lost in the complex application processes.

**3\. Karim (The Mid-Career Professional)**

* Feels stagnant in his current job and wants to pivot his career through certifications or advanced education abroad.  
* Ambitious yet unsure about how to balance work, finances, and deadlines to secure opportunities.

<!--
move to personas page
-->

Despite their differences, they all share common struggles:

## **Problem Statement**

### **Complexity of Scholarship Applications:**

* Identifying and applying for the most suitable scholarships.  
* But with over 500+ scholarships available globally, varying criteria, and strict deadlines, it’s overwhelming to keep track of the opportunities.  
* Because there are no centralized tools or guidance to help manage the applications and deadlines.  
* Which makes one feel stressed and uncertain, induced by missed deadlines and the complexity of finding the right scholarships.
<!---
TRACKING...
web scrapping
list popular universities
fine tuned google search
data transform using AI agent to a particular idea
RAG AI model
****unified model for scholarschips**** (list and identify all the fields)
tracking the scholarships and properly updating them
scrap specialized websites that provides scholarship info
-->

### **Standardized Testing Requirements:**

* One needs to prepare for standardized tests like IELTS, TOEFL, GRE, and GMAT, which are prerequisites for most scholarships and programs.  
* However, preparing for these tests while managing application timelines is overwhelming.  
* Because there’s no centralized platform to guide test preparations alongside the application process.  
* Which makes one feel unprepared, anxious, and prone to missing key testing deadlines.

<!---
preparation materials -> outsourced -> curated resources -> formatted for particulars (for demo, IELTS contents)
mock tests -> tracking -> ai generated questions (RAG, existing models) -> back propagate to resources (add hand crafted tests as references)
course selling, affiliate marketing -> money
list out existing open source models for this task
-->

### **Lack of Guidance on University Selection:**

* Trying to select a university and program that aligns with one’s academic interests and career goals.  
* But with over 2,000 universities worldwide, it is a struggle to narrow down the options and assess their suitability.  
* Because of the lack of tools and resources to compare institutions, rankings, and program details.  
* Which makes one feel lost and unsure about their decisions, resulting in poor application quality.
<!--
list out all the constraints for this problem as input (money, program preference, test grades, program value) 
constraint modeling result generation
good to have feature: match the achivements against university requirements
convert university requirements to measurable metrics/goals
track and find out how much of that goal is fulfilled
-->

### **Challenges in Showcasing Achievements:**

* Tracking and showcasing academic achievements, extracurricular activities, and volunteer work for scholarship applications.  
* But without an organized platform, the achievements have to be manually compiled and organized, making it difficult to present them effectively.  
* Because there are no integrated tools to streamline this process.  
* Which makes one feel stressed and uncertain, induced by incomplete or disorganized applications.
<!--
same problem
-->

### **Inadequate Support for Statement of Purpose (SOP) Writing:**

* Writing a compelling SOP to highlight my skills, goals, and motivations.  
* But the struggle with structuring and presenting the story effectively.  
* Because of no access to personalized templates, feedback, or editing services.  
* Which makes one feel anxious and less confident about the quality of my application.
<!--
use the constraint model problem metrics
cv, achievements,
if all information is given then generate SOP story from that

if nothing or partial is there (should be premium feature)
questionnare using bot using relevant questions
and generate a story

how to measure quality of the generated/manual SOP

find out the all the features of a good SOP manually and use it in the AI algorithm
and find out how much of the features are there.

paraphrasing, grammar...
**5\. Cultural Differences in Application Processes:**

* **Challenge**: Different universities and scholarship bodies have varying requirements and cultural expectations for applications. Adapting to these nuances may prove difficult for a universal platform.  
* **Solution**: Customize scholarship and university data based on region-specific application rules and provide localized SOP writing tips and requirements for different countries.
-->

### **Disorganization and Time Management Challenges:**

* Managing deadlines, documents, and submissions efficiently.  
* But the scattered nature of the process makes it hard to keep track of what has to be done and what’s pending.  
* Because there’s no centralized system to monitor progress and deadlines.  
* Which makes one feel overwhelmed and prone to missing important tasks.

<!--
think about the UI/UX design
provide and checklist and track against it
advance tracking using historical timeline
preapare a roadmap for him
how it is generated (generate the roadmap around fixed points, exams, application deadline)
-->


### **Limited Access to Financial Aid Information:**

* Trying to find grants, assistantships, and student loans to fund my studies abroad.  
* But financial aid options are not clearly laid out or tailored to my needs.  
* Because the available information is scattered and difficult to verify.
* Which makes one feel discouraged and uncertain about affording my education.

<!--
helps to get financial announcement
  - how to get unofficial help using past data and preparing documents
  gives out a idea on how to earn
  and the related expenditure or living costs
  and advice on good starting points on earning money 
student loan advertisement (geographicically locked)
-->

### **Automation Gap:**

* Simplifying the application process by automating repetitive tasks like filling out forms and submitting documents.  
* But there’s no platform to assist with these tasks and send timely reminders.  
* Because existing solutions are fragmented and lack comprehensive automation features.  
* Which makes one feel frustrated and more likely to delay or abandon my application process.

### **Professor:**
<!--
- cold mail to matched professors limited upto 200, suggest professors matched by criterias
- show student profiles to professors, when professors are onboard
-->

**6\. Language Barriers:**

* **Challenge**: Many students in Bangladesh may not be proficient in English, the primary language for many scholarship applications, limiting their ability to effectively use the platform.  
* **Solution**: Offer multilingual support, including Bengali, to ensure all students can understand the platform and write applications in their native language before translating them into English.
<!--
google auto translation
--> 

**3\. Internet Accessibility and Infrastructure:**

* **Challenge**: Limited internet access in rural or underserved areas of Bangladesh may hinder students’ ability to use the platform effectively.  
* **Solution**: Optimize the platform for low bandwidth and offer offline functionality where students can download forms, templates, and guides to work offline, with synchronization when the internet is available.
<!--
which features will be accessible without internet
-->


## **Solution**

Our platform addresses these challenges by:

1. Providing a centralized database of scholarships, universities, and financial aid opportunities with search and filter options.  
2. Offering personalized recommendations based on academic profiles, interests, and career goals.  
3. Enabling users to organize and showcase their achievements through built-in templates and trackers.  
4. Supporting SOP writing with AI-powered suggestions, templates, and editing tools.  
5. Simplifying time management with automated reminders, task lists, and progress trackers.  
6. Guiding users in finding professors and research assistantships through integrated networks and outreach templates.  
7. Offering resources and scheduling tools to prepare for standardized tests alongside application planning.  
8. Automating repetitive tasks and document preparation to save time and reduce errors.

With our platform, students and professionals can focus on achieving their dreams without the stress of navigating a fragmented and complex application process.

Problem Statement
1. Sourcing Reliable Scholarship and Program Data
The education landscape is dynamic, with new scholarships and programs being introduced regularly. However, sourcing this data from reliable and updated sources is a significant challenge. Many scholarships and university programs do not have centralized repositories, forcing students to scour multiple websites and platforms. This leads to missed opportunities and incomplete information.

2. Frequent Updates to Application Requirements
University and scholarship requirements often change without notice, such as eligibility criteria, required documents, or deadlines. Staying updated with these changes is a daunting task, especially for students who don’t have the time or expertise to monitor multiple platforms simultaneously.

3. Lack of a Unified System for Financial Aid Information
Financial aid opportunities, including grants, loans, and assistantships, are scattered across different websites and portals. Students often have to search manually and piece together information, which is time-consuming and prone to errors.

4. Managing Large Volumes of User-Generated Data
Our platform will handle data like academic records, extracurricular achievements, test scores, and personal statements from thousands of users. Without a robust data management system, it becomes difficult to ensure accuracy, prevent duplication, and provide personalized recommendations.

5. Automating Complex Processes
Students have to repeatedly fill out similar forms for different applications, such as university admissions, scholarships, and standardized tests. These repetitive tasks consume a lot of time and often result in errors. Automating such processes is technically challenging but necessary for an efficient user experience.

6. Providing Up-to-Date Resources for Standardized Test Preparation
Preparing for exams like IELTS, GRE, or GMAT requires access to the latest resources, practice tests, and tips. Without regular updates, these materials can become outdated, putting students at a disadvantage.

7. Creating Multilingual and Accessible Content
Many students in Bangladesh, especially from rural areas, may not be fluent in English or tech-savvy. Providing content in Bengali and ensuring the platform is intuitive for all users is a critical challenge.

8. Ensuring Data Privacy and Security
Collecting sensitive information such as academic records, financial details, and personal documents poses security risks. Any breach or misuse of data can result in loss of trust and legal liabilities.

9. Scalability of the Platform
As the platform grows, scaling its infrastructure to support more users and handle a large volume of data without compromising speed or performance is a major challenge.

10. Building Credibility and Trust Among Users
Students and parents are often skeptical of new platforms, especially when it involves providing sensitive information. Establishing credibility through reliable partnerships and consistent delivery of value is crucial for adoption.

  
