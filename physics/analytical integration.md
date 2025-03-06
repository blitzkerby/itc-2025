
**KEY CONCEPTS**

**Analytical Integration**

If the position coordinate \( s \) is known for all values of the time \( t \), then successive mathematical or graphical differentiation with respect to \( t \) gives the velocity \( v \) and acceleration \( a \). 

In many problems, however, the functional relationship between position coordinate and time is unknown, and we must determine it by successive integration from the acceleration. 

Acceleration is determined by the forces which act on moving bodies and is computed from the equations of kinetics discussed in subsequent chapters. Depending on the nature of the forces, the acceleration may be specified as a function of time, velocity, or position coordinate, or as a combined function of these quantities. The procedure for integrating the differential equation in each case is indicated as follows.


**(a) Constant Acceleration.** When \( a \) is constant, the first of Eqs. 2/2 and 2/3 can be integrated directly.

For simplicity with $s = s_0$, $v = v_0$, and $t = 0$ designated at the beginning of the interval, then for a time interval $t$, the integrated equations become:

$$ \int_{v_0}^{v} v \, dv = a \int_{0}^{t} dt \quad \text{or} \quad v = v_0 + at $$

$$ \int_{s_0}^{s} v \, dv = a \int_{s_0}^{s} ds \quad \text{or} \quad v^2 = v_0^2 + 2a(s - s_0) $$

Substitution of the integrated expression for \( v \) into Eq. 2/1 and integration with respect to \( t \) give:

$$ \int_{s_0}^{s} ds = \int_{0}^{t} (v_0 + at) \, dt \quad \text{or} \quad s = s_0 + v_0t + \frac{1}{2} at^2 $$

These relations are necessarily restricted to the special case where the acceleration is constant. The integration limits depend on the initial and final conditions, which for a given problem may be different from those used here. It may be more convenient, for instance, to begin the integration at some specified time \( t_1 \) rather than at time \( t = 0 \).

**Caution:** The foregoing equations have been integrated for constant acceleration only. A common mistake is to use these equations for problems involving variable acceleration, where they do not apply.

**(b) Acceleration Given as a Function of Time, \( a = f(t) \).** Substitution of the function into the first of Eqs. 2/2 gives \( f(t) = \frac{dv}{dt} \). Multiplying by \( dt \) separates the variables and permits integration. Thus,

$$ \int_{v_0}^{v} v \, dv = \int_{0}^{t} f(t) \, dt \quad \text{or} \quad v = v_0 + \int_{0}^{t} f(t) \, dt $$

Here's the text extracted from the image you uploaded:

---

From this integrated expression for v as a function of t, the position coordinate s is obtained by integrating Eq. 2/1, which, in form, would be:

$$\int_{s_0}^{s} ds = \int_{t_0}^{t} v dt \quad \text{or} \quad s = s_0 + \int_{t_0}^{t} v dt$$

If the indefinite integral is employed, the end conditions are used to establish the constants of integration. The results are identical to those obtained by using the definite integral.

If desired, the displacement \( s \) can be obtained by a direct solution of the second-order differential equation \( \ddot{s} = f(t) \) obtained by substitution of \( f(t) \) into the second of Eqs. 2/2.

**(c) Acceleration Given as a Function of Velocity, \( a = f(v) \)**. Substitution of the function into the first of Eqs. 2/2 gives \( f(v) = \frac{dv}{dt} \), which permits separating the variables and integrating. Thus,

$$t = \int_{v_0}^{v} \frac{dv}{f(v)} = \int_{t_0}^{t} dt$$

This result gives \( t \) as a function of \( v \). Then it would be necessary to solve for \( v \) as a function of \( t \) so that Eq. 2/1 can be integrated to obtain the position coordinate \( s \) as a function of \( t \).

Another approach is to substitute the function \( a = f(v) \) into the first of Eqs. 2/3, giving \( v \, dv = f(v) \, ds \). The variables can now be separated and the equation integrated in the form:

$$\int_{v_0}^{v} \frac{v \, dv}{f(v)} = \int_{s_0}^{s} ds \quad \text{or} \quad s = s_0 + \int_{v_0}^{v} \frac{v \, dv}{f(v)}$$

Note that this equation gives \( s \) in terms of \( v \) without explicit reference to \( t \).

**(d) Acceleration Given as a Function of Displacement, \( a = f(s) \)**. Substituting the function into Eq. 2/3 and integrating gives the form:

$$\int_{v_0}^{v} v \, dv = \int_{s_0}^{s} f(s) \, ds \quad \text{or} \quad v^2 = v_0^2 + 2 \int_{s_0}^{s} f(s) \, ds$$

Next, we solve for \( v \) to give \( v = g(s) \), a function of \( s \). Now we can substitute \( \frac{ds}{dt} \) for \( v \), separate variables, and integrate in the form:

$$\int_{s_0}^{s} \frac{ds}{g(s)} = \int_{t_0}^{t} dt \quad \text{or} \quad t = \int_{s_0}^{s} \frac{ds}{g(s)}$$

which gives \( t \) as a function of \( s \). Finally, we can rearrange to obtain \( s \) as a function of \( t \).

In each of the foregoing cases when the acceleration varies according to some functional relationship, the possibility of solving the equations by direct mathematical integration will depend on the form of the function. In cases where the integration is excessively awkward or difficult, integration by graphical, numerical, or computer methods can be utilized.

---

Let me know if you need any more help with this text!