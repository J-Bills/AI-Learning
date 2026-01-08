# Week1 Foundations

## What are Agents?

     AI Agents are programs where LLM outputs control the workflow
     Examples:
      -Multiple LLM calls
      -LLMs with the ability to use Tools
      -An environment where LLMs interact
      -A planner to coordinate activities
      -Autonomy

## What are the 2 types of Agentic Systems?

    Workflows: Systems where LLMs and tools are orchestrated through predefinied code paths
    Agents: Systems where LLMs dynamically direct their own processes and tool useage, maintaining control over how they accomplish tasks

## 5 Workflow design patterns

    1. Prompt Chaining - Have an LLM carry out a task and pass that response to another LLM(Decomposing)
    2. Routing - A direct input comes in and a LLM chooses which LLM is the best for the job
    3. Parallelization - Code that takes a tasks and breaks it down and runs the parts through an LLM in pieces and combines the results.
    4. Orchestrator-Worker - Complex tasks are broken down dynamically and combined using only models
    5. Evaluator-Optimizer - LLM output is validated by another

## Agents differ

    1. Open-ended
    2. Feedback Loops
    3. No fixed path

## Risks of Agent Frameworks

    1. Unpredictable path
    2. Unpredictable output
    3. Unpredictable costs
    It's very important to monitor your agents
    Create guardrails that ensure the agents behave safely, consistently, and within the boundaries that we choose.
