# Tools, Actions & Environment Execution

Tools allow agents to interact with the real world—performing actions beyond text generation.

---

### 1. Tool Types

- Web search  
- File operations  
- Database queries  
- Email sending  
- Browser automation  
- Code execution  
- Domain-specific APIs  

---

### 2. React Loop
Thought → Action → Observation → Reflection

Agents dynamically choose tools based on reasoning steps.

---

### 3. Tool Safety

- allowlist of approved tools  
- rate limits  
- execution timeouts  
- argument validation  
- output schema enforcement  

---

### 4. Permission Matrix

| Tool | Default Access | Risk Level |
|------|----------------|------------|
| Search API | Allowed | Low |
| SQL Read | Allowed | Low |
| SQL Write | Restricted | High |
| Email Send | HITL Required | Medium |
| File Write | Restricted | Medium |

---

### Summary
Tooling bridges reasoning with action to create fully capable agent systems.
