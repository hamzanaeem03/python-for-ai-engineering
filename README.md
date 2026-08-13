# Python for AI Engineering

A practical, project-based Python roadmap designed to prepare me for Generative AI and AI Engineering.

The purpose of this repository is **not to become an expert Python developer**. The goal is to become comfortable enough with Python and its ecosystem to build AI-powered applications using LLM APIs, embeddings, RAG, agents, vector databases, and production deployment.

---

## 🎯 Final Goal

Complete this roadmap and reach the point where I can confidently start a Generative AI / AI Engineering course covering:

* Large Language Models
* Transformers
* LLM APIs
* Prompt Engineering
* Function Calling
* Embeddings
* Vector Databases
* RAG
* Advanced RAG
* Fine-Tuning
* AI Agents
* Multi-Agent Systems
* LLM Evaluation
* Guardrails
* Production Deployment

---

# 🧭 Learning Philosophy

I already have software development experience, so this is **not a beginner programming curriculum**.

The focus is on:

1. Learning Python syntax and conventions
2. Understanding Python's ecosystem
3. Building practical applications
4. Learning Python tools used in AI
5. Connecting Python concepts directly to AI Engineering
6. Building projects instead of only watching tutorials

The objective is:

```text
Learn → Practice → Build → Review → Build Again
```

Not:

```text
Watch tutorials → Copy code → Forget everything
```

---

# 📚 Course Roadmap

## Phase 1 — Python Fundamentals

### Topics

* [ ] Python installation and setup
* [ ] Variables
* [ ] Numbers
* [ ] Strings
* [ ] Booleans
* [ ] Lists
* [ ] Tuples
* [ ] Sets
* [ ] Dictionaries
* [ ] Conditional statements
* [ ] For loops
* [ ] While loops
* [ ] Functions
* [ ] Return values
* [ ] User input
* [ ] Basic debugging

### Practice

Build small programs without tutorials.

Examples:

* Calculator
* Number guessing game
* To-do list CLI
* Simple expense tracker
* Word counter

### Exit Criteria

I should be able to:

* Write a Python program from scratch
* Use lists and dictionaries comfortably
* Write functions
* Use loops and conditions
* Read basic Python code without difficulty

---

# Phase 2 — Intermediate Python

### Topics

* [ ] Function arguments
* [ ] Default arguments
* [ ] `*args`
* [ ] `**kwargs`
* [ ] List comprehensions
* [ ] Dictionary comprehensions
* [ ] Lambda functions
* [ ] `map()`
* [ ] `filter()`
* [ ] `zip()`
* [ ] `enumerate()`
* [ ] Scope
* [ ] Modules
* [ ] Packages
* [ ] Imports
* [ ] Exception handling
* [ ] File handling
* [ ] JSON
* [ ] Type hints

### Practice Projects

* [ ] JSON-based contact manager
* [ ] File analyzer
* [ ] Log parser
* [ ] CLI task manager

### Exit Criteria

I should be able to write reusable Python code and understand moderately-sized Python scripts.

---

# Phase 3 — Object-Oriented Python

### Topics

* [ ] Classes
* [ ] Objects
* [ ] Constructors
* [ ] Instance attributes
* [ ] Instance methods
* [ ] Class methods
* [ ] Static methods
* [ ] Inheritance
* [ ] Composition
* [ ] Encapsulation
* [ ] Dunder methods
* [ ] Dataclasses

### Practice Project

Build a small:

**Library Management System**

It should contain classes such as:

```text
Book
Member
Library
```

### Exit Criteria

I should be able to understand and create Python classes and comfortably read object-oriented Python code.

---

# Phase 4 — Python Development Environment

### Topics

* [ ] Python virtual environments
* [ ] `venv`
* [ ] `pip`
* [ ] `requirements.txt`
* [ ] Environment variables
* [ ] `.env`
* [ ] `.gitignore`
* [ ] Package installation
* [ ] Logging
* [ ] Debugging
* [ ] Basic testing
* [ ] `pytest`

### Practice

Create a properly structured Python project with:

```text
src/
tests/
.env
.gitignore
requirements.txt
README.md
```

### Exit Criteria

I should be able to clone, install, configure, run, and test a Python project.

---

# Phase 5 — Python for Backend Development

Because I already have backend development experience, this phase should focus mainly on learning the Python ecosystem.

### Topics

* [ ] HTTP fundamentals
* [ ] REST APIs
* [ ] `requests`
* [ ] `httpx`
* [ ] Async programming
* [ ] `async`
* [ ] `await`
* [ ] `asyncio`
* [ ] FastAPI
* [ ] Pydantic
* [ ] Request validation
* [ ] Response models
* [ ] Error handling
* [ ] API documentation

### Project

Build:

**Python FastAPI Backend**

Features:

* CRUD API
* Request validation
* Error handling
* Environment configuration
* Tests
* API documentation

### Exit Criteria

I should be able to build a small production-style Python API.

---

# Phase 6 — Python for Data

The goal is not to become a Data Scientist.

The goal is to become comfortable processing data used by AI applications.

### NumPy

* [ ] Arrays
* [ ] Shapes
* [ ] Indexing
* [ ] Basic operations
* [ ] Vector operations

### Pandas

* [ ] DataFrames
* [ ] Series
* [ ] Reading CSV
* [ ] Reading JSON
* [ ] Filtering
* [ ] Sorting
* [ ] Grouping
* [ ] Missing data
* [ ] Basic transformations

