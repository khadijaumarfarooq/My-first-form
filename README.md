<!DOCTYPE html>
<html lang="en">
<head>
   <title>Khadija Umar Farooq - HTML Practice</title>
 <style>
    body {
    font-family: Arial, sans-serif;
    background: #f8f9fa;
    margin: 0;
    padding: 20px;
  }
  h1, h2, h3 {
    color: #2c3e50;
  }
  section {
    background: white;
    padding: 15px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }
  table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
  }
  th, td {
    border: 1px solid #555;
    padding: 8px;
    text-align: center;
  }
  th {
    background: #2c3e50;
    color: white;
  }
  form {
    display: flex;
    flex-direction: column;
  }
  input, select, textarea, button {
    margin: 8px 0;
    padding: 8px;
    border-radius: 5px;
    border: 1px solid #aaa;
  }
  button {
    background: #2c3e50;
    color: white;
    cursor: pointer;
  }
  button:hover {
    background: #34495e;
  }
</style>
  <h1>🌸 Welcome to HTML Playground 🌸</h1>
  <p style="text-align:center;">Here I will practice basic HTML tags and elements.</p>

  <!-- About Section -->
  <section>
    <h2>About Me</h2>
    <p>I am <b>Khadija Umar Farooq</b>, a student of <b>12th Class</b> in the field of <b>Pre-Engineering</b>.  
    This page demonstrates HTML concepts like headings, lists, tables, forms, audio, and video.</p>
  </section>

  <!-- Headings -->
  <section>
    <h2>Headings</h2>
    <h1>Main Title - H1</h1>
    <h2>Section Title - H2</h2>
    <h3>Subsection - H3</h3>
    <h4>Details - H4</h4>
    <h5>More Details - H5</h5>
    <h6>Smallest - H6</h6>
  </section>

  <!-- Lists -->
  <section>
    <h2>My Interests</h2>
    <ul>
      <li>Mathematics</li>
      <li>Chemistry</li>
      <li>Programming</li>
    </ul>

  <h2>My Skills</h2>
    <ol>
      <li>HTML</li>
      <li>CSS</li>
      <li>Basic Python</li>
    </ol>

   <h2>Description List</h2>
    <dl>
      <dt>Physics</dt>
      <dd>Study of matter and energy.</dd>
      <dt>Chemistry</dt>
      <dd>Study of atoms and reactions.</dd>
      <dt>Math</dt>
      <dd>Study of numbers and logic.</dd>
    </dl>
  </section>

  <!-- Table -->
  <section>
    <h2>Education</h2>
    <table>
      <tr>
        <th>Class</th>
        <th>Field</th>
        <th>Status</th>
      </tr>
      <tr>
        <td>10th</td>
        <td>Science</td>
        <td>Completed ✅</td>
      </tr>
      <tr>
        <td>12th</td>
        <td>Pre-Engineering</td>
        <td>Currently Studying 📚</td>
      </tr>
    </table>
  </section>

  <!-- Form -->
  <section>
    <h2>Contact Form</h2>
    <form>
      <label>Name:</label>
      <input type="text" placeholder="Enter your name">

  <label>Email:</label>
      <input type="email" placeholder="Enter your email">

   <label>Password:</label>
      <input type="password" placeholder="Enter password">

   <label>Gender:</label>
      <input type="radio" name="gender" value="male"> Male
      <input type="radio" name="gender" value="female"> Female

   <label>Date of Birth:</label>
      <input type="date">

   <label>Choose your City:</label>
      <select>
        <option>Hyderabad</option>
        <option>Karachi</option>
        <option>Islamabad</option>
      </select>

   <label>Choose your Interests:</label>
      <input type="checkbox" value="reading"> Reading
      <input type="checkbox" value="coding"> Coding
      <input type="checkbox" value="traveling"> Traveling

  

  label>Upload File:</label>
      <input type="file">

  <button>
  <type="submit">Submit</button>
      <button type="reset">Reset</button>
    </form>
  </section>
   <!-- Media -->
  <section>
    <h2>Media (Audio & Video)</h2>
    <p>Audio Example:</p>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    </audio>

    <p>Video Example:</p>
    <video controls width="300">
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
    </video>
  </section>

</body>
</html>
