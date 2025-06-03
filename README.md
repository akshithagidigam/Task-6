# Password Strength Evaluation Report

## Overview
This report presents the creation and evaluation of multiple passwords with varying complexity levels. It includes test results from a password strength checker, best practices, tips learned, common attack methods, and a summary of how complexity impacts password security.

---

## Passwords Created

| Password        | Length | Uppercase | Lowercase | Numbers | Symbols | Notes                   |
|-----------------|--------|-----------|-----------|---------|---------|-------------------------|
| password123     | 11     | No        | Yes       | Yes     | No      | Simple and common       |
| Passw0rd!       | 9      | Yes       | Yes       | Yes     | Yes     | Moderate complexity     |
| abcdefghijkl    | 12     | No        | Yes       | No      | No      | Lowercase only          |
| Qwerty!2024     | 10     | Yes       | Yes       | Yes     | Yes     | Common keyboard pattern |
| G!5^k2LmN#qR    | 12     | Yes       | Yes       | Yes     | Yes     | Random and strong       |

---

## Password Strength Test Results

*Tested using  https://www.passwordmonster.com/   Password Checker*

| Password        | Score (0-4) | Feedback                         |
|-----------------|-------------|---------------------------------|
| password123     | 0           | Very weak, common password       |
| Passw0rd!       | 2           | Moderate, needs more length      |
| abcdefghijkl    | 0           | Weak, only lowercase letters     |
| Qwerty!2024     | 1           | Weak, common pattern             |
| G!5^k2LmN#qR    | 4           | Very strong                    |

---

## Best Practices for Creating Strong Passwords

- Use a mix of **uppercase**, **lowercase**, **numbers**, and **symbols**.
- Make passwords **at least 12 characters** long.
- Avoid **dictionary words**, common phrases, and predictable sequences.
- Use **random or unrelated characters**.
- Do not use personal information (e.g., names, birthdays).
- Change passwords regularly and avoid reusing them.

---

## Tips Learned from Evaluation

- Common or simple passwords are easily compromised.
- Adding uppercase letters, numbers, and symbols greatly improves strength.
- Longer passwords score better and resist attacks more effectively.
- Keyboard patterns reduce security even with added complexity.
- Testing passwords helps identify weaknesses early.

---

## Common Password Attacks

### Brute Force Attack  
- Attempts every possible combination until the password is found.  
- Complexity and length increase time exponentially, making attacks infeasible.

### Dictionary Attack  
- Uses lists of common words or leaked passwords to guess.  
- Avoiding common words or phrases reduces this risk.

---

## How Password Complexity Affects Security

- The number of potential passwords increases exponentially with increasing character variety.  
- The time needed for brute force attacks is significantly increased by longer passwords.   

---

## Conclusion

Creating strong passwords requires combining length, complexity, and unpredictability. Regular testing and awareness of attack methods help maintain secure access and protect sensitive information.

---

