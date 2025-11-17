# Memory Systems in Agentic AI

Memory transforms stateless language models into stateful, context-aware intelligent agents.

---

### 1. Memory Categories

### **Short-Term Memory (STM)**
Held in the system’s context window.  
Contains:
- current instructions
- tool responses
- task progress

### **Long-Term Memory (LTM)**
Stored externally (e.g., vector DB).  
Stores:
- embeddings of documents
- prior tasks
- organization knowledge
- user preferences

### **Episodic Memory**
Chronological logs of:
- actions
- decisions
- outcomes
- reflections

### **Tool Memory**
Metadata for tools:
- parameters
- schemas
- API docs
- auth requirements

---

### 2. Memory Update Loop
Reflection → Memory Write → Memory Retrieval → Next Action

---

### 3. Retrieval Techniques

- semantic search (embedding similarity)
- keyword search (BM25)
- hybrid retrieval (BM25 + embeddings)
- reranking using cross-encoders

---

### 4. Memory Safety

- PII masking or encryption  
- scoped retrieval  
- TTL-based expiration  
- audit logs  
- access-control layers  

---

### Summary
Memory provides continuity, personalization, and adaptive learning for agent systems.
