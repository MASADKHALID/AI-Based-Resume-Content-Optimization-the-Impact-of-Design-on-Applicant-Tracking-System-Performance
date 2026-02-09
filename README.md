##📄 AI-Based Resume Content Optimization and ATS Design Impact##

📌 Overview

This repository contains the experimental materials, dataset structure, and analysis workflow for an undergraduate research study titled:

AI-Based Resume Content Optimization and the Impact of Design on Applicant Tracking System Performance

The study experimentally analyzes how resume design and content structure affect Applicant Tracking System (ATS) scores and evaluates whether AI-based resume content optimization can improve ATS performance.

🎯 Research Objectives

The objectives of this study are to:

Analyze how different resume designs influence ATS scores when resume content remains unchanged

Identify which resume sections most strongly affect ATS evaluation

Extract ATS-friendly content and formatting rules based on experimental data

Validate the effectiveness of an AI-optimized resume using multiple ATS tools

🧪 Experimental Design
Resume Versions

H1–H5: Human-created resumes using different templates

H6: Initial AI-generated resume using a basic prompt

H7: Refined AI-generated resume created using dataset-derived optimization rules

All resumes:

Use identical candidate information

Differ only in design, structure, and content presentation

ATS Evaluation

Each resume version was evaluated using multiple online ATS tools with varying levels of strictness. The same ATS tools were used consistently across all resume versions.

Recorded outputs include:

ATS score

Parsing feedback

Missing sections

Design recommendations

Skill detection behavior

📊 Dataset Structure

The dataset was collected in tabular form with the following columns:

Column Name	Description
cv_id	Resume identifier
Resume_Type	Human or AI
Template_Name	Resume template/version
ATS_Tool	ATS platform used
ATS_Score (%)	ATS evaluation score
Quantifying_impact	Detection of measurable experience
Affected_Section	Section flagged by ATS
Parsing_Errors	Low / Medium / High
Missing_details	Missing resume information
Essentials_section	Detection of essential sections
Design_Recommendation	ATS design feedback
skills_detected	Hard skills identified by ATS
📈 Analysis & Visualization

Data analysis was performed using spreadsheet-based tools (Excel). The following results were visualized using tables and bar charts:

Average ATS score per ATS tool

ATS score comparison before vs after AI optimization

Frequency of design recommendations

Essential section sensitivity

Missing details frequency

Impact of quantifiable experience

Figures and tables are referenced in the research paper and submitted as separate files.

🤖 AI Resume Optimization

The AI-generated resume was created in two stages:

Initial version (H6): Generated using a basic AI prompt

Refined version (H7): Generated using a refined prompt informed by empirical ATS feedback

Prompt refinement focused on:

Experience section structure

Strong action verbs

Bullet point length

Proper spacing

Inclusion of quantifiable achievements

The exact prompt text is not included, as reproducibility is ensured through detailed description of applied optimization rules.

📌 Key Findings

Resume design significantly affects ATS scores even when content is unchanged

The experience section is the most ATS-sensitive component

Missing details and weak phrasing negatively impact ATS performance

AI-based optimization guided by real ATS feedback consistently improves ATS scores

📚 References

Background references related to ATS, resume parsing, and AI-based recruitment systems are included in the research paper. All experimental results are based on original data generated in this study.

👤 Author

Muhammad Asad Khalid
Department of Computer Science
University of Karachi
📧 Muhammad.Asad.Khalid@outlook.co

📄 License

This repository is intended for academic and educational purposes only.
