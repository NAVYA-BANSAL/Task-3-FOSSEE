# Task-3 FOSSEE
This is Task-3 submitted by Navya Bansal(22BCE10225) from VIT Bhopal University.

I will examine freely available AI models capable of reading and comprehending Python code. My focus will be on models like **CodeT5** and **CodeBERT**, which are designed for code analysis. I will check how well those models are able to examine student-composed Python code, highlight errors, and generate guiding questions(prompts) that encourage students to think more abstractly rather than simply providing the correct answers. The main idea is to see if these models can connect the code with useful learning feedback. 

To test this, I would run the chosen model on small examples of Python code. I would then verify whether the outputs are relevant by looking at two questions:  1. does the mdoel's feedback or prompt correctly reflect what student tried to do, and 2. does it encourage student to reason further? I would also ask teachers or experienced learners to rate how useful the model's prompts are. This way, I can judge whether the model is suitable for supporting student learning. 

**REASONING:**

**1. What makes a model suitable for competence analysis?**
- It should understand both code and natural language.
- It must explain or ask questions about the student's code effectively.

**2. How would you test whether a model generates meaningful prompts?**
- By asking teachers and experienced learners to rate them
- By observing if prompts guide the student instead of giving away the solution.

**3. Trade-offs that might exist between accuracy, interpretability, and cost**
- Bigger models are more accurate but expensive to run.
- Simple to interpret feedback is more helpful for learning, even if it is not as detailed.

**4. Why CodeT5? Strengths & Limitations**
- **Strengths:** Designed for code tasks, free to use, and good at turning code into natural language(summaries or prompts).
- **Limitations:** Not as powerful as large and expensive models, and may need fine-tuning on educational data to give best results.
