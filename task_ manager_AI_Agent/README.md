# Task Manager AI Agent

AI-powered task management assistant built with :contentReference[oaicite:0]{index=0}, Telegram Bot API, OpenAI API, and Google Sheets.

## 📌 Overview

Task Manager AI Agent helps users manage tasks directly from Telegram using natural language commands.

## Workflow Preview

![Workflow](/task_%20manager_AI_Agent/images/task_manager_AI_Agent.png)

## Demo

![Demo](/task_%20manager_AI_Agent/images/photo_2026-05-20_11-18-09.jpg)

The AI agent can:

- show all tasks
- add new tasks
- mark tasks as completed
- update task statuses in Google Sheets
- send Telegram notifications

---

## ⚡ Features

- AI-powered Telegram assistant
- Task management automation
- Google Sheets integration
- Natural language processing
- Real-time Telegram notifications
- Automated task status updates

---

## 🔄 Workflow Logic

1. User sends a message in Telegram
2. AI agent analyzes the request
3. The workflow selects the required tool:

- Get Task
- Add Task
- Done Task

4. Google Sheets is updated
5. Telegram sends a response to the user

## 🛠 Available Tools

### Get Task

![Workflow](/task_%20manager_AI_Agent/images/get_task.png)

Returns the current list of tasks from Google Sheets.

---

### Add Task

![Workflow](/task_%20manager_AI_Agent/images/add_task.png)

Adds a new task to Google Sheets and confirms successful creation in Telegram.

---

### Done Task

![Workflow](/task_%20manager_AI_Agent/images/done_task.png)

Marks a task as completed in Google Sheets.
