# Day 3: Memory Management

Welcome to Day 3! Learn how to give your agents both short-term and long-term memory, enabling them to maintain context and learn from past interactions.

## 📚 Notebooks

### 💾 Day 3a: Agent Sessions
**File:** `day-3a-agent-sessions.ipynb`

Build stateful agents with session management and context handling.

**What You'll Learn:**
- Understanding sessions and their role in agents
- Building stateful agents with sessions and events
- Persisting sessions in databases
- Context management and compaction techniques
- Sharing session state across agents

**What Are Sessions?**

Sessions provide **short-term memory** for agents:
- 💬 Track single conversation threads
- 🔄 Maintain context within a dialogue
- 📝 Remember what was said earlier in the conversation
- 🎯 Keep track of the current task state

**Key Features:**

1. **Conversation Threading**
   - Keep related messages together
   - Maintain dialogue context
   - Track conversation flow

2. **State Management**
   - Store temporary variables
   - Track progress through workflows
   - Manage current task status

3. **Context Compaction**
   - Summarize long conversations
   - Keep context within token limits
   - Preserve important information while reducing size

4. **Session Persistence**
   - Save sessions to databases
   - Resume conversations later
   - Share state across agent instances

**Key Concepts:**
- **Session**: A container for conversation history and state
- **Events**: Individual messages and actions in a session
- **Context Window**: The amount of history available to the agent
- **Compaction**: Reducing context size while preserving meaning

**Use Cases:**
- 💬 Multi-turn conversations
- 🔄 Workflow tracking
- 📊 Progress monitoring
- 🤝 Collaborative agent systems

**Learning Outcomes:**
- ✅ Implement session-based memory
- ✅ Persist conversation history
- ✅ Apply context compaction strategies
- ✅ Share state between agents
- ✅ Manage conversation threads effectively

---

### 🧠 Day 3b: Agent Memory
**File:** `day-3b-agent-memory.ipynb`

Add long-term, persistent knowledge storage to your agents.

**What You'll Learn:**
- Difference between Sessions (short-term) and Memory (long-term)
- Cross-conversation knowledge recall
- LLM-powered fact extraction and consolidation
- Semantic search capabilities
- Persistent storage across application restarts

**What Is Memory?**

Memory provides **long-term knowledge storage** for agents:
- 🧠 Persist information across multiple conversations
- 🔍 Search past interactions semantically
- 📚 Build growing knowledge bases
- 💡 Learn user preferences over time

**Session vs Memory Comparison:**

| Feature | Session (Short-Term) | Memory (Long-Term) |
|---------|---------------------|-------------------|
| **Duration** | Single conversation | Multiple conversations |
| **Storage** | Temporary | Persistent |
| **Scope** | Current dialogue | All past interactions |
| **Analogy** | Working memory | Knowledge base |
| **Example** | "What did I say 5 min ago?" | "What are my preferences?" |
| **Tech Analogy** | Application state | Database |

**Memory Capabilities:**

1. **Cross-Conversation Recall**
   - Access information from any past conversation
   - Build on previous interactions
   - Maintain continuity across sessions

2. **Intelligent Extraction**
   - LLM-powered fact consolidation
   - Extract key information from conversations
   - Store meaningful insights, not raw messages

3. **Semantic Search**
   - Meaning-based retrieval
   - Find related information conceptually
   - Not limited to keyword matching

4. **Persistent Storage**
   - Survives application restarts
   - Grows over time
   - Builds agent intelligence

**Example Use Case:**

```python
# Session: "What did we discuss today?"
# Memory: "What are my dietary restrictions from all our conversations?"

# Session remembers: Today's lunch discussion
# Memory remembers: "User is allergic to peanuts" (from 3 months ago)
```

**Key Concepts:**
- **Memory Service**: Long-term knowledge storage system
- **Semantic Search**: Meaning-based information retrieval
- **Fact Extraction**: Converting conversations to structured knowledge
- **Cross-Conversation Context**: Information that spans multiple sessions

**Learning Outcomes:**
- ✅ Implement long-term memory storage
- ✅ Enable cross-conversation recall
- ✅ Use semantic search for knowledge retrieval
- ✅ Build agents with growing knowledge bases
- ✅ Extract and consolidate facts intelligently

---

## 🚀 Getting Started

1. **Start with Day 3a** to understand sessions
2. **Then move to Day 3b** to add long-term memory
3. **Combine both** for powerful, stateful agents

## ⚠️ Important Notes

> **Build on Previous Days**  
> Ensure you've completed Days 1-2 before starting Day 3.

> **Understand the Distinction**  
> Sessions ≠ Memory. They serve different purposes and work together.

> **Run Cells Individually**  
> Avoid "Run All" to prevent API rate limiting.

## 🛠️ Prerequisites

- Completion of Days 1-2
- Understanding of database concepts (helpful)
- Familiarity with state management
- Basic knowledge of search/retrieval systems (helpful)

## 📖 Key Takeaways

After completing Day 3, you will:
- ✅ Understand sessions vs memory
- ✅ Implement both short-term and long-term memory
- ✅ Build stateful, conversational agents
- ✅ Apply context management techniques
- ✅ Create agents that learn and remember

## 🎯 Practical Applications

**What You Can Build:**

**With Sessions:**
- 💬 Multi-turn chatbots
- 🔄 Workflow management systems
- 📝 Task tracking agents
- 🎯 Goal-oriented assistants

**With Memory:**
- 🤖 Personal assistants that remember preferences
- 🎓 Learning systems that build knowledge over time
- 👤 User profile management
- 📚 Knowledge base agents

**With Both:**
- 🌟 Sophisticated personal AI assistants
- 🏢 Enterprise agents with institutional knowledge
- 🎯 Adaptive systems that improve over time
- 🤝 Customer service agents with history awareness

## 🔗 Resources

- [ADK Memory Documentation](https://google.github.io/adk-docs/)
- [Session Management Guide](https://google.github.io/adk-docs/sessions)
- [Kaggle Discord Community](https://discord.com/invite/kaggle)

## 💬 Need Help?

- Join the [Kaggle Discord Server](https://discord.com/invite/kaggle)
- Review session and memory examples
- Ask about specific use cases

---

**Previous:** [Day 2](../day2/README.md) - Agent Tools  
**Next:** [Day 4](../day4/README.md) - Observability & Evaluation
