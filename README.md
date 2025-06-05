# 🔐 Create a Strong Password and Evaluate Its Strength

## 🎯 Objective

Understand what makes a password strong and evaluate it using online strength-checking tools. Demonstrate awareness of password security, common attack methods, and best practices.

---

## 🛠 Tools Used

- [Password Meter](https://www.passwordmonster.com/)
- [Kaspersky Password Checker](https://password.kaspersky.com/)
- [NordPass Password Strength Tool](https://nordpass.com/password-strength-checker/)

---

## 🧪 Passwords Tested

| Password            | Complexity Level | Components Used                        |
|---------------------|------------------|----------------------------------------|
| `password123`       | Weak             | Lowercase, digits                      |
| `Pa$$wo2024`      | Medium           | Uppercase, lowercase, digits, symbols  |
| `H#72c!eQ9*vZr!2p`  | Strong           | Uppercase, lowercase, digits, symbols, 16 chars |

---

## 📊 Password Strength Evaluation

### 🔴 1. `password123`

- **Result:** Weak
- **Issues:** Common pattern, predictable, lacks symbols, short length
- 📷 Screenshot: `screenshots/weak-password-test.png`

---

### 🟡 2. `Pa$$wo2024`

- **Result:** Medium
- **Issues:** Slightly predictable base word, decent complexity
- 📷 Screenshot: `screenshots/medium-password-test.png`

---

### 🟢 3. `H#72c!eQ9*vZr!2p`

- **Result:** Strong
- **Strength Factors:**
  - 16 characters
  - Mixed case
  - Symbols
  - High entropy
- 📷 Screenshot: `screenshots/strong-password-test.png`

---

## 📚 Best Practices for Creating Strong Passwords

- ✅ Use **at least 12–16 characters**
- ✅ Combine **uppercase**, **lowercase**, **numbers**, and **symbols**
- ✅ Avoid **dictionary words**, personal info, and common substitutions (e.g., `p@ssw0rd`)
- ✅ Use **random or generated** passwords, not patterns
- ✅ Consider using a **password manager**

---

## ⚠️ Common Password Attack Methods

| Attack Type      | Description                                                                              |
|------------------|------------------------------------------------------------------------------------------|
| Brute Force      | Tries all possible character combinations; time-consuming but guaranteed eventually     |
| Dictionary Attack| Uses a list of common passwords or words to guess credentials quickly                   |
| Credential Stuffing | Uses stolen username/password pairs to try accessing other systems                    |
| Social Engineering| Tricks users into revealing passwords through phishing or deception                     |

---

## 🔐 Password Complexity vs. Security

Password complexity directly affects resistance to attacks:
- A **short, simple** password can be cracked in **seconds**.
- A **long, complex** password can take **years to brute-force**.
- Tools like PasswordMeter show **entropy and pattern analysis**.

**Conclusion:** More **entropy = more secure**.

---

