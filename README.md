# Uncommon CSS `calc()` Errors and Solutions

This repository demonstrates and resolves some uncommon errors related to the CSS `calc()` function.  `calc()` is a powerful tool, but its flexibility can lead to unexpected issues if not used correctly.  This example highlights common pitfalls and provides clear solutions.

## Bugs

* **Incompatible Units:** Mixing units without proper consideration (e.g., combining percentages and pixels directly without handling potential conflicts) can lead to unexpected results. 
* **Missing Spaces:** Forgetting spaces around operators (+, -, *, /) within the `calc()` function can cause parsing errors.
* **Invalid Results:**  If the calculation in `calc()` results in an invalid value (e.g., a negative width), it can have unforeseen consequences.

## Solutions

The provided solution addresses these issues by:

* **Unit Consistency:** Ensuring consistent use of units within a single `calc()` expression to maintain predictability.
* **Space Usage:** Using spaces correctly to ensure correct calculation parsing. 
* **Error Handling:** Implementing checks to anticipate and handle invalid `calc()` results gracefully (e.g., providing default values).

## How to Use

1. Clone this repository.
2. Open `bug.css` to see the example with issues. 
3. Open `bugSolution.css` to view the corrected CSS. 