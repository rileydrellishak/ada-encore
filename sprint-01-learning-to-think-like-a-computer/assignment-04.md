# 🧱 Writing Clean, Reusable Functions

## 🌱 Why are we doing this?

So far, you’ve been:

* breaking down problems
* writing basic Python
* debugging broken code

Now we take the next step:

> Instead of writing one long sequence of instructions, we start packaging logic into reusable pieces.

Functions are how we give structure to code.

Without them, programs become hard to understand very quickly.

With them, programs become:

* readable
* testable
* reusable
* easier to debug

This assignment is about learning to think in *units of logic*, not just lines of code.

---

## 📚 Learning Objectives

By the end of this assignment, you will be able to:

* Write functions that encapsulate a single clear purpose
* Pass parameters to functions intentionally
* Return values instead of relying only on print statements
* Identify when code should be split into multiple functions
* Refactor repeated logic into reusable functions
* Read function signatures as “intent statements”

---

## 📚 Refer to these Ada lessons (optional)

This assignment builds directly on Ada’s early function concepts.

You may recognize these ideas:

### 📖 [Defining Functions](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/fundamentals/defining-functions.md)

* how functions are structured
* inputs vs outputs
* indentation and scope

### 📖 [Invoking Functions](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/fundamentals/invoking-functions.md)

* how arguments are passed
* how return values are used

### 📖 [Functions Overview](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/fundamentals/functions-overview.md)

* why functions exist at all
* reducing repetition
* organizing logic

If these feel familiar, you’re not reviewing — you’re strengthening.

---

## 📖 Refresher (optional)

Before starting, think about this:

Pick a repetitive task you do often, like:

* making coffee
* checking your phone in the morning
* packing a bag

Now ask:

> What parts of this task are always the same?

> What parts change slightly each time?

This is exactly what functions are for:

* stable structure + flexible inputs

---

## 📝 Assignment Spec

You will take messy logic and refactor it into clean, reusable functions.

---

### Part 1 — Identify repeated logic

Look at a small piece of code (or write one yourself) that includes repetition.

Example idea:

* multiple conditional checks
* repeated calculations
* repeated print logic

Your job:

* identify what is being repeated
* describe it in plain English

---

### Part 2 — Extract into functions

Take the repeated logic and turn it into at least **2 functions**.

Each function must:

* have a clear purpose
* take at least one parameter
* return a value OR produce a clearly defined output

Example structure:

```python id="func_example_1"
def is_even(number):
    return number % 2 == 0
```

---

### Part 3 — Refactor usage

Rewrite your original code so it uses your new functions.

Goal:

* remove repetition
* improve clarity
* make the code read like a sequence of intentions

Before:

```text id="before_example"
check number
if number % 2 == 0:
    print("even")
if number % 2 == 0:
    do something else
```

After:

```python id="after_example"
if is_even(number):
    print("even")
```

---

### Part 4 — Function tracing

Pick one of your functions and answer:

* What goes in?
* What transformations happen inside?
* What comes out?
* What would break if I changed the input type?

Be explicit. Walk through execution line by line.

---

## ⚠️ Common Pitfalls (read before starting)

* Writing functions that do too many things at once
* Using functions that only print instead of returning values
* Copy-pasting logic instead of refactoring
* Naming functions vaguely (e.g., `do_thing`, `process`)
* Forgetting that functions should be reusable

---

## ✅ Acceptance Criteria

You are done when:

* You created at least 2 meaningful functions
* Each function has a clear, single responsibility
* You replaced repeated logic with function calls
* You used parameters instead of hardcoding values
* You included at least one function trace explanation
* Your code is easier to read than the original version

---

## ⭐ Stretch Goals (optional)

If you want to go further:

* Break one function into two smaller functions
* Convert a print-based function into a return-based function
* Add type hints (lightly, optional preview of future habits)
* Write a second version of your solution that is even simpler
* Rename all functions for maximum clarity (pretend someone else will read them)

---

## ⏱️ Estimated Time

~60–90 minutes

Refactoring often takes longer than writing from scratch — that is normal.

---

## 🧠 Reflection Questions

* Did breaking code into functions make it easier or harder to understand?
* Where did you struggle to decide what “one responsibility” means?
* Did you initially write functions too large or too small?
* What changed when you started naming functions clearly?
* How does this compare to how you wrote code during Ada?

---

## 🌿 Encore Notes

Future Riley reflection space:

* Did you resist or embrace refactoring?
* Did you notice repeated logic more quickly than before?
* Did functions feel like structure or overhead?
* Where did clarity improve most noticeably?

---

## 🧰 Engineering Checklist

Before submitting:

* [ ] Each function has a single clear purpose
* [ ] No duplicated logic remains
* [ ] Functions use parameters (not hardcoded values)
* [ ] Function names are descriptive and readable
* [ ] Code reads like a sequence of intentions
* [ ] You can explain each function in one sentence

---

## ☕ Coffee Chat with Future Riley

If you had to explain functions to someone new in one sentence:

> What would you say they are actually for?

(no mentioning Python syntax allowed)

---

## 🏆 Achievement Unlocked

**"You learned to package thinking into reusable pieces."**

Functions are not a Python feature.

They are a way of organizing thought so it doesn’t collapse under its own complexity.

This is one of the first real “engineering habits” you are building in this sprint.