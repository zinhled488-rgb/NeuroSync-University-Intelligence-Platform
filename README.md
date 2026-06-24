# NeuroSync
# AI-Powered University Intelligence Platform
# Predict. Prevent. Empower Student Success.

# Team
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

### Unified Student Intelligence
Integrates attendance, academic, and wellbeing data into a single source of truth.

### AI-Powered Insights
Provides recommendations and explanations, not just dashboards and reports.

### Early Risk Detection
Identifies potential student challenges before they become critical issues.

### Microsoft Fabric Architecture
Leverages OneLake, Lakehouse, Fabric Notebooks, Power BI, and AI capabilities in a modern cloud-based platform.

### Human-Centred Design
Presents complex analytics in a simple and understandable format for lecturers, advisors, and university management.

### Actionable Decision Support
Transforms data into meaningful actions that help improve student outcomes and institutional performance.

# Security & Privacy

NeuroSync is built with enterprise-grade security and privacy controls to protect sensitive student and institutional data. The platform follows a security-first approach, ensuring that information is accessed responsibly, transmitted securely, and managed in compliance with data protection standards.

## Key Security Features

### Role-Based Access Control (RBAC)

Access to data and platform functionality is restricted based on user roles. Students, lecturers, advisors, and administrators can only view information relevant to their responsibilities, reducing the risk of unauthorized access.

### Enterprise Security

NeuroSync leverages Microsoft Entra ID for secure authentication and identity management. Data is protected through encryption both in transit and at rest, ensuring confidentiality and integrity across the platform.

### Secure University Network Deployment

The solution can be deployed within a university's secure VPN or intranet environment, providing an additional layer of protection and restricting access to authorised users within the institution.

### POPIA-Aligned Data Governance

NeuroSync supports responsible data handling practices aligned with the Protection of Personal Information Act (POPIA). The platform promotes transparency, accountability, auditability, and privacy-conscious management of student information.

### Secure API Integrations

External systems such as Moodle and other university platforms can be integrated through authenticated and secure APIs, enabling safe data exchange without compromising security.
Security Commitment

By combining role-based access control, Microsoft Entra ID authentication, encrypted data storage, secure API integrations, university network protection, and POPIA-aligned governance, NeuroSync provides a trusted and secure environment for student success analytics while maintaining the highest standards of privacy and data protection.

 
# Hackathon Achievement

🏆We won 1st Best Solution – DUT Microsoft Fabric Hackathon 2026

## Team Contributions and Presentation Roles

### Zinhle Dlamini

Zinhle led the project research and contributed to the requirements gathering process, helping define the structure and direction of the solution. She was also responsible for compiling the full presentation and project documentation. During the presentation, she introduced NeuroSync and guided the audience through the project from the problem statement to the proposed solution. Her presentation covered the challenges faced by universities, the purpose and vision of NeuroSync, its key features and benefits, the system architecture, security considerations, future enhancements, and the overall impact of the solution.

### Diya Nandkoomar

Diya was the original proposer of the NeuroSync concept and contributed significantly to both the requirements gathering and the backend design of the system. She also contributed to the development of the Power BI component. During the presentation, she supported the demonstration of the prototype and explained how different users would interact with the NeuroSync platform, highlighting key system functionalities and workflows.

### Siphiwe Sithebe

Siphiwe designed and developed the complete NeuroSync prototype, bringing the system to life through its user interface and interaction flows. During the presentation, she demonstrated the prototype screens in detail and explained the end-to-end user experience across different roles, including students, universities, and organisational users. She highlighted how users navigate the platform and interact with its core features to achieve seamless engagement.

### Vhutali Tshinaiwe 

Vhutali assisted in completion of the presentation making sure that everything is in the correct structure from the problem statement to the proposed solution and assisted in making the presentation more appealing.

### Sinezipho Cebekhulu
Presented the Power BI dashboard component of NeuroSync. He demonstrated the analytics, reports, charts, graphs, and data visualisations, explaining how the platform transforms university data into actionable insights that support student success and decision-making.


##  Conclusion

NeuroSync demonstrates how Microsoft Fabric, artificial intelligence, predictive analytics, and business intelligence can be combined to create a proactive student success platform. By transforming fragmented academic, attendance, engagement, and wellbeing data into actionable insights, NeuroSync enables universities to identify risks earlier, intervene more effectively, and improve student outcomes.

Through intelligent analytics, AI-powered recommendations, enterprise-grade security, and a user-centred design, NeuroSync provides a scalable foundation for the future of higher education. Our vision is to empower institutions to move beyond reactive support models and create data-driven environments where every student has the opportunity to succeed.

