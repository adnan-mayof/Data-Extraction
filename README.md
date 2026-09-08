# Step 10 — Data Extraction

[← Previous Step: Full-Text Screening](https://github.com/adnan-mayof/Full-Text-Screening/blob/main/README.md)

Maya has completed the risk-of-bias assessment.

After applying the rule specified in her protocol, **111 studies are available for the primary synthesis**.

Now she needs to systematically collect the information required for analysis.

> **Maya:** “I know which studies will contribute to my primary synthesis. What should I do next?”

> **Mentor:** “Now you need to systematically extract the information you will need from those studies.”

> **Maya:** “Can't I just read each paper and write down whatever seems important?”

> **Mentor:** “You could, but that would make the process inconsistent. Instead, create a structured data-extraction form based on your research question, protocol, and analysis plan.”

---

# 1. What Is Data Extraction?

**Data extraction** is the systematic process of collecting relevant information from the studies included in a review.

Maya extracts information using a predefined form.

The information she collects should be connected to:

* The research question
* Eligibility criteria
* Planned analyses
* Effect-size calculations
* Moderator analyses
* Risk-of-bias assessment
* Study characteristics

The goal is to create a structured dataset that can later be used for synthesis and analysis.

---

# 2. Why Use a Data-Extraction Form?

Maya asks:

> **Maya:** “Why do I need a form?”

> **Mentor:** “Because you want to extract comparable information from every study.”

Without a structured form, Maya might:

* Collect different information from different studies
* Forget important variables
* Record information inconsistently
* Make it difficult to reproduce her work
* Have difficulty preparing the dataset for meta-analysis

A structured form helps her follow the same process across studies.

---

# 3. What Should Maya Extract?

The exact information depends on the review question and protocol.

For Maya's review, she may extract information about:

### Study identification

* Study ID
* Author
* Publication year
* Title
* DOI
* Publication type

### Study characteristics

* Study design
* Country
* Educational setting
* Sample size
* Participant characteristics

### Population

* Education level
* Student characteristics
* Prior knowledge or experience
* Other planned population variables

### Intervention

* AI technology
* AI tool or system
* AI function
* AI role
* Duration
* Frequency
* Instructional approach
* How students interacted with the technology

### Comparison

* Control condition
* Traditional instruction
* Alternative technology
* Other comparator

### Outcomes

* Outcome type
* Outcome measure
* Measurement instrument
* Time point
* Descriptive statistics
* Information needed to calculate effect sizes

### Methodological information

* Study design
* Sample allocation
* Analysis approach
* Risk-of-bias judgment

---

# 4. Build the Extraction Form Before Extracting Everything

Maya creates a draft extraction form.

> **Maya:** “Should I start extracting immediately?”

> **Mentor:** “First test your form.”

Maya selects several studies and conducts a **pilot extraction**.

She asks:

* Are all important variables included?
* Are the instructions clear?
* Are the categories consistent?
* Can the required statistics be recorded?
* Are there variables that are difficult to interpret?
* Are there variables she does not actually need?

She then revises the form before extracting all studies.

---

# 5. Maya's Data-Extraction Form

Her initial form contains fields such as:

| Category       | Variable                    |
| -------------- | --------------------------- |
| Identification | Study ID                    |
| Identification | Author                      |
| Identification | Year                        |
| Study          | Study design                |
| Study          | Country                     |
| Population     | Sample size                 |
| Population     | Education level             |
| Population     | Participant characteristics |
| Intervention   | AI technology               |
| Intervention   | AI function                 |
| Intervention   | AI role                     |
| Intervention   | Duration                    |
| Comparison     | Comparator                  |
| Outcome        | Outcome type                |
| Outcome        | Measurement instrument      |
| Outcome        | Time point                  |
| Results        | Mean                        |
| Results        | Standard deviation          |
| Results        | Sample size                 |
| Results        | Effect-size information     |
| Bias           | Risk-of-bias judgment       |

---

# 6. Extract Information From the Full Text

Maya begins with the first study.

She does not rely only on the abstract.

She checks the:

* Methods section
* Participants section
* Intervention description
* Results section
* Tables
* Figures
* Supplementary materials

She records information according to the extraction form.

---

# 7. Example: Extracting One Study

Maya extracts the following information from **Study 001**.

| Variable              | Extracted Information       |
| --------------------- | --------------------------- |
| Study ID              | Study 001                   |
| Year                  | 2024                        |
| Country               | United States               |
| Study design          | Randomized controlled trial |
| Sample size           | 120                         |
| Population            | Undergraduate students      |
| AI technology         | Generative AI chatbot       |
| AI function           | Feedback and explanation    |
| AI role               | Learning support            |
| Intervention duration | 8 weeks                     |
| Comparison            | Traditional instruction     |
| Outcome               | Academic achievement        |
| Measurement           | Course achievement test     |
| Intervention mean     | 82.4                        |
| Intervention SD       | 8.6                         |
| Intervention n        | 60                          |
| Control mean          | 76.8                        |
| Control SD            | 9.1                         |
| Control n             | 60                          |
| Risk of bias          | Low                         |

Maya now has the information needed for later effect-size calculation.

---

# 8. One Study Can Produce Multiple Outcomes

Maya discovers something important.

Study 002 reports several outcomes.

> **Maya:** “This study has achievement, motivation, and knowledge outcomes. Should I treat these as three separate studies?”

> **Mentor:** “No. They are multiple outcomes from the same study.”

A single study may contribute:

* Multiple outcomes
* Multiple time points
* Multiple intervention groups
* Multiple comparison groups
* Multiple effect sizes

Maya therefore needs to preserve the relationship between the observations and the original study.

For example:

```text id="1n2y6j"
Study 002
   ├── Achievement
   ├── Motivation
   └── Knowledge
```

All three remain linked to **Study 002**.

---

# 9. Example: Multiple Outcomes

Maya extracts:

| Study ID  | Outcome     | Time Point | Intervention n | Control n |
| --------- | ----------- | ---------- | -------------: | --------: |
| Study 002 | Achievement | Post-test  |             75 |        74 |
| Study 002 | Motivation  | Post-test  |             75 |        74 |
| Study 002 | Knowledge   | Post-test  |             75 |        74 |

These are **three outcome observations from one study**, not three independent studies.

This distinction becomes especially important during meta-analysis because treating correlated outcomes as independent can affect the analysis.

---

# 10. Extract Variables That Can Explain Differences Between Studies

Maya remembers her research question.

She is not only asking:

> **Does AI improve learning outcomes?**

She also wants to understand:

> **Which characteristics explain variation in the effects?**

Therefore, she extracts variables that may later be used as moderators.

For example:

| Potential Moderator    | Example Categories                    |
| ---------------------- | ------------------------------------- |
| Education level        | Undergraduate / Graduate              |
| AI technology          | Chatbot / ITS / Adaptive learning     |
| AI role                | Tutor / Feedback / Content generation |
| Intervention duration  | Short / Medium / Long                 |
| Subject area           | STEM / Humanities / Language          |
| Learning outcome       | Achievement / Knowledge / Skill       |
| Instructional approach | AI-supported / AI-integrated          |

Maya should only extract moderator variables that are relevant to her protocol and analysis plan.

---

# 11. Do Not Create Categories Without a Plan

Maya notices that studies describe AI roles differently.

One study says:

> “AI tutor”

Another says:

> “AI learning assistant”

Another says:

> “AI feedback system”

> **Maya:** “Can I just create categories while I extract the data?”

> **Mentor:** “You can develop coding rules, but you need to document them and apply them consistently.”

Maya creates a coding guide.

For example:

```text id="q5s1w2"
AI Role

1 = Tutor
2 = Feedback
3 = Content generation
4 = Learning assistant
5 = Other
```

She defines what qualifies for each category.

---

# 12. What If Information Is Missing?

Maya encounters Study 006.

The study reports the sample size but does not report the standard deviation needed for her planned effect-size calculation.

> **Maya:** “The study doesn't report the information I need. Should I leave the field blank?”

> **Mentor:** “Record that the information is missing, and follow the procedure specified in your protocol.”

Maya may need to:

* Check supplementary materials
* Check another report from the same study
* Look for a dissertation or related publication
* Contact the study authors
* Use another reported statistic if appropriate
* Record the information as unavailable

She should **not invent a value**.

---

# 13. Example of Missing Information

Maya records:

| Study ID  | Variable        | Value        | Note              |
| --------- | --------------- | ------------ | ----------------- |
| Study 006 | Intervention SD | Not reported | Checked full text |
| Study 006 | Control SD      | 10.2         | Reported          |
| Study 006 | Sample size     | 84           | Reported          |

Her extraction record might include:

```text id="l1v0pq"
Missing information:
Intervention-group standard deviation

Action:
Checked full text and supplementary materials.

Status:
Not available.
```

This creates an audit trail.

---

# 14. What If Different Reports Describe the Same Study?

Maya finds two publications that appear to come from the same research project.

> **Maya:** “Should I extract them as two studies?”

> **Mentor:** “Not automatically. First determine whether they represent the same underlying study.”

Multiple reports may include:

* Journal article
* Conference paper
* Dissertation
* Follow-up publication
* Secondary analysis

Maya links related reports to the same **Study ID** when they represent the same underlying study.

For example:

```text id="k2h6nq"
Study 021
   ├── Journal article
   ├── Conference paper
   └── Supplementary report
```

This prevents the same participants from being unintentionally counted as independent studies.

---

# 15. Keep Study-Level and Outcome-Level Information Separate

Maya realizes that some information belongs to the study, while other information belongs to a particular outcome.

For example:

### Study-level information

* Study ID
* Country
* Design
* Sample
* AI technology
* Intervention duration

### Outcome-level information

* Outcome
* Measurement instrument
* Time point
* Mean
* Standard deviation
* Effect-size information

A useful structure is:

```text id="0h6y5n"
Study Table
      ↓
Study-level characteristics

Outcome Table
      ↓
Outcome-level results

Both linked by Study ID
```

This structure will make the dataset easier to prepare for meta-analysis.

---

# 16. Example Extraction Results

After Maya pilots her form and begins full extraction, she creates an example dataset.

| Study ID  | Year | Design             | AI Technology               | AI Role            | Outcome     |   n | Risk of Bias  |
| --------- | ---: | ------------------ | --------------------------- | ------------------ | ----------- | --: | ------------- |
| Study 001 | 2024 | RCT                | Generative AI chatbot       | Feedback           | Achievement | 120 | Low           |
| Study 002 | 2023 | RCT                | Intelligent tutoring system | Tutor              | Knowledge   | 149 | Low           |
| Study 003 | 2022 | Quasi-experimental | Adaptive learning           | Learning support   | Achievement |  96 | Some concerns |
| Study 004 | 2021 | RCT                | Chatbot                     | Tutor              | Skill       | 110 | Low           |
| Study 005 | 2024 | Quasi-experimental | Generative AI               | Content generation | Achievement |  88 | Some concerns |
| Study 006 | 2023 | RCT                | Intelligent tutoring system | Feedback           | Knowledge   |  84 | Low           |

This is an **example extraction dataset**.

The actual review would contain the information extracted from the included studies.

---

# 17. What Happens When Data Extraction Produces Multiple Rows?

Maya's dataset eventually contains more rows than studies.

For example:

```text id="m8q6a2"
111 studies
      ↓
Multiple outcomes
      ↓
Multiple time points
      ↓
Multiple effect sizes
      ↓
More than 111 extracted observations
```

This is expected.

The important thing is to maintain the relationship between:

**Study → Outcome → Comparison → Time Point → Effect Size**

Maya therefore creates unique identifiers.

For example:

| Study ID  | Outcome ID  | Outcome     |
| --------- | ----------- | ----------- |
| Study 001 | Study001_O1 | Achievement |
| Study 002 | Study002_O1 | Knowledge   |
| Study 002 | Study002_O2 | Motivation  |
| Study 002 | Study002_O3 | Achievement |

---

# 18. Check the Extracted Data

Maya does not immediately move to analysis.

First, she checks the extraction dataset.

She looks for:

* Missing values
* Impossible values
* Inconsistent coding
* Duplicate study IDs
* Duplicate outcomes
* Incorrect sample sizes
* Inconsistent intervention categories
* Inconsistent outcome labels
* Data-entry errors

She compares the dataset against the original publications.

---

# 19. Example Data-Extraction Quality Check

Maya discovers:

```text id="x9v4sk"
Study 014
Reported sample = 150

Extraction dataset
Sample = 105
```

She returns to the paper.

She discovers that 105 was the intervention-group sample size, while 150 was the total study sample.

She corrects the extraction and documents the distinction.

This illustrates why quality checking is important.

---

# 20. If Multiple Reviewers Extract Data

If multiple reviewers are involved, the protocol should specify how extraction will be conducted.

For example:

```text id="q7p2jx"
Reviewer 1 extracts data
            +
Reviewer 2 verifies data
            ↓
Compare
            ↓
Resolve discrepancies
            ↓
Final extraction dataset
```

If Maya is working alone, she can use a structured checking procedure, such as reviewing a sample of extracted studies or rechecking the dataset against the source articles.

The actual procedure should match the protocol.

---

# 21. Maya's Data-Extraction Workflow

Maya summarizes the process:

```text id="g4v6cw"
Studies Available for Planned Synthesis
                ↓
        Build Extraction Form
                ↓
           Pilot the Form
                ↓
         Revise Coding Rules
                ↓
        Extract Study Data
                ↓
      Extract Outcome Data
                ↓
      Record Missing Information
                ↓
        Quality Check Data
                ↓
       Final Extraction Dataset
```

---

# 22. What Should Maya Save?

Maya organizes her extraction materials.

```text id="j8q3rm"
data-extraction/
├── extraction-form.xlsx
├── coding-guide.md
├── extraction-data.xlsx
├── missing-data-log.md
└── extraction-decisions.md
```

The files document:

* What variables were extracted
* How variables were coded
* What information was missing
* What decisions were made during extraction
* The final dataset used for analysis

---

# ⭐ Important Principle

> **Data extraction should be systematic, structured, and guided by the research question, protocol, and planned analysis. Extract information consistently across studies, preserve the relationship between studies and their outcomes, document missing information and coding decisions, and check the extracted dataset before analysis.**

---

# 🚀 Maya's Journey Continues

Maya looks at her completed extraction dataset.

> **Maya:** “Now I have the study characteristics, intervention information, outcomes, and statistics I need.”

> **Mentor:** “Good. But before you start calculating effect sizes, there is another question.”

> **Maya:** “What question?”

> **Mentor:** “Are these studies and their data appropriate for a meta-analysis?”

Maya realizes that not every systematic review automatically requires a meta-analysis.

> **Next step: Decide Whether Meta-Analysis Is Appropriate.**

---

# Assessment

## Multiple-Choice Questions

### 1. What is data extraction?

A. Searching databases for studies
B. Systematically collecting relevant information from included studies
C. Removing duplicate records
D. Calculating the pooled effect size

### 2. Why should Maya use a structured extraction form?

A. To ensure information is collected consistently
B. To automatically eliminate high-risk studies
C. To replace the protocol
D. To guarantee statistically significant results

### 3. What should Maya do before extracting data from all studies?

A. Begin the meta-analysis
B. Pilot the extraction form and refine it if necessary
C. Remove studies with missing information
D. Change the research question

### 4. A single study reports achievement, motivation, and knowledge. How should Maya handle these?

A. Treat them automatically as three independent studies
B. Delete two outcomes
C. Record the multiple outcomes while maintaining their link to the same study
D. Count the study three times as separate studies

### 5. Why is Study ID important?

A. It links multiple observations or reports to the underlying study
B. It determines the effect size
C. It replaces the DOI
D. It identifies the highest-quality study

### 6. What should Maya do when a required statistic is not reported?

A. Invent an estimate
B. Ignore the missing information
C. Follow the protocol and document the missing information and any actions taken
D. Automatically exclude the study

### 7. Why should Maya extract moderator-related variables?

A. To identify characteristics that may explain variation in effects
B. To replace risk-of-bias assessment
C. To determine which database to search
D. To eliminate the need for effect sizes

### 8. Two publications appear to describe the same underlying study. What should Maya do?

A. Automatically count them as two independent studies
B. Determine whether they represent the same underlying study and link related reports appropriately
C. Delete both publications
D. Use only the newer publication without checking

### 9. Which information is generally outcome-level information?

A. Country
B. Study design
C. Measurement instrument and time point
D. Publication year

### 10. Why should Maya quality-check the extraction dataset?

A. To identify inconsistencies, missing information, and data-entry problems
B. To increase the number of studies
C. To change the eligibility criteria
D. To guarantee a significant meta-analysis

### 11. Maya has 111 studies but 250 extracted outcome observations. Is this necessarily a problem?

A. Yes, there can only be one observation per study
B. No, studies can contribute multiple outcomes, time points, or effect sizes
C. Yes, all studies must have identical outcomes
D. No study should have more than one effect size

### 12. What should guide the variables Maya extracts?

A. Whatever information happens to be easiest to find
B. The research question, protocol, and planned analysis
C. Only the abstract
D. Only the statistically significant results

---

# Answer Key

| Question | Answer |
| -------: | :----: |
|        1 |    B   |
|        2 |    A   |
|        3 |    B   |
|        4 |    C   |
|        5 |    A   |
|        6 |    C   |
|        7 |    A   |
|        8 |    B   |
|        9 |    C   |
|       10 |    A   |
|       11 |    B   |
|       12 |    B   |

---

# Repository Structure

```text id="p6s4nk"
step-11-data-extraction/
│
├── README.md
│
├── data-extraction/
│   ├── extraction-form.xlsx
│   ├── coding-guide.md
│   ├── extraction-data.xlsx
│   ├── missing-data-log.md
│   └── extraction-decisions.md
│
└── assessment/
    └── assessment.md
```

## 🚀 Maya's Journey Continues

Maya has now **completed the Data Extraction Stage**.
The next challenge is to conduct the Risk-of-Bias Assessment.

She is now ready to move to:

### Next Step

### **[Step 9 — Risk-of-Bias Assessment](https://github.com/adnan-mayof/Risk-of-Bias-Assessment/blob/main/README.md)**
