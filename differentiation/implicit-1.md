## Implicit Problem 1

_Given..._

* $x^2 + y^2 = 25$
* $\frac{dx}{dt} = 7$
* find $\frac{dy}{dt}$ when $x = 3$

**Step 1: Find the value of y when x = 3**

* $3^2 + y^2 = 25$
* $9 + y^2 = 25$
* $y^2 = 25 - 9$
* $y = \sqrt{16}$
* $y = 4$

**Step 2: Differentiate implicitly with respect to t**

* take derivative of both sides: 
* $\frac{d}{dt} (x^2 + y^2) = \frac{d}{dt} 25$
* chain rule:
* $2x \frac{dx}{dt} + 2y \frac{dy}{dt} = 0$

**Step 3: Solve for dy/dt**

* $2y\frac{dy}{dt} = -2x\frac{dx}{dt}$
* $\frac{dy}{dt} = -x\frac{dx}{dt} / y$

**Step 4: Substitute the known values**

* if y = 7: $\frac{dy}{dt} = -\frac{(3)(7)}{4} = \frac{-21}{4} = -5.25$
* if y = -7: $\frac{dy}{dt} -\frac{(3)(7)}{-4} = \frac{21}{4} = 5.25$

###### dpw | 2025-11-08

