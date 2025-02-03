# CSS `calc()` Pitfalls

This example demonstrates some unexpected behaviors that can occur when using the CSS `calc()` function, particularly concerning operator precedence, unit consistency, and limitations in certain property contexts.

The `bug.css` file shows the problematic code, while `bugSolution.css` offers a corrected version.  The issue is that calculating percentage values within nested elements where the container size isn't rigidly defined leads to unexpected output.

The solution addresses the problem by ensuring proper unit consistency and providing explicit container sizing or using alternative layout strategies when required.