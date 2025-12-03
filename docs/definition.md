# Minimum Viable Clarity (MVC) — Formal Definition (v1.0)

## 1. Definition
**Minimum Viable Clarity (MVC)** is the smallest sufficient amount of intent, context, and boundary clarity required for a human team and an AI system to collaborate without misunderstanding.

When MVC is satisfied:
- AI produces consistent, interpretable, and aligned output.

When MVC is violated:
- AI produces confident but incorrect or misaligned results.

## 2. Core Components

### 2.1 Intent
A one-sentence, unambiguous description of the desired end-state.  
Defines what should be achieved, not how.

### 2.2 Context
Background knowledge the AI cannot infer:
- purpose  
- audience  
- constraints  
- dependencies  
- environment  

### 2.3 Criteria
Clear boundaries and success conditions:
- what “good” looks like  
- what is out of scope  
- formatting rules  
- quality constraints  

### 2.4 Exemplar
A concrete example illustrating expected structure, tone, or quality.  
Functions as the **unit test** for AI alignment.

## 3. Rationale
AI systems interpret patterns, not intentions.  
MVC ensures enough overlap between the user’s mental model and the AI’s operational model to avoid divergence.

## 4. Minimum Requirement Model
**MVC = Intent × Context × Criteria × Exemplar**

If any component is missing → effective clarity collapses toward zero.

## 5. Scope
MVC applies to:
- prompting  
- task delegation  
- AI-assisted engineering workflows  
- multi-agent systems  
- organizational AI-readiness frameworks  

## 6. Version
**Version:** 1.0  
**Author:** László Kiss  
**License:** CC BY 4.0
