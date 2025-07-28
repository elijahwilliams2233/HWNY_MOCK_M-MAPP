# HWNY_MOCK_MM-APP
Empowering the next generation of healthcare professionals through connection and support.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HWNY Mentorship Hub</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f9ff;
      color: #1a355e;
    }
    header {
      background-color: #1a355e;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      text-align: center;
      background-color: #24497c;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-size: 16px;
    }
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }
    h1, h2 {
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      line-height: 1.6;
    }
    .button {
      margin-top: 20px;
      display: inline-block;
      padding: 12px 24px;
      background-color: #1a355e;
      color: white;
      text-decoration: none;
      font-size: 16px;
      border-radius: 6px;
    }
    .button:hover {
      background-color: #3e5d91;
    }
    form {
      margin-top: 30px;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: left;
    }
    form label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
    }
    form input, form select, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 16px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    form button {
      background-color: #1a355e;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #24497c;
    }
    .outreach-box {
      margin-top: 40px;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: left;
    }
    footer {
      margin-top: 60px;
      text-align: center;
      padding: 20px;
      background-color: #e1e9f0;
      font-size: 14px;
      color: #444;
    }
    #confirmation {
      display: none;
      padding: 20px;
      margin-top: 20px;
      background-color: #e6f9e8;
      border: 1px solid #a8e6b4;
      border-radius: 6px;
      color: #256029;
      font-size: 18px;
      text-align: center;
    }
  </style>
  <script>
    function handleFormSubmit(event) {
      event.preventDefault();
      document.getElementById('confirmation').style.display = 'block';
      event.target.reset();
      window.scrollTo({ top: document.getElementById('confirmation').offsetTop, behavior: 'smooth' });
    }
  </script>
</head>
<body>
  <header>
    <h1>HWNY Mentorship Hub</h1>
    <p>Empowering the next generation of healthcare professionals through connection and support.</p>
  </header>

  <nav>
    <a href="#welcome">Welcome</a>
    <a href="#application">Application</a>
    <a href="#outreach">Outreach</a>
  </nav>

  <div class="container" id="welcome">
    <h2>Your Pathway Starts Here</h2>
    <p>
      Whether you're a student exploring your options or a professional looking to give back, HWNY's Mentor–Mentee Matching Program is designed to foster community, inspire confidence, and break down barriers to healthcare careers.
    </p>
    <a class="button" href="#application">Apply Now</a>
  </div>

  <div class="container" id="application">
    <h2>Mentor–Mentee Application Form</h2>
    <form onsubmit="handleFormSubmit(event)">
      <label for="fullname">Full Name</label>
      <input type="text" id="fullname" name="fullname" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="role">I am a:</label>
      <select id="role" name="role">
        <option value="mentee">Mentee (Student/Pre-Health)</option>
        <option value="mentor">Mentor (Healthcare Professional)</option>
      </select>

      <label for="location">Where are you from?</label>
      <input type="text" id="location" name="location" placeholder="City, State or Country">

      <label for="nationality">Nationality</label>
      <input type="text" id="nationality" name="nationality">

      <label for="interest">Healthcare Career Interest</label>
      <input type="text" id="interest" name="interest" placeholder="e.g., Nursing, Public Health, Dentistry">

      <label for="background">Briefly describe your background and what you're looking for in a mentor/mentee</label>
      <textarea id="background" name="background" rows="4"></textarea>

      <label for="learningStyle">Preferred Learning/Teaching Style</label>
      <input type="text" id="learningStyle" name="learningStyle" placeholder="e.g., Visual, Hands-on, Discussion-based">

      <button type="submit">Submit Application</button>
    </form>
    <div id="confirmation">
      ✅ Thank you for applying! Your form has been submitted. Our team will be in touch soon.
    </div>
  </div>

  <div class="container" id="outreach">
    <h2>📣 Outreach Toolkit</h2>
    <div class="outreach-box">
      <p><strong>Want to help spread the word?</strong> Use the resources below to share our mission and get others involved in the program:</p>
      <ul>
        <li><strong>Flyer PDF:</strong> <a href="#">Download and share in classrooms or clinics</a></li>
        <li><strong>Social Post Templates:</strong> Ready-to-use messages for LinkedIn, Instagram, and Facebook</li>
        <li><strong>Email Script:</strong> Prewritten text to invite colleagues or students to participate</li>
        <li><strong>Ambassador Signup:</strong> <a href="#">Become an Outreach Ambassador</a></li>
      </ul>
    </div>
  </div>

  <footer>
    &copy; 2025 HWNY Mentorship. All rights reserved.
  </footer>
</body>
</html>
