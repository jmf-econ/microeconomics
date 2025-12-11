# Microeconomics | Fall 2026

   This is my repository for microeconomics class materials.

   ## Positive Vibes Only!!!
   **Positive Economics** describes economic phenomena as it is. It focuses on testable hypotheses and empirical validation.
  > "The ultimate goal of a positive science is the development of a “theory” or “hypothesis” that yields valid and meaningful (i.e., not truistic) predictions about phenomena not yet observed."
  > — Milton Friedman

---

## 📚 Lecture 1: Preferences

### Topics Covered

#### 1. Assumptions on Preferences
- Completeness: Ability to rank all bundles
- Transitivity: Consistency in preferences
- Monotonicity: More is (weakly) better
- Continuity: No sudden jumps in preferences
- Convexity: Preference for diversification

#### 2. Indifference Curves
- Definition and graphical representation
- Properties of indifference curves:
  - Downward sloping
  - Cannot intersect
  - Higher curves represent higher utility
  - Convex to the origin
- Level sets and the preference relation

#### 3. Utility Functions
- Mathematical representation: $U(x_1, x_2, ..., x_n)$
- Ordinal vs. cardinal utility
- Existence of utility functions
- Common functional forms:
  - Cobb-Douglas: $U(x_1, x_2) = x_1^a x_2^b$
  - Perfect substitutes: $U(x_1, x_2) = ax_1 + bx_2$
  - Perfect complements: $U(x_1, x_2) = \min\{ax_1, bx_2\}$
  - CES (Constant Elasticity of Substitution)

#### 4. Properties of Utility Functions
- Monotonic transformations preserve preferences
- Marginal utility (MU): $\frac{\partial U}{\partial x_i}$
- Marginal Rate of Substitution (MRS)
- Relationship between MRS and marginal utilities
- Diminishing MRS and convexity

### 🎯 Learning Objectives
By the end of this lecture, you should be able to:
- State and explain the standard assumptions on preferences
- Draw and interpret indifference curves
- Construct utility functions from preferences
- Calculate MRS and understand its economic meaning

---

## 📚 Lecture 2: Types of Preferences

### Topics Covered

#### 1. Degree of Substitutability
- **Perfect Substitutes**
  - Constant MRS
  - Linear indifference curves
  - Example: Two brands of identical products
  
- **Perfect Complements**
  - Zero substitutability
  - L-shaped indifference curves
  - Example: Left and right shoes
  
- **Imperfect Substitutes**
  - Variable MRS
  - Standard convex indifference curves
  - Most real-world goods

#### 2. Homothetic Preferences
- Definition: MRS depends only on ratio of goods, not levels
- Utility functions: $U(tx_1, tx_2) = t^k U(x_1, x_2)$ for some $k > 0$
- Properties:
  - Expansion paths are straight lines through origin
  - Income elasticity = 1 for all goods
- Examples: Cobb-Douglas, perfect substitutes, perfect complements
- Non-homothetic preferences and their implications

#### 3. Quasilinear Preferences
- Definition: Linear in one good, non-linear in others
- Form: $U(x_1, x_2) = v(x_1) + x_2$
- Properties:
  - Parallel indifference curves (constant vertical distance)
  - No income effects on good 1
  - MRS independent of $x_2$
- Applications: Consumer surplus analysis, partial equilibrium
- When quasilinearity is a useful approximation

#### 4. Essential vs. Non-Essential Goods
- **Essential Goods**
  - Always consumed in positive amounts
  - Indifference curves never touch axes
  - Example: Cobb-Douglas preferences
  
- **Non-Essential Goods**
  - May have zero consumption at optimum
  - Indifference curves can touch axes
  - Example: Perfect substitutes
  
- **Satiation points** and thick indifference curves
- Bliss points and local non-satiation

### 🎯 Learning Objectives
By the end of this lecture, you should be able to:
- Classify preferences by degree of substitutability
- Identify homothetic and quasilinear preferences
- Distinguish between essential and non-essential goods
- Predict consumption patterns based on preference types

---

## 📚 Lecture 3: Consumer Optimum

### Topics Covered

#### 1. Consumption Set and Budget Constraint
- **Consumption Set (X)**
  - Feasible bundles: $X = \{(x_1, x_2) : x_1 \geq 0, x_2 \geq 0\}$
  - Non-negativity constraints
  - Physical or institutional constraints
  
- **Budget Constraint**
  - Budget line: $p_1 x_1 + p_2 x_2 = m$
  - Slope: $-\frac{p_1}{p_2}$ (price ratio)
  - Budget set: $\{(x_1, x_2) : p_1 x_1 + p_2 x_2 \leq m\}$
  - Changes in prices and income

#### 2. Consumer Optimum: Graphical Solution
- **Tangency Condition**
  - Optimal point where indifference curve is tangent to budget line
  - $MRS = \frac{p_1}{p_2}$ at interior solution
  - Geometric interpretation
  
- **Corner Solutions**
  - When tangency doesn't occur
  - Consuming only one good
  - Boundary optimum conditions
  
- **Graphical Analysis**
  - Finding optimum for different preference types
  - Effect of price and income changes
  - Income and substitution effects (preview)

#### 3. Mathematical Solution to Consumer Problem
- **The Optimization Problem**
  
  $$\max_{x_1, x_2} U(x_1, x_2)$$
  
  subject to: 
  
  $$p_1 x_1 + p_2 x_2 = m$$
  
  $$x_1, x_2 \geq 0$$

- **Lagrangian Method**
  - $\mathcal{L} = U(x_1, x_2) + \lambda[m - p_1 x_1 - p_2 x_2]$
  - First-order conditions (FOCs)
  - Interpretation of Lagrange multiplier $\lambda$

- **Solving the FOCs**
  - $\frac{MU_1}{p_1} = \frac{MU_2}{p_2} = \lambda$
  - Deriving demand functions
  - Examples with specific utility functions

- **Kuhn-Tucker Conditions**
  - Handling non-negativity constraints
  - Complementary slackness conditions

#### 4. Difficulties with Mathematical Solutions
- **When Standard FOCs Fail**
  - Non-differentiable utility functions (e.g., perfect complements)
  - Kinked indifference curves
  - Corner solutions and boundary conditions
  
- **Non-convex Preferences**
  - Multiple local optima
  - Need for global optimization check
  - Failure of second-order conditions
  
- **Satiation and Bliss Points**
  - Interior maxima without tangency
  - When "more is better" fails
  
- **Practical Solutions**
  - Checking corner solutions explicitly
  - Comparing utility levels at candidate points
  - Graphical verification
  - Understanding when Lagrangian method applies

### 🎯 Learning Objectives
By the end of this lecture, you should be able to:
- Define the budget constraint and consumption set
- Find optimal consumption both graphically and mathematically
- Set up and solve the consumer's problem using the Lagrangian
- Recognize when standard optimization methods may fail
- Handle corner solutions and non-standard cases

---

**Course Repository:** [github.com/jmf-econ/microeconomics](https://github.com/jmf-econ/microeconomics)
