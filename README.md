# NeuroSync
# AI-Powered University Intelligence Platform
# Predict. Prevent. Empower Student Success.

# Team - Techno Legends
1. Zinhle Dlamini
2. Diya Nandkoomar
3. Vhutali Tshinaiwe 
4. Siphiwe Sithebe
5. Sinezipho Cebekhulu

# Overview
NeuroSync is an intelligent university analytics platform built using Microsoft Fabric.

The platform combines academic, attendance, engagement, wellbeing and behavioural data into a unified ecosystem that helps universities identify at-risk students before problems become critical.
Instead of relying on reactive support systems, NeuroSync enables proactive intervention through AI-powered recommendations, predictive analytics, and real-time dashboards.

# Problem Statement

Universities worldwide face increasing challenges in supporting student success due to growing enrolment numbers, fragmented student data systems, and limited early intervention capabilities.

### Key Statistics

Global tertiary enrolment has increased from **19% to 44% since 2000**, placing greater pressure on universities to support diverse student populations.

More than **20% of bachelor's degree students leave during or after their first year** in several higher education systems.

Approximately **15% or more of first-year students drop out** due to poor engagement, academic challenges, or wellbeing concerns.

Research consistently identifies **attendance, engagement, and assessment performance** as strong predictors of student success and retention.

These challenges highlight the need for a unified, intelligent platform that can identify at-risk students early and enable proactive intervention.

## References

1. OECD. (2025). *Education at a Glance 2025*.
2. Times Higher Education. (2025). *Student Retention and First-Year Dropout Trends in Higher Education*.
3. ArXiv. (2024). *Predicting Student Success Through Attendance, Engagement and Assessment Analytics*.

# Solution

The NeuroSync solution is an intelligent university analytics platform designed to provide real-time insights into student performance, attendance, and wellbeing. It addresses the challenge of delayed intervention in identifying at-risk students by centralising fragmented institutional data into a unified, AI-powered ecosystem built on Microsoft Fabric.

The system ingests multiple data sources, including attendance records, academic performance, and student wellbeing indicators, into Microsoft OneLake, where the data is stored and managed in a structured Lakehouse environment. From there, Fabric Notebooks are used for data cleaning, transformation, and preparation for analysis.

A key component of the solution is the **Risk Analysis Engine**, which applies logic and predictive modelling to identify students who may be at risk academically or emotionally. This engine processes patterns such as declining attendance, poor academic performance, and wellbeing signals to generate early warning indicators.

To enhance decision-making, NeuroSync integrates an **AI Insight Agent**, which acts as an intelligent assistant for educators and administrators. This AI agent interprets processed data and provides clear, human-readable recommendations such as identifying students who need urgent academic support, suggesting interventions, and summarising key trends across departments. It enables non-technical users to interact with complex data in a simple, conversational manner.

Finally, insights are visualised through **Power BI dashboards**, allowing stakeholders to monitor student risk levels, track trends over time, and make data-driven decisions. This end-to-end pipeline ensures that universities can move from reactive responses to proactive student support, improving retention and academic success rates.


# Technologies Used
- Microsoft Fabric
- OneLake
- Lakehouse
- Power BI
- Fabric Notebooks
- AI Insights

  
# AI Insight Agent

The AI Insight Agent is the intelligent layer of NeuroSync that transforms student data into actionable insights. Rather than simply displaying information, the agent analyses attendance records, academic performance, and wellbeing indicators to identify patterns that may signal student risk.

Using these insights, the AI Insight Agent provides human-readable recommendations and summaries, enabling lecturers and university administrators to make informed decisions quickly. By converting complex data into meaningful guidance, the agent supports proactive interventions that improve student success and retention.


# Example Interaction

## User Question:

Why has Student A been flagged as high risk?


## AI Insight Agent Response:

Student A has missed **35%** of scheduled classes over the past month, achieved below-average assessment results in two modules, and has reported wellbeing concerns. These combined indicators increase the likelihood of academic difficulty, and early intervention is recommended.


## Key Capabilities
- Early identification of at-risk students
- Intelligent recommendations and intervention suggestions
- Real-time analysis of student performance trends
- Automated insight generation
- Decision support for university staff


# What Makes NeuroSync Unique?

NeuroSync is more than a traditional student analytics platform. It combines advanced data integration, predictive intelligence, and AI-driven recommendations within a single Microsoft Fabric ecosystem, enabling universities to move from reactive decision-making to proactive student support.

 ## Unique Value Proposition

