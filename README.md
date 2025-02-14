# CSS calc() Unexpected Behavior

This repository demonstrates a common, yet often overlooked, issue when using the CSS `calc()` function. The problem arises from a combination of operator precedence, unit handling, and nested calculations.

The `bug.css` file contains CSS code that exemplifies the unexpected behavior. The `bugSolution.css` provides a corrected version.

**Key Issues:**

* **Missing Units:**  `calc()` requires units for all values.
* **Operator Precedence:**  Nested calculations may lead to unexpected results if the order of operations is not explicitly controlled.
* **Unit Mismatch:** Combining `calc()` with properties expecting specific units needs careful consideration.

This example highlights the importance of thorough testing and understanding the intricacies of the `calc()` function to prevent such subtle errors.