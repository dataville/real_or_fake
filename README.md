# ESA DataX AI Security Challenge
Fake or Real: The Impostor Hunt in Texts Kaggle Competition

## 📜 Description

ESA’s European Space Operations Centre initiated a project to outline a clear direction for data strategy and AI implementation in mission operations. This initiative led to the creation of the **DataX** strategy, developed to improve the scalability of advanced analytics applications, including AI systems, and to increase the value of data within the organization.

One of the key elements of developing an AI system is the security of AI applications. This is addressed within the *Assurance for Space Domain AI Applications* project and its *Catalogue of Security Risks for AI Applications in Space*.

This competition is based on two real-life AI security threats identified within the project: **data poisoning** and **overreliance for text data**.

---

## 🛰️ Story

A company uses large language models (LLMs) to perform operations such as summarization on its official documents. The history of which model, with which settings, processed which document is not strictly tracked.

It was discovered that sometimes the models malfunction and provide harmful output (hallucinations or hidden triggers changing the facts in documents). The root cause is unknown, but the critical task is **detection**: identifying which text is correct (real) and which has been altered (fake).

Recently, a small dataset of documents was found where both real and fake versions are available. For some, the real/fake label has been identified. The task is to continue this work and build an algorithm that distinguishes real from fake documents.

---

## 🎯 Task

* You are provided with **document pairs**.
* In each pair:

  * One text is **real** (closest to the original hidden text).
  * One text is **fake** (altered by an LLM).
* The order is randomized, so you must determine which is which.

The documents:

* Cover topics related to space projects, research, devices, workshops, and people in science and engineering.
* Are all in English.
* Have been significantly modified using LLMs.

Not all modification types may appear in the public test sets. Therefore, **manual or rule-based solutions may not generalize well**.

---

## 📂 Data

* Documents are grouped into folders, each containing a pair:

  * `file_1.txt`
  * `file_2.txt`
* One file is real, one is fake.
* Labels (when available) indicate which file is real.

Details about the dataset structure and usage can be found in the competition’s **Data tab**.

