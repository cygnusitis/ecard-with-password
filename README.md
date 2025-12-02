# 💌 Collaborative E-Card Project

This repository hosts a single-page HTML E-Card application. The primary goal of this repository is collaboration: everyone is invited to **fork this project, change the secret message, and set their own unique password** for their version of the card.

---

## ✨ Project Overview

This is a simple, stylish E-Card built with HTML, CSS, and vanilla JavaScript.

* **Password Protected:** The personal message is hidden until the user enters the correct secret password.
* **Interactive:** Prompts the user for their name upon loading for a personalized greeting.
* **Simple & Clean:** All code is contained in a single `index.html` file, making it easy to share, host, and edit.

---

## 🚀 How to Run Locally

You only need a modern web browser to run this project.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
    cd YourRepoName
    ```
2.  Open the `index.html` file directly in your web browser (e.g., double-click it in your file explorer).

---

## 🛠️ How to Contribute (Personalize Your Card)

The core contribution to this repository is by **personalizing the E-Card** in your own fork. You will need to edit two specific sections inside the `index.html` file: the **Secret Password** and the **Message Content**.

### Step 1: Change the Secret Password

You need to update the JavaScript variable `correctPassword`.

1.  Open the `index.html` file.
2.  Find the `<script>` section at the bottom of the file (around line 140).
3.  Change the value of `correctPassword` to your new, secret phrase:

```javascript
// Line 140 in index.html
const correctPassword = "your-new-secret-password";
// Example: const correctPassword = "happybirthday2025";
