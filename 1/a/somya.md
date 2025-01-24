### Checkpoint 1:
- Each door is toggled when the pass number _i_ is a divisor of the door number.

### Checkpoint 2:
- A door's state will ultimately change **if it is toggled an odd number of times**.

### Checkpoint 3:
- Doors with **odd divisors** remain open.

---

### Idea:
- Only **perfect squares** have an odd number of divisors.
  - Example: 
    - 16: Divisors = \(1, 2, 4, 8, 16\) → Odd number of divisors.
    - 12: Divisors = \(1, 2, 3, 4, 6, 12\) → Even number of divisors.

---

### Final Result:
- Open doors = All perfect squares ≤ \(n\).
  - For \(n = 100\): Open doors = \(1, 4, 9, 16, 25, 36, 49, 64, 81, 100\).
  - i.e, they will be toggled odd number of times so they become open

### Ans:
The integer just less than $\sqrt{n}$

### First correct ans:
@aditigarg 💥
