# CSS Specificity Gotcha: Unexpected Cascading with IDs and Nested Selectors

This repository demonstrates an uncommon issue related to CSS specificity, particularly involving the interaction of ID selectors, class selectors, and nested elements. The issue lies in the sometimes-unintuitive way specificity rules cascade when combining these selector types.

## Bug Description

The core problem arises from the unexpected behavior when combining high-specificity selectors (IDs) with more general selectors (classes) and nested elements.  This can lead to unexpected visual results, making debugging more complex.

## Bug Reproduction

The `bug.css` file contains the CSS code that demonstrates the problem.  The HTML (not included, as it's not strictly necessary to demonstrate the bug) would simply involve elements matching the selectors in the CSS (e.g., a `div` with an ID of `myDiv` and a class of `container`).

## Solution

The `bugSolution.css` file provides a corrected approach, enhancing clarity and predictability.  The solution demonstrates how to structure the CSS to achieve the desired style and avoid the specificity-related conflict.