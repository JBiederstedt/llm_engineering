# llm-engineering

This repository contains all the hands-on projects I completed as part of the [LLM Engineering: Master AI and Large Language Models](https://www.udemy.com/course/llm-engineering-master-ai-and-large-language-models/) course on Udemy, instructed by Edward Donner. This course is an outstanding, practical deep dive into the world of large language models (LLMs), guiding students through eight weeks of progressive, real-world projects.

## Course Overview

The course spans eight weeks, each focused on a different aspect of LLM development and deployment. By the end of the course, you will have built a range of applications, from simple chatbots to fully autonomous agentic AI systems.

## Repository Structure

Each folder corresponds to a weekly module and contains the associated project files, code notebooks, and supporting documentation.

- **week1**: _Getting Started & Local LLM Setup_

  - Install and configure Ollama for local LLM experimentation (Llama 3.2).
  - Run basic chat completions and explore prompt variations.

- **week2**: _Prompt Engineering & Chain of Thought_

  - Techniques for crafting effective prompts.
  - Implement chain-of-thought prompting to improve reasoning in LLM outputs.

- **week3**: _Embeddings & Semantic Search_

  - Generate text embeddings with Hugging Face.
  - Build a vector database for semantic document retrieval.

- **week4**: _Fine-Tuning & Custom Models_

  - Fine-tune open-source LLMs on domain-specific data.
  - Evaluate and compare model variants.

- **week5**: _Evaluation & Benchmarking_

  - Define evaluation metrics for LLM performance.
  - Automate benchmark tests across multiple models and datasets.

- **week6**: _Agent Design & Tooling_

  - Architect multi-step agent workflows.
  - Integrate external tools and APIs (e.g., search, databases).

- **week7**: _Multi-Turn Dialogue & Retrieval_

  - Maintain conversational context across turns.
  - Combine retrieval-augmented generation for knowledge-driven agents.

- **week8**: _Autonomous Agentic AI_

  - Build an end-to-end autonomous agent that plans, acts, and evaluates its own tasks.
  - Deploy the agent in a production-like environment.

## Setup & Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/jbiederstedt/llm-engineering.git llm-engineering
   ```

2. Navigate to the project directory:

   ```bash
   cd llm-engineering
   ```

3. Install dependencies (using Conda):

   ```bash
   conda env create -f environment.yml
   conda activate llm-engineering
   ```

For detailed setup instructions per operating system, see the `SETUP-*.md` files in the root directory.
