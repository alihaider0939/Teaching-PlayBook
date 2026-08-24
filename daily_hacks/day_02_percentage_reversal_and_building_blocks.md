# Day 2: The Percentage Reversal Loophole ($x\% \text{ of } y = y\% \text{ of } x$)

> **The Problem:** When a test asks for $69\%$ of $200$, students panic because calculating $69 \times 0.69$ vertically is tedious. We reach for calculators because no one showed us that percentage order is completely reversible.
> **The Student Hack:** Swap the numbers. $69\%$ of $200$ is identical to $200\%$ of $69$. Double $69$ to get $138$ in two seconds.

---

## 💡 How a Student Explains Percentage Swapping to a Classmate

If you get hit with a gross percentage question on a test, don't do hard decimal multiplication. Just flip the expression around.

* **Textbook Way:** "Convert $69\%$ to $0.69$. Multiply $200 \times 0.69$. $200 \times 9 = 1800$, $200 \times 6 = 1200$, shift decimals..."
* **Peer Shortcut:** "Bro, just flip it. $69\%$ of $200$ is the exact same as $200\%$ of $69$. What's $200\%$ of $69$? Just double it: $69 + 69 = 138$. Done."

### Why It Works Mathematically
Percentages are just multiplication: 
$$x\% \text{ of } y = \frac{x}{100} \times y = \frac{x \times y}{100} = \frac{y}{100} \times x = y\% \text{ of } x$$

Because multiplication is commutative ($a \times b = b \times a$), you are allowed to swap the percentage sign to whichever number is easier to work with!

---

## 🧠 Two Modular Hacks Every Student Uses

### Trick 1: The Number Swap
* **$16\%$ of $50 \rightarrow$** Swap it to $50\%$ of $16 \rightarrow \mathbf{8}$
* **$84\%$ of $25 \rightarrow$** Swap it to $25\%$ of $84 \rightarrow 84 \div 4 = \mathbf{21}$
* **$69\%$ of $200 \rightarrow$** Swap it to $200\%$ of $69 \rightarrow 69 \times 2 = \mathbf{138}$

### Trick 2: The "10% + Half" Building Block (For 15%)
When you can't swap to an easy number, break $15\%$ into $10\% + 5\%$:
* **$15\%$ of $80 \rightarrow$** $10\% = 8$, half of that is $5\% = 4 \rightarrow 8 + 4 = \mathbf{12}$

---

## 🤖 ChatGPT Prompt for Teachers

Copy and paste this into ChatGPT or Gemini to generate a lesson built around these mental shortcuts:

```text
Act as a smart student explaining mental math loopholes to a classmate before a test.

I want to teach my class two major percentage shortcuts:
1. The Percentage Reversal Trick (x% of y = y% of x), like solving 16% of 50 by doing 50% of 16.
2. The "10% + 5%" Building Block method for calculating 15% mentally.

Generate:
- A 2-minute "cheat code" script explaining why swapping numbers works.
- 5 practice problems that look impossible at first but become trivial when flipped.
- A 1-sentence notebook summary for students.
