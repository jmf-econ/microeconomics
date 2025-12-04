# Lecture 1: Introduction to Microeconomics

## 1. Why this course is important?

### Positive Vibes Only!!!
- **Positive Economics** describes economic phenomena as it is. It focuses on testable hypotheses and empirical validation.
  > "The ultimate goal of a positive science is the development of a “theory” or “hypothesis” that yields valid and meaningful (i.e., not truistic) predictions about phenomena not yet observed."
  > — Milton Friedman

### Assumptions in Economics
- Simplifying complex reality to identify key relationships
- Allowing mathematical tractability
- Enabling clear predictions and testable implications
- Trade-off between realism and analytical power

### Applicability 
- Understanding individual decision-making.
- Building analytical skills applicable across disciplines and fields (micro, macro, environmental, labor, monetary economics, education, etc).

### 📚 Resources
- 📄 **Readings:**
  - Friedman, M. (1953). The methodology of positive economics.

---

## 2. Preferences

### Assumptions on Preferences
1. **Completeness**: People can tell what they prefer. For any two bundles A and B, either A ≿ B, B ≿ A, or both.
2. **Transitivity**: Preferences have some kind of coherence. If A ≿ B and B ≿ C, then A ≿ C.
3. **Monotonicity**: More is better (at least weakly).
4. **Convexity**: People usually prefer to consume a variety of different goods. 
5. **Continuity**: Small changes in bundles lead to small changes in preferences, never jumps. 

### Utility Functions
- Mathematical representation of preferences: U(x₁, x₂, ..., xₙ)
- Common utility functions and their assumptions:
  - Cobb-Douglas: $U(x_1, x_2) = x_1^{\alpha}x_2^{\beta}$
  - Perfect substitutes: $U(x_1, x_2) = \alpha x_1 + \beta x_2$
  - Perfect complements: $U(x_1, x_2) = \min \{[x_1, x_2]\}$

### Indifference Curves
- Set of bundles that provide the same level of utility
- Properties:
  - Downward sloping (monotonicity)
  - Cannot cross (transitivity)
  - Convex to the origin (diminishing MRS, convexity)

### Marginal Rate of Substitution (MRS)
- Rate at which consumer is willing to trade one good for another
- Diminishing MRS: Willingness to substitute decreases as consumption changes

### 📚 Resources
- 📄 **Readings:**
  - Nechyba, T. J. (2011). **Chapter 4**. In Microeconomics: An intuitive approach with calculus. South-Western Cengage Learning.
  - Nechyba, T. J. (2011). **Chapter 5**. In Microeconomics: An intuitive approach with calculus. South-Western Cengage Learning.

---

## 3. Multivariate Calculus for Economics

### Functions of Multiple Variables
- 3D representation
- Level curves

### Partial Derivatives
- Derivative with respect to one variable, holding others constant
- Notation: $\frac{\partial f}{\partial x}$ or $U_x$

### The Gradient
- An operator that, when given a function, returns it's vector of partial derivatives
- Vector of all partial derivatives: $\nabla f = \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z}, \ldots \right)$
- Points in direction of steepest ascent
- Perpendicular to level curves

**λ (lambda)**: Lagrange multiplier
- It transforms the units in which the constraint is expressed in (e.g. usd), to the units in which the objective function is expressed in (i.g. utils)
- Economic interpretation: Additional utility from one more dollar of income

### 📚 Resources
- 📹 **Videos:**
  - https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/gradient-and-directional-derivatives/v/gradient

---

## 4. Constrained Optimization

### The Economic Problem
- Maximize utility subject to constraints
- Example: study microeconomics or history?

### Finding tagency with multivariate functions
- For this, we have to find the point in which the gradient of the objective function is proportional to the gradient of the constraint.
  $\nabla U = \lambda \nabla B$

### The Lagrangian Method
**Setup:**
- Objective function: $f(x,y)$
- Constraint: $g(x, y) = c$
- Lagrangian: $\mathcal{L}(x, y, \lambda) = f(x, y) + \lambda[c - g(x, y)]$

### First-Order Conditions (FOCs)
- Opportunity cost = marginal rate of substitution

### 📚 Resources
- 📹 **Videos:**
  - https://www.khanacademy.org/math/multivariable-calculus/applications-of-multivariable-derivatives/lagrange-multipliers-and-constrained-optimization/v/constrained-optimization-introduction
- 📄 **Readings:**
  - Nechyba, T. J. (2011). **Chapter 6**. In Microeconomics: An intuitive approach with calculus. South-Western Cengage Learning.

---

## Key Takeaways
- Economics uses assumptions to build tractable models, for your sake, don't try always to understand.
  With that in mind,
  - Preferences can be represented mathematically through utility functions
  - Multivariate calculus provides the tools for marginal analysis
  - The Lagrangian method solves constrained optimization problems
  - Optimal choice equates marginal rates of substitution with price ratios

---

## Additional Resources
- Practice problems on utility maximization
- Review of calculus concepts (Khan Academy, 3Blue1Brown)
- Economic applications of optimization
