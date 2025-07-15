## Step 1: Setting Up Your Prompt Engineering Environment

You are a professional learning to use AI tools effectively. Your goal is to master prompt engineering techniques that will make you more productive in your daily work, whether you're writing content, analyzing data, or solving problems.

In this step, you'll learn to set up a codespace to start crafting and testing effective prompts.

### 📖 Theory: Introduction to Prompt Engineering

> [!NOTE]
> Prompt engineering is the art and science of crafting effective instructions for AI models. A well-written prompt can mean the difference between getting a vague response and getting exactly what you need.

**Key Benefits of Good Prompt Engineering:**

- **Precision**: Get specific, actionable responses
- **Efficiency**: Reduce back-and-forth iterations with AI
- **Consistency**: Reliable results for similar tasks
- **Control**: Guide AI to follow your preferred style and format
- **Productivity**: Accomplish complex tasks faster

### ⌨️ Activity: Set Up Your Prompt Engineering Workspace

1. **Open your codespace** if you have not already opened it up in a new tab, and ensure GitHub Copilot is active (look for the Copilot icon in the status bar)

2. Right click in the file explorer on the left and the following popup will open in your codespace:

   ![Paste text popup](https://raw.githubusercontent.com/anton-roos/ai-skills/refs/heads/main/images/paste-text-popup.png)

click Allow

3. **Create a new prompt document**
- Ensure your terminal is open. If terminal is not open press `CTRL + ~`
- Copy the following into the terminal
```bash
touch my-prompts.yml
```
- Press Enter

4. **Write your first prompt**:
   
In your `my-prompts.yml` file, add this content to practice prompt engineering:
   
```yaml
prompt: "Write a professional email to a stakeholder explaining that you need more information for the new WhatsApp project to do a thorough requirement analysis."
ai_response: "[Paste the AI's response here when you test this prompt]"
```
   
**Practice Activity:** 
- Test these prompts with GitHub Copilot or M365 Copilot
- Copy the AI responses and paste them in the designated areas

5. **Commit and push your workspace setup**:
   
   Now let's save your progress to GitHub. Copy and paste these commands one by one:
   
```bash
git add .
```

```bash
git commit -m "Set up prompt engineering workspace structure"
```

```bash
git push origin main
```
   
> [!NOTE]
> In professional environments, it's recommended to create feature branches and use pull requests instead of pushing directly to the main branch. However, for this learning exercise, pushing directly to main is perfectly fine!
   
**What these commands do:**
- `git add .` - Stages all your new files for commit
- `git commit -m "message"` - Creates a snapshot of your changes with a descriptive message
- `git push origin main` - Uploads your changes to GitHub on the main branch

✅ **Success!** Your workspace is now saved to GitHub and ready for prompt engineering practice!

If everything went well. Mona will give you your next task.
