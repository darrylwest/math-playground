# Conjugate to Solve a Limit

**f(x) = [√(4+x) - 2]/x**

This would give us a 0/0 indeterminate form, which is perfect for the conjugate method! Let me solve that:

---

**Finding: lim(x→0) [√(4+x) - 2]/x**

**Step 1:** Multiply by the conjugate
$$\lim_{x \to 0} \frac{\sqrt{4+x} - 2}{x} \cdot \frac{\sqrt{4+x} + 2}{\sqrt{4+x} + 2}$$

**Step 2:** Expand the numerator using difference of squares
$$= \lim_{x \to 0} \frac{(\sqrt{4+x})^2 - (2)^2}{x(\sqrt{4+x} + 2)}$$

$$= \lim_{x \to 0} \frac{(4+x) - 4}{x(\sqrt{4+x} + 2)}$$

**Step 3:** Simplify
$$= \lim_{x \to 0} \frac{x}{x(\sqrt{4+x} + 2)}$$

$$= \lim_{x \to 0} \frac{1}{\sqrt{4+x} + 2}$$

**Step 4:** Substitute x = 0
$$= \frac{1}{\sqrt{4} + 2} = \frac{1}{2 + 2} = \frac{1}{4}$$

---

Is this the problem you intended? If you really did mean √(4+x)/x, let me know and I can explain why that limit diverges!


