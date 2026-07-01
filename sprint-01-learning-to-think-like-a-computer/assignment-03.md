# 🐛 Debugging Without Panic

## 🌱 Why are we doing this?

At some point, every program will break.

Not because you are bad at coding.

But because:

* computers are literal
* humans are imprecise
* and the space between those two is where bugs live

Debugging is not a failure state.

It is a normal part of writing software.

This assignment is about learning how to read errors without emotional interference — and how to treat broken code as information, not judgment.

---

## 📚 Learning Objectives

By the end of this assignment, you will be able to:

* Read Python error messages without immediately guessing
* Identify where a program fails using tracebacks
* Distinguish between syntax, runtime, and logic errors (light introduction)
* Use print statements as a debugging tool
* Trace code execution step-by-step
* Develop a calm, structured debugging workflow

---

## 📚 Refer to these Ada lessons (optional)

This assignment builds on earlier Ada debugging material.

You do NOT need to re-study everything — use this as a memory anchor.

### 📖 [Intro to Debugging](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/intro-to-debugging/intro-to-debugging.md)

* what debugging means in practice
* common types of errors
* why errors are expected, not exceptional

### 📖 [Intro to Errors](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/intro-to-debugging/intro-to-errors.md)

* syntax vs runtime errors
* reading error messages
* understanding where failure occurs

### 📖 [Identifying Errors](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/intro-to-debugging/identifying-errors.md)

* interpreting tracebacks
* locating the source of a problem vs the symptom

### 📖 [Debugging Cont’d](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/debugging-contd/debugging-contd.md) (light reference)

* iterative debugging process
* narrowing down failure points

If these feel familiar, that’s the point.

We are strengthening recall through repetition with experience.

---

## 📖 Refresher (optional)

Before starting, try this mental warm-up:

Think of a time something “didn’t work” in daily life:

* a recipe that went wrong
* a miscommunication
* a plan that failed halfway through

Ask yourself:

* What was the first sign something was wrong?
* What information helped you figure it out?
* What assumptions turned out to be incorrect?

That is debugging.

---

## 📝 Assignment Spec

You will work with intentionally broken code and practice diagnosing issues.

---

### Part 1 — Reading Errors First

You will be given (or create) small Python snippets that contain errors.

For each snippet:

1. Run the code
2. Read the error message carefully
3. Answer:

   * Where did the error occur?
   * What type of error is it?
   * What is Python trying to tell you?

Do NOT fix anything yet.

Your only job is interpretation.

---

### Example

```python id="error_example"
def add_numbers(a, b):
    return a + b

print(add_numbers(5))
```

### Your response:

* Where did it fail?
* What does Python think is wrong?
* What information is missing?

---

### Part 2 — Fix the Code

Now fix the issues you identified.

Rules:

* Make the smallest possible change to fix the bug
* Do not rewrite the whole function unless necessary
* Keep original intent intact

After fixing, explain:

> What was actually wrong vs what you initially thought was wrong?

---

### Part 3 — Print-Based Debugging

Take a simple function and insert print statements to understand execution flow.

Example:

```python id="debug_example"
def calculate_total(price, tax):
    print("Starting calculation")
    total = price + tax
    print("Total so far:", total)
    return total
```

Your goal:

* Use prints to observe values at each step
* Identify where logic diverges from expectation

Then remove or reduce prints after understanding the flow.

---

### Part 4 — Trace the Execution

Choose one function you wrote earlier in this sprint.

Write a step-by-step trace of:

* what values enter the function
* what happens at each line
* what gets returned
* where confusion *could* occur

Be extremely literal.

Assume no intuition — only execution.

---

## ⚠️ Common Pitfalls (read this before starting)

* Jumping to fix code before reading the error
* Assuming the bug is “obvious”
* Ignoring line numbers in tracebacks
* Changing multiple things at once (makes debugging harder)
* Forgetting to test after a fix

---

## ✅ Acceptance Criteria

You are done when:

* You correctly interpret at least 2 error messages
* You fix at least 2 broken code snippets
* You use print statements to debug at least 1 function
* You write a full execution trace for 1 function
* You can explain at least one bug before fixing it
* You make minimal, intentional fixes

---

## ⭐ Stretch Goals (optional)

If you want to go further:

* Categorize each error as syntax / runtime / logic
* Try fixing a bug in 2 different ways and compare
* Debug without immediately running code (predict first)
* Remove all print statements and re-verify correctness
* Introduce a bug intentionally and then debug it

---

## ⏱️ Estimated Time

~60–90 minutes

This assignment is intentionally slower than it looks.

Most of the work is thinking, not coding.

---

## 🧠 Reflection Questions

* What was your first instinct when you saw an error?
* Did you read or skip the traceback first?
* Where did your mental model of the code differ from reality?
* What changed after you started using print debugging?
* How would you describe “debugging” to someone new now?

---

## 🌿 Encore Notes

Future Riley reflection space:

* Did you panic or pause when you saw errors?
* Did you rush to fix or understand first?
* Did print debugging feel clarifying or messy?
* Where did you notice improvement in patience or structure?

---

## 🧰 Engineering Checklist

Before submitting:

* [ ] You read error messages before fixing anything
* [ ] You made minimal, targeted fixes
* [ ] You can explain at least one bug clearly
* [ ] You used print debugging intentionally
* [ ] You removed unnecessary debugging prints
* [ ] You understand what actually went wrong (not just the fix)

---

## ☕ Coffee Chat with Future Riley

If someone asked:

> “What does debugging feel like now compared to Ada?”

What would you say in one or two sentences?

---

## 🏆 Achievement Unlocked

**"You stopped guessing and started listening to the code."**

Debugging is not about being right immediately.

It is about narrowing uncertainty until the problem becomes obvious.

That skill changes everything that comes next.