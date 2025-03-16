To prove 
$$
\lim_{x \to -\infty} \frac{3x+1}{x-5} = 3
$$ 
using the formal $\epsilon$-$\delta$ definition of a limit, we proceed as follows:

### Limit Definition:
For a limit 
$$
\lim_{x \to -\infty} f(x) = L
$$
we need to show that for every $\epsilon > 0$, there exists a corresponding $N < 0$ such that whenever $x < N$, the inequality $|f(x) - L| < \epsilon$ holds.

### Applying the Definition:
Here, $f(x) = \frac{3x+1}{x-5}$ and $L = 3$.

1. **Express the Difference**:
   $$
   \left| \frac{3x+1}{x-5} - 3 \right|
   $$

   Simplify the expression:
   $$
   \frac{3x+1}{x-5} - 3 = \frac{(3x+1) - 3(x-5)}{x-5} = \frac{3x+1 - 3x + 15}{x-5} = \frac{16}{x-5}.
   $$

   Therefore, we need to bound:
   $$
   \left| \frac{16}{x-5} \right| < \epsilon.
   $$

2. **Find a Condition for $x$:**
   Since $|x-5| = -(x-5)$ as $x \to -\infty$, we can rewrite:
   $$
   \frac{16}{|x-5|} < \epsilon \quad \implies \quad |x-5| > \frac{16}{\epsilon}.
   $$

   Thus:
   $$
   x - 5 < -\frac{16}{\epsilon} \quad \implies \quad x < -\frac{16}{\epsilon} + 5.
   $$

3. **Choose $N$:**
   Let 
   $$
   N = -\frac{16}{\epsilon} + 5.
   $$ 
   For any $\epsilon > 0$, whenever $x < N$, the inequality $|f(x) - 3| < \epsilon$ is satisfied.

### Conclusion:
By the $\epsilon$-$\delta$ definition, 
$$
\lim_{x \to -\infty} \frac{3x+1}{x-5} = 3.
$$ 
Let me know if you’d like further clarification!
