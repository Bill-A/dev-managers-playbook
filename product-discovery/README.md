# AI Agents for Product Discovery and Development

In 2025, AI agents have evolved from experimental tools into robust, practical solutions widely adopted across software development teams. This repository demonstrates how advanced multi-agent architectures can significantly enhance the product discovery and development lifecycle, particularly in ideation and collaborative brainstorming activities. AI agents can facilitate streamlined workflows, improved creativity, and more effective team collaboration, empowering software teams to achieve superior outcomes.

## Overview

Onboarding AI agents to support the brainstorming efforts of key software development roles, fostering efficient and creative product discovery and development. Herein we create AI agents to occupy these dev team roles:

- **Product Owner**: Automates extensive market research, trend analysis, and feature ideation, enabling informed decision-making.
- **Development Manager**: Enhances traceability and alignment between business objectives and technical implementation, optimizing architectural decision-making.
- **Scrum Master**: Generates data-driven insights to improve sprint retrospectives, backlog refinement, and overall team collaboration.
- **Developer Agents**: Act as collaborative partners, participating in pair or mob programming sessions, accelerating code development, refining testing practices, optimizing CI/CD pipelines, and maintaining consistent code quality.
- **Solution Architects**: Evaluates the feasibility of product ideas, suggesting technical architectures, and validating that the proposed solution aligns with business needs. Addresses technical challenges throughout the implementation process.

This repository showcases a practical implementation of AI agents utilizing the CrewAI framework.

## Project Structure

```
.
├── README.md
├── requirements.txt
├── setup.sh
├── utils.py
├── briefs
│   ├── Product_Owner_Brief.md          
│   ├── Dev_Manager_Brief.md
│   ├── Scrum_Master_Brief.md
│   └── Software_Developers_Brief.md
├── src
│   ├── config
│   │   ├── agents.yaml
│   │   └── tasks.yaml
│   └── ai_driven_agile_team.py
│   └── ai_driven_agile_team_ollama.py
└── workshop_starter_files
    ├── agents.yaml
    └── tasks.yaml
```

## Repository Structure

- **CrewAI Setup**: Implementation details and configuration for defining roles, skills, and agent interactions.
- **Practical Examples**: Illustrative scenarios and examples demonstrating effective multi-agent collaboration.
  
# License

CC-BY-SA-4.0 (Creative Commons Attribution ShareAlike 4.0)
