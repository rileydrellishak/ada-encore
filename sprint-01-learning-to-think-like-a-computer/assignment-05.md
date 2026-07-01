# 🧪 Testing as a Thinking Tool

## 🌱 Why are we doing this?

So far, you’ve been writing code and checking if it “seems right.”

Testing is the shift from:

> “I think this works”

to:

> “I can prove what this code does.”

Tests are not about catching failure after the fact.

They are about defining what success *means* before you even run the code.

This changes how you think about programming entirely.

---

## 📚 Learning Objectives

By the end of this assignment, you will be able to:

* Understand tests as specifications of behavior
* Write simple unit tests using pytest-style thinking
* Distinguish between implementation and expected behavior
* Verify functions using repeatable test cases
* Think in terms of inputs → expected outputs
* Use testing to clarify unclear logic

---

## 📚 Refer to these Ada lessons (optional)

### 📖 [Intro to Tests / pytest](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/intro-to-tests/intro-to-pytest.md)

* what automated tests are
* how tests describe expected behavior
* basic structure of test functions

### 📖 [Test-Driven Development (TDD)](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/intro-to-tests/test-driven-development.md)

* writing expectations before implementation
* using tests to guide design

### 📖 [Activity: Tests](https://github.com/Ada-Developers-Academy/core-unit-1/blob/main/intro-to-tests/activity-tests.md)

* understanding expected vs actual output

If this feels familiar, good — now you’re using it as an engineering tool, not just a concept.

---

## 📖 Refresher (optional)

Think about something you *expect* to always behave the same way:

* a calculator
* a light switch
* a vending machine

Now ask:

> What inputs would prove it is working correctly?

That is testing.

---

## 📝 Assignment Spec

You will write simple functions and verify them using test cases.

---

### Part 1 — Define behavior clearly

Choose 2 simple functions (you may reuse from previous assignments).

For each function, write:

* what it should do
* what inputs it expects
* what outputs are correct

---

### Part 2 — Write test cases

For each function, write at least 3 test cases.

Example:

```python id="test_example"
def test_is_even():
    assert is_even(2) == True
    assert is_even(3) == False
    assert is_even(0) == True
```

Focus on:

* normal cases
* edge cases (small or unusual inputs)
* clarity of expectation

---

### Part 3 — Run and validate

Make sure:

* all tests pass
* failing tests are understood before fixing code
* tests match intended behavior (not implementation)

---

### Part 4 — Reflect on mismatch

If any test fails:

* Was the test wrong?
* Was the function wrong?
* Or was your understanding incomplete?

Write a short explanation.

---

## ⚠️ Common Pitfalls

* writing tests after confirming code works
* testing implementation instead of behavior
* using only “happy path” inputs
* changing code instead of understanding failing tests

---

## ✅ Acceptance Criteria

You are done when:

* You wrote at least 2 testable functions
* You wrote at least 6 test cases total
* You used assertions to verify behavior
* You can explain at least one test failure (if any occurred)
* Your tests describe behavior, not implementation

---

## ⭐ Stretch Goals (optional)

* Practice TDD (write tests before code)
* Add edge case tests deliberately
* Break one function and ensure tests catch it
* Improve function design based on test difficulty
* Group related tests together for clarity

---

## ⏱️ Estimated Time

~60–90 minutes

Testing slows you down at first — and makes you much faster later.

---

## 🧠 Reflection Questions

* Did writing tests change how you wrote your functions?
* Did you discover unclear behavior while writing tests?
* Which was harder: writing code or writing tests?
* Did tests make your thinking more precise?
* How does “correctness” feel different now?

---

## 🌿 Encore Notes

* Did tests reveal assumptions you didn’t realize you made?
* Did you think more about edge cases than usual?
* Did you trust your code less or more after testing?
* What did tests clarify that code alone didn’t?

---

## 🧰 Engineering Checklist

* [ ] At least 2 functions tested
* [ ] At least 6 test cases written
* [ ] Tests reflect behavior, not implementation
* [ ] Edge cases included
* [ ] All tests pass
* [ ] Failed tests (if any) were understood, not guessed at

---

## ☕ Coffee Chat with Future Riley

> How has your definition of “working code” changed after writing tests?

---

## 🏆 Achievement Unlocked

**"You learned to define correctness before execution."**

Testing is not about catching mistakes.

It is about making expectations explicit.

That is what turns code into engineering.