Here’s your updated markdown with the linked image properly embedded in the tutorial:

---

# Ada: A Chatbot for Introductory Calculus

A custom-built educational assistant that helps students master introductory calculus concepts. Ada provides step-by-step guidance, scaffolding techniques, and Socratic questioning to enhance understanding without giving direct answers. Designed in collaboration with Northeastern University faculty to align with course syllabi.
Try it: [https://chatgpt.com/g/g-JMkUy05pG-ada-calculus-bot](https://chatgpt.com/g/g-JMkUy05pG-ada-calculus-bot)

---

# Using Ada for Calculus Help — A Guided Example

This tutorial shows how a student can use Ada to work through calculus problems by:

* Asking about discontinuities and asymptotes
* Uploading handwritten derivatives
* Getting guided help with integration, limits, and the chain rule

---

## Example 1: Graph with Discontinuity and Asymptote

**Prompt:**
Draw me a graph of a function with one removable discontinuity and one vertical asymptote.

**Ada's Response:**
Ada returns a graph that:

* Has a removable discontinuity (a "hole") at $x = 1$
* Has a vertical asymptote at $x = -2$

Ada also explains the behavior and offers to zoom in or modify the function.

---

## Example 2: Uploading a Derivative Mistake

**Student Uploads Image:**
![Handwritten derivative problem](https://raw.githubusercontent.com/Humanitariansai/Art/refs/heads/main/Art/ada_handwritten.png)

**Prompt:**
Is this correct? If not, why is this wrong?

**Ada's Explanation:**
Ada walks through the error step-by-step, identifying that the student neglected to use the product rule. The correct process is:

1. Recognize $u = x^2$, $v = \sin(x)$
2. Use the product rule:

   $$
   F'(x) = u'v + uv' = 2x \sin(x) + x^2 \cos(x)
   $$

---

## Example 3: Integration with Substitution

**Prompt:**
How do I take the integral of $x^2 e^{x^3}$?

**Ada's Step-by-Step:**

1. Substitution: Let $u = x^3$
2. Then $du = 3x^2 dx$, so $x^2 dx = \frac{1}{3} du$
3. Rewrite the integral:

   $$
   \int x^2 e^{x^3} dx = \frac{1}{3} \int e^u du
   $$
4. Final result:

   $$
   \frac{1}{3} e^{x^3} + C
   $$

---

## Example 4: Solving a Limit with Factoring

**Prompt:**
How do I take the limit as $x \to 1$ of $\frac{x^2 - 2x + 1}{x^2 - 3x + 2}$?

**Ada's Steps:**

1. Direct substitution gives $\frac{0}{0}$: an indeterminate form
2. Factor the expression:

   $$
   \frac{(x - 1)^2}{(x - 1)(x - 2)} = \frac{x - 1}{x - 2}
   $$
3. Evaluate the simplified form:

   $$
   \lim_{x \to 1} \frac{x - 1}{x - 2} = \frac{0}{-1} = 0
   $$

---

## Example 5: Understanding the Chain Rule

**Prompt:**
How does the chain rule work?

**Ada's Explanation:**

The chain rule is used to differentiate a composite function:

$$
y = f(g(x)) \quad \Rightarrow \quad \frac{dy}{dx} = f'(g(x)) \cdot g'(x)
$$

**Example:**
Let $y = \sin(x^2)$

1. Outer function: $\sin(u)$, inner function: $u = x^2$
2. Derivatives: $\frac{dy}{du} = \cos(u)$, $\frac{du}{dx} = 2x$
3. Chain rule:

   $$
   \frac{dy}{dx} = \cos(x^2) \cdot 2x = 2x \cos(x^2)
   $$

---

## Summary

Ada is more than a calculator — it's a tutor that walks through problems step-by-step. You can:

* Upload handwritten work
* Ask conceptual questions
* Get visualizations and worked examples
* Learn through guided reasoning

Try it now: [Ada on ChatGPT](https://chatgpt.com/g/g-JMkUy05pG-ada-calculus-bot)

