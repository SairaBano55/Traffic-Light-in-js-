🚦 Traffic Light Simulator | JavaScript Basics

## 📌 Description
This repository features an interactive JavaScript practice file that simulates a real-world **Traffic Light System**. The program dynamically captures user input via a browser prompt, processes the variable state through standard conditional statements, and logs the safety action directly to the console.

---

## ⚡ Key Concepts Practiced
* 💬 **Dynamic User Input:** Utilizing the `prompt()` method to take runtime values.
* 🔀 **Conditional Comparison:** Evaluating matching string values using strict equality (`===`).
* 🛡️ **Fallback Logic:** Providing an `else` block to successfully catch and flag invalid string entries.

---

## 💻 Source Code

Here is the exact bug-free source code saved in this practice file:

```javascript
let user = prompt("Enter Your Traffic light Color");
let red = "red";

if(user === "red"){
    console.log("Stop! Danger");
}
else if(user === "yellow"){
    console.log("Slow down and wait");
}
else if(user === "green"){
    console.log("Go ahead");
}
else{
    console.log("Invalid Color");
}
```

---

## 📊 Traffic Rules Logic Matrix

| Input Color Value | Console Log Response | Action Required |
| :---: | :--- | :---: |
| 🔴 **"red"** | `"Stop! Danger"` | **Stop Immediately** |
| 🟡 **"yellow"** | `"Slow down and wait"` | **Decelerate / Prepare** |
| 🟢 **"green"** | `"Go ahead"` | **Proceed Safely** |
| ❓ *Any other text* | `"Invalid Color"` | **Input Unrecognized** |

---

## 🖥️ Expected Live Output

When executed in a browser console environment:

1. **User types `red` inside prompt:**
   ```text
   Stop! Danger
   ```
2. **User types `yellow` inside prompt:**
   ```text
   Slow down and wait
   ```
3. **User types `purple` inside prompt:**
   ```text
   Invalid Color
   ```

---

## 🚀 Step-by-Step Execution Guide

1. Since the script relies on the window object's `prompt()` function, it **must run in a browser environment**.
2. Open any active browser webpage.
3. Right-click anywhere and choose **Inspect** (or press `F12`) to access Developer Tools.
4. Navigate to the **Console** tab.
5. Paste the complete code block and click **Enter**.
6. Enter a traffic light color when the dialog box prompts you!

---
<p align="center">
  🚦 <i>Flawless logic! Keep building, practicing, and leveling up your coding skills.</i> 🚀
</p>

## ✍️ Author
- GitHub: [SairaBano55](https://github.com/SairaBano55)
