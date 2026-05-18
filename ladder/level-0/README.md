# Level 0 — Basic AI Chat

*Part of the [ContextOS Maturity Ladder](../../README.md#maturity-ladder).*

---

## Purpose

This is the starting point. Everyone begins here.

A person at Level 0 uses an AI assistant the way most people do: as a conversational tool. They open a chat, ask a question or give a task, get a response, and move on. There is no formal structure, no persistent memory, and no system for capturing what was useful.

This level is not a failure state. It is where everyone starts. The goal of documenting it is to help people recognise where they are without feeling judged, and to show them what they gain by taking one small step forward.

---

## Starting State

- Access to at least one AI assistant (any model, any interface)
- No notes system connected to AI work
- No source-of-truth document
- No handover habit
- No version control for AI-assisted work
- Context lives in chat history or the user's head

---

## Minimum Setup

There is one action at Level 0: create a simple Starter Profile.

This is a short instruction document containing three things:

- Who you are
- What you are working on
- How you prefer the AI to work with you

For most tools, this can be pasted into custom instructions, project instructions, or the first message of a new chat. The specific format does not matter. What matters is that you stop re-explaining yourself from scratch every time.

A ready-to-fill template is available at: [`starter-profile.md`](./starter-profile.md)

Fill in three fields. Five minutes. You are now operating better than the vast majority of AI users.

---

## Tools Required

**One AI assistant.** Any model, any interface. Browser, app, API, terminal. The specific tool does not matter at this level.

No other tools are required. That is both the simplicity and the limitation.

---

## Operating Rules

There are no formal operating rules at Level 0. That is part of what makes it Level 0.

In practice, most Level 0 users develop informal habits:

- Re-explain their context at the start of every new chat
- Copy-paste useful outputs into documents or messages manually
- Lose track of what they asked last week
- Repeat similar prompts across sessions without realising
- Trust the AI's memory (which does not exist between sessions in most tools)

These habits are not wrong. They are simply the natural result of using a powerful tool without any supporting structure.

---

## Example Workflow

**Task:** Write an email to a client about a project delay.

**During:** Open an AI assistant. Type: "Help me write a professional email explaining that our project is delayed by two weeks due to a supply chain issue." Read the response. Copy it. Paste it into email. Send.

**After:** Close the chat. The email is sent. The conversation is gone. If you need a similar email next month, you start from scratch.

---

## Success Test

Level 0 is working when you can start a fresh chat, paste your Starter Profile, ask a relevant question, and get a response that already reflects:

- who you are
- what you are working on
- how you prefer the assistant to work with you

The test is simple:

1. Open a new chat with any AI assistant.
2. Paste your Starter Profile.
3. Ask: "Based on this profile, help me with one task I am likely to care about."
4. Check whether the response feels more relevant than a blank-chat answer.

If the assistant understands your context without you re-explaining it, Level 0 is working.

**First prompt to run:**

Open a new chat, paste your Starter Profile, then add this on a new line:

```
Based on this profile, help me with one task I am likely to care about right now.
```

---

## When Level 0 Starts To Feel Limited

Level 0 starts to feel limited when:

- You start a complex project that spans multiple sessions and lose context between them
- You find yourself re-explaining the same background information every time you open a new chat
- Useful outputs (a good prompt, a framework, a decision rationale) disappear into closed chats and cannot be found again
- You start relying on AI for work that matters (client deliverables, code, strategy) but have no way to verify, version, or recover what was produced
- You are spending more time getting the AI up to speed than doing actual work

These failure modes are not catastrophic. They are friction. But friction compounds. When the friction becomes noticeable, you are ready for Level 1.

---

## Lessons Learned

These are the patterns most people notice once they start using AI regularly.

### Chat history is not memory
If you keep re-explaining your role, projects, preferences, or working style, your setup has no continuity. AI assistants do not reliably retain context between sessions unless you give them a structure to read.

### Useful outputs vanish unless you capture them
Good prompts, frameworks, and decisions disappear quickly if they stay buried in chat history. If something is worth reusing, copy it into a note, document, or file with a permanent address.

### Re-establishing context costs more than maintaining it
Every minute spent re-explaining old context is a minute not spent on the task. When rebuilding context becomes more expensive than keeping a simple notes file, you are ready for Level 1.

---

## Upgrade Trigger

You are ready for Level 1 when any of these become true:

1. You catch yourself re-explaining your background or preferences more than twice a week
2. You lose a useful AI output and cannot find it again
3. You start a project that will take more than one session and realise the AI has no idea what happened in the previous session
4. You are spending more time getting the AI up to speed than doing the actual work

These are observable, specific signals — not feelings. If one of these is true, you have outgrown Level 0.

The fix is simple: one notes app, one source-of-truth document, one handover habit. That is Level 1.

---

## Upgrade Detection

The [Starter Profile](./starter-profile.md) includes one extra paragraph that asks your assistant to watch for frustration signals during the conversation and ask a single question when they appear.

Signals the assistant watches for:

- Repeated re-explanation of the same background information within a session
- Short sharp corrections: "no, not like that", "I've told you this before", "why do I keep explaining this"
- Expressions of friction around context loss or memory
- Starting a sentence with "again" or "as I said"

When the assistant detects these patterns it pauses and asks:

> "It sounds like you might be hitting the limits of this setup. Would you like to know how to fix that permanently?"

If yes, the assistant shares the Level 1 guide link. If no, the conversation continues.

This works within a single session only — the assistant reads the profile and watches the conversation as it happens. Detecting patterns across multiple sessions requires a notes system, which is what Level 1 adds.

---

*Next: Level 1 — Solo Starter (coming soon)*
