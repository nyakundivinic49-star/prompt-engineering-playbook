# Foundational Prompt Design Methods

## Overview

This document outlines several core prompting strategies used to guide Large Language Models toward clearer, more accurate, and better-structured responses.

---

# 1. Direct Task Prompting

Direct task prompting asks the model to complete a request without providing examples.

### Description

This method is useful when the task is straightforward and does not require a specific pattern to be learned from examples.

### Example

> Explain the pathophysiology of septic shock using simple, beginner-friendly language.

---

# 2. Example-Guided Prompting

Example-guided prompting provides one or more sample question-and-answer pairs before asking the model to complete a similar task.

### Description

This approach helps the model understand the expected style, level of detail, and response format.

### Example

**Question:**

What is hypertension?

**Answer:**

Hypertension is a condition where blood pressure remains consistently higher than normal.

**Question:**

What is sepsis?

**Answer:**

[Model completes the response]

---

# 3. Role-Based Prompting

Role-based prompting assigns the model a specific perspective or professional identity before the task.

### Description

This technique helps shape tone, expertise level, and response focus.

### Example

> Act as an experienced intensive care nurse. Explain the early clinical indicators of septic shock.

---

# 4. Stepwise Reasoning Prompting

Stepwise reasoning prompting asks the model to analyze information in an organized sequence before reaching a final answer.

### Description

This is useful for complex tasks that require evaluation, prioritization, or decision-making.

### Example

> Review this clinical case step by step, identify the key concerns, and then provide a final recommendation.

---

# 5. Format-Constrained Prompting

Format-constrained prompting requires the model to answer using a predefined structure.

### Description

This improves consistency and makes outputs easier to review, compare, or reuse.

### Example

Return your answer using the following format:

```text
Clinical Impression:
Risk Factors:
Recommended Actions:
Safety Notes:
```

---

# Practical Uses

These techniques can support:

* Healthcare education prompts
* Clinical reasoning workflows
* AI response evaluation
* Structured output generation
* Prompt optimization experiments
