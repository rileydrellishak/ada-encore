# 🐛 A Calm, Repeatable Debugging Workflow

## 🌱 Why this exists

Debugging can feel chaotic at first.

This is a simple, repeatable workflow you can fall back on when things break.

You don’t need to be clever.

You just need to be systematic.

---

## 🧭 Step 1 — Read the error slowly

Before touching your code:

* Read the full traceback
* Find the **last line first**
* Identify:

  * file
  * line number
  * error type

👉 Do not guess yet.

---

## 🧭 Step 2 — Locate the problem line

Go to the exact line mentioned in the error.

Ask:

* What was I expecting this line to do?
* What is it actually doing?

If unclear → read surrounding lines.

---

## 🧭 Step 3 — Classify the problem

Most bugs fall into 3 categories:

### 1. Syntax error

Python can’t read your code at all.

Examples:

* missing colon
* missing parenthesis

### 2. Runtime error

Code runs, then breaks.

Examples:

* wrong type
* missing key
* invalid operation

### 3. Logic error

Code runs perfectly… but does the wrong thing.

👉 These are the trickiest.

---

## 🧭 Step 4 — Isolate the issue

Reduce uncertainty:

* Comment out parts of code
* Print intermediate values
* Simplify inputs

Goal:

> make the problem smaller, not more complex

---

## 🧭 Step 5 — Make ONE change

Do not:

* rewrite everything
* change multiple things at once

Do:

* change one thing
* re-run
* observe

---

## 🧭 Step 6 — Verify understanding

After fixing:

Ask yourself:

> What was actually wrong?

Not:

> “What did I change?”

---

## 🌿 Reminder

Debugging is not:

* guessing faster
* trying random fixes

Debugging is:

> reducing uncertainty until the answer becomes obvious