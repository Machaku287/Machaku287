<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MACHAKU PREMIER TUTORING</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #588800; /* Purple background color */
    color: #fff; /* Text color */
    text-align: center;
    padding-top: 50px;
  }
  form {
    width: 80%;
    margin: 0 auto;
  }
  input[type="text"], input[type="number"], input[type="email"], select, textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: none;
    box-sizing: border-box;
  }
  input[type="file"] {
    margin-top: 10px;
  }
  input[type="submit"] {
    background-color: #fff;
    color: #6a0dad; /* Purple text color */
    padding: 10px 20px;
    border-radius: 5px;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  input[type="submit"]:hover {
    background-color: #ddd;
  }
</style>
</head>
<body>
<h2>MACHAKU PREMIER TUTORING REGISTRATION FORM</h2>
<form action="#" method="post" enctype="multipart/form-data">
  <input type="text" name="first_name" placeholder="First Name" required><br>
  <input type="text" name="middle_name" placeholder="Middle Name"><br>
  <input type="text" name="surname" placeholder="Surname" required><br>
  <input type="number" name="age" placeholder="Age" required><br>
  <select name="sex" required>
    <option value="">Select Sex</option>
    <option value="male">Male</option>
    <option value="female">Female</option>
    <option value="other">Other</option>
  </select><br>
  <select name="marital_status" required>
    <option value="">Select Marital Status</option>
    <option value="single">Single</option>
    <option value="married">Married</option>
    <option value="divorced">Divorced</option>
    <option value="widowed">Widowed</option>
  </select><br>
  <input type="text" name="phone_number" placeholder="Phone Number" required><br>
  <input type="email" name="email" placeholder="Email" required><br>
  <input type="text" name="whatsapp_number" placeholder="Whatsapp Number" required><br>
  <select name="employment_status" required>
    <option value="">Select Employment Status</option>
    <option value="employed">Employed</option>
    <option value="unemployed">Unemployed</option>
    <option value="student">Student</option>
    <option value="self_employed">Self-Employed</option>
  </select><br>
  <input type="file" name="passport1" accept="image/*" required><br>
  <input type="file" name="passport2" accept="image/*" required><br>
  <textarea name="comment" placeholder="Comment"></textarea><br>
  <textarea name="purpose_of_enrollment" placeholder="Purpose of Enrollment to MACHAKU PREMIER TUTORING" required></textarea><br>
  <input type="text" name="location" placeholder="Your Location" required><br>
  <input type="submit" value="Submit"><br>
</form>
<p>Thank you for registering with MACHAKU PREMIER TUTORING. We will contact you shortly.</p>
</body>
</html>
