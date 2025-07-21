# 🎯 Cursor AI Assistant Guide

A comprehensive guide for working effectively with Cursor AI in Next.js applications.

---

## 🚀 Effective Prompting Strategies

### Core Principles
- **Act as a senior engineer** working with a Next.js application
- **Break down complex problems** into smaller, manageable tasks and connect them logically
- **Be specific**: Always mention file names, function names, and exact locations
- **Provide context**: Include documentation when Cursor seems to go off direction

### Prompting Techniques
- Use `// TODO` comments or instructions in your code as prompts
- Use **"Explain All"** in a file to get a quick mental model
- Add context to prevent generic responses

---

## ⚖️ Handling Ambiguity

### Decision Making Process
When facing unclear requirements:

1. **Provide 3+ options** to move forward with a decision
2. **Include a small summary** explaining why each option would be beneficial
3. **Ask for clarification** if you're not 90% confident in the approach

### Prompt Optimization
Adjust your prompting based on output quality:

| Problem | Solution |
|---------|----------|
| **Too Generic** | Add more context and specific details |
| **Too Lengthy** | Say "make it concise" |
| **Incomplete** | Ask "continue from here" |

---

## 📋 Implementation Approach

### Best Practices
- **Don't jump to conclusions** midway without understanding the full scope
- **Understand the detailed approach first**, then modify if needed before implementing
- **Save detailed plans** in documentation files (e.g., `/cursor/suggestions/feature.md`)

### Workflow
1. 🔍 **Analyze** the problem thoroughly
2. 📝 **Plan** the approach in detail
3. 🔧 **Implement** step by step
4. 📚 **Document** the solution

---

## ✨ Cursor Excels At

Cursor AI is particularly effective for:

- 🔄 **Refactoring code** - Modernizing and improving existing codebases
- 🗺️ **Understanding large unfamiliar repos** - Navigating complex project structures
- 📖 **Explaining legacy code** - Breaking down old or complex implementations
- 🧪 **Generating unit tests** - Creating comprehensive test suites

---

## 💡 Working Philosophy

> **Treat Cursor like a junior developer**: Guide it, review output, and iterate collaboratively.

### Key Mindset
- Provide clear direction and expectations
- Review all outputs critically
- Iterate and refine based on results
- Maintain oversight of the development process

---

## 📚 Quick Reference

### Essential Commands
- `"Explain All"` - Get comprehensive file/function overview
- `// TODO: [specific task]` - Direct implementation guidance
- `"Be specific about [topic]"` - Get detailed technical information
- `"Provide 3 options for [decision]"` - Get multiple approaches

### File Organization
```
/cursor/
├── suggestions/
│   ├── feature.md
│   ├── refactoring-plan.md
│   └── implementation-notes.md
└── documentation/
    ├── decisions.md
    └── architecture.md
```
