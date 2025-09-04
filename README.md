```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="An enhanced HTML5 form example with structured content, multimedia, and validation." />
  <title>Enhanced HTML Form</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    header, footer { background-color: #f0f0f0; padding: 10px; }
    form { max-width: 600px; margin: 20px 0; }
    label { display: block; margin: 10px 0 5px; }
    input, select, textarea { width: 100%; padding: 8px; }
    table { width: 100%; border-collapse: collapse; margin-top: 20px; }
    th, td { border: 1px solid #ccc; padding: 8px; text-align: left; }
    ul { margin-top: 10px; }
  </style>
</head>
<body>

<header>
  <h1>Enhanced HTML5 Form Page</h1>
  <nav>
    <ul>
      <li><a href="#form-section">Form</a></li>
      <li><a href="#info">Info</a></li>
      <li><a href="#media">Media</a></li>
    </ul>
  </nav>
</header>

<main>
  <section id="form-section">
    <h2>User Registration Form</h2>
    <form action="/submit" method="post">
      <label for="fullname">Full Name:</label>
<input type="text" id="fullname" name="fullname" placeholder="Enter full name" required autocomplete="name" />

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" placeholder="example@mail.com" required autocomplete="email" />

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required />

      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" placeholder="08012345678" pattern="[0-9]{11}" required />

      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required>
        <option value="">Select one</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>

      <label for="bio">Short Bio:</label>
      <textarea id="bio" name="bio" placeholder="Tell us about yourself..." rows="4"></textarea>

      <label>
        <input type="checkbox" name="terms" required />
        I agree to the terms and conditions
      </label>

      <input type="submit" value="Submit Form" />
    </form>
  </section>

  <section id="info">
    <h2>Why Use Enhanced Forms?</h2>
    <ul>
      <li>Improves user experience</li>
<li>Ensures better data validation</li>
      <li>Enhances accessibility</li>
    </ul>

    <h3>Sample Data Table</h3>
    <table>
      <thead>
        <tr>
          <th>Field</th>
          <th>Validation</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Email</td>
          <td>Required, must be valid format</td>
        </tr>
        <tr>
          <td>Phone</td>
          <td>Required, 11-digit pattern</td>
        </tr>
        <tr>
          <td>Date of Birth</td>
          <td>Required, must select a date</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section id="media">
    <h2>Media Example</h2>
    <p>Watch the video below to learn more about HTML5 forms:</p>
    <video width="100%" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
      Your browser does not support HTML5 video.
    </video>
  </section>
</main>

<footer>
  <p>&copy; 2025 Your Name. All rights reserved.</p>
</footer>

</body>
</html>
```

This file includes:
- *Semantic structure* with `<header>`, `<main>`, `<section>`, `<footer>`, and clear heading hierarchy.
- *HTML5 form* with fields using `required`, `placeholder`, `autocomplete`, and `pattern`.
- *Accessibility* via proper form labeling and layout.
- - *SEO-friendly metadata* and readable content.
- *Media* (`<video>`) and structured content (`<ul>`, `<table>`). 
