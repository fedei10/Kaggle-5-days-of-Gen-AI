# Day 2: Empowering Agents with Tools

Welcome to Day 2! Now that you've built basic agents, it's time to unlock their full potential with custom tools and advanced patterns.

## 📚 Notebooks

### 🛠️ Day 2a: Agent Tools
**File:** `day-2a-agent-tools.ipynb`

Transform your agents by creating custom tools and building multi-tool systems.

**What You'll Learn:**
- Converting Python functions into agent tools
- Using agents as tools within other agents
- Building multi-tool agents
- Exploring different tool types in ADK
- Real-world tool integration patterns

**Why Tools Matter:**

Without tools, agents are limited by:
- ❌ Knowledge frozen in training data
- ❌ No access to real-time information
- ❌ Cannot interact with external systems
- ❌ Unable to take concrete actions

With tools, agents can:
- ✅ Access current information and data
- ✅ Interact with APIs and databases
- ✅ Perform calculations and data processing
- ✅ Take actions in the real world

**Key Concepts:**
- **Tool Creation**: Turn any Python function into an agent tool
- **Tool Calling**: How agents decide when and how to use tools
- **Multi-Tool Agents**: Agents that can use multiple tools intelligently
- **Agent-as-Tool**: Using entire agents as reusable tools

**Example Tool Types:**
```python
# Function Tool
def get_weather(city: str) -> dict:
    """Get current weather for a city"""
    return weather_api.fetch(city)

# Agent as Tool
research_agent = Agent(
    name="Researcher",
    tools=[google_search]
)
# Use research_agent as a tool in another agent
```

**Learning Outcomes:**
- ✅ Create custom Python-based tools
- ✅ Build nested agent architectures
- ✅ Implement multi-tool workflows
- ✅ Understand tool selection strategies

---

### 🎨 Day 2b: Agent Tool Patterns & Best Practices
**File:** `day-2b-agent-tools-best-practices.ipynb`

Advanced patterns for external services and complex operations.

**What You'll Learn:**
- Connecting to external MCP (Model Context Protocol) servers
- Implementing long-running operations
- Building resumable workflows
- Maintaining state across conversation breaks
- Handling asynchronous operations

**Advanced Patterns:**

1. **External MCP Integration**
   - Connect to third-party services
   - Use standardized MCP protocol
   - Consume remote capabilities

2. **Long-Running Operations**
   - Handle operations that take time
   - Pause agent execution for external input
   - Resume workflows when data is ready

3. **Resumable Workflows**
   - Maintain state across sessions
   - Handle conversation interruptions
   - Continue from where you left off

**Key Concepts:**
- **MCP (Model Context Protocol)**: Standard for exposing tools and context
- **Stateful Operations**: Maintaining context across multiple interactions
- **Workflow Resumption**: Picking up where an agent left off
- **External Services**: Integrating with third-party APIs and tools

**Use Cases:**
- 🔄 Multi-day tasks requiring human approval steps
- 🌐 Integration with external systems (CRM, databases, APIs)
- ⏱️ Time-consuming operations (data processing, batch jobs)
- 🤝 Workflows requiring human-in-the-loop validation

**Learning Outcomes:**
- ✅ Integrate external MCP services
- ✅ Design pausable agent workflows
- ✅ Implement stateful operations
- ✅ Apply best practices for tool design
- ✅ Handle complex, multi-step operations

---

## 🚀 Getting Started

1. **Complete Day 2a first** to understand tool fundamentals
2. **Then tackle Day 2b** for advanced patterns
3. **Experiment with custom tools** - try creating your own!

## ⚠️ Important Notes

> **Build on Day 1 Knowledge**  
> Make sure you've completed Day 1 before starting Day 2.

> **Run Cells Individually**  
> Avoid "Run All" to prevent API rate limiting (429 errors).

> **Test Your Tools**  
> Always test custom tools independently before integrating them.

## 🛠️ Prerequisites

- Completion of Day 1 (agent fundamentals)
- Understanding of Python functions
- Basic knowledge of APIs (for Day 2b)
- Familiarity with asynchronous programming (helpful for Day 2b)

## 📖 Key Takeaways

After completing Day 2, you will:
- ✅ Know how to create custom agent tools
- ✅ Understand tool selection and calling mechanisms
- ✅ Be able to integrate external services via MCP
- ✅ Handle complex, stateful workflows
- ✅ Apply best practices for tool design

## 🎯 Practical Applications

**What You Can Build:**
- 🔍 Research agents with custom data sources
- 💼 Business process automation agents
- 🧮 Data analysis and calculation agents
- 🌐 API integration agents
- 📊 Multi-step workflow agents

## 🔗 Resources

- [ADK Tools Documentation](https://google.github.io/adk-docs/)
- [MCP Protocol Specification](https://modelcontextprotocol.io/)
- [Kaggle Discord Community](https://discord.com/invite/kaggle)
- [Tool Design Best Practices](https://google.github.io/adk-docs/tools)

## 💬 Need Help?

- Join the [Kaggle Discord Server](https://discord.com/invite/kaggle)
- Review tool examples in the notebooks
- Check the MCP documentation for external services

---

**Previous:** [Day 1](../day1/README.md) - Getting Started with AI Agents  
**Next:** [Day 3](../day3/README.md) - Memory Management
