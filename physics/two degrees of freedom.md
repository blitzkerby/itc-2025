**Prerequisites**

[[intuitive understanding of pulleys]]
[[the datum in pulleys]]

---

<center>
	<image src="./images/two-degrees-of-freedom.png"/>
</center>

In the system shown above, the lengths of the cables attached to the cylinders $A$ and $B$ can be written, respectively, as:

$$
\begin{cases}
	L_A = y_A + 2y_D + \text{constant} \\ \\
	L_B = y_B + y_C + (y_C - y_D) + \text{constant}
\end{cases}
$$

and their time derivatives are:

$$
\begin{cases}
	0 = \dot{y}_A + 2\dot{y}_D \quad \\ \\
	0 = \dot{y}_B + 2\dot{y}_C - \dot{y}_D
\end{cases}
$$

and

$$
\begin{cases}
	0 = \ddot{y}_A + 2\ddot{y}_D \\ \\
	0 = \ddot{y}_B + 2\ddot{y}_C - \ddot{y}_D	
\end{cases}
$$

Eliminating the terms in $\dot{y}_D$ gives:


$$
\dot{y}_A + 2\dot{y}_B + 4\dot{y}_C = 0 \quad \text{or} \quad v_A + 2v_B + 4v_C = 0
$$

and in $\ddot{y}_D$ gives: 

$$
\ddot{y}_A + 2\ddot{y}_B + 4\ddot{y}_C = 0 \quad \text{or} \quad a_A + 2a_B + 4a_C = 0
$$

It is clearly impossible for the signs of all three terms to be positive simultaneously. 


For example, if both $A$ and $B$ have downward (positive) velocities, then $C$ will have an upward (negative) velocity.


These results can also be found by inspecting the motions of the two pulleys at $C$ and $D$.


For an increment $dy_A$ (with $y_B$ held fixed), 
	the center of $D$ moves up by an amount $dy_A/2$, 
	which causes an upward movement $dy_A/4$ of the center of $C$.
	
For an increment $dy_B$ (with $y_A$ held fixed), 
	the center of $C$ moves up by a distance $dy_B/2$. 
	
A combination of the two movements gives an upward movement:

$$
-dy_C = \frac{dy_A}{4} + \frac{dy_B}{2}
$$

so that:

$$
-v_C = \frac{v_A}{4} + \frac{v_B}{2}
$$

Visualization of the actual geometry of the motion is an important ability [but when in doubt, do the math to really figure out the right intuition.]
