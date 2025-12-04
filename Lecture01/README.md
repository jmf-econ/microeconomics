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
  - Cobb-Douglas: U(x₁, x₂) = x₁ᵃx₂ᵇ
  - Perfect substitutes: U(x₁, x₂) = ax₁ + bx₂
  - Perfect complements: U(x₁, x₂) = min{ax₁, bx₂}

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
- 3D representation: z = f(x, y)
- Level curves: Sets where f(x, y) = constant

### Partial Derivatives
- Derivative with respect to one variable, holding others constant
- Notation: ∂f/∂x or fₓ

### The Gradient
- An operator that, when given a function, returns it's vector of partial derivatives
- Vector of all partial derivatives: $\nabla f = \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z}, \ldots \right)$

- Points in direction of steepest ascent
- Perpendicular to level curves/surfaces


### 📚 Resources
- 📹 **Videos:**
  - [Add YouTube link here]
  - [Add YouTube link here]
- 📄 **Readings:**
  - [Add reading/article link here]
  - [Add reading/article link here]
- 🔗 **Additional Materials:**
  - [Add supplementary link here]

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
- Objective function: f(x, y)
- Constraint: g(x, y) = c
- Lagrangian: ℒ(x, y, λ) = f(x, y) + λ[c - g(x, y)]

**λ (lambda)**: Lagrange multiplier
- Represents shadow price or marginal value of relaxing the constraint
- Economic interpretation: Additional utility from one more dollar of income

### First-Order Conditions (FOCs)
1. ∂ℒ/∂x = 0
2. ∂ℒ/∂y = 0
3. ∂ℒ/∂λ = 0 (recovers the constraint)

### Solving the Consumer Problem
**Problem:** max U(x₁, x₂) s.t. p₁x₁ + p₂x₂ = m

**Lagrangian:** ℒ = U(x₁, x₂) + λ[m - p₁x₁ - p₂x₂]

**FOCs:**
- ∂ℒ/∂x₁ = MU₁ - λp₁ = 0
- ∂ℒ/∂x₂ = MU₂ - λp₂ = 0
- ∂ℒ/∂λ = m - p₁x₁ - p₂x₂ = 0

**Result:** MU₁/p₁ = MU₂/p₂ = λ
- Marginal utility per dollar spent must be equal across all goods
- Equivalently: MRS = p₁/p₂

### 📚 Resources
- 📹 **Videos:**
  - [Add YouTube link here]
  - [Add YouTube link here]
- 📄 **Readings:**
  - [Add reading/article link here]
  - [Add reading/article link here]
- 🔗 **Additional Materials:**
  - [Add supplementary link here]

---

## Key Takeaways
- Economics uses rigorous assumptions to build tractable models
- Preferences can be represented mathematically through utility functions
- Multivariate calculus provides the tools for marginal analysis
- The Lagrangian method solves constrained optimization problems
- Optimal choice equates marginal rates of substitution with price ratios

---

## For Next Lecture
- Demand curves and comparative statics
- Income and substitution effects
- Consumer surplus and welfare analysis

---

## Additional Resources
- Practice problems on utility maximization
- Review of calculus concepts (Khan Academy, 3Blue1Brown)
- Economic applications of optimization
