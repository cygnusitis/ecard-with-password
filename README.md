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
```
### Step 2: Insert Your Custom Message

Find the `<div id="messageCard">` section (around line 77) and replace the placeholder message.

```<!-- Around Line 77 in index.html -->

<div id="messageCard" style="display: none;">
  <h3 style="text-align: left;">[Custom Greeting Line Here]</h3>
  <p>
    <!--insert message here-->
    This is my secret message! I updated the password to my dog's name.

    Hope you have a wonderful day!
  </p>
</div>
```
### Step 3: Commit and Push

Once you've made your changes, commit them to your repository and push:

***MANUAL FIX REQUIRED: Wrap the following code in \\\bash and \\\ after copying.*** git add index.html git commit -m "feat: Added my personalized message and password" git push origin main ***END OF CODE BLOCK***

Feel free to also change the CSS styles (lines 17-70) if you want a different color scheme or layout!

## 🤝 Getting Started

If you're new to Git or GitHub, this is a great, simple project to practice the Fork > Clone > Edit > Commit > Push workflow!

## 📄 License

This project is licensed under the MIT License.
