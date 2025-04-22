# CIS 3500: Nara Extension Starter

## Overview
This assignment involves enhancing a Chrome extension developed by one of the Top 3 winners of the MCIT hackathon. The project provides hands-on experience in web development, API integration, and collaborative coding.

**Original project:** [Nara](https://github.com/luyiZhang818/Nara-Chrome-Extension)

## Project Description
Nara is a Chrome extension that helps users manage their tasks and reminders efficiently. Your task is to enhance this extension by implementing new features.

## Enhancement Options
Choose one of the following enhancements to implement:

1. **Speech Bubble Encouragement**: Implement a feature where, whenever the user checks off a task, a speech or thought bubble appears near the deer with a short, encouraging message (e.g., “Great job!”, “You’re making progress!”, “Keep going!”).
2. **Daily Gratitude Log**: Implement a small text area where users can note one thing they’re grateful for each day. Over time, they can revisit a dedicated “gratitude log” to see their positive moments. Provide an interesting method to save these entries and display them on a separate screen so users can easily access their past entries.
3. **Mood Selection Prompt**: Implement a simple mood selection feature(e.g., happy, stressed, neutral) with a small icon or emoji. This allows users to log their emotional state quickly each day.
4. **Rotating Weekly Challenge**: Implement a weekly challenge system—such as “Drink 8 glasses of water each day” or “Take a 10-minute walk daily.” Users can check off these mini-challenges alongside their normal tasks for extra motivation.
5. **Inspirational Quote Overlay**: Implement a short inspirational quote or positive affirmation that appears on each new tab, displayed in a subtle text overlay.
6. **Implement a History Feature**: Maintain a log of all tasks and reminders created by the user, allowing them to revisit past items and track progress over time.
7. **Custom Feature**: Propose a unique feature (requires instructor/TA approval).

## Getting Started

### Step 1: Team Organization
- Assign a team member as the **Product Manager (PM)** for Nara.
- Ensure this PM is different from the one assigned to the Lunch Lotto project.

### Step 2: Repository Setup
The PM should fork the repository:
1. Navigate to the `nara-extension-starter` repository on GitHub.
2. Click the **Fork** button to create a copy under their account.

### Step 3: Cloning the Repository
Once the PM has forked the repository, team members should clone it locally:
```sh
git clone https://github.com/<PM-username>/nara-extension-starter.git
```

### Step 4: Development Workflow
1. Open the project in a text editor (e.g., **Visual Studio Code** recommended).
2. Make changes to the codebase.
3. Use the following commands to commit and push your changes:

```sh
git add .
git commit -m "feat: [feature name] added"
git push
```

4. As team members contribute, collaborate using **Pull Requests (PRs)** on GitHub.
5. Regularly sync your local repository with the latest changes:

```sh
git pull
```

6. Resolve merge conflicts as needed and ensure smooth integration.

## Features Implemented

### 1. Daily Gratitude Input
Users can write and save one thing they’re grateful for each day through a clean, accessible input area. Each entry is stored with a timestamp in `chrome.storage.local`, encouraging consistent reflection and positivity. If a user inputs two things in one day the first is overwritten.

Clicking the “View Gratitude Log” button transitions the user to a dedicated gratitude log screen with a new background. Entries are grouped by date and dynamically displayed from storage, allowing users to revisit their moments of gratitude anytime. A “Back” button returns users to the main UI seamlessly.

### 3. Speech Bubble Encouragement
Each time a task is checked off, a speech bubble appears near the deer character with a random motivational message (e.g., “Great job!”, “You’re making progress!”). This adds a playful, rewarding touch to task completion and reinforces positive behavior.


## Submission
- Submit the final version of your project as per course guidelines.
- Include a brief write-up of your implemented features and any challenges faced.

---
Happy coding, and good luck with Nara! 🦌
