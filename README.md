# Tailwind CSS Gradient Distortion Bug

This repository demonstrates a bug encountered while using Tailwind CSS gradients. The gradient applied to an element shows unexpected visual artifacts, deviating from the expected smooth transition.

## Bug Description

The gradient defined using `bg-gradient-to-r from-blue-500 to-purple-500` appears distorted. The transition between colors is not smooth and shows irregularities in various browsers. This issue seems related to the interaction between the gradient and other CSS properties, or specific browser rendering engines.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the visual distortion in the gradient.

## Solution

The solution involves specifying precise color values and adjusting the gradient stops to create a smoother visual transition. The `solution.html` file demonstrates the corrected version.   Additional CSS overrides might be needed depending on the specific context of the project. 

## Further Investigations

* Check for CSS conflicts within your project.
* Test in different browsers to narrow down the issue's scope.
* Consider inspecting the element's computed styles using your browser's developer tools.  
* Verify that the `tailwindcss` package and its peer dependencies are up to date.
* Check for any potential issues related to the dimensions or aspect ratio of the element to which the gradient is applied.