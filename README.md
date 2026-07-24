# 🌍 TravelGenie-AI
### ✈️ An Intelligent Multi-Agent AI Travel Planning Assistant

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Groq](https://img.shields.io/badge/LLM-Groq-orange)
![Llama](https://img.shields.io/badge/Model-Llama%203.3%2070B-green)
![Gradio](https://img.shields.io/badge/UI-Gradio-red)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

---

## 📖 Overview

**TravelGenie-AI** is an intelligent **Multi-Agent AI Travel Planning Assistant** that automates the complete travel planning process using multiple AI agents.

Instead of relying on a single AI model, TravelGenie-AI divides the planning process into specialized AI agents. Each agent performs one dedicated task and communicates with the next agent to produce an accurate, personalized, and well-organized travel plan.

The system is powered by **Groq LLM (Llama 3.3 70B)** and provides a user-friendly interface using **Gradio**.

---

# Objectives

TravelGenie-AI helps users by:

- Planning complete trips automatically
- Researching destinations
- Estimating travel budgets
- Creating detailed itineraries
- Reviewing travel plans
- Delivering personalized recommendations

---

# Features

- 🤖 Multi-Agent AI Architecture
- 🌍 Destination Research
- 💰 Budget Planning
- 📅 Day-wise Itinerary Generator
- ⭐ Travel Plan Reviewer
- 🧠 Shared Memory Between Agents
- ⚡ Powered by Groq LLM
- 💬 Gradio Chat Interface
- 📌 Personalized Recommendations
- 📱 Simple & Interactive UI

---

# 🏗 Multi-Agent Architecture

The system consists of **five specialized AI agents** that collaborate to create an optimized travel plan.

```
                User
                  │
                  ▼
         Planner Agent
                  │
                  ▼
        Research Agent
                  │
                  ▼
          Budget Agent
                  │
                  ▼
        Itinerary Agent
                  │
                  ▼
         Reviewer Agent
                  │
                  ▼
           Final Travel Plan
```

---

# 🤖 AI Agents

---

# 1️⃣ Planner Agent

## Purpose

Acts as the starting point of the travel planning workflow.

## Responsibilities

- Understands user travel request
- Identifies destination
- Understands travel duration
- Understands user preferences
- Creates an initial travel plan

## Input

- User Travel Request

## Output

- Travel Execution Plan

## Communicates With

➡ Research Agent

---

# 2️⃣ Research Agent

## Purpose

Collects all destination-related information.

## Responsibilities

- Tourist attractions
- Hotels
- Restaurants
- Transportation
- Local food
- Weather information
- Travel tips
- Best visiting time

## Input

- User Request
- Planner Output

## Output

- Destination Research Report

## Communicates With

➡ Budget Agent

---

# 3️⃣ Budget Agent

## Purpose

Calculates the complete estimated travel cost.

## Responsibilities

- Transport cost
- Hotel expenses
- Food expenses
- Local transportation
- Sightseeing
- Miscellaneous expenses

## Input

- User Request
- Research Report

## Output

- Budget Estimation Report

## Communicates With

➡ Itinerary Agent

---

# 4️⃣ Itinerary Agent

## Purpose

Creates a detailed travel schedule.

## Responsibilities

- Day-wise planning
- Places to visit
- Time schedule
- Hotel recommendations
- Restaurant suggestions
- Activity planning

## Input

- User Request
- Research Report
- Budget Report

## Output

- Complete Day-wise Itinerary

## Communicates With

➡ Reviewer Agent

---

# 5️⃣ Reviewer Agent

## Purpose

Performs quality assurance of the travel plan.

## Responsibilities

- Reviews itinerary
- Checks feasibility
- Finds missing information
- Suggests improvements
- Verifies budget
- Ensures plan consistency

## Input

- Planner Output
- Research Report
- Budget Report
- Itinerary

## Output

- Final Reviewed Travel Plan
- Recommendations

---

# 🔄 Agent Communication Flow

```
User
 │
 ▼
Planner Agent
 │
 ▼
Research Agent
 │
 ▼
Budget Agent
 │
 ▼
Itinerary Agent
 │
 ▼
Reviewer Agent
 │
 ▼
Final Travel Plan
```

---

# 📊 Agent Communication Matrix

| From Agent | To Agent | Information Shared |
|------------|----------|--------------------|
| User | Planner Agent | Travel Request |
| Planner Agent | Research Agent | Travel Plan |
| Research Agent | Budget Agent | Destination Research |
| Budget Agent | Itinerary Agent | Budget Estimation |
| Itinerary Agent | Reviewer Agent | Complete Itinerary |
| Reviewer Agent | User | Final Travel Plan |

---

# 🧠 Shared Memory

TravelGenie-AI uses **Shared Memory** to enable seamless collaboration between agents.

### Shared Memory Stores

- User preferences
- Destination
- Travel dates
- Budget
- Research information
- Hotel choices
- Transportation
- Itinerary
- Recommendations

### Benefits

- No repeated questions
- Consistent responses
- Faster execution
- Better collaboration
- Improved personalization

---

# ⚙️ Workflow

### Step 1

User submits travel request.

↓

### Step 2

Planner Agent analyzes requirements.

↓

### Step 3

Research Agent gathers destination information.

↓

### Step 4

Budget Agent estimates expenses.

↓

### Step 5

Itinerary Agent prepares a day-wise travel schedule.

↓

### Step 6

Reviewer Agent validates and improves the travel plan.

↓

### Step 7

Final travel itinerary is delivered to the user.


# 💬 Example User Request

```
Plan a 5-day family trip to Ooty with a budget of ₹30,000.
```

---

# 📤 Example Output

✔ Destination Research

✔ Budget Estimation

✔ Hotel Recommendations

✔ Tourist Attractions

✔ Transportation Plan

✔ Restaurant Suggestions

✔ Day-wise Itinerary

✔ Travel Tips

✔ Final Reviewed Travel Plan

---

# 🛠 Technologies Used

- Python
- Groq API
- Llama 3.3 70B
- Gradio
- Multi-Agent AI
- Prompt Engineering
- Shared Memory

---

# 🌟 Advantages

- Saves travel planning time
- Personalized recommendations
- Optimized travel budget
- Reliable destination research
- Well-organized itineraries
- Expert travel plan review
- Easily scalable architecture
- Easy to extend with additional AI agents

---

# 🎯 Use Cases

- 👨‍👩‍👧 Family Trips
- 🧍 Solo Travel
- 💕 Honeymoon Planning
- 👥 Group Tours
- 🏖 Weekend Getaways
- 💼 Business Travel


---

# 👨‍💻 Developed by

**R. Sugumar, M.B.A.,**
📧 **Email:** contact.sugumarai@gmail.com

