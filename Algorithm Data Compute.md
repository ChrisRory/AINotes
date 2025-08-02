# Algorithms

## Hierarchical Reasoning Model Official https://github.com/sapientinc/HRM
- 27M parameters
- Trained on only 1000 examples
- Inspired by the human brain
- Beat Claude, o3-mini & Deepseek

# Application
## TTS
https://indextts2.org/

# Compute
How to Scale Your Model https://jax-ml.github.io/scaling-book/

# Data

# Vibe coding
## Claude with CodeRabbit + TaskMaster https://x.com/PrajwalTomar_/status/1950565560494014816
Plan with AI, Code with AI, Review with AI.
• Plan clearly (PRD) with @ChatGPT
• Break it down using TaskMaster
• Execute one task at a time using Claude Code inside Cursor
• Review everything with @coderabbitai

1.Plan → Write a clean 1-page PRD
2.Break → Use TaskMaster to map exact tasks
3.Execute → Feed ONE task at a time to Claude inside Cursor
4.Review → Open PR, let CodeRabbit catch bugs

Step 1: Write the PRD
Start with a simple doc that explains:
• What you’re building
• Why it matters
• Key features + edge cases
You can use ChatGPT or Claude to draft it fast.
Step 2: Use TaskMaster
This is where the magic happens.
→ Paste the PRD into TaskMaster
→ Let it break features into tasks
→ Check complexity scores
→ Expand anything above 6/10 into smaller subtasks
Repeat till everything is simple.
Step 3: Claude Code, one task at a time
Don’t dump 10 prompts at once.
→ Pick one task
→ Run it with Claude
→ Read the output
→ Clean it if needed
Only then move to the next.
AI builds better when it’s not rushed.
Step 4: Review with CodeRabbit

Start with an internal review using CodeRabbit’s “Fix with AI” feature.
It’ll help you clean up the code and catch obvious issues before moving forward.

Once you’re done with that, push the code and open a PR for a formal review.

CodeRabbit will then:
• Catch hidden bugs
• Suggest better logic
• Improve readability
• Flag missing edge cases

It’s like having a senior developer review every pull request—instantly.
My full setup for stress-free AI dev

Claude Code → The executor
TaskMaster → The planner
CodeRabbit → The reviewer

If you’re building MVPs with AI, try this flow.

I’ve never shipped this fast or this clean.
