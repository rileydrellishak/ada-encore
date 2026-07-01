# 🧩 Breaking Down Problems Like a Programmer

## 🌱 Why are we doing this?

Before you write code that runs, you need to write thoughts that *behave like code*.

Most programming bugs don’t come from Python.

They come from unclear thinking.

This assignment is about slowing down just enough to turn messy human thoughts into steps that are precise enough to survive misinterpretation.

Not perfect steps.

Just *clear enough steps that you could explain them to someone else without waving your hands around wildly.*

---

## 📚 Learning Objectives

By the end of this assignment, you will be able to:

* Break a problem into smaller, meaningful steps
* Translate natural language into pseudocode
* Identify inputs, outputs, and constraints
* Practice structured thinking before writing Python
* Communicate a solution clearly enough for another engineer to follow

---

## 📚 Refer to these Ada lessons (optional)

- [Approaching a Problem](https://github.com/Ada-Developers-Academy/core-unit-1/tree/main/approaching-a-problem)

---

## 📖 Refresher (optional)

If you want a quick warm-up before starting:

* Think of a recipe you know well (like making pasta or coffee)
* Ask yourself:

  * What are the steps?
  * What must happen first?
  * What can go wrong?
* Notice how you naturally *sequence* actions without thinking about code yet

You are already doing programming in everyday life — we’re just making it explicit.

---

## 📝 Assignment Spec

You are going to practice turning vague problems into structured solutions.

### Part 1 — Break it down

Choose **one** of the following everyday tasks:

* Making a sandwich
* Planning a morning routine
* Packing a bag for travel
* Doing laundry
* Getting ready for work or school

Now write:

### 1. Inputs

What information do you start with?

Example:

* Hunger level
* Available ingredients
* Time available

---

### 2. Outputs

What does “done” look like?

Example:

* A finished sandwich
* You are ready and out the door

---

### 3. Step-by-step breakdown

Write the process as a sequence of instructions.

Rules:

* Be specific enough that a very literal robot could follow it
* Avoid vague steps like “get ready” or “prepare food”
* If a step is unclear, break it down further

Example format:

```text id="b1kq2p"
1. Open fridge
2. Check for bread
3. Remove two slices of bread
4. Place bread on plate
```

---

### Part 2 — Pseudocode translation

Now rewrite your steps as **pseudocode**.

You are not writing Python yet.

You are writing *structured logic*.

You may use constructs like:

* IF / ELSE
* WHILE
* FOR EACH
* SET / DEFINE

Example:

```text id="pseudocode_example"
IF bread is available:
    take 2 slices
ELSE:
    choose alternative food
```

---

### Part 3 — Tiny Python bridge (light intro)

Take ONE small part of your pseudocode and translate it into Python.

Keep it simple.

Example:

```python id="py_example"
bread_available = True

if bread_available:
    print("Take 2 slices of bread")
else:
    print("Choose alternative food")
```

You are NOT expected to build a full program.

This is just to connect thinking → syntax.

---

## ✅ Acceptance Criteria

You are done when:

* You have clearly defined inputs and outputs
* You wrote a step-by-step breakdown of a real-world task
* You translated that breakdown into pseudocode
* You wrote at least one small Python snippet from your logic
* Your steps are specific enough that someone else could follow them without guessing
* Your solution avoids vague instructions like “do it” or “prepare”

---

## ⭐ Stretch Goals (optional)

If you want to push a bit further:

* Break your steps into reusable functions (even in pseudocode)
* Add edge cases (What if you're missing an ingredient? What if you're out of time?)
* Rewrite your steps in a more efficient order
* Ask: “Where would a computer get confused here?”
* Turn your pseudocode into *actual runnable Python* for the whole flow

---

## ⏱️ Estimated Time

~45–90 minutes

This assignment is intentionally light on code and heavier on thinking.

---

## 🧠 Reflection Questions

Answer in 3–6 sentences each:

* What part of breaking down the problem felt easiest?
* Where did you notice ambiguity in your thinking?
* Did you refine any steps after writing them down?
* What would have confused a computer in your first draft?
* How does this compare to how you would have approached this during Ada?

---

## 🌿 Encore Notes

Future Riley observation space:

* Did you naturally want to skip steps?
* Did you find yourself using vague language at first?
* Did pseudocode feel helpful or restrictive?
* Did you notice improvement in clarity after rewriting?

---

## 🧰 Engineering Checklist

Before submitting:

* [ ] Steps are specific, not vague
* [ ] Inputs and outputs are clearly defined
* [ ] Pseudocode uses structured logic (IF / ELSE / etc.)
* [ ] At least one Python snippet is included
* [ ] No unnecessary complexity added
* [ ] You could hand this to someone else and they could follow it
* [ ] You would be comfortable opening this as a PR

---

## ☕ Coffee Chat with Future Riley

If you had to explain this assignment to someone on your Oracle team in 30 seconds:

> What would you say you were actually practicing here?

---

## 🏆 Achievement Unlocked

**"You taught a human idea how to behave like a program."**

At this stage, programming is less about syntax and more about translation.

You are learning the language between intention and execution.

That’s the real skill underneath everything else.