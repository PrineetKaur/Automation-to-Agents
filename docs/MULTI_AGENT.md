# Multi-Agent Collaboration Patterns

Agentic systems often involve multiple specialized agents working together.

---

### 1. Collaboration Models

### **Peer-to-Peer**
Agents communicate directly.

### **Planner + Worker**
One planner delegates to many executors.

### **Hierarchical**
Tree-like chains of command.

### **Pipeline**
Sequential handoff between agents:
- RAG agent → Analysis agent → Generation agent

---

### 2. Communication Patterns
Planner → Worker → Verifier → Aggregator

Each agent has:
- its own memory  
- its own toolset  
- its own autonomy level  

---

### 3. When Multi-Agent Is Useful

- Large or complex tasks  
- Specialized domains  
- Cross-validation  
- High reliability needs  

---

### Summary
Multi-agent patterns encourage modularity, parallelism, and scalable reasoning.
