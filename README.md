# One Moment

A minimal emotional regulation tool for the moment right before procrastination happens.

---

## What It Does

One Moment creates a single steady pause at the edge of avoidance. When uncomfortable feelings like anxiety, overwhelm, sadness, or frustration start to build before a task, the user names the feeling and the companion models regulation — tensing slightly, then breathing, then settling into stillness. At the end, the user chooses to continue or step away.

It does not track, judge, reward, or remember anything.

---

## How to Use

1. Open `index.html` in a browser (or use Live Server in VS Code)
2. Type what you are feeling into the input field
3. Press Enter or click the button
4. Watch the companion and follow the breath guide
5. When ready, choose **stay** or **leave**

---

## Files
```
index.html   — structure and SVG companion
style.css    — layout, animation, and emotion themes
script.js    — ritual logic, emotion classification, expressions
```

---

## Emotions Recognized

| What you type | Theme |
|---|---|
| anxious, stressed, nervous, worried, panic... | Anxious |
| overwhelmed, stuck, frozen, scattered, lost... | Overwhelmed |
| sad, lonely, grief, empty, tired, heartbroken... | Sad |
| angry, frustrated, rage, irritated, furious... | Angry |
| calm, peaceful, okay, content, relaxed... | Calm |

Anything not recognized defaults to the overwhelmed theme.

---

## Design Principles

- No data is stored. No behavior is tracked.
- The user is never rewarded or punished for their choice.
- The companion reflects the emotional tone without exaggerating it.
- Emotions rise and settle. The tool models that without instruction.

---

## Running Locally

No build step or dependencies required. Open `index.html` directly in any modern browser, or use the **Live Server** extension in VS Code for auto-reload during development.