# Day 1: Getting Started with AI Agents

Welcome to Day 1 of the Kaggle 5-Day Gen AI Agents Course! Today you'll learn the fundamentals of AI agents and build your first multi-agent system.

## 📚 Notebooks

### 🎯 Day 1a: From Prompt to Action
**File:** `day-1a-from-prompt-to-action.ipynb`

Build your first AI agent that can take real actions beyond simple text responses.

**What You'll Learn:**
- Installing and configuring the Agent Development Kit (ADK)
- Setting up your Gemini API key
- Building a simple agent with Google Search integration
- Understanding how agents differ from basic LLM prompts
- Running and testing your first agent

**Key Concepts:**
- **Agent**: An AI system that can take actions, not just respond to prompts
- **Tools**: Functions that give agents capabilities (like Google Search)
- **ADK**: Google's Agent Development Kit for building production-ready agents

**Learning Outcomes:**
- ✅ Set up your development environment
- ✅ Create your first functioning AI agent
- ✅ Integrate external tools into your agent
- ✅ Execute agent queries and view results

---

### 🏗️ Day 1b: Agent Architectures
**File:** `day-1b-agent-architectures.ipynb`

Scale from single agents to collaborative multi-agent systems.

**What You'll Learn:**
- When and why to use multi-agent systems
- Using an LLM as a "manager" to orchestrate agent teams
- Three core workflow patterns for agent coordination
- Building specialized agents that work together

**Core Workflow Patterns:**

1. **Sequential Workflow**
   - Agents execute one after another
   - Output of one agent feeds into the next
   - Example: Research agent → Analysis agent → Report agent

2. **Parallel Workflow**
   - Multiple agents work simultaneously
   - Tasks are distributed and executed concurrently
   - Example: Multiple search agents gathering different data sources

3. **Loop Workflow**
   - Agents iterate until a condition is met
   - Useful for refinement and optimization tasks
   - Example: Code generator → Validator → Generator (repeat until valid)

**Key Concepts:**
- **Multi-Agent Systems**: Teams of specialized agents working together
- **Agent Orchestration**: Coordinating multiple agents to solve complex problems
- **Workflow Patterns**: Structured approaches to agent collaboration

**Learning Outcomes:**
- ✅ Understand when to use multi-agent systems vs single agents
- ✅ Build coordinated agent teams
- ✅ Implement Sequential, Parallel, and Loop patterns
- ✅ Create specialized collaborative agents

---

## 🚀 Getting Started

1. **Start with Day 1a** to build your first agent
2. **Then move to Day 1b** to learn about agent architectures
3. **Run cells one at a time** - avoid "Run All" to prevent API rate limits

## ⚠️ Important Notes

> **No Submission Required**  
> These notebooks are for learning only. No submission needed.

> **Avoid "Run All"**  
> Running all cells at once can trigger QPM (Queries Per Minute) limits and cause 429 errors. Run cells individually for best results.

> **API Key Setup**  
> You'll need a Gemini API key. Instructions are provided in the Day 1a notebook.

## 🛠️ Prerequisites

- Python 3.8+
- Jupyter Notebook or Kaggle environment
- Gemini API key (free from Google AI Studio)
- Basic Python programming knowledge

## 📖 Key Takeaways

After completing Day 1, you will:
- ✅ Understand the difference between LLMs and AI agents
- ✅ Know how to build single and multi-agent systems
- ✅ Be familiar with agent workflow patterns
- ✅ Have hands-on experience with the ADK framework

## 🔗 Resources

- [ADK Documentation](https://google.github.io/adk-docs/)
- [Kaggle Discord Community](https://discord.com/invite/kaggle)
- [Troubleshooting & FAQs](https://www.kaggle.com/code/kaggle5daysofai/day-0-troubleshooting-and-faqs)

## 💬 Need Help?

- Join the [Kaggle Discord Server](https://discord.com/invite/kaggle)
- Check the troubleshooting guide for common issues
- Ask questions in the course discussion forum

---

**Next:** Move on to [Day 2](../day2/README.md) to learn about Agent Tools!
