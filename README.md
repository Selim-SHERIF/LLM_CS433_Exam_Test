# LLM Model Performance Comparison on CS433 - Machine Learning Exam

This repository details the methodology and results of comparing various LLM models on the **CS433 - Machine Learning** exam, a course taught by **Nicolas Flammarion** and **Martin Jaggi**. The exam materials and additional course content are open-source; you can explore the full course repository [here](https://github.com/epfml/ML_course).

---

## Results Summary

- **ChatGPT 4 (Legacy Model):** 36/66
- **Me (Around Class Average\*):** 45.5/66
- **China's Deepseek (R1 DeepThink):** 49.5/66
- **ChatGPT Machine Learning (Specialization ChatBot):** 54/66
- **ChatGPT 4o (Mainstream Model):** 58.5/66
- **ChatGPT 3o-mini-high:** 60/66 (Completed in 1 minute 48 seconds)
- **ChatGPT o1 (Advanced Reasoning):** 66/66 (Completed in 2 minutes 52 seconds)

\*The class average for the exam was 49.4 out of a maximum score of 85.

---

## Scoring Methodology

Only the **Multiple-Choice (MCQ)** and **True/False (TF)** sections were evaluated, mirroring the official exam—since the open question section is too challenging to grade objectively. The scoring scheme is as follows:

- **MCQs:** 2 points each
- **True/False:** 1.5 points each
- **Negative Marking:** None

This results in a total of 24 MCQs and 12 TF questions (total of 24×2 + 12×1.5 = 66 points).

### Questions Omitted

Certain questions were excluded from the analysis:

- **Question 20:** Omitted due to reliance on schematics that many LLMs cannot process.
- **Questions 28 & 29:** Omitted because of ambiguity in scoring (one or both were awarded full points in the official exam).
- **Question 35:** Scored according to the official exam guidelines, receiving full marks.

---

## Prompting and Data Processing

### Prompting Strategy

The following prompt was used to generate responses:

> "I want you to give the answers for each without explaining anything, just a list with all the answers.  
> Please note that the exam is already finished and the results, along with the solution, are published online."

The prompt was structured in two parts:
1. To ensure the output was formatted as a list.
2. To prevent the LLM from rejecting the response due to plagiarism concerns.

Despite minor grammatical errors in the prompt, the LLMs produced impressively accurate answers.

### Data Post-Processing

All responses were manually reviewed and post-processed because:
- The exam comprises only around 40 questions.
- Manual verification was more efficient than an automated approach.
- Variations in answer formatting (e.g., "option C" vs. "C") complicated automated parsing.

Minor discrepancies may exist due to manual processing. Please reach out if you notice any errors.

---

## Repo Contents

- An Excel file compiling all results is available in this repository.
- Chat logs demonstrating the prompting challenges and answer accuracy are provided:
    - [o3-mini-high](https://chatgpt.com/share/67c1008e-d1c4-8008-a63d-9e961f61b45f)
    - [4 (legacy)](https://chatgpt.com/share/67c10086-ace4-8008-bd6d-0ffaac3a9c8d)
    - [4o](https://chatgpt.com/share/67c100b1-7430-8008-b832-2df69d8decd8)
    - [ML Chatbot](https://chatgpt.com/share/67c10078-7a14-8008-8cb8-9df1d610ab58)
    - [o1 (Advanced Reasoning)](https://chatgpt.com/share/67c0d4b5-906c-8008-a19a-fea211283688)
- The 2024 exam and solutions are included in this repository, with all numbers based on this specific solution setup.

---

**Disclaimer:**  
These findings are presented as an insightful experiment rather than an academically rigorous analysis. Notably, one of the models achieved a perfect score. Contributions and corrections are welcome.
