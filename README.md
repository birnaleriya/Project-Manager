# 🤖 AI-Powered Project Management with AI Agents

Ever wished you had a smart assistant that could take your project idea and instantly break it down into tasks, assign them to the right people, flag risks, and give you actionable insights — all in one go? That's exactly what this does.

Built with **Streamlit** for the interface and **Airtable** as the backend, this tool uses a chain of AI agents that work together to take a project description from raw idea to a fully structured, allocated, and risk-assessed plan.

---

## What it does

Here's what happens when you hit that submit button:

- 📋 Reads your team's skills from a CSV you upload
- 🤖 Generates a list of tasks from your project description
- 🧩 Figures out which tasks depend on each other
- 📅 Schedules tasks in the right order
- 👥 Assigns each task to the best-fit team member
- ⚠️ Spots potential risks before they become problems
- 📊 Wraps it all up with insights you can actually use
- 🔄 Saves everything to Airtable and lets you export a CSV

---

## CSV format

Your team CSV should look like this:

```csv
Name,Profile Description
Alice,Python, ML, AI
Bob,Project Management, Scrum
```

Keep it simple — just names and skills. The agents handle the rest.
