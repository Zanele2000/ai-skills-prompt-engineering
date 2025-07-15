## Step 2: Mastering Prompt Techniques

Great job setting up your workspace! Now you'll learn to write effective prompts using different prompt techniques.

### 📖 Theory: Zero-Shot Prompting Fundamentals

> [!NOTE]
> Zero-shot prompting means giving AI a task without providing examples. It relies on clear, specific instructions and the AI's pre-trained knowledge to generate appropriate responses.

**Key Elements of Effective Zero-Shot Prompts:**

- **Clear Objective**: Exactly what you want the AI to do
- **Context**: Background information the AI needs
- **Format Specification**: How you want the output structured
- **Constraints**: Any limitations or requirements
- **Tone/Style**: The voice or approach you want

### ⌨️ Activity: Create Professional Zero-Shot Prompts

1. Add a file for your Zero-shot prompts using the terminal.

```bash
touch zero-shot-prompts.yml
```

2. **Add these zero-shot prompt templates**:
   
```yaml
# Zero-Shot Prompt Practice
# Email Writing
prompt: "Write a professional email to stakeholders explaining a 2-week delay in the WhatsApp integration project. Include an apology, brief explanation of technical challenges, revised timeline, and next steps. Keep the tone professional but reassuring."
ai_response: "[Test this prompt and paste the response here]"

# Meeting Summary
prompt: "Create a concise meeting summary with the following structure: Key Decisions, Action Items (with owners and deadlines), and Next Meeting Date. Write it for a project status meeting about implementing WhatsApp customer service capabilities."
ai_response: "[Test this prompt and paste the response here]"

# Technical Documentation:
prompt: "Write a brief technical requirements document for integrating WhatsApp Business API into an existing customer service system. Include sections for: Overview, Technical Requirements, Integration Points, and Success Criteria. Use bullet points and keep it under 300 words."
ai_response: "[Test this prompt and paste the response here]"
```

3. **Test each prompt** with GitHub Copilot, M365 Copilot, or your preferred AI tool

4. **Analyze the results** - Notice how specific instructions improve response quality

5. **Commit your work**:
```bash
git add .
git commit -m "Added zero-shot prompting practice"
git push origin main
```

### 🎯 Next Step

Excellent work mastering zero-shot prompting! You've learned the foundation of effective AI communication through clear, specific instructions.

**What's Next**: In Step 3, you'll discover how providing a single example can dramatically improve response quality and consistency. One-shot prompting builds on everything you just learned while introducing the power of examples.
