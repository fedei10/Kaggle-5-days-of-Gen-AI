# 🚀 Kaggle 5-Day Gen AI Agents Course

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

Welcome to the **Kaggle 5-Day Gen AI Agents Course**! This comprehensive learning path will take you from building your first AI agent to deploying production-ready multi-agent systems using Google's **Agent Development Kit (ADK)**.

## 📚 Course Overview

This course provides hands-on experience building intelligent AI agents that can take actions, use tools, manage memory, and collaborate with other agents. Each day focuses on critical concepts and practical implementations.

### Course Structure

- **Day 1**: Foundation & Architecture
- **Day 2**: Agent Tools & Best Practices
- **Day 3**: Memory Management
- **Day 4**: Observability & Evaluation
- **Day 5**: Communication & Deployment

---

## 📅 Daily Learning Path

### **Day 1: Getting Started with AI Agents**

#### 🎯 Day 1a: From Prompt to Action
Learn the fundamentals of AI agents and build your first agent that can take real actions.

**Key Topics:**
- Installing and configuring the Agent Development Kit (ADK)
- Setting up Gemini model API access
- Building a simple agent with Google Search tool
- Understanding the difference between prompts and actions

**Learning Outcomes:**
- ✅ Set up your development environment
- ✅ Create your first functioning AI agent
- ✅ Integrate external tools (Google Search)
- ✅ Run and test agent interactions

#### 🏗️ Day 1b: Agent Architectures
Scale from single agents to collaborative multi-agent systems.

**Key Topics:**
- Multi-agent system concepts and use cases
- LLM-based agent managers
- Core workflow patterns:
  - **Sequential**: Step-by-step execution
  - **Parallel**: Concurrent task processing
  - **Loop**: Iterative problem solving
- Team-based agent collaboration

**Learning Outcomes:**
- ✅ Understand when to use multi-agent systems
- ✅ Build coordinated agent teams
- ✅ Implement workflow patterns
- ✅ Create specialized collaborative agents

---

### **Day 2: Empowering Agents with Tools**

#### 🛠️ Day 2a: Agent Tools
Unlock the full power of agent tools by creating custom logic and specialist agents.

**Key Topics:**
- Converting Python functions to agent tools
- Using agents as tools within other agents
- Building multi-tool agents
- Exploring different tool types in ADK
- Real-world tool integration patterns

**Why Tools Matter:**
Without tools, agents are limited to frozen knowledge. Tools transform isolated LLMs into capable agents that can:
- Access real-time information
- Interact with external systems
- Take actions on your behalf
- Connect to databases and APIs

**Learning Outcomes:**
- ✅ Create custom Python-based tools
- ✅ Build nested agent architectures
- ✅ Implement multi-tool workflows
- ✅ Understand tool design patterns

#### 🎨 Day 2b: Agent Tool Patterns & Best Practices
Advanced patterns for external services and complex operations.

**Key Topics:**
- Connecting to external MCP (Model Context Protocol) servers
- Implementing long-running operations
- Building resumable workflows
- Maintaining state across conversation breaks
- Handling asynchronous operations

**Learning Outcomes:**
- ✅ Integrate external MCP services
- ✅ Design pausable agent workflows
- ✅ Implement stateful operations
- ✅ Apply best practices for tool design

---

### **Day 3: Memory Management**

#### 💾 Day 3a: Agent Sessions
Build stateful agents with session management and context handling.

**Key Topics:**
- Understanding sessions in agent systems
- Building stateful agents with sessions and events
- Persisting sessions in databases
- Context management and compaction techniques
- Sharing session state across agents

**Session Capabilities:**
- Track conversation threads
- Maintain short-term context
- Manage application state
- Handle multi-turn interactions

**Learning Outcomes:**
- ✅ Implement session-based memory
- ✅ Persist conversation history
- ✅ Apply context compaction strategies
- ✅ Share state between agents

#### 🧠 Day 3b: Agent Memory
Add long-term, persistent knowledge storage to your agents.

**Key Topics:**
- Difference between Sessions (short-term) and Memory (long-term)
- Cross-conversation knowledge recall
- LLM-powered fact extraction and consolidation
- Semantic search capabilities
- Persistent storage across application restarts

**Memory vs Session:**

| Feature | Session | Memory |
|---------|---------|--------|
| **Duration** | Single conversation | Multiple conversations |
| **Storage** | Temporary | Persistent |
| **Analogy** | Application state | Database |
| **Use Case** | "What did I say 5 minutes ago?" | "What are my preferences from last week?" |

**Learning Outcomes:**
- ✅ Implement long-term memory storage
- ✅ Enable cross-conversation recall
- ✅ Use semantic search for knowledge retrieval
- ✅ Build agents with growing knowledge bases

---

### **Day 4: Production Readiness**

#### 🔍 Day 4a: Agent Observability
Master logs, traces, and metrics for debugging and monitoring agents.

**Key Topics:**
- Three pillars of observability:
  - **Logs**: Record individual events
  - **Traces**: Connect events into complete stories
  - **Metrics**: Measure performance and behavior
- Debugging mysterious agent failures
- Understanding agent decision-making processes
- Tracking tool usage and LLM interactions

**The Challenge:**
AI agents can fail unpredictably. Observability reveals:
- What prompts were sent to the LLM
- Which tools were available
- How the model responded
- Where failures occurred

**Learning Outcomes:**
- ✅ Implement comprehensive logging
- ✅ Create trace visualizations
- ✅ Track agent metrics
- ✅ Debug agent behavior effectively

#### 📊 Day 4b: Agent Evaluation
Proactively test and measure agent performance.

