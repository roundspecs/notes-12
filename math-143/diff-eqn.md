# Dependent vs Independent variable
In $\frac{dy}{dx}$ -
- y is dependent
- x is independent

Think of $\frac{dy}{dx}$ as a tower where the 1st floor ($dy$) is dependent on the existence of ground floor ($dy$)

# Differential Equation
- **DEF:** An equation involving derivative(s) of 1/+ dependent variable(s) w.r.t 1/+ independent variable(s)
## Types
- **ODE:** 1 independent variable
- **PDE:** 1+ independent variable

# Order of Differential Equation
- **DEF:** Order of highest order derivative

# Degree of Differential Equation
- **DEF:** Degree of highest order derivative
- Fractional power must be removed first
- Degree of the differential equation does not exist, if it contains the following terms:\
  $\log{\frac{dy}{dx}}$, $e^{\frac{dy}{dx}}$, $\sin{\frac{dy}{dx}}$, $\cos{\frac{dy}{dx}}$

# Formation of Differential Equation
- No. of arbitrary variables = Order of differential equation

## Standard Equations
- Circle with center at $(h,k)$ of radius $r$\
  $(x-h)^2+(y-k)^2=r^2$
- Parabolar standard equations\
  ![Alt text](<parabola standard equations.png>)

# Variable Separation Method
- If it can be written in the form, $\frac{dy}{dx}=f(x)\times f(y)$, then this method is applicable
- $\frac{dy}{dx}=f(x)\times f(y)$\
  $\Rightarrow \frac{1}{f(y)}dy=f(x)dx$\
  $\Rightarrow\int \frac{1}{f(y)}dy=\int f(x)dx$

# Reducable to Variable Separation Method
- If you see $ax+by+c$, especially if it repeats, replace with $z$

# Homogeneous Differential Equation
- Differential equation of the form $\frac{dy}{dx}=f(\frac{y}{x})=f(\frac{x}{y})$
- Trick: Degree of each term in both numerator and denominator are equal
- If you see $y/x$ terms, let: $y=vx$
- If you see $x/y$ terms, let $x=vy$

# Reducable to Homogeneous Differential Equation
**Form:** $\frac{dy}{dx}=\frac{ax+by+c}{a'x+b'y+c'}$
- if $\frac{a}{a'}= \frac{b}{b'}$\
  Reduce to Variable Separation
- else\
  $x=X+h$\
  $y=Y+k$

# Linear Differential Equation
- **DEF:** A differential equation is linear if
  - every dependent variable and every derivative is in first degree
  - no product of dependent variables and derivatives
- Steps:
  - Write it in the form: $\frac{dy}{dx} + Py = Q$ ($P,Q$ are functions of $x$)
  - $IF=e^{\int Pdx}$
  - $y\times IF=\int Q\times IFdx$

# Reducable to Linear Differential Equation
- Form:
  - $f'(y) \frac{dy}{dx} + P\times f(y) = Q$
  - Let, $v=f(y)$
- Special:
  - $\frac{dy}{dx} + Py = Qy^n$