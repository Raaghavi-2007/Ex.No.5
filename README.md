

# EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

# Aim:To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using a problem selected from a student's 3rd-year or final-year project work. 

### AI Tools Required: CHATGPT 

# EXPERIMENT OVERVIEW:

In this experiment, each student/team selects a genuine problem from their ongoing or completed 3rd-year or final-year engineering project.
The same engineering problem is given to an AI system using different prompting techniques. Students then compare the responses based on relevance, accuracy, completeness, clarity, feasibility and usefulness.
The purpose is not simply to obtain an AI-generated answer. Students must analyse how changing the prompting technique changes the quality of the solution.

# EXPERIMENT PROCEDURE:
Step 1 – Select the Engineering Problem
Choose one genuine problem from the student's 3rd-year or final-year project.
Step 2 – Write the Base Prompt
Write a simple prompt describing the engineering problem without using advanced prompting techniques.
Step 3 – Apply Different Prompting Techniques
Rewrite the same problem using at least four different prompting techniques.
For example:
Technique 1 – Straightforward Prompt
Suggest a method to detect crop diseases using computer vision.structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

#**STUDENT SUBMISSION FORMAT**
Each student/team should submit:
Project title and problem statement
Selected engineering scenario
Base prompt
Minimum four improved prompts using different techniques
AI-generated outputs
Comparison/evaluation table
Analysis and observations
Final selected prompting technique
Refined/final prompt
Engineering validation

## Project Title: AI-Based Smart Traffic Management System

## Problem Statement:

Urban traffic congestion causes delays, fuel wastage, and increased pollution. The objective is to design an AI-based traffic management system that can monitor traffic density and dynamically control traffic signals to reduce congestion.

## Step 1: Base Prompt (Naïve Prompt):

## Prompt:

Design an AI-based Smart Traffic Management System.

## AI Output:

The AI suggests using cameras, sensors, and machine learning to monitor traffic and control signals automatically.

## Step 2: Improved Prompts Using Different Techniques:
## Technique 1 – Role Prompting:
## Prompt:

Act as a Traffic Engineering Expert. Design an AI-based Smart Traffic Management System that can monitor vehicle density and adjust traffic signal timings automatically.

## AI Output:

* Traffic cameras and IoT sensors collect data.
* AI model predicts congestion levels.
* Traffic signals are adjusted dynamically.
* Dashboard for monitoring traffic conditions.

## Technique 2 – Context Prompting:
## Prompt:

A metropolitan city experiences severe traffic congestion during peak hours. Design an AI-based Smart Traffic Management System using computer vision and machine learning to optimize traffic flow and reduce waiting time.

## AI Output:

* Vehicle detection using CCTV cameras.
* Traffic density analysis using computer vision.
* ML model predicts traffic patterns.
* Smart signal scheduling reduces congestion.

## Technique 3 – Constraint Prompting:
## Prompt:

Design an AI-based Smart Traffic Management System using Python and OpenCV. The solution must be low-cost, scalable, and suitable for deployment at city intersections with limited hardware resources.

## AI Output:

* OpenCV-based vehicle counting.
* Lightweight ML algorithms.
* Raspberry Pi deployment.
* Cloud-based monitoring platform.

## Technique 4 – Chain of Thought Prompting:
## Prompt:

Design an AI-based Smart Traffic Management System. Think step-by-step:
1. Identify requirements.
2. Design system architecture.
3. Select algorithms.
4. Create flowchart.
5. Generate Python implementation.
6. Suggest testing procedures.

## AI Output:
* Detailed requirement analysis.
* Layered architecture.
* Traffic density prediction algorithm.
* Flowchart representation.
* Python code structure.
* Testing and validation plan.

## Prompt Chaining Demonstration:
## Prompt 1 – Problem Identification:

What are the major challenges in urban traffic management?

## Output:
Traffic congestion, signal inefficiency, accidents, and fuel wastage.

↓

## Prompt 2 – Requirement Analysis:

Based on these challenges, list functional and non-functional requirements for a Smart Traffic Management System.

## Output:
Traffic monitoring, density analysis, adaptive signal control, scalability, reliability.

↓

## Prompt 3 – System Architecture:

Design the architecture for the proposed system.

## Output:
Camera → Processing Unit → AI Model → Traffic Controller → Dashboard.

↓

## Prompt 4 – Algorithm Design:

Develop an algorithm for adaptive traffic signal control.

## Output:
Vehicle detection → Density calculation → Signal timing adjustment.

↓

## Prompt 5 – Flowchart:

Create a flowchart for the algorithm.

## Output:
Start → Capture Image → Count Vehicles → Calculate Density → Adjust Signal → Repeat.

↓

## Prompt 6 – Python Code:

Generate Python code using OpenCV for vehicle counting.

## Output:
Python implementation using OpenCV and image processing.

↓

## Prompt 7 – Testing:

Suggest testing methods for the system.

## Output:
Unit Testing, Integration Testing, Performance Testing, Accuracy Testing.

↓

## Prompt 8 – Documentation:

Generate project documentation for the system.

## Output:
Complete project report with objectives, methodology, results, and future enhancements.

## Comparison Table:

| Prompting Technique        | Relevance (5) | Accuracy (5) | Completeness (5) | Clarity (5) | Total (20) |
| -------------------------- | ------------- | ------------ | ---------------- | ----------- | ---------- |
| Base Prompt                | 3             | 3            | 2                | 3           | 11         |
| Role Prompting             | 4             | 4            | 4                | 4           | 16         |
| Context Prompting          | 4             | 5            | 4                | 4           | 17         |
| Constraint Prompting       | 4             | 4            | 5                | 4           | 17         |
| Chain of Thought Prompting | 5             | 5            | 5                | 5           | 20         |

## Analysis and Observations:

1. The naïve prompt generated only a general solution with limited details.
2. Role prompting improved domain-specific recommendations.
3. Context prompting provided a more realistic and practical solution.
4. Constraint prompting generated an implementable and cost-effective design.
5. Chain-of-Thought prompting produced the most detailed and structured output.
6. Prompt clarity significantly improved response quality, accuracy, and depth.
7. Well-structured prompts consistently produced better engineering solutions than naïve prompts.

## Final Selected Prompting Technique:

## Chain of Thought Prompting:

## Reason:

It breaks the problem into logical steps, resulting in a comprehensive and systematic engineering solution.

## Refined Final Prompt:

Design an AI-Based Smart Traffic Management System. Analyze the problem step-by-step by performing:

1. Requirement Analysis
2. System Architecture Design
3. Algorithm Development
4. Flowchart Creation
5. Python Implementation using OpenCV
6. Testing and Validation
7. Project Documentation

Provide detailed explanations for each stage.

## Engineering Validation:

* Technically feasible using AI, IoT, and Computer Vision.
* Can be implemented using Python, OpenCV, and machine learning libraries.
* Reduces traffic congestion and improves traffic flow.
* Scalable for smart city applications.
* Suitable as a final-year engineering project.
  
**Conclusion:**

This experiment compared different prompting techniques for solving an engineering problem using AI. The results showed that well-structured prompts produce more accurate, detailed, and useful responses than simple prompts. Among all techniques, Chain-of-Thought Prompting gave the best results by providing a step-by-step solution. The experiment highlights the importance of prompt engineering in improving AI-generated outputs for real-world engineering applications.

# RESULT: 
The prompt for the above said problem executed successfully
