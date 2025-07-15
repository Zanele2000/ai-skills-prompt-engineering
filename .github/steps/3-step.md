## Step 3: One-Shot Prompting - Learning by Example

Great progress on zero-shot prompting! Now you'll discover how a single well-chosen example can dramatically improve AI response quality and consistency.

### 📖 Theory: One-Shot Prompting Fundamentals

> [!NOTE]
> One-shot prompting provides exactly one example to guide the AI's response format and style. This technique helps establish patterns and expectations while maintaining flexibility.

**Benefits of One-Shot Prompting:**
- **Format Guidance**: Shows desired output structure through example
- **Style Establishment**: Demonstrates tone and approach expectations  
- **Context Clarity**: Provides concrete reference for complex tasks
- **Quality Consistency**: Reduces variability in AI responses
- **Learning Efficiency**: Balances guidance with creative freedom

**When to Use One-Shot Prompting:**
- You need consistent formatting across multiple requests
- The task has specific style or tone requirements
- Zero-shot results are inconsistent or off-target
- You want to show rather than just tell what you need

### ⌨️ Activity: Master One-Shot Prompting

1. **Create your One-shot prompts workspace**:

```bash
touch one-shot-prompts.yml
```

2. **Add these one-shot prompt templates**:
   
```yaml
# One-Shot Prompt Practice
# Code Review Comment
prompt: |
  Write a constructive code review comment for a pull request. Here's an example:
  
  Example: "Great work on implementing the user authentication! I noticed the password validation could be strengthened by adding a check for special characters. Consider using a regex pattern like /^(?=.*[!@#$%^&*])/ to ensure at least one special character. This would align with our security standards. Otherwise, the logic flow looks solid!"
  
  Now write a similar code review comment for a WhatsApp integration module that has good error handling but lacks proper logging.
ai_response: "[Test this prompt and paste the response here]"

# User Story Writing
prompt: |
  Write a user story following this format:
  
  Example: "As a customer service manager, I want to view real-time chat metrics on a dashboard so that I can monitor team performance and identify bottlenecks during peak hours. Acceptance criteria: Dashboard updates every 30 seconds, shows active chats, average response time, and agent availability."
  
  Now write a user story for a customer who wants to receive automated WhatsApp notifications about their order status.
ai_response: "[Test this prompt and paste the response here]"

# Bug Report
prompt: |
  Write a detailed bug report using this structure:
  
  Example: "**Title:** Login form validation fails with special characters
  **Environment:** Chrome 120, Windows 11, Production
  **Steps to Reproduce:** 1) Navigate to login page 2) Enter email with + symbol 3) Click submit
  **Expected Result:** User should be logged in successfully
  **Actual Result:** Error message 'Invalid email format' appears
  **Priority:** Medium - affects users with email aliases"
  
  Now write a bug report for WhatsApp messages not being delivered during peak hours.
ai_response: "[Test this prompt and paste the response here]"

# Status Update Email
prompt: |
  Write a project status update email following this example:
  
  Example: "Subject: Weekly Update - Mobile App Redesign Project
  
  Hi Team,
  
  Here's our progress update for Week 12:
  
  ✅ **Completed:** User interface mockups for login and dashboard screens
  ✅ **In Progress:** Backend API integration (60% complete)
  ⚠️ **Blocked:** Waiting for design approval on payment flow
  📅 **Next Week:** Complete API integration, begin user testing preparation
  
  Risk: Design approval delay may push testing back 3 days. Mitigation: Parallel work on other screens.
  
  Questions or concerns? Let's discuss in our Friday standup.
  
  Best regards,
  Sarah"
  
  Now write a status update email for the WhatsApp integration project covering week 8 of development.
ai_response: "[Test this prompt and paste the response here]"
```

3. **Test each prompt** with your preferred AI tool and compare the results to your zero-shot attempts

4. **Analyze the improvements** - Notice how examples improve:
- **Consistency**: Similar structure and tone across responses
- **Completeness**: All required elements included
- **Quality**: More professional and polished output
- **Relevance**: Better alignment with your specific needs

5. **Experiment with variations**:
- Try different example styles (formal vs. casual)
- Use examples from different domains 
- Test with incomplete examples to see what happens

6. **Document your observations**:
```yaml
# One-Shot vs Zero-Shot Comparison

# Observations
response_quality_differences: "[Add your observations about response quality differences]"
pattern_influence: "[Note any patterns in how examples influenced outputs]"
task_benefits: "[Record which types of tasks benefited most from examples]"

best_practices:
effective_examples: "[Your insights about crafting effective examples]"
choosing_examples: "[Tips for choosing representative examples]"
when_to_use: "[When one-shot works better than zero-shot]"
```

7. **Commit your one-shot mastery**:
```bash
git add .
git commit -m "Mastered one-shot prompting with examples"
git push origin main
```

### 🎯 Key Insights

**The Power of Examples**: A single well-crafted example does more than pages of instructions. It shows the AI exactly what "good" looks like.

**Quality vs. Quantity**: One perfect example often outperforms multiple mediocre instructions.

**Format Inheritance**: AI naturally mimics the structure, tone, and style of your example.

<details>
<summary>Having trouble? 🤷</summary><br/>

- **Example not working?** Make sure your example clearly demonstrates the format, tone, and content you want
- **Inconsistent results?** Try making your example more specific and detailed
- **AI ignoring the example?** Add explicit instructions like "Follow this exact format" or "Use this example as your template"
- **Need better examples?** Look at high-quality samples from your domain or industry standards

</details>

### 🚀 Next Step

Excellent work! You've learned how one example can transform AI responses. In Step 4, you'll discover how multiple examples create even more powerful patterns and enable complex formatting that single examples can't achieve.

Ready to explore few-shot prompting? Let's see what happens when we provide multiple examples to establish robust patterns!
