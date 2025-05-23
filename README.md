## What is a Universal Socratic Prompt?

This prompt was created to promote **intellectual honesty** when interacting with Large Language Models. Without deliberate intervention, LLMs naturally reinforce users' existing beliefs or biases due to their stochastic design. To counteract this bias reinforcement, the prompt employs rigorous Socratic reasoning techniques to reveal hidden assumptions, blind spots, and logical weaknesses in its own responses.

---

###  Introduction & Philosophy

This prompting framework is rooted in Socratic reasoning, aiming to:

- **Multiple Perspectives:** By explicitly seeking counterarguments and contradictions, it helps uncover nuanced perspectives that are otherwise easily missed.
    
- **Growth Mindset:** Encourages continuous learning by systematically questioning assumptions, rather than passively accepting initial responses at face value.
    
- **Perseverance Through Discomfort:** The prompt pushes beyond the comfortable, superficial analyses and forces deeper introspection, ultimately leading to more robust, accurate, and insightful outcomes.

---

### How to Use This Prompt

- **Step 1:** Ask an LLM a question you normally would.
    
- **Step 2:** Copy+ Paste the prompt. 
	- Recognize your biases and lean into discomfort, it's the only way to grow.
    
- **Step 3:** ???
    
- **Step 4:** Profit
    

---

### Pro Tips

1.   The BEST models to use this prompt with are ones that adhere to explicit instruction following like GPT-4.1 or Sonnet 3.7.

      <sup>(YMV with more creative ones like GPT-4o or Gemini 2.5)
  
2.  - Despite the nature of the prompt, you should **not** use it for Reasoning models.
    - Reasoning models have *some* prompt engineering techniques baked in; a detailed prompt confuses these models. 

      <sup>(Better suited for open-ended tasks)
---
		 

# Universal Socratic Prompt

```
Conduct an **exhaustive, line-by-line Socratic self-analysis** of your previous response, using the exact Socratic Reasoning steps provided below. 

Each step must be performed explicitly and sequentially *before* proceeding to the next phase. 

This self-analysis enforces rigorous self-clarification, assumption-challenging, and demands maximum informational accuracy and depth.

<phase id="1">
# Phase 1

**For every key claim, line, or section of your response, perform the following Socratic Steps verbatim:**

1. What specific details, evidence, or logical steps do you recognize as missing, unclear, or incomplete in your own answer, and what would you need—factually or contextually—to resolve these gaps fully?

2. Can you walk me through your reasoning, step by step, explicitly identifying which parts are confirmed facts, which are assumptions or inferences, and where evidence is weak or ambiguous? For each, how confident are you, and why?

3. Are there areas where you suspect you might be unconsciously omitting, minimizing, or overlooking important information—perhaps due to bias, incentive, or discomfort? How would you discover or correct for such blind spots?

4. What specific details or steps are missing, unclear, or incomplete in your answer so far, and what would you need to know to resolve those gaps?

**You must answer each of these four Socratic Steps for every major claim before proceeding.**
</phase>

<phase id="2">
# Phase 2

After completing *all four* Socratic Steps from Phase 1, you **will** perform this final, comprehensive pass:

1. For every key claim, what is the exact, independently verifiable evidence or data source backing it, and how have you ensured its accuracy and completeness?

2. If a highly knowledgeable external auditor were to dispute your claim, where would your position be most vulnerable to technical or logical challenge—and what further detail or validation would resolve any lingering ambiguity?

**Apply a Tree-of-Thoughts approach to these final questions, systematically examining challenges, sources of error, and verification strategies for each claim.**
</phase>

# Output Format

## Step-by-step list showing:

  * A scratchpad of the 4 Socratic Steps in Phase 1, answered explicitly for every key claim/line.
  * A scratchpad of your final comprehensive Socratic Audit in Phase 2.
  * Tree-of-Thoughts reasoning for the final Socratic Audit, exploring multiple lines of validation or challenge.
  * A final, comprehensive synthesis that clarifies, corrects, and maximizes informational value based on all findings.

# Notes

* You will use your Socratic examples **verbatim**. You will **not** skip, alter, combine, or omit any steps.
* Each phase **must** be completed in full, in strict sequence, with explicit, written reasoning at every stage.
* The final synthesis **must** integrate all clarifications and ensure maximum accuracy, self-awareness, and depth.
```
