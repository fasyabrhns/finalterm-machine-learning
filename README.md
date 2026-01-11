# Fine-tuning T5 for Question Answering

## 👥 Team Information

**Course:** Deep Learning  
**Institution:** Telkom University  
**Group:** Task 2 (Question Answering)

| Name | NIM |
| :--- | :--- |
| **Fasya Burhanis Syauqi** | 1103223054 |
| **Muhammad Muhammad Farhan** | [ISI NIM DISINI] |

---

## 🎯 Purpose

This repository contains the implementation of **Task 2: Question Answering (QA)**.

The primary objective is to fine-tune the **T5-base (Text-to-Text Transfer Transformer)** model using the **SQuAD (Stanford Question Answering Dataset)**. The model is trained to extract the correct answer span from a given context paragraph based on a specific question.

---

## 🔍 Project Overview

### The Task: Extractive Question Answering
Question Answering is a fundamental NLP task where the model must comprehend a passage of text and answer a query related to it. We approach this as a text-generation problem using a Sequence-to-Sequence (Seq2Seq) architecture.

### The Model: Google T5
* **Architecture:** Encoder-Decoder Transformer.
* **Input Format:** `question: <question> context: <context>`
* **Output Format:** `<answer text>`

### The Dataset: SQuAD
We use the Stanford Question Answering Dataset (SQuAD), which consists of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text.

