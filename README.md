# :nth-child(n) Selector Issue with Nested Elements

This repository demonstrates a common issue encountered when using the `:nth-child(n)` CSS selector with nested elements. The selector is not behaving as expected when targeting elements within a nested structure.  The issue is that `:nth-child` only considers the direct children of the parent element, thus ignoring children of nested elements.

## Bug Description
The `:nth-child(n)` selector is intended to select elements based on their position among their siblings. However, when used with nested elements, it often fails to target the intended elements.

## Reproduction

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Observe that the styling does not correctly target the expected elements.

## Solution
This problem can be solved by using a different approach, such as structural selectors, or adding more specific selectors to get around the behavior of `:nth-child(n)`.  The solution is provided in `bugSolution.css`