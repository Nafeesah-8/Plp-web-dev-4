<!DOCTYPE html>
<html lang="en">
  <style>
    body {
      padding: 0 2%;
    }
    h2 {
      padding: 0 3%;
      font-size: medium;
    }
  </style>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>FORM CREATION</title>
  </head>
  <body>
    <h2>MY WEB DEVELOPMENT FORM PRACTICE</h2>
    <p>Plp web development week 3</p> <br>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" placeholder="Enter your name" required/> <br> <br>
      <label for="date_birth">Date of birth:</label>
      <input type="date" id="date_birth" required>
      <fieldset>
        <legend>Gender</legend>
        <input type="radio" id="female" name="female" required> <label for="gender">Female</label> <br>
        <input type="radio" id="male" name="male" required> <label for="male">Male</label>
      </fieldset> <br>
      <label for="address" name="address">Address:</label>
      <input type="text" id="address" placeholder="Enter your address" required> <br> <br>
      <label for="Telephone">Telephone:</label>
      <input type="text" id="Telephone" name="Telephone" placeholder="Input your contact" required> <br> <br>
      <label for="email">Email:</label>
      <input type="email" id="email" placeholder="Enter your mail" required> <br> <br>
      <label for="course">Course of study</label>
      <select required>
        <option>English Language</option>
        <option>Mathematics</option>
        <option>Lit-in-English</option>
        <option>Economics</option>
        <option>Civic Education</option>
        <option>Other</option>
      </select> <br> <br>
      <label  for="Other">Other</label>
      <input type="text" id="Other" name="Other" placeholder="Other course of study"> <br> <br> <br>
      <button type="button">Register</button> <button type="button" style="text-align: center";>Cancel</button>
    </form> 
  </body>
</html>
