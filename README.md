# 🔐 Password Strength Checker

A simple interactive Python-based tool that helps you **evaluate and improve your password**. It checks for:

- ✅ Length (minimum 8 characters)
- ✅ Uppercase letters
- ✅ Lowercase letters
- ✅ Numbers
- ✅ Special characters (like !, @, #, etc.)

The tool **keeps prompting you** until you create a strong password or choose to exit.

---

## 🚀 Features

- Loops continuously until a strong password is entered
- Provides detailed suggestions on how to improve weak passwords
- Lets users exit anytime by typing `exit` or `quit`
- Uses only built-in Python libraries (`re`) — no installation required

---

## 🧠 Password Strength Logic

| Criteria                     | Points |
|-----------------------------|--------|
| 8 or more characters         | 1      |
| At least one uppercase letter | 1      |
| At least one lowercase letter | 1      |
| At least one number           | 1      |
| At least one special character | 1      |

| Total Score | Strength   |
|-------------|------------|
| 5           | ✅ Strong   |
| 3–4         | ⚠️ Moderate |
| 0–2         | ❌ Weak     |

---

## 📦 Requirements

- Python 3.x
- Works on Windows, Linux, MacOS

---

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Password_Strength_Checker.git
   cd Password_Strength_Checker
2. **Run the script**
    ````bash
    python password_strength_checker.py
3. **Follow the prompt**
- Enter passwords to test their strength.
- Type exit or quit to close the program.

## Example:

🔐 Password Strength Checker
Type 'exit' anytime to quit.

Enter your password: hello123
Assessment: ❌ Weak password
Suggestions to improve:
- ❌ Include at least one uppercase letter.
- ❌ Include at least one special character (!@#$, etc).

Try again or type 'exit' to quit.


## 🧙‍♂️ Pro Tips

- Use a mix of uppercase, lowercase, numbers, and symbols.
- Longer passwords are safer.
- Avoid using your name, DOB, or common words.**

Created by codex21venom as part of a cybersecurity internship @SkillCraft_Technology.