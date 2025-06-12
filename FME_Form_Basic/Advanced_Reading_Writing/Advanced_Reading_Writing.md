# 🛠️ Mini Project: Advanced Reading & Writing with FME Form

[![FME Form](https://img.shields.io/badge/FME-Form%202024-orange?logo=fme)](https://www.safe.com/fme/)
[![Course Module](https://img.shields.io/badge/Module-Day%204%20Completed-brightgreen)](https://academy.safe.com/path/fme-form-basic/design-workspaces-for-advanced-reading-and-writing/155975)
[![Skill Focus](https://img.shields.io/badge/Focus-Advanced%20Reading%20%26%20Writing-blue)](#)

This mini project showcases my work on **Day 4** of the [FME Form Basic course](https://academy.safe.com/path/fme-form-basic/design-workspaces-for-advanced-reading-and-writing/155975), where I built a workspace to read multiple feature types, write to multiple destinations, and control writing behavior through writer order and schema mapping. It represents hands-on learning of **advanced reading and writing concepts in FME**.

---

## ✅ What I Did

I completed a guided exercise series that involved:

- Reading multiple feature types from a **GML (Geography Markup Language)** dataset
- Writing outputs to **multiple Excel sheets** and **GML files** using **Feature Type Fanout**
- Organizing the workspace with **multiple writers** and controlling the **writer order**
- Renaming feature types and customizing output using **Writer Parameters**
- Automating schema definitions and attribute mapping
- Using the **Inspector** for output validation

---

## 🔍 Project Workflow Overview

### 🗂️ Input:
- A single GML dataset containing several layers (e.g., Parcels, Roads, Zoning)

### 🔧 Process:
- Fanout by Feature Type to organize outputs
- Rename feature types and apply writer settings per format
- Use Excel and GML writers simultaneously
- Set writer order to ensure dependencies (e.g., Zoning written last)

### 📤 Output:
- One Excel workbook with multiple sheets (Parcels, Roads, Zoning)
- Separate GML files split by feature type

---

## 🧠 Key Learnings

| Concept | What I Learned |
|--------|----------------|
| Feature Type Fanout | Automatically direct features into separate outputs based on type |
| Multiple Writers | Add and manage more than one output format in the same workspace |
| Writer Order | Control the execution order of outputs (important for dependencies) |
| Writer Parameters | Rename output sheets/files dynamically and structure them meaningfully |
| Schema Mapping | Handle mismatches and automate output schema setup |
| Workspace Organization | Maintain readability and performance for complex outputs |

---

## 🎯 Outcome

- Gained confidence in handling **multi-format outputs** in FME
- Understood how to **structure real-world ETL workflows** using multiple writers
- Improved skills in schema automation and writer configuration
- Reinforced best practices for workspace clarity and scalability

---

## 📁 Files in This Repo

- `exercise-set-reader-and-writer-parameters-complete.fmw`: Final workspace
- `Design Workspaces for Advanced Reading and Writing.PNG`: Key screenshot of each stage
- `CommunityMap.gdb.zip`: Dataset files
- `Advanced_Reading_Writing.md`: My summary notes and key takeaways from the exercise

---

> 🧩 This mini-project reflects my commitment to learning FME deeply and applying it to real-world GIS data challenges.
