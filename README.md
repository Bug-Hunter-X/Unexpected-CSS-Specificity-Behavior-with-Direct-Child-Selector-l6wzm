# Unexpected CSS Specificity Behavior

This repository demonstrates a subtle issue related to CSS specificity and the direct child selector (`>`).

The `bug.css` file contains CSS code that exhibits unexpected behavior due to the interaction between inheritance, general selectors, and the direct child selector. The solution is provided in `bugSolution.css`, illustrating how to correctly apply the rules.

The problem arises from the fact that the direct child selector has a higher specificity. This often leads to unexpected results, especially when dealing with nested elements and general selectors.

## Understanding the Issue

The core issue involves the unexpected overriding of a less-specific CSS rule by a more-specific one. While seemingly straightforward, understanding the implicit order of precedence is key to avoiding unexpected styling in complex projects.