- ### Unified Student Intelligence
Integrates attendance, academic, and wellbeing data into a single source of truth.

- ### AI-Powered Insights
Provides recommendations and explanations, not just dashboards and reports.

- ### Early Risk Detection
Identifies potential student challenges before they become critical issues.

- ### Microsoft Fabric Architecture
Leverages OneLake, Lakehouse, Fabric Notebooks, Power BI, and AI capabilities in a modern cloud-based platform.

- ### Human-Centred Design
Presents complex analytics in a simple and understandable format for lecturers, advisors, and university management.

- ### Actionable Decision Support
Transforms data into meaningful actions that help improve student outcomes and institutional performance.


# System Architecture

The following architecture diagram is provided as evidence of the NeuroSync system design. It illustrates the end-to-end flow of data through the platform, from student data sources to analytics and decision-making outputs. The diagram highlights the integration of Microsoft Fabric components, including OneLake, Lakehouse, Fabric Notebooks, the Risk Analysis Engine, the AI Insight Agent, and Power BI. It demonstrates how NeuroSync transforms raw student data into actionable insights that support proactive intervention and informed decision-making within universities.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7efddd94-b0bc-41e4-b981-6b5fc7d73618" />
The architecture highlights the technical foundation of NeuroSync, showcasing how Microsoft Fabric, intelligent risk analysis, and AI-powered recommendations work together to create a secure, scalable, and data-driven student intelligence platform.


# Power BI Dashboard

NeuroSync leverages Power BI to transform complex student data into clear, interactive, and actionable visual insights. The dashboard serves as the primary interface for lecturers, advisors, and university administrators, enabling them to monitor student performance, attendance patterns, wellbeing indicators, and overall risk levels in real time.
By consolidating data from multiple sources into a single view, the dashboard supports faster decision-making, early intervention strategies, and improved student success outcomes. Interactive reports allow stakeholders to identify trends, track key performance indicators, and focus support efforts where they are needed most. The following dashboard screenshots are provided as evidence of NeuroSync's reporting and analytics capabilities. They demonstrate how Power BI transforms processed data into meaningful visualisations that support proactive intervention, risk monitoring, and data-driven decision-making within higher education institutions.

<img width="933" height="521" alt="dashboard 11" src="https://github.com/user-attachments/assets/12e937d1-2c84-4779-ab11-cc6cbca65a43" />

### Dashboard 1 – Wellbeing Overview
This dashboard shows student wellbeing across the university, including mood, stress levels, study hours, and overall risk classifications. It helps identify students who may require support.

<img width="979" height="518" alt="dashboard 12" src="https://github.com/user-attachments/assets/27986524-411e-4f20-92ac-e912537b259c" />

### Dashboard 2 – Risk Analytics
This dashboard combines wellbeing, attendance, and academic data to identify at-risk students. It provides a quick view of student risk levels and highlights faculties that may require intervention..

 <p align="center"> 
<img width="600" height="600" alt="dashboard 13" src="https://github.com/user-attachments/assets/80f291ad-6d52-4646-a4de-dfe5344a692d" />
   
 ### Dashboard 3 – Academic Performance
This dashboard tracks assessment performance and submission rates. It helps lecturers identify students who are failing, achieving distinctions, or missing submissions.

## Overall

Together, these dashboards give universities a complete view of student success, enabling early intervention and data-driven decision-making. 


# Prototype

The NeuroSync prototype demonstrates how users would interact with the platform in a real-world university environment. It provides a visual representation of the user experience, showcasing how lecturers, advisors, and administrators can access student insights, monitor risk indicators, and receive AI-powered recommendations through an intuitive interface.
The prototype was designed with usability and accessibility in mind, ensuring that complex analytics can be understood and acted upon by both technical and non-technical users. The following prototype screens are provided as evidence of the NeuroSync user interface and user experience design. They illustrate how key features, including student monitoring, risk analysis, AI-generated insights, and dashboard navigation, would be presented within the platform.

## 👨‍🎓 Student Portal

The Student Portal serves as the primary interface for students within the NeuroSync platform. It provides students with access to their academic information, attendance records, wellbeing insights, and personalised recommendations generated by the AI Insight Agent. The portal is designed to empower students by providing a clear view of their progress and enabling early action when potential challenges are identified.The following prototype screens demonstrate the Student Portal interface and user experience. They showcase how students can monitor their academic performance, track attendance, access wellbeing information, and interact with personalised insights through a simple and intuitive platform.

### Prototype Screen 1: Portal Selection Page
<img width="1920" height="925" alt="proto 1" src="https://github.com/user-attachments/assets/30b27a00-e099-4640-814b-13cd77ba7bb9" />
he Portal Selection Page serves as the entry point to the NeuroSync platform. Users can choose between the Student Portal and Organisation Portal based on their role. This interface provides secure access to personalised dashboards, analytics, and AI-powered insights.

### Prototype Screen 2: Portal Sign in 
<img width="1920" height="924" alt="pro2" src="https://github.com/user-attachments/assets/effb9edd-a8fb-4cb7-8d3d-2219fe1345ac" />
The Sign-In Page provides secure access to the NeuroSync platform, allowing users to authenticate their accounts and access personalised features, dashboards, and insights based on their role.

### Prototype Screen 3: Portal Aunthentication Security
<img width="1920" height="918" alt="pro3" src="https://github.com/user-attachments/assets/9164fc3a-7ab0-4901-93b3-c0e5933e994f" />
he Authentication and Security page provides an additional layer of protection through secure user verification. It ensures that only authorised users can access the NeuroSync platform, helping to safeguard sensitive student and institutional data.

### Prototype Screen 4: Student Home Page Dashboard
<img width="1920" height="1020" alt="pro4" src="https://github.com/user-attachments/assets/8af2170c-717f-4924-9c9b-5108b8b761ca" />
The Home Dashboard provides students with a personalized overview of their academic performance, wellbeing status, module progress, submission tracking and key recommendations. It serves as a central hub for monitoring progress, staying organized, and receiving AI-powered guidance.

### Prototype Screen 5: Learning Analytics 
<img width="1920" height="921" alt="pro5" src="https://github.com/user-attachments/assets/8cf923f0-7d62-4850-b579-2d218b689ddb" />
rovides detailed insights into academic performance, learning trends, and progress over time to help students improve their outcomes.

### Prototype Screen 6: Submission Tracker
<img width="1920" height="928" alt="pro6" src="https://github.com/user-attachments/assets/c0d450d3-39df-4c7e-b3b6-d2c364fcda94" />


# Presentation Highlights

The following slides are provided as evidence of the NeuroSync solution, highlighting only the core components of the project. This includes the problem statement, the proposed AI-driven solution, and the security and data protection built using Microsoft Fabric. These selected slides demonstrate the technical design and overall approach of the system in a clear and focused manner.

# THE PROBLEM STATEMENT <img width="1179" height="662" alt="SLIDE 1" src="https://github.com/user-attachments/assets/ded7bd8c-5442-4433-a6b2-47d11591d34a" />
# THE SOLUTION <img width="1171" height="663" alt="SLIDE 2" src="https://github.com/user-attachments/assets/09cc636b-6fc3-4ed9-80b0-92fa30e221ef" />
# SECURITY & DATA PROTECTION <img width="1177" height="664" alt="image" src="https://github.com/user-attachments/assets/5b761ed9-ddf5-491b-a8ea-2be90ad70377" />


 
# Hackathon Achievement

🏆We won 1st Best Solution – DUT Microsoft Fabric Hackathon 2026

## Team Contributions and Presentation Roles

### Zinhle Dlamini
Conducted the project research, created the complete presentation, and created the project documentation. During the presentation, she introduced NeuroSync and presented the project from the problem statement through to the proposed solution. This included explaining the challenges faced by universities, the purpose of NeuroSync, its key features, benefits, architecture, security considerations, future enhancements, and overall impact.

### Diya Nandkoomar
Contributed to requirements gathering, developed the NeuroSync concept and  with the Power BI component of the project. During the presentation, she participated in presenting the prototype and demonstrated how different users would interact with the NeuroSync platform through the designed interfaces.

### Vhutali Tshinaiwe
Assisted with the creation and preparation of the project presentation, contributing to the development and organisation of presentation content used during the final demonstration.

### Siphiwe Sithebe
Designed and developed the complete NeuroSync prototype. During the presentation, she demonstrated the prototype screens and explained the user experience, including the student, university, and organisational interfaces and how users would navigate the platform.

### Sinezipho Cebekhulu
Presented the Power BI dashboard component of NeuroSync. He demonstrated the analytics, reports, charts, graphs, and data visualisations, explaining how the platform transforms university data into actionable insights that support student success and decision-making.



