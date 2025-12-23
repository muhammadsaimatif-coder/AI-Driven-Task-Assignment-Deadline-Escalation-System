📌 Automated Task Monitoring & Escalation Workflow
🧠 Project Overview

This project is an automation workflow built in n8n that monitors tasks stored in an Excel sheet. It evaluates task assignment, completion status, and deadlines using conditional logic (if-else statements). If a task is overdue and incomplete, the system automatically sends an email notification to the manager.

This workflow helps organizations reduce manual follow-ups, improve accountability, and ensure deadlines are met.

⚙️ Workflow Logic

Read task data from an Excel sheet

Check whether the task is assigned to an employee

If assigned:

Check whether the task is completed

If not completed:

Compare the end date with the current date

If the deadline has passed:

Send an email alert to the manager with:

Employee name

Task name

Due date

Status

✨ Key Features

Excel-based task input

Conditional logic using if/else

Automatic deadline validation

Email escalation to managers

No-code / low-code automation

Fully customizable workflow

🛠️ Tech Stack

n8n (Workflow Automation)

Excel (Task data source)

Email Service (SMTP/Gmail/Outlook)

Conditional Logic (IF/ELSE)

📈 Use Cases

Task management automation

Employee performance tracking

Deadline monitoring

Manager escalation system

Operations and HR automation
