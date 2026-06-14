<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>

<h1 align="center">🏥 Health BMI Checker</h1>

<p align="center">
A simple and user-friendly Python application that calculates Body Mass Index (BMI)
and provides a health status report based on the user's weight and height.
</p>

<hr>

<h2>📌 Features</h2>

<ul>
    <li>Calculate BMI accurately using weight and height.</li>
    <li>Automatic conversion from centimeters to meters.</li>
    <li>Displays BMI score with health category.</li>
    <li>Provides personalized health tips.</li>
    <li>Handles invalid inputs safely.</li>
    <li>Clean and beginner-friendly Python code.</li>
</ul>

<hr>

<h2>🧮 BMI Categories</h2>

<table border="1" cellpadding="8">
    <tr>
        <th>BMI Range</th>
        <th>Category</th>
    </tr>
    <tr>
        <td>Below 18.5</td>
        <td>🟡 Underweight</td>
    </tr>
    <tr>
        <td>18.5 - 24.9</td>
        <td>🟢 Healthy Weight</td>
    </tr>
    <tr>
        <td>25.0 - 29.9</td>
        <td>🟠 Overweight</td>
    </tr>
    <tr>
        <td>30.0 and Above</td>
        <td>🔴 Obese</td>
    </tr>
</table>

<hr>

<h2>🚀 Getting Started</h2>

<h3>Requirements</h3>

<ul>
    <li>Python 3.x</li>
</ul>

<h3>Run the Program</h3>

<pre>
python bmi_checker.py
</pre>

<hr>

<h2>📷 Example Output</h2>

<pre>
═════════════════════════════════════════════
🏥      HEALTH BMI CHECKER      🏥
═════════════════════════════════════════════

📥 Enter Your Information

⚖️ Weight (kg) : 70
📏 Height (cm) : 175

───────────────────────────────────
📊 YOUR BMI REPORT
───────────────────────────────────

⚖️ Weight      : 70.0 kg
📏 Height      : 175.0 cm
🧮 BMI Score   : 22.86
❤️ Health Type : 🟢 Healthy Weight

───────────────────────────────────

🎉 Great! Your BMI is in a healthy range.

✅ Calculation Completed Successfully!
</pre>

<hr>

<h2>🛡️ Input Validation</h2>

<ul>
    <li>Prevents negative or zero values.</li>
    <li>Handles non-numeric input using exception handling.</li>
    <li>Displays clear error messages for invalid data.</li>
</ul>

<hr>

<h2>📚 Technologies Used</h2>

<ul>
    <li>Python 3</li>
    <li>Functions</li>
    <li>Conditional Statements</li>
    <li>Exception Handling</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<strong>Nahian Kabir Siam</strong><br>
Python Developer & Programming Enthusiast
</p>

<hr>

<p align="center">
⭐ If you like this project, consider giving it a star on GitHub!
</p>

</body>
</html>
