
# Comprehensive Guide to Differential Calculus

Differential calculus is a branch of calculus that deals with the study of how functions change when their inputs change. It is concerned with the concept of the derivative, which measures the rate of change of a function.

## Table of Contents
1. Introduction to Differential Calculus
2. Limits and Continuity
    - Definition of a Limit
    - Properties of Limits
    - Continuity of a Function
3. The Derivative
    - Definition of the Derivative
    - Notation for Derivatives
    - Geometric Interpretation
    - Differentiability and Continuity
4. Rules of Differentiation

## 1. Introduction to Differential Calculus

Differential calculus is the study of how functions change. It focuses on the concept of the derivative, which provides a way to quantify the rate of change of a function with respect to one of its variables.

### Why Learn Differential Calculus?
- **Understanding Change**: Differential calculus is essential for understanding and modeling change in various contexts, from physics to economics.
- **Applications**: The concepts of differential calculus are applied in optimization, motion analysis, and many other areas.

## 2. Limits and Continuity

### Definition of a Limit

The limit of a function \( f(x) \) as \( x \) approaches a value \( c \) is the value that \( f(x) \) approaches as \( x \) gets closer to \( c \). It is denoted as:

$$
\lim_{{x 	o c}} f(x) = L
$$

Where \( L \) is the limit.

### Properties of Limits

- **Limit of a Sum**: \( \lim_{{x 	o c}} [f(x) + g(x)] = \lim_{{x 	o c}} f(x) + \lim_{{x 	o c}} g(x) \)
- **Limit of a Product**: \( \lim_{{x 	o c}} [f(x) \cdot g(x)] = \lim_{{x 	o c}} f(x) \cdot \lim_{{x 	o c}} g(x) \)
- **Limit of a Quotient**: \( \lim_{{x 	o c}} \left[ rac{f(x)}{g(x)} 
ight] = rac{\lim_{{x 	o c}} f(x)}{\lim_{{x 	o c}} g(x)} \) (provided \( \lim_{{x 	o c}} g(x) 
eq 0 \))

### Continuity of a Function

A function \( f(x) \) is continuous at a point \( c \) if the following conditions are met:
1. \( f(c) \) is defined.
2. \( \lim_{{x 	o c}} f(x) \) exists.
3. \( \lim_{{x 	o c}} f(x) = f(c) \).

If a function is continuous at every point in an interval, it is said to be continuous on that interval.

## 3. The Derivative

### Definition of the Derivative

The derivative of a function \( f(x) \) with respect to \( x \) is the limit of the average rate of change of the function as the interval approaches zero. It is denoted as:

$$
f'(x) = \lim_{{h 	o 0}} rac{f(x+h) - f(x)}{h}
$$

### Notation for Derivatives

- **Leibniz Notation**: \( rac{dy}{dx} \) or \( rac{d}{dx}f(x) \)
- **Lagrange Notation**: \( f'(x) \)
- **Newton Notation**: \( \dot{y} \) (used mainly in physics)

### Geometric Interpretation

The derivative of a function at a point represents the slope of the tangent line to the function's graph at that point.

### Differentiability and Continuity

If a function is differentiable at a point, it is also continuous at that point. However, a function can be continuous at a point without being differentiable there (e.g., a sharp corner or cusp).

## 4. Rules of Differentiation

### Power Rule

For any real number \( n \), the derivative of \( x^n \) is given by:

$$
rac{d}{dx} x^n = nx^{n-1}
$$

### Product Rule

For two functions \( u(x) \) and \( v(x) \), the derivative of their product is given by:

$$
rac{d}{dx} [u(x) \cdot v(x)] = u'(x) \cdot v(x) + u(x) \cdot v'(x)
$$

### Quotient Rule

For two functions \( u(x) \) and \( v(x) \), the derivative of their quotient is given by:

$$
rac{d}{dx} \left[ rac{u(x)}{v(x)} 
ight] = rac{v(x) \cdot u'(x) - u(x) \cdot v'(x)}{[v(x)]^2}
$$

### Chain Rule

The chain rule is used to differentiate a composite function. If \( y = f(g(x)) \), then:

$$
rac{dy}{dx} = rac{df}{dg} \cdot rac{dg}{dx}
$$

### Higher-Order Derivatives

The second derivative of a function is the derivative of its first derivative, denoted by \( f''(x) \) or \( rac{d^2y}{dx^2} \). Higher-order derivatives follow similarly.

## 5. Applications of Derivatives

### Slope of a Curve

The derivative of a function gives the slope of the tangent to the curve at any point.

### Optimization Problems

Derivatives are used to find the maximum and minimum values of functions by setting \( f'(x) = 0 \) and solving for \( x \).

### Related Rates

Related rates problems involve finding the rate at which one quantity changes with respect to another, using the chain rule.

### Motion Along a Line

In physics, the derivative of the position function with respect to time gives the velocity, and the derivative of the velocity gives the acceleration.

## 6. Implicit Differentiation

### Differentiating Implicit Functions

When a function is not explicitly solved for one variable, implicit differentiation is used. For example, for the equation \( x^2 + y^2 = r^2 \), differentiate both sides with respect to \( x \) to find \( rac{dy}{dx} \).

### Applications of Implicit Differentiation

Implicit differentiation is often used in related rates problems and in finding the derivatives of inverse functions.