### Visualization

* [ ] Matplotlib basics
* [ ] Simple charts

### Project

Analyze a real dataset and produce:

* Data cleaning
* Basic analysis
* Simple visualizations
* Findings

### Exit Criteria

I should be able to load, inspect, manipulate, and prepare a dataset using Python.

---

# Phase 7 — Python for AI

This is where Python starts connecting directly to Generative AI.

### AI Concepts

* [ ] Artificial Intelligence
* [ ] Machine Learning
* [ ] Deep Learning
* [ ] Neural Networks
* [ ] NLP
* [ ] Tokens
* [ ] Tokenization
* [ ] Embeddings
* [ ] Vectors
* [ ] Similarity
* [ ] Cosine similarity
* [ ] Transformers
* [ ] Attention
* [ ] LLMs
* [ ] Inference

### Python Practice

* [ ] Text preprocessing
* [ ] Tokenization
* [ ] Generate embeddings
* [ ] Compare vectors
* [ ] Calculate cosine similarity
* [ ] Perform semantic search

### Project

Build:

**Semantic Search Engine**

Flow:

```text
Documents
    ↓
Text Processing
    ↓
Embeddings
    ↓
Vector Representation
    ↓
Similarity Search
    ↓
Most Relevant Documents
```

### Exit Criteria

I should understand how text becomes vectors and how semantic search works.

---

# Phase 8 — LLM Application Development

This is the final preparation phase before starting the Generative AI course.

### LLM APIs

* [ ] API keys
* [ ] API requests
* [ ] Model selection
* [ ] Input/output
* [ ] Tokens
* [ ] Context windows
* [ ] Pricing concepts
* [ ] Streaming
* [ ] Error handling
* [ ] Rate limits

### Prompting

* [ ] System prompts
* [ ] User prompts
* [ ] Few-shot prompting
* [ ] Prompt templates
* [ ] Structured outputs
* [ ] JSON responses

### Tool Use

* [ ] Function calling
* [ ] Tool definitions
* [ ] Tool execution
* [ ] Handling tool results

### RAG Fundamentals

* [ ] RAG architecture
* [ ] Document loading
* [ ] Chunking
* [ ] Embeddings
* [ ] Vector databases
* [ ] Retrieval
* [ ] Context injection
* [ ] Grounded generation

### Final Preparation Project

Build:

**Mini RAG Application**

Architecture:

```text
                Documents
                    ↓
              Text Extraction
                    ↓
                 Chunking
                    ↓
                Embeddings
                    ↓
              Vector Database
                    ↓
User Question → Retrieval
                    ↓
              Relevant Context
                    ↓
                   LLM
                    ↓
                 Answer
```

### Exit Criteria

I should be able to explain and implement the basic RAG pipeline without blindly copying a tutorial.

---

# 🚀 Final Readiness Check

Before starting the Generative AI course, I should be able to answer "yes" to the following:

## Python

* [ ] Can I write Python without constantly checking syntax?
* [ ] Can I work comfortably with lists and dictionaries?
* [ ] Can I write functions?
* [ ] Can I create classes?
* [ ] Can I handle exceptions?
* [ ] Can I work with JSON?
* [ ] Can I use virtual environments?
* [ ] Can I install and manage packages?
* [ ] Can I use environment variables?
* [ ] Can I write basic tests?

## Backend

* [ ] Can I consume a REST API?
* [ ] Can I build a basic API in FastAPI?
* [ ] Do I understand HTTP requests and responses?
* [ ] Do I understand async/await?

## AI Fundamentals

* [ ] Can I explain what an LLM is?
* [ ] Do I understand tokens?
* [ ] Do I understand context windows?
* [ ] Do I understand embeddings?
* [ ] Do I understand vector similarity?
* [ ] Do I understand transformers at a high level?
* [ ] Do I understand what RAG is?

## LLM Development

* [ ] Can I call an LLM API from Python?
* [ ] Can I handle API errors?
* [ ] Can I create structured prompts?
* [ ] Can I request structured/JSON output?
* [ ] Can I implement basic function calling?
* [ ] Can I generate embeddings?
* [ ] Can I perform semantic search?
* [ ] Can I build a basic RAG application?

If most of these are checked, I am ready to start the Generative AI course.

---

# 🎯 Final Target

The final progression should be:

```text
Python
   ↓
Python Development
   ↓
Python Backend
   ↓
Python Data Processing
   ↓
AI Fundamentals
   ↓
LLM APIs
   ↓
Embeddings
   ↓
Vector Databases
   ↓
RAG
   ↓
AI Agents
   ↓
Production AI
```

The goal is not to "finish Python."

The goal is to become capable of **building AI applications with Python**.

---

# 🏆 Definition of Done

This preparation is complete when I can independently build:

1. A Python CLI application
2. A Python REST API
3. A FastAPI backend
4. A data-processing script
5. A semantic search application
6. An application that calls an LLM API
7. A basic RAG application

At that point, I should stop preparing and start the Generative AI course.

---

## Next Course

After completing this repository:

**Generative AI / AI Engineering Course**

Main topics:

```text
Transformers
LLMs
LLM APIs
Prompt Engineering
Function Calling
Embeddings
Vector Databases
RAG
Advanced RAG
Fine-Tuning
AI Agents
Multi-Agent Systems
Evaluation
Guardrails
Deployment
Production AI
```

---

## Principle

> **Don't learn Python for the sake of Python. Learn Python so I can build AI systems.**
