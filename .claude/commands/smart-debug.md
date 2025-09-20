---
name: smart-debug
description: Auto-route debugging based on issue type
---

Debugging: {{issue}}

Let me analyze and route this properly:

{{#if (contains issue "auth")}}
/Task security-auditor: Investigate authentication issue: {{issue}}
/Task debugger: Debug authentication flow
{{else if (contains issue "performance")}}
/Task performance-engineer: Analyze performance issue: {{issue}}
/Task database-optimizer: Check for database bottlenecks
{{else if (contains issue "database")}}
/Task database-optimizer: Debug database issue: {{issue}}
/Task data-engineer: Review data flow
{{else}}
/Task debugger: Investigate general issue: {{issue}}
/Task code-reviewer: Review related code quality
{{/if}}