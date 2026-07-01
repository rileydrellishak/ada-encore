# 🧠 Python Fundamentals for Real Thinking

## 🌱 Why are we doing this?

At this point, Python is not new to you.

But clarity in Python is still something worth practicing.

This assignment is about refreshing the core building blocks — not as syntax to memorize, but as tools for expressing structured thought.

The goal is not speed.

The goal is control:

* knowing what your code is doing
* knowing why it is doing it
* and being able to explain it without guessing

---

## 📚 Learning Objectives

By the end of this assignment, you will be able to:

* Write and interpret basic Python syntax with confidence
* Use variables to represent state clearly
* Use conditionals to express decision-making logic
* Define and call simple functions
* Trace execution step-by-step without relying on intuition alone

---

## 📚 Refer to these Ada lessons (optional)

You may recognize much of this from earlier Ada Unit 1 material.

This is intentional — this assignment is a structured revisit of foundational Python concepts.

### 📖 [Fundamentals](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/fundamentals/functions-overview.md)

* variables and naming
* conditionals (`if / elif / else`)
* defining and invoking functions
* basic vocabulary of Python execution

### 📖 [How to Read Documentation](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/fundamentals/how-to-read-documentation.md)

* understanding function inputs and outputs
* interpreting examples instead of memorizing behavior

### 📖 [Invoking Functions](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/fundamentals/invoking-functions.md)

* how function calls actually execute
* argument passing and return values

If this feels familiar, treat it as reinforcement.

If it feels slightly fuzzy, that’s expected — clarity builds through repetition.

---

## 📖 Refresher (optional)

Before starting, try this quick mental warm-up:

Pick a simple decision you make daily, like:

* “Do I bring a jacket?”
* “Do I make coffee now or later?”

Then ask:

* What information do I use to decide?
* What are the possible outcomes?
* Can I express that decision as an IF / ELSE structure?

This is Python thinking without Python.

---

## 📝 Assignment Spec

You will complete a small set of exercises that reinforce core Python fundamentals.

---

### Part 1 — Variables and Meaning

Create variables that represent a real-world situation.

Example theme: “Getting ready in the morning”

Define at least:

* one boolean variable
* one string variable
* one numeric variable

Then write a short explanation:

> What does each variable represent in human terms?

---

### Part 2 — Conditionals as Decisions

Write at least **3 conditional statements** based on your variables.

Each conditional should represent a real decision.

Example structure:

```python id="cond_example"
if is_raining:
    print("Take an umbrella")
else:
    print("No umbrella needed")
```

Rules:

* Each condition must be meaningful (not arbitrary)
* Avoid overly complex logic
* Prioritize clarity over cleverness

---

### Part 3 — Functions as Reusable Logic

Write **one simple function** that encapsulates a decision or transformation.

Requirements:

* takes at least one parameter
* returns a value OR prints a result
* includes a docstring explaining what it does in plain English

Example structure:

```python id="func_example"
def should_bring_jacket(temp):
    """
    Determines whether a jacket is needed based on temperature.
    """
    if temp < 60:
        return True
    else:
        return False
```

---

### Part 4 — Trace the Code

For one of your conditionals or functions:

Write out step-by-step what the computer is doing when it runs it.

Do not skip steps.

Assume the reader has no intuition — only instructions.

---

## ✅ Acceptance Criteria

You are done when:

* You used variables to represent meaningful state
* You wrote at least 3 conditionals
* You wrote at least 1 function with a parameter
* You included a docstring explaining your function
* You can explain one piece of code step-by-step
* Your code is readable and uses clear naming

---

## ⭐ Stretch Goals (optional)

If you want to push further:

* Add multiple parameters to your function
* Add nested conditionals (only if clarity is preserved)
* Rewrite one conditional as a function
* Add edge cases to your logic (e.g., extreme temperatures, missing values)
* Refactor your variable names to be more descriptive

---

## ⏱️ Estimated Time

~60–90 minutes

This is a “slow is smooth” assignment — speed is not the objective.

---

## 🧠 Reflection Questions

* What felt familiar from Ada?
* What felt more intentional this time?
* Did you rely on intuition or step-by-step reasoning?
* Where did you notice ambiguity in your own logic?
* What part of your code would you improve for readability?

---

## 🌿 Encore Notes

Future Riley reflection space:

* Did you name variables clearly on the first try?
* Did you simplify or overcomplicate conditionals?
* Did writing functions feel natural or forced?
* Where did you pause to think instead of typing immediately?

---

## 🧰 Engineering Checklist

Before submitting:

* [ ] Variable names are meaningful
* [ ] Conditionals are readable and intentional
* [ ] Function has a clear purpose
* [ ] Function includes a docstring
* [ ] Code can be understood without explanation
* [ ] No unnecessary complexity
* [ ] Logic flows in a predictable way

---

## ☕ Coffee Chat with Future Riley

If someone asked you:

> “What are you practicing in this assignment?”

What would you say — in one or two sentences — without mentioning Python syntax?

---

## 🏆 Achievement Unlocked

**"You translated decisions into code without losing meaning."**

Python is not difficult because of syntax.

It is difficult because it forces clarity.

This assignment is about practicing that clarity deliberately.