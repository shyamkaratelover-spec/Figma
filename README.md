# Ex09 Event Registration Web Application
# Date:06/10/2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saveetha Engineering College</title>

  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Background styling */
    body {
      height: 100vh;
      background: url('sports_background.jpg') no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: "Arial", sans-serif;
    }

    /* Container */
    .container {
      text-align: center;
      width: 90%;
      max-width: 400px;
    }

    /* Top Saveetha Logo */
    .top-logo {
      width: 100%;
      max-width: 350px;
      display: block;
      margin: 0 auto 20px;
    }

    /* Emblem */
    .emblem img {
      width: 200px;
      margin: 20px auto;
      display: block;
    }

    /* Buttons */
    .buttons {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
      margin-top: 20px;
    }

    /* Button Style */
    .btn {
      background-color: #d9d9d9;
      border: none;
      padding: 10px 40px;
      font-size: 22px;
      font-weight: 500;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background-color: #bfbfbf;
    }
  </style>
</head>

<body>

  <div class="container">
    <!-- Top Header Logo -->
    <img src="saveetha_header.png" alt="Saveetha Engineering College" class="top-logo">

    <!-- College Emblem -->
    <div class="emblem">
      <img src="college_emblem.png" alt="College Emblem">
    </div>

    <!-- Buttons -->
    <div class="buttons">
      <button class="btn">Login</button>
      <button class="btn">Registered</button>
    </div>
  </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sports Day Event 2025</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      height: 100vh;
      background: url('sports_bg.jpg') no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: "Arial", sans-serif;
    }
    .container {
      text-align: center;
      color: black;
    }
    h2 {
      font-size: 18px;
      letter-spacing: 1px;
      margin-bottom: 30px;
      font-weight: bold;
    }
    .event-list {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      margin-left: 20px;
    }
    .event-list p {
      font-size: 22px;
      font-weight: 500;
      margin: 10px 0;
      display: flex;
      align-items: center;
      gap: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>SPORTS DAY EVENT 2025</h2>
    <div class="event-list">
      <p>→ <span>volley ball</span></p>
      <p>→ <span>hand ball</span></p>
      <p>→ <span>tennis</span></p>
      <p>→ <span>kho-kho</span></p>
      <p>→ <span>cricket</span></p>
      <p>→ <span>kabbadi</span></p>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Event Registration Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #ff6a00, #ee0979);
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .form-container {
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
      width: 350px;
    }
    .form-container h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #ee0979;
    }
    label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }
    input, select {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .register-btn {
      background-color: #ee0979;
      color: white;
      border: none;
      padding: 10px;
      margin-top: 20px;
      width: 100%;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }
    .register-btn:hover {
      background-color: #ff6a00;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h2>Event Registration Form</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="regno">Register No:</label>
      <input type="text" id="regno" name="regno" required>

      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required>
        <option value="">Select</option>
        <option value="Male">Male</option>
        <option value="Female">Female</option>
        <option value="Other">Other</option>
      </select>

      <label for="department">Department:</label>
      <input type="text" id="department" name="department" required>

      <label for="year">Year:</label>
      <input type="text" id="year" name="year" value="2025" readonly>

      <label for="mobile">Mobile No:</label>
      <input type="tel" id="mobile" name="mobile" required>

      <label for="email">Email ID:</label>
      <input type="email" id="email" name="email" required>

      <label for="game">Interested Game:</label>
      <input type="text" id="game" name="game" required>

      <button type="submit" class="register-btn">REGISTER</button>
    </form>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sports Day Celebration</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #fbc2eb, #a6c1ee);
      color: #333;
    }
    .container {
      max-width: 700px;
      margin: 40px auto;
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    .header {
      text-align: center;
      border-bottom: 2px solid #ee0979;
      padding-bottom: 10px;
    }
    .header h1 {
      margin: 0;
      font-size: 28px;
      color: #ee0979;
    }
    .header p {
      margin: 5px 0;
      font-size: 14px;
      color: #555;
    }
    .thank-you {
      text-align: center;
      font-size: 22px;
      color: red;
      margin: 20px 0;
    }
    .message {
      text-align: center;
      font-size: 18px;
      color: #6a1b9a;
      line-height: 1.6;
      margin-bottom: 30px;
    }
    .contact {
      background-color: #f3f3f3;
      padding: 15px;
      border-radius: 8px;
      font-size: 16px;
      color: #333;
    }
    .contact p {
      margin: 8px 0;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="header">
      <h1>SAVEETHA ENGINEERING COLLEGE</h1>
      <p><strong>AUTONOMOUS</strong></p>
      <p>Affiliated to Anna University | Approved by AICTE</p>
      <p>NAAC A+ Accredited Institution</p>
    </div>

    <div class="thank-you">THANK YOU ALL</div>

    <div class="message">
      I warmly welcome you all to our Sports Day celebration.<br>
      Today is a day of energy, excitement, and sportsmanship.<br>
      Let’s cheer for every participant and enjoy the spirit of the games.
    </div>

    <div class="contact">
      <p><strong>Contact us:</strong></p>
      <p>Email: saveethaengineeringcollege@gmail.com</p>
      <p>Phone: 7653605657</p>
      <p>Phone: 4561496599</p>
    </div>
  </div>

</body>
</html>
```
# OUTPUT:
<img width="404" height="828" alt="Screenshot 2025-10-04 141658" src="https://github.com/user-attachments/assets/ab86107e-e38e-48ca-b686-cdd37a245191" />
<img width="343" height="743" alt="Screenshot 2025-10-04 143538" src="https://github.com/user-attachments/assets/232b851a-90f3-4eac-895e-f4ff49ec7687" />
<img width="329" height="708" alt="Screenshot 2025-10-04 181921" src="https://github.com/user-attachments/assets/e29c2ed3-3643-4e0c-a66c-37e17593a84f" />
<img width="329" height="708" alt="Screenshot 2025-10-04 181921" src="https://github.com/user-attachments/assets/5fc42c45-4a10-406f-8240-889fe2711a9c" />
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
