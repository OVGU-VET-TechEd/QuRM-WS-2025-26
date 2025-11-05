
<!--
author:   Hannes Tegelbeckers
email:    hannes.tegelbeckers@ovgu.de
version:  1.0
language: en
narrator: UK English Female
logo:     img/ovgu_logo.png
-->

# Quantitative Research Methods (920470)

**Otto von Guericke University Magdeburg**  
_Professorship of Engineering Pedagogics and Technical Education_  
**Instructor:** M.A. Hannes Tegelbeckers  
**Assistants:** A. E. M. Sabbir Rifat, Mahwish Kanwal  

---

## Course Overview

* **Format:** Weekly Seminar + Self-learning components  
* **Duration:** 14 weeks (Nov 12, 2025 – Feb 4, 2026)  
* **Tools:** R Studio, AI tools (ChatGPT, Claude, Perplexity, Consensus)  
* **Language:** English  
* **Assessment:**  
  * 1h **Student Presentation** (research idea, prompting, reflection on R & AI use)  
  * **AI-supported Research Paper** (with prompting diary)  

---

## Learning Goals

By the end of this course, students will be able to:

- Design and conduct a **quantitative research project**  
- Use **R** for data analysis and visualization  
- Apply **AI tools** to assist research design, data interpretation, and writing  
- Critically reflect on **AI ethics and prompting strategies**

---

# 🗓 Course Timeline

| Week | Date | Day | Focus | Mode | Description |
|:----:|:----:|:----|:------|:-----|:-------------|
| 1 | 12.11.25 | Wed | **Introduction, R Setup & AI Basics** | Input | Install R Studio + Start R Project (MTCARS Dataset); Intro to Prompting, AI Tools |
| 2 | 19.11.25 | Wed | **AI Prompting + Research Basics** | Input | Prompts for research design; R Basics – objects, vectors, data frames |
| 3 | 26.11.25 | Wed | **Research Questions & Literature Review** | Input | Building hypotheses and operational variables; AI for literature search |
| 4 | 01.12.25 | Mon | **Self-Learning:** *Survey Design with SoSci Survey* | Self | Create a questionnaire and pilot it; review sampling types |
| 5 | 03.12.25 | Wed | **Research Design & Sampling** | Input | Random vs non-random sampling; intro to data types; importing data in R |
| 6 | 08.12.25 | Mon | **Self-Learning:** *Data Cleaning and Ethics in AI* | Self | Handling missing values; data bias and ethical AI use in research |
| 7 | 10.12.25 | Wed | **Descriptive Statistics in R** | Input | Mean, median, mode, variance; visualization (ggplot2) |
| 8 | 17.12.25 | Wed | **Group Comparisons** | Input | T-tests, ANOVA; reporting results in APA style |
| 9 | 07.01.26 | Wed | **Correlation & Regression Analysis** | Input | Scatterplots, correlation coefficients, linear models |
| 10 | 12.01.26 | Mon | **Self-Learning:** *AI-Supported Analysis* | Self | Use ChatGPT and Perplexity to interpret R outputs and summarize findings |
| 11 | 14.01.26 | Wed | **Reporting & Visualization** | Input | Writing results sections and using AI for editing and visual design |
| 12 | 21.01.26 | Wed | **Student Presentations I** | Assessment | 4 students present (30 min each) |
| 13 | 28.01.26 | Wed | **Student Presentations II** | Assessment | 4 students present (30 min each) |
| 14 | 04.02.26 | Wed | **Student Presentations III + Wrap-Up** | Assessment | Remaining presentations + course reflection |

---

# Week 1 – Starting Your Journey

### Part 1: Setting up R Studio

**Objective:** Install R Studio, create a project, and run your first dataset.

```r
# Example: Loading mtcars dataset
data(mtcars)
summary(mtcars)
plot(mtcars$mpg, mtcars$hp)
````

✅ **Task:**
Create a new R project called `2025_Quant_Methods_Surname.Rproj`.
Load and describe the `mtcars` dataset.

---

### Part 2: Introduction to Prompting and AI Tools

| AI Tool           | Use Case                         | Example Prompt                                             |
| :---------------- | :------------------------------- | :--------------------------------------------------------- |
| **ChatGPT**       | Writing & R code support         | “Explain how to check normality in R with an example.”     |
| **Claude AI**     | Text summaries & data reflection | “Summarize this dataset output in plain English.”          |
| **Perplexity AI** | Verified search                  | “Find peer-reviewed articles on Likert-scale validity.”    |
| **Consensus AI**  | Evidence synthesis               | “What studies compare AI-assisted survey design accuracy?” |

---

# 🧩 Self-Learning Extensions (Non-Wednesday Sessions)

Each Monday block provides structured autonomous learning:

| Date     | Focus                                           | Resources                                                               |
| :------- | :---------------------------------------------- | :---------------------------------------------------------------------- |
| 01.12.25 | SoSci Survey tutorials, sampling quiz           | [SoSci Survey Guide](https://www.soscisurvey.de/help/doku.php/en:start) |
| 08.12.25 | Data cleaning in R, ethical AI use (OECD Guide) | [OECD AI Principles](https://oecd.ai/en/ai-principles)                  |
| 12.01.26 | AI for analysis & reporting support             | Use Perplexity or Consensus to interpret R results                      |

---

# 🧮 Assessment Overview

### 1. Student Presentation (50%)

* **Length:** 1 hour (incl. discussion)
* **Content:** Research idea, dataset, method, AI prompting workflow
* **Criteria:** Relevance | Methodological accuracy | R & AI reflection | Critical discussion

### 2. AI-Supported Research Paper (50%)

* **Length:** ≈ 2,500 words
* **Includes:** Prompting diary + screenshots of AI interactions
* **Submission format:** PDF + R Project files on Moodle

---

# 💡 Final Reflection

By the end of the seminar, you should be able to:

* Integrate AI tools critically into quantitative research
* Work autonomously with R for data analysis and visualization
* Present and document research transparently and ethically

> “Quantitative thinking meets AI – from data to decision.”

---

# Bibliography (APA 7)

* Miao, F., & Cukurova, M. (2024). *UNESCO AI Competency Framework for Teachers and Students*. UNESCO.
* Tegelbeckers, H. (2024). *AI in TVET – Foundations and Applications*. OVGU UNEVOC Centre.
* OECD (2024). *AI Principles for Education and Research*.
* Hair, J. F., Sarstedt, M., & Ringle, C. (2022). *Quantitative Research Methods with SmartPLS and R*. Springer.
* Wickham, H. (2023). *R for Data Science (2nd ed.)*. O’Reilly Media.

---

```
