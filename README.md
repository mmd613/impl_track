# TRAILS Tier 2 Program Implementor Tracking
The following code was used for the weekly upkeep of a cross-functional dashboard that tracked the implementation progress of student mental health providers. 
## Background
In 2022, TRAILS received funding from the IES to study the impacts of their Tier 2 program in the Detroit Public School system (DPSCD). TRAILS Tier 2 is a program that trains school mental health providers (SMHP) to deliver CBT and Mindfulness skills to children in hopes of reducing symptoms of anxiety and depression. As Evaluation Manager, I oversaw the IES evaluation in collaboration with the Youth Policy Lab at UM and our external evaluators. I managed evaluation timelines, fidelity protocols, and stakeholder coordination across TRAILS, DPSCD, and YPL. 
## Problem
Before my time at TRAILS, cross-collaboration was hindered by misaligned study priorities, communication breakdowns, and unclear roadmaps to implementation. One of the main issues was that the team lacked access to current and actionable data on program implementation. To provide the correct support at the right time, the team needed to understand how many providers were being trained, their fidelity to our program, their ability to see/not see students, and any barriers they might face during program delivery.
## Solution
In the face of friction between YPL and TRAILS (e.g., late data asks, unclear agenda additions), I created new documentation processes and products that helped the team quickly access relevant data and understand limitations. One of these products was the progress dashboard on the delivery of Tier 2 programming. These dashboards tracked 5 key metrics or KPIs:

1. No. of SMHPs trained
2. No. of CBT&M components delivered
3. No. of student sessions held
4. Barriers to implementation 
5. Survey response rates

Generated every week, this program is shared internally with the program and implementation teams and externally with YPL and DPSCD.

## Method
Student mental health providers had a total of four surveys and a weekly log to complete each semester. Using the QualtRics package in R, I pulled data directly from Qualtrics. I filtered out non-participating SMHPs and cleaned and threaded together data for our 116 IES SMHPs. Data had to be manually and closely combed through to check for user errors, duplicates or re-dos, and any inconsistencies. 

## Product
I created a dashboard in Excel with the abovementioned KPIs, which our external partners and TRAILS had access to. These dashboards were crucial for the coordination between TRAILS and DPSCD when reaching out to clinical coaches and program implementers. I worked closely with the implementation team to create detailed dossier-like documents on each SMHP to track their training and delivery progress. DPSCD was especially appreciative of this targeted approach that allowed us to provide quick and accessible solutions to providers. The dashboard also gave YPL reassurance that the necessary data for our impact analysis. 

Not included here: I generated mid-term and end-of-term reports for DPSCD. Created in the middle of the semester, the mid-term reports were comprised of a PowerPoint presentation with delivery rates and trends, as well as engagement drops and barriers to implementation. These mid-term reports were especially helpful. For example, my analysis of trends revealed that SMHPs who attended coaching sessions were more likely to complete weekly logs and deliver components. To solve issues with program delivery, I held brainstorming sessions with DPSCD to design simple and actionable solutions, like low-lift communication strategies, creation of physical products for ease of use and access, and targeted outreach to building administration. 

## Result
The reports I created for implementation tracking were a pivotal point in our IES study. With this data, we were able to come to decisions more quickly and with greater confidence in our support to implementers. The creation of weekly dashboards and quarterly reviews generated a 20% improvement in partner feedback on clarity and timeliness of reports (based on informal feedback, e.g., "very helpful," " finally felt heard,"etc.). In turn, the reduction in lag time and misscomunication miscommunication incidents between TRAILS and DPSCD fell by ~50% between 2023 and 2025, as inferred from fewer escalations or breakdowns logged in meeting notes.
