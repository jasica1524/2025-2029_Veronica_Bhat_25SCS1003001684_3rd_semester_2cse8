# Artificial Intelligence & Generative AI Virtual Internship

## Internship Project

This repository contains the work completed during the **Artificial Intelligence & Generative AI Virtual Internship**.

The internship focused on understanding and implementing important concepts of Generative AI, including Prompt Engineering, Structured Output, Retrieval-Augmented Generation (RAG), embeddings, grounding, guardrails, and evaluation.

---

## Student Details

**Name:** Veronica Bhat  
**Course:** B.Tech CSE  
**Batch:** 2025–2029  
**University:** IILM University, Greater Noida  
**School:** School of Computer Science and Engineering  

---

## Internship Objectives

The main objectives of this internship were:

- To understand the fundamentals of Artificial Intelligence and Generative AI.
- To learn how effective prompts can improve AI responses.
- To understand structured outputs and JSON validation.
- To implement Retrieval-Augmented Generation (RAG).
- To create a college information assistant using provided documents.
- To understand embeddings and semantic search.
- To apply grounding and guardrails to AI systems.
- To evaluate the performance of a generative AI system.

---

# Tasks Completed

## Task 01 – Prompt Engineering

The first task focused on understanding **Prompt Engineering**.

Prompt Engineering is the process of designing effective instructions for an AI model to obtain useful, accurate, and consistent responses.

The task covered:

- Writing clear prompts.
- Giving proper instructions to an AI model.
- Specifying the required output.
- Controlling the format and behavior of responses.
- Improving prompts through refinement.

### Key Learning

A well-designed prompt can make AI responses more accurate, relevant, and consistent.

---

## Task 02 – Structured Output

The second task focused on generating structured responses from AI systems.

Structured output allows information to be returned in a predefined format such as JSON.

The task covered:

- JSON-based responses.
- Defining required fields.
- Maintaining a consistent output structure.
- Validating generated JSON.
- Handling malformed or incomplete responses.

### Key Learning

Structured output makes AI responses easier for software applications to process and use.

---

## Task 03 – Retrieval-Augmented Generation (RAG)

The third task focused on implementing a basic **Retrieval-Augmented Generation (RAG)** system.

RAG allows an AI system to retrieve relevant information from external documents before producing an answer.

For this project, a college library rules document was used as the knowledge source.

### Knowledge Base

The document contains information about:

- Library opening hours.
- Maximum number of books students can borrow.
- Book issue duration.
- Late return fines.
- College ID requirements.
- Library holidays.

### RAG Process

The system follows these steps:

1. Load the college information document.
2. Split the document into smaller text chunks.
3. Convert the text chunks into embeddings.
4. Convert the user's question into an embedding.
5. Compare the question embedding with document embeddings.
6. Retrieve the most relevant information.
7. Return the retrieved information as the answer.

### Example

**Question:**

> How many books can a student borrow?

**Answer:**

> Students can borrow up to three books at one time.

### Out-of-Scope Example

If the user asks:

> What is the cafeteria menu?

The system responds that the information could not be found in the provided documents.

This prevents the system from inventing information that is not present in the knowledge base.

---

## Task 04 – College Grounded Assistant

The fourth task involved creating a **College Grounded Assistant**.

The assistant uses the college rules document as its source of information and answers questions using retrieved passages from the document.

### Features

- Document-based question answering.
- Semantic similarity search.
- Source identification.
- Retrieved passage display.
- College-related question filtering.
- Out-of-scope question handling.
- Usage tracking.
- Basic evaluation system.

### Example Questions

**Question:**  
How many books can a student borrow?

**Answer:**  
Students can borrow up to three books at one time.

**Question:**  
What is the library fine?

**Answer:**  
A late return may result in a fine of Rs. 2 per day per book.

**Question:**  
What are the library timings?

**Answer:**  
The college library is open from 8:00 AM to 8:00 PM from Monday to Saturday.

---

## Conclusion

The Artificial Intelligence & Generative AI Virtual Internship provided practical experience in building and evaluating AI-based applications.

The internship tasks helped in understanding how prompts, structured outputs, embeddings, RAG, grounding, and evaluation can be combined to create a simple and reliable AI assistant.

The final College Grounded Assistant demonstrates how an AI system can retrieve information from college documents and provide answers based on the available knowledge while avoiding unsupported information.

## Author

Veronica Bhat
B.Tech CSE | IILM University
Batch: 2025–2029
