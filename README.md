# Developer QR Resume Generator

## Project Overview

The **Developer QR Resume Generator** is a beginner programming challenge where students create a program that generates a **QR Code containing a short developer resume**.

When the QR code is scanned, it should display information about the developer, including their **name, experience level, skills, and GitHub profile**.

This project helps beginners practice:

* User input
* Conditional logic
* Input validation
* String formatting
* QR code generation
* File creation
* Looping for multiple outputs

Students may use **any programming language**.

---

# Project Objective

Create a program that:

1. Collects developer information
2. Determines their **developer level using logic**
3. Validates user input
4. Generates a **Developer Resume Message**
5. Converts that message into a **QR Code**
6. Saves the QR code as an **image file**
7. Allows generating **multiple QR codes**

---

# Program Requirements

## 1. Collect User Information

Your program must ask the user to input the following:

* Name
* GitHub Username
* Favorite Programming Language
* Years of Programming Experience

Example input:

Enter your name: Maria
Enter your GitHub username: mariadev
Enter your favorite programming language: Python
Enter your years of experience: 4

---

# 2. Input Validation

Your program must validate the **GitHub username**.

If the username is empty, display an error message and ask the user to enter it again.

Example:

Username cannot be empty. Please enter a valid GitHub username.

---

# 3. Count Username Length

After receiving the username, your program must **count the number of characters** in the username and display it.

Example:

GitHub Username: mariadev
Username Length: 8 characters

---

# 4. Developer Level Logic

Determine the developer level based on years of experience.

| Years of Experience | Developer Level        |
| ------------------- | ---------------------- |
| 0 – 1               | Beginner Developer     |
| 2 – 4               | Intermediate Developer |
| 5+                  | Expert Developer       |

---

# 5. Add Emoji Based on Developer Level

Your program must add an emoji depending on the developer level.

| Level        | Emoji |
| ------------ | ----- |
| Beginner     | 🌱    |
| Intermediate | 🚀    |
| Expert       | 🧠    |

Example:

Developer Level: Intermediate Developer 🚀

---

# 6. Generate Developer Resume Message

Your program must generate a message like this:

Developer Profile

Name: Maria
Level: Intermediate Developer 🚀
Favorite Language: Python

GitHub Profile:
https://github.com/mariadev

Username Length: 8 characters

Scan this QR code to view my developer profile.

---

# 7. Generate QR Code

Convert the **developer resume message** into a QR Code.

When scanned, the QR code should display the developer profile message.

---

# 8. Save the QR Code

Save the QR code as an image file.

File format:

developer_qr_[name].png

Example:

developer_qr_maria.png

---

# 9. Generate Multiple QR Codes

Your program must allow users to generate **multiple developer QR resumes**.

After generating one QR code, ask the user:

Do you want to generate another QR code? (yes/no)

Example flow:

Welcome to the Developer QR Resume Generator!

QR code created successfully.
Saved as: developer_qr_maria.png

Generate another QR code? yes

---

# Example Program Output

Welcome to the Developer QR Resume Generator!

Enter your name: Maria
Enter your GitHub username: mariadev
Enter your favorite programming language: Python
Enter years of experience: 4

Username Length: 8 characters

Developer Level: Intermediate Developer 🚀

Generating QR Code...

Success!
Your Developer QR Resume has been created.

Saved as: developer_qr_maria.png

---

# Example Scan Result

Developer Profile

Name: Maria
Level: Intermediate Developer 🚀
Favorite Language: Python

GitHub Profile:
https://github.com/mariadev

Username Length: 8 characters

---

# Submission Requirements

Students must submit:

1. Source Code
2. Generated QR Code Image
3. Screenshot showing the scanned QR result
4. Programming language used

---

# Grading Criteria

| Criteria                          | Points |
| --------------------------------- | ------ |
| Program runs successfully         | 20     |
| Correct developer level logic     | 20     |
| Input validation (username check) | 15     |
| Username length calculation       | 10     |
| QR Code generation                | 20     |
| Multiple QR generation logic      | 10     |
| Code readability                  | 5      |

Total: **100 Points**

---

# Learning Outcome

After completing this project, students will understand:

* Input validation
* Conditional logic
* String manipulation
* Looping
* File generation
* QR code creation
* Building a small real-world program
