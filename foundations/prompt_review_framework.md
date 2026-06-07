# Prompt Review Framework

## Purpose

Use this framework to assess the quality of prompts before deployment or evaluation. Well-designed prompts improve response accuracy, reduce ambiguity, and increase output consistency.

---

## Prompt Assessment Criteria

### Task Definition

* Is the objective clearly stated?
* Can the model easily determine what is being requested?
* Are expected actions explicitly described?

---

### Audience Specification

* Is the intended audience identified?
* Is the required knowledge level clear?
* Is the response tailored to the audience's needs?

---

### Output Requirements

* Is the desired response format specified?
* Are structure requirements included (e.g., JSON, table, checklist, report)?
* Are length expectations defined?

---

### Context and Constraints

* Is sufficient background information provided?
* Are limitations or boundaries clearly stated?
* Does the prompt include any mandatory requirements?

---

### Safety and Reliability

* Are safety considerations addressed when appropriate?
* Does the prompt discourage unsupported assumptions?
* Are hallucination risks minimized through clear instructions?

---

### Communication Quality

* Is the preferred tone specified?
* Is the wording unambiguous?
* Can different evaluators interpret the prompt consistently?

---

### Evaluation Readiness

* Can the output be measured against objective criteria?
* Are success conditions clearly defined?
* Is the prompt suitable for comparison across multiple AI systems?

---

# Prompt Enhancement Example

## Initial Version

> Explain ventilators.

### Potential Issues

* Audience is not specified
* Scope is unclear
* No structure requirements
* No guidance on complexity level

---

## Refined Version

Assume the role of a nursing educator.

Explain mechanical ventilation to a first-year nursing student.

Your explanation should include:

* Definition of mechanical ventilation
* Common clinical indications
* Basic risks and complications
* Key monitoring responsibilities

Additional Requirements:

* Use simple language
* Organize information with clear headings
* Avoid unnecessary medical jargon

---

## Key Improvements

* Defined audience
* Clear objective
* Structured output requirements
* Appropriate complexity level
* Improved evaluation consistency
