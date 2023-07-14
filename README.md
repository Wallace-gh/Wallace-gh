<!DOCTYPE html>
<html>
<head>
  <title>Student Registration Form</title>
</head>
<body>
  <h1>Student Registration Form</h1>

  <form action="process_form.php" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br><br>

    <label for="telephone">Telephone Number:</label>
    <input type="tel" id="telephone" name="telephone" required><br><br>

    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required><br><br>

    <label for="admission">Admission Number:</label>
    <input type="text" id="admission" name="admission" required><br><br>

    <label for="course">Course:</label>
    <select id="course" name="course" required>
      <option value="CBIT">CBIT</option>
      <option value="CIT">CIT</option>
    </select><br><br>

    <label for="gender">Gender:</label>
    <input type="radio" id="male" name="gender" value="Male" required>
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="Female" required>
    <label for="female">Female</label><br><br>

    <input type="submit" value="Submit">
  </form>
</body>
</html>
