# AI Builder Starter Kit — Prompt Pack

Use these prompts with ChatGPT, Claude, Gemini, Cursor, Lovable, Bolt, or Replit.

## 1) Idea → MVP Scope

```text
Act as a senior product engineer and startup PM.

I want to build: [describe your idea]
Target user: [who]
Main pain/problem: [pain]
My skill level: beginner / non-coder
Time budget: [e.g. 1 day, 1 week]
Tools I can use: ChatGPT, Cursor, Lovable/Bolt, GitHub Pages, Google Sheet

First, ask me up to 5 clarifying questions if needed.
Then produce:
1. The smallest useful MVP scope
2. Must-have vs nice-to-have features
3. User flow
4. Data needed
5. Step-by-step build plan
6. Risks/unknowns
7. A first prompt I should paste into my coding tool
```

## 2) Build Plan → Coding Tool Prompt

```text
You are my AI coding assistant.

Build a simple MVP with this scope:
[PASTE MVP SCOPE]

Constraints:
- Keep it simple and beginner-friendly
- Use plain HTML/CSS/JS unless a framework is truly needed
- Explain file structure first
- Build one working version before adding polish
- Include comments for any non-obvious code
- After code, give me a test checklist

Start by proposing the file structure and implementation plan. Do not write code until the plan is clear.
```

## 3) Debug Prompt

```text
Act as a patient senior developer debugging with a beginner.

Goal: [what I expected]
Actual result/error: [paste error]
Code/context: [paste relevant code]
Environment/tool: [Cursor/Lovable/Bolt/browser/Node/etc.]

Rules:
- Do not guess wildly
- Identify the 2-3 most likely causes
- Tell me exactly what to check first
- Then provide the smallest fix
- Explain why the fix works in simple language
```

## 4) API Learning Prompt

```text
Teach me how to use this API as a beginner: [API/tool]

I want to build: [small use case]

Explain:
1. What the API does in plain English
2. What an API key is and how to keep it safe
3. The simplest request example
4. Common errors and fixes
5. Estimated cost/rate limits
6. A tiny practice project
```

## 5) Launch Prompt

```text
Act as a practical growth marketer for a tiny AI-built project.

Product: [describe]
Target users: [who]
Main benefit: [benefit]
Proof/current status: [demo / beta / free]

Create:
1. Landing page headline and subheadline
2. 5 bullet benefits
3. FAQ
4. 3 launch posts: LinkedIn, Facebook group, Reddit/Discord style
5. Feedback questions for first 10 users
6. A low-pressure call-to-action

Avoid hype. Sound useful, human, and specific.
```