**Key Topics:**
- Systematic agent testing across scenarios
- Quality dimension measurement
- Continuous performance monitoring
- Catching quality degradations early
- Evaluation vs traditional testing

**Evaluation vs Testing:**
```
Observability + Agent Evaluation
  (reactive)      (proactive)
```

**Why Evaluation Matters:**
Standard testing isn't enough for AI agents because they:
- Generate non-deterministic responses
- Handle unpredictable user inputs
- Make autonomous decisions
- Evolve over time

**Learning Outcomes:**
- ✅ Design comprehensive test scenarios
- ✅ Implement automated evaluation
- ✅ Monitor quality metrics
- ✅ Prevent regressions proactively

---

### **Day 5: Advanced Integration & Deployment**

#### 🤝 Day 5a: Agent-to-Agent Communication
Build interoperable multi-agent systems using the A2A protocol.

**Key Topics:**
- Agent2Agent (A2A) Protocol fundamentals
- When to use A2A vs sub-agents
- Common architecture patterns:
  - Cross-framework integration
  - Cross-language communication
  - Cross-organization collaboration
- Exposing agents via `to_a2a()`
- Consuming remote agents with `RemoteA2aAgent`
- Building integrated systems

**The Problem A2A Solves:**
- Single agents can't handle everything
- Specialized agents need to collaborate
- Different teams build different agents
- External vendor integration requirements

**Learning Outcomes:**
- ✅ Implement A2A protocol
- ✅ Expose agents as services
- ✅ Consume remote agents
- ✅ Build cross-framework systems

#### 🚢 Day 5b: Agent Deployment
Deploy production-ready agents to Vertex AI Agent Engine.

**Key Topics:**
- Vertex AI Agent Engine overview
- Building production-ready ADK agents
- Using ADK CLI for deployment
- Testing deployed agents with Python SDK
- Monitoring and management in Google Cloud Console
- Adding Memory with Vertex AI Memory Bank
- Cost management and cleanup practices

**Why Deploy?**
Your agent needs to:
- Be publicly available
- Run independently of your notebook
- Serve multiple users concurrently
- Scale with demand
- Persist beyond development sessions

**Learning Outcomes:**
- ✅ Deploy agents to production
- ✅ Configure Vertex AI Agent Engine
- ✅ Implement production monitoring
- ✅ Manage costs effectively

---

## 🎓 Prerequisites

- **Python 3.8+**
- **Google Cloud Account** (for Vertex AI deployment)
- **Gemini API Key**
- Basic Python programming knowledge
- Familiarity with Jupyter notebooks

## 🚀 Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/fedei10/Kaggle-5-days-of-Gen-AI.git
   cd Kaggle-5-days-of-Gen-AI
   ```

2. **Install Agent Development Kit (ADK):**
   ```bash
   pip install google-adk
   ```

3. **Configure your API key:**
   - Obtain a Gemini API key from Google AI Studio
   - Set up authentication according to Day 1 instructions

4. **Start with Day 1:**
   - Open `day1/day-1a-from-prompt-to-action.ipynb`
   - Follow the instructions in each notebook

## 📖 How to Use This Repository

Each day's folder contains:
- **Part A**: Core concepts and foundations
- **Part B**: Advanced patterns and best practices

**Recommended Approach:**
1. Complete notebooks in sequential order
2. Run cells one at a time (avoid "Run All" to prevent QPM limits)
3. Experiment with code examples
4. Join the [Kaggle Discord](https://discord.com/invite/kaggle) for help

## ⚠️ Important Notes

> **ℹ️ No Submission Required**  
> These notebooks are for hands-on practice and learning. You do not need to submit them anywhere.

> **⏸️ Queue Wait Times**  
> You may see "Waiting for the next available notebook" when starting. Wait times are typically short but may increase during peak hours.

> **❌ Avoid "Run All"**  
> Running all cells at once can trigger QPM (Queries Per Minute) limits and cause 429 errors. Run cells individually.

## 🛠️ Technology Stack

- **Agent Development Kit (ADK)**: Google's framework for building AI agents
- **Gemini Models**: Large language models powering the agents
- **Vertex AI**: Production deployment platform
- **Python**: Primary programming language
- **MCP (Model Context Protocol)**: External service integration

## 📚 Additional Resources

- [ADK Documentation](https://google.github.io/adk-docs/)
- [Vertex AI Agent Engine](https://docs.cloud.google.com/agent-builder/agent-engine/overview)
- [Kaggle Discord Community](https://discord.com/invite/kaggle)
- [Kaggle Notebooks Documentation](https://www.kaggle.com/docs/notebooks)
- [Troubleshooting & FAQs](https://www.kaggle.com/code/kaggle5daysofai/day-0-troubleshooting-and-faqs)

## 🤝 Contributing

This is a learning repository based on Kaggle's official course. Feel free to:
- Report issues
- Share improvements
- Add your own examples
- Help others in discussions

## 📄 License

Licensed under the Apache License 2.0. See notebook headers for full license text.

```
Copyright 2025 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## 🎯 Learning Outcomes

By completing this course, you will:
- ✅ Build production-ready AI agents
- ✅ Implement multi-agent systems
- ✅ Create custom tools and integrations
- ✅ Manage agent memory and state
- ✅ Monitor and evaluate agent performance
- ✅ Deploy agents to production
- ✅ Integrate agents across frameworks
- ✅ Apply AI agent best practices

## 💬 Get Help

- **Discord**: [Kaggle Discord Server](https://discord.com/invite/kaggle)
- **Documentation**: Check the ADK docs for detailed API references
- **Community**: Engage with other learners in the course discussions

---

**Happy Learning! 🚀**

*Building the future, one agent at a time.*
