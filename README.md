# 📊 SPSS Modeler — Data Mining Playground

<p align="center">

<img src="https://img.shields.io/badge/IBM-SPSS%20Modeler-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM SPSS Modeler"/>

<img src="https://img.shields.io/badge/Data%20Mining-Learning-6C63FF?style=for-the-badge" alt="Data Mining"/>

<img src="https://img.shields.io/badge/Predictive%20Analytics-Exploring-00A67E?style=for-the-badge" alt="Predictive Analytics"/>

<img src="https://img.shields.io/badge/Status-🚧%20Learning-FFA500?style=for-the-badge" alt="Learning"/>

</p>

<p align="center">
  <b>Turning raw data into insights — one node at a time. 🧩📊</b>
</p>

---

## 👋 Welcome to My SPSS Modeler Playground!

This repository contains my **hands-on work, practicals, experiments, datasets, and learning journey with IBM SPSS Modeler**.

The goal is simple:

> **Take messy data → understand it → prepare it → analyze it → build models → learn something useful.**

Or, in student language:

> **Give SPSS the data and ask: "Bhai, isme kuch pattern hai kya?" 😭📊**

Sometimes the answer is surprisingly useful. 😂

---

## 🧠 What is This Repository?

This is my personal collection of work done while learning **IBM SPSS Modeler and Predictive Analytics**.

Here you'll find practical work involving:

* 📥 Data Import
* 🔍 Data Understanding
* 🧪 Data Audit
* 🏷️ Data Type Definition
* 🧹 Data Preparation
* 🔎 Filtering
* ➕ Deriving New Fields
* 🔄 Reclassification
* ✂️ Data Partitioning
* 📊 Exploratory Analysis
* 🤖 Predictive Modeling
* 📈 Model Evaluation
* 🧠 Pattern Discovery
* 📚 Dataset-based Assignments

This repository will continue to grow as I learn and complete more SPSS Modeler work.

---

# 🗺️ Repository Navigation

| Section           | What's Inside                        |
| ----------------- | ------------------------------------ |
| 📂 `datasets/`    | Datasets used for practicals         |
| 📊 `practicals/`  | SPSS Modeler practical work          |
| 🧩 `streams/`     | `.str` / SPSS Modeler stream files   |
| 📸 `screenshots/` | Screenshots of workflows and outputs |
| 📝 `notes/`       | Learning notes and explanations      |
| 📄 `README.md`    | You are here 👀                      |

---

# 🧩 My SPSS Modeler Learning Map

```text
                    📊 SPSS MODELER
                         │
                         ▼
                  📥 Import Data
                         │
                         ▼
                   🔍 Understand
                         │
                         ▼
                    🧪 Data Audit
                         │
                         ▼
                  🏷️ Define Types
                         │
                         ▼
                    🧹 Prepare
                         │
              ┌──────────┼──────────┐
              ▼          ▼          ▼
           Filter      Derive    Reclassify
              │          │          │
              └──────────┼──────────┘
                         ▼
                    ✂️ Partition
                         │
                         ▼
                   📊 Explore Data
                         │
                         ▼
                    🤖 Build Model
                         │
                         ▼
                    📈 Evaluate
                         │
                         ▼
                  💡 Find Insights
```

### The basic philosophy:

> **Don't build a model before understanding your data.**

Because...

```text
Bad Data
   ↓
Fancy Model
   ↓
Fancy Wrong Answer
   ↓
😭
```

---

# 🛠️ Concepts I'm Learning

### 📥 1. Data Import

Learning how to bring datasets into SPSS Modeler and work with different data formats.

---

### 🔍 2. Data Audit

Using the **Data Audit node** to investigate:

* Missing values
* Invalid values
* Data distributions
* Basic statistics
* Field characteristics
* Potential data-quality issues

Basically:

> **Before asking the data a question, first check whether the data is awake. ☕**

---

### 🏷️ 3. Type Node

Understanding and defining the role and measurement level of variables.

Examples:

```text
Field
 ├── Input
 ├── Target
 ├── None
 └── Partition
```

Measurement levels may include:

```text
Nominal
Ordinal
Continuous
```

---

### 🔎 4. Filter Node

Removing unnecessary fields from the dataset.

```text
Too Many Columns
       ↓
     Filter
       ↓
Only Relevant Columns
```

Because sometimes the dataset has **50 columns and only 7 actually matter.** 😭

---

### ➕ 5. Derive Node

Creating new variables from existing variables.

Example:

```text
Age + Income + Spending
          ↓
    Derived Feature
```

This helps transform raw information into useful features for analysis and modeling.

---

### 🔄 6. Reclassify Node

Grouping or transforming existing categories into more meaningful classes.

Example:

```text
Age

18–25  ──────► Young
26–40  ──────► Adult
41+    ──────► Senior
```

---

### ✂️ 7. Partition Node

Splitting data into different subsets for modeling and evaluation.

Typical idea:

```text
                 Dataset
                    │
             ┌──────┴──────┐
             ▼             ▼
          Training        Testing
             │             │
             ▼             ▼
          Learn Model    Evaluate
```

---

# 📚 Practical Work

> This section will grow as I complete more practicals.

<details>
<summary>📌 Practical 01 — Data Import & Initial Exploration</summary>

### 🎯 Objective

Import a dataset into SPSS Modeler and understand its basic structure.

### 🧩 Main Tasks

* Import dataset
* Identify fields
* Understand data types
* Inspect records
* Perform initial exploration

### 🧠 Key Learning

The first step in data mining is not modeling.

It's **understanding what you actually have.**

</details>

---

<details>
<summary>🔍 Practical 02 — Data Audit</summary>

### 🎯 Objective

Perform a detailed audit of the dataset.

### 🧩 Node Used

`Data Audit`

### 🔎 Things Investigated

* Missing values
* Invalid values
* Distribution
* Minimum / maximum values
* Mean
* Standard deviation
* Field characteristics

### 💡 Learning

> **Data quality comes before model quality.**

</details>

---

<details>
<summary>🏷️ Practical 03 — Defining Data Types</summary>

### 🎯 Objective

Define the appropriate field roles and measurement levels.

### 🧩 Node Used

`Type`

### Example

```text
Student_ID     → None
Age            → Input
Study_Hours    → Input
Result         → Target
```

### 💡 Learning

The model needs to know:

> **"Which column am I supposed to predict?"** 🤖

</details>

---

<details>
<summary>🔎 Practical 04 — Filtering Data</summary>

### 🎯 Objective

Remove unnecessary fields and retain only relevant information.

### 🧩 Node Used

`Filter`

### Example

```text
Original Dataset
      ↓
   20 Fields
      ↓
    Filter
      ↓
   12 Fields
```

### 💡 Learning

More columns ≠ automatically better analysis.

Sometimes less is more. 😌

</details>

---

<details>
<summary>➕ Practical 05 — Deriving New Fields</summary>

### 🎯 Objective

Create meaningful new variables from existing data.

### 🧩 Node Used

`Derive`

### Example

```text
Marks Obtained
       +
Total Marks
       ↓
Percentage
```

### 💡 Learning

Feature engineering can turn raw information into something much more useful.

</details>

---

<details>
<summary>🔄 Practical 06 — Reclassifying Data</summary>

### 🎯 Objective

Convert detailed values into meaningful categories.

### 🧩 Node Used

`Reclassify`

### Example

```text
Score
 │
 ├── 0–40    → Low
 ├── 41–70   → Medium
 └── 71–100  → High
```

### 💡 Learning

Sometimes categories make patterns easier to un
