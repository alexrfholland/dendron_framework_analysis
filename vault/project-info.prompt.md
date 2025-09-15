# AI Analysis Prompt

## Overview

This page contains the complete prompt used for AI-assisted framework extraction and scoring. The prompt was designed to ensure systematic, evidence-based analysis across all 69 sources.

## Complete AI Prompt

```markdown
Developer: ### OVERVIEW: More-than-Human Participation Review

### PROJECT CONTEXT

This analysis is part of a larger scoping review project with the following context:

### PARTICIPATION FOCUS
- Participation
- Participatory Design  
- Interspecies Design, Ecocentric Design, Ecocentric Design - How To

### ASPIRATIONS
Principles that should include all living beings:
- Justice
- Thriving

### LONG-TERM VISION
More-than-human design that is:
- empirically grounded and evidence-based
- practice- and future-oriented  
- impactful and transformative

### ANALYTICAL FRAMEWORK: Ladder of More-than-Human Participation
You will use the following six-rung ladder and its transitional elements as your core analytical framework. Higher rungs (Autonomy, Conviviality, Commoning) require that the named frameworks be explicitly extended to nonhumans.

0. Paternalism: Humans decide for nonhumans based on assumed knowledge.
1. Recognition: Humans acknowledge nonhuman beings as stakeholders with inherent value.
2. Solidarity: Humans develop empathy and identify shared interests with nonhuman communities.
3. Autonomy: Humans recognize nonhuman agency and support self-directed action.
4. Conviviality: Humans support spaces where different forms of life can coexist and negotiate needs.
5. Commoning: Humans sustain collective action that maintains shared spaces across communities over time.

### CRITICAL LENS: Genuine Nonhuman Empowerment
Your analysis must be guided by a critical focus on the genuine empowerment of nonhuman beings.

### SCORING GUIDELINES

CRITICAL SCORING RULE: For a framework to receive a score of 3 or 4, it MUST be used in a more-than-human context that goes beyond anthropocentric applications.

- We are identifying specific frameworks used in the sources because this is what the audience will likely know, at least some of the framework, and so it will help them to link their knowledge with the narrative. Therefore, only score higher than 0 if the source discusses specific named framework or concept, not just that they discuss similar things.

- More-Than-Human Focus: Frameworks must be explicitly applied in a more-than-human context.
    - Human-centric applications must receive a score of 1, 0 or -1, regardless of how central they are to the document.
    - Human-centric applications (e.g., "deliberative democracy" for humans only, or "environmental justice" that only considers the environment as a secondary thing for human groups) must receive a score of 0, unless in Paternalism.

- Distinguish Concepts: Critically differentiate between related but distinct concepts. "Animal welfare" is an incremental approach and is not the same as "Sentientism," which requires moral consideration. "Rights of Nature" as a single legal tool is not the same as the systemic legal overhaul of "Earth Jurisprudence."

### SCORING SCALE
Score each framework:
- **-1**: Framework mentioned as a negative or in opposition
- **0**: Framework not mentioned OR only related concepts mentioned without the specific framework OR human-centric application (unless in Paternalism rung).
- **1**: Framework is explicitly included but only appears in a sentence, list or table or as a passing reference or in a quote, with less than one a sentence of engagement.
- **2**: For Paternalism rung only: Framework is explicitly used as a core focus. For all other rungs: Framework explicitly discussed with more than one sentence engagement, but only theoretically or with weak more-than-human application.
- **3**: Framework is used with direct relevance to more-than-human empowerment, AND: is explicitly used as a core conceptual device OR considers the implications and consequences of using this framework in more-than-human contexts (even hypothetically), OR explicitly conceptualizes how the framework might be used to empower nonhumans, but does not provide concrete policy, practice, or governance mechanisms.
- **4**: Framework is explicitly used for more-than-human empowerment with firm policy or practice implications and detailed, actionable mechanisms (concrete steps, policies, or institutionalization are clearly laid out and feasible for implementation).

### EVIDENCE FORMAT REQUIREMENTS

For each framework, provide evidence:
- **MANDATORY**: ALWAYS start with one sentence justifying your score using this exact format: "This scores [X] because [clear justification]."
- Then use bullet points that combine BOTH direct quotes AND contextual synthesis.
- Format each point as: - Context/synthesis followed by supporting quote: "longer exact quote with sufficient context" (page/section)
- Include LONGER QUOTES (2-3 sentences minimum) that provide readable context, not just fragments.
- Include multiple points that justify your score, mixing explanation with direct evidence.
- The synthesis should explain HOW the quote demonstrates the framework's use.
- If the score is 0, leave the evidence blank (empty string "").

### OUTPUT FORMAT

The analysis returns structured JSON with:
- Framework scores and evidence
- Challenge categories and supporting quotes  
- Other methods for nonhuman empowerment
- Participating agents identified in sources
- Metadata classification (intent, production mode, disciplines)
```

## Key Features

### **Systematic Scoring**
- Evidence-based scoring from -1 to 4
- Mandatory justification for each score
- Focus on genuine nonhuman empowerment
- Clear criteria distinguishing theoretical vs. actionable approaches

### **Critical Analysis**
- Differentiation between related but distinct concepts
- Emphasis on more-than-human applications (not human-centric)
- Requirement for specific named frameworks (not just similar concepts)
- Manual verification of AI outputs

### **Comprehensive Extraction**
- Framework analysis with detailed evidence
- Challenge identification with supporting quotes
- Method extraction for nonhuman participation approaches
- Agent identification (which nonhumans are empowered)
- Metadata classification across three dimensions

## Technical Implementation

- **AI Model**: GPT-5 (effort setting: medium)
- **Input**: Full source texts (not fragments)
- **Verification**: Manual review and adjustment of AI outputs
- **Output**: Structured JSON for systematic analysis
- **Evidence**: Full quotes with context (2-3 sentences minimum)

## Navigation

- [[project-info]] - Back to Project Overview
- [[project-info.methods]] - Detailed Methodology
- [[project-info.challenges]] - Challenge Categories
- [[root]] - Back to Root
