# Probability — Numerical Questions (~8–10 of the Stats/Probability questions)

These need actual calculation, not just recall. Learn the **4 rules** below — almost every numerical question is one of these in disguise.

## The 4 rules you need

1. **Basic probability:** P(event) = (favorable outcomes) / (total possible outcomes)
2. **Complement rule:** P(NOT event) = 1 − P(event)
3. **Multiplication rule (AND, independent events):** P(A and B) = P(A) × P(B)
4. **Addition rule (OR, mutually exclusive events):** P(A or B) = P(A) + P(B)
5. **Conditional / dependent events (without replacement):** recalculate the total for the second pick.

---

**Q1.** A fair coin is tossed once. What is the probability of getting heads?
A) 1/4  B) 1/3  C) 1/2  D) 1
**Answer: C) 1/2**

**Q2.** A fair six-sided die is rolled once. What is the probability of getting a 4?
A) 1/6  B) 1/4  C) 1/3  D) 1/2
**Answer: A) 1/6**

**Q3.** A fair six-sided die is rolled once. What is the probability of getting an **even number**?
A) 1/6  B) 1/3  C) 1/2  D) 2/3
**Answer: C) 1/2** — favorable outcomes {2,4,6} = 3 out of 6 = 1/2

**Q4.** A bag contains 5 red balls and 3 blue balls. What is the probability of picking a red ball at random?
A) 3/8  B) 5/8  C) 1/2  D) 5/3
**Answer: B) 5/8**

**Q5.** Two coins are tossed together. What is the probability of getting **exactly one head**?
A) 1/4  B) 1/2  C) 3/4  D) 1
**Answer: B) 1/2** — outcomes: HH, HT, TH, TT (4 total); exactly one head = HT, TH = 2/4 = 1/2

**Q6.** A card is drawn from a standard deck of 52 cards. What is the probability of drawing a King?
A) 1/52  B) 1/26  C) 1/13  D) 4/13
**Answer: C) 1/13** — 4 Kings out of 52 = 4/52 = 1/13

**Q7.** A die is rolled AND a coin is tossed. What is the probability of getting a 6 on the die **and** Heads on the coin? (independent events)
A) 1/6  B) 1/8  C) 1/12  D) 1/2
**Answer: C) 1/12** — multiplication rule: P(6) × P(H) = (1/6) × (1/2) = 1/12

**Q8.** The probability a student passes Math is 0.7, and passes English is 0.6 (independent). What is the probability the student passes **both**?
A) 0.30  B) 0.42  C) 0.65  D) 0.13
**Answer: B) 0.42** — 0.7 × 0.6 = 0.42

**Q9.** A bag has 4 red and 6 green balls (10 total). Two balls are drawn **without replacement**. What is the probability that **both** are red?
A) 4/25  B) 2/15  C) 12/100  D) 1/5
**Answer: B) 2/15** — P(1st red) = 4/10; P(2nd red | 1st was red) = 3/9 (one red ball is now gone, 9 balls left); (4/10)×(3/9) = 12/90 = 2/15

**Q10.** What is the probability of **NOT** rolling a 6 on a fair die?
A) 1/6  B) 1/3  C) 1/2  D) 5/6
**Answer: D) 5/6** — complement rule: 1 − 1/6 = 5/6

**Q11.** A box has 3 defective and 7 working bulbs (10 total). What is the probability of picking a **working** bulb?
A) 3/10  B) 7/10  C) 3/7  D) 1/2
**Answer: B) 7/10**

**Q12.** Events A and B are **mutually exclusive**. P(A) = 0.3, P(B) = 0.4. What is P(A or B)?
A) 0.12  B) 0.70  C) 0.10  D) 1.0
**Answer: B) 0.70** — addition rule for mutually exclusive events: 0.3 + 0.4 = 0.7

---

## Common traps to remember

- **"And" → multiply. "Or" → add** (only when the two events can't both happen at once — "mutually exclusive").
- **"Without replacement" changes the total for the second draw** — this is the #1 numerical mistake people make (forgetting the bag now has one less ball).
- A probability can **never** be negative or greater than 1 — if your answer is outside [0, 1], you made an arithmetic error, go back and check.
