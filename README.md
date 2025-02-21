<div>
    <h1>HuggingFace Agent Course</h1>
</div>

<p align="center">
    <a href="https://www.python.org/downloads/release/python-31111/">
        <img alt="python" src="https://img.shields.io/badge/python-3.11-blue.svg"/>
    </a>
      <a href="https://python-poetry.org/">
    <img alt="poetry" src="https://img.shields.io/pypi/v/poetry?label=poetry">
  </a>
  <a href="https://github.com/qhreul/huggingface-agent-course/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-Apache%202.0-green"/>
  </a>
</p>

<!-- omit in toc -->
## Table of Content
- [Description](#description)
- [Getting started](#getting-started)
  - [Requirements](#requirements)
  - [Set up Environment](#set-up-environment)

## Description
The HuggingFace Agent Course is designed to take you from beginner to expert in understanding, using, and building AI Agents. The course covers the theory, design, and practice of AI Agents, and teaches you how to use established AI Agent libraries like smolagents, LangChain, and LlamaIndex.

## Getting started

### Requirements
- Git 
- Python >=3.11, <3.12
- [Poetry](https://python-poetry.org/) >= 2.0

### Set up Environment
1. Configure access to Poetry virtual environment
   ```
   poetry config virtualenvs.in-project true
   ```
2. Install dependencies
   ```
   poetry install
   ```
3. Select Poetry virtual environment as Jupyter kernel
   1. Activate the Poetry virtual environment
   ```
   poetry env activate
   ```
   2. Click `Select Kernel` in VS Code and select the activated kernel
