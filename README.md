
# Overview of MAT496

In this course, we have primarily learned Langgraph. This is helpful tool to build apps which can process unstructured `text`, find information we are looking for, and present the format we choose. Some specific topics we have covered are:

- Prompting
- Structured Output 
- Semantic Search
- Retreaval Augmented Generation (RAG)
- Tool calling LLMs & MCP
- Langgraph: State, Nodes, Graph

We also learned that Langsmith is a nice tool for debugging Langgraph codes.

------

# Capstone Project objective

The objective of this project is to apply advanced concepts from LangGraph—such as state management, memory, multi-agent collaboration, and iterative LLM reasoning—to build an AI-driven system capable of evaluating how closely a resume matches a job description. As a final-year engineering student preparing for placements, this project demonstrates my ability to work with cutting-edge AI frameworks, build end-to-end agentic workflows, and develop solutions that bridge the gap between artificial intelligence and real recruitment challenges.


-------------------------

# Project report Template

## Title: Resume–Job Description Matching Agent

## Overview

The Resume–Job Description Matching Agent is an AI-driven system built using LangGraph, designed to automate and enhance the candidate screening process. Traditional resume evaluation is often time-consuming, subjective, and inconsistent across reviewers. This project aims to address these challenges by leveraging advanced agentic workflows, large language models (LLMs), and embedding-based similarity measures to deliver a consistent, scalable, and intelligent recruitment support tool.

The project applies all core concepts taught in the LangChain – Introduction to LangGraph (Modules 1–4) course. Using a StateGraph, the system maintains structured memory, routes information through multiple evaluator personas, and executes deterministic multi-step workflows. Each evaluator agent—modelled as HR, Technical Reviewer, and Hiring Manager—assesses the candidate from a specific perspective, enabling a holistic and human-like evaluation.

The system combines LLM reasoning, embedding similarity scoring, multi-agent collaboration, and iterative loop-based refinement to generate a detailed match analysis between a resume and job description. By simulating human reasoning patterns while ensuring computational consistency, the agent produces a structured final report highlighting strengths, weaknesses, and fit percentage.

This project demonstrates how modern AI frameworks like LangGraph can be used to build reliable, modular, and explainable agentic systems. As a final-year capstone, it showcases the practical application of cutting-edge AI concepts and reflects readiness for industry roles in AI engineering, software development, and intelligent automation.

## Reason for picking up this project

The primary reason for choosing this project is the growing need for intelligent automation in recruitment, where organizations face high volumes of applications and struggle to manually evaluate resumes with consistency and accuracy. As companies increasingly rely on AI to streamline HR processes, building a Resume–Job Description Matching Agent provides both real-world relevance and technical depth for a final-year engineering capstone(Helpful during the placement season).

This project also aligns closely with current industry trends in agentic AI systems, LLM-based reasoning, and workflow orchestration frameworks like LangGraph. By selecting this project, I aimed to gain hands-on experience with modern AI engineering practices, including multi-agent collaboration, state management, embedding-based similarity, and controlled graph execution—skills that are highly valued in software, AI, and data science roles.

Additionally, the project allowed me to apply all concepts learned in the LangChain Introduction to LangGraph course (Modules 1–4), ensuring that the work is both academically grounded and technically rigorous. It provides an opportunity to demonstrate my ability to design, implement, and optimize an end-to-end AI system that solves a real-world problem through structured reasoning and explainable automation.

Ultimately, I chose this project because it:

- Solves a meaningful, industry-relevant problem
- Demonstrates mastery of cutting-edge AI tools and workflows
- Strengthens my portfolio for placements in AI/ML, software development, and automation
- Combines theoretical understanding with practical engineering implementation
- Provides a solid foundation for building more advanced agentic systems in the future

## Plan

I plan to execute the following steps to complete my project:

[TODO] Step 1: Problem Understanding & Requirement Definition
Identify the core problem in resume–JD matching, define system requirements, and finalize the objectives and scope of the project.

[TODO] Step 2: Study LangGraph Concepts (Modules 1–4)
Review and understand LangGraph topics such as State, Memory, Multi-Agent Collaboration, Graph Execution, and LLM Reasoning to prepare for implementation.

[TODO] Step 3: Design System Architecture
Create a high-level architecture diagram showing the flow of data through the StateGraph, evaluator agents, embedding generator, and aggregator node.

[TODO] Step 4: Set Up Development Environment
Install Python, LangChain, LangGraph, embedding models, and required libraries. Configure the project folder and version control using GitHub.

[TODO] Step 5: Construct the StateGraph
Define the state structure, create nodes, connect START → evaluator → loop → END, and configure routing logic.

[TODO] Step 6: Implement Embedding-Based Similarity Scoring
Convert resume and JD into embeddings, compute cosine similarity, and store results in the state object.

[TODO] Step 7: Build Multi-Persona Evaluator Agents
Create HR, Technical, and Hiring Manager personas that evaluate the resume using LLMs based on specific role prompts.

[TODO] Step 8: Implement Iterative Evaluation Loop
Configure a looping mechanism where evaluation runs repeatedly until similarity or evaluation thresholds are met.

[TODO] Step 9: Create Aggregation Logic
Combine persona evaluations into a final summary, generate a match score, and produce explanation-based output.

[TODO] Step 10: Testing & Debugging
Run multiple resume–JD pairs, validate results, fix logic issues, and ensure the system behaves consistently.

[TODO] Step 11: Documentation & README Preparation
Write explanations, architecture details, LangGraph concepts applied, and final results for academic evaluation.

[TODO] Step 12: Final Report, GitHub Submission & Presentation
Complete the project report, upload the full code to GitHub, and prepare for viva/presentation.

## Conclusion:

I had planned to achieve {this this}. I think I have/have-not achieved the conclusion satisfactorily. The reason for your satisfaction/unsatisfaction.

----------

# Added instructions:

- This is a `solo assignment`. Each of you will work alone. You are free to talk, discuss with chatgpt, but you are responsible for what you submit. Some students may be called for viva. You should be able to each and every line of work submitted by you.

- `commit` History maintenance.
  - Fork this respository and build on top of that.
  - For every step in your plan, there has to be a commit.
  - Change [TODO] to [DONE] in the plan, before you commit after that step. 
  - The commit history should show decent amount of work spread into minimum two dates. 
  - **All the commits done in one day will be rejected**. Even if you are capable of doing the whole thing in one day, refine it in two days.  
 
 - Deadline: Nov 30, Sunday 11:59 pm


# Grading: total 25 marks

- Coverage of most of topics in this class: 20
- Creativity: 5
  
