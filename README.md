# Ex01 Portfolio
## Date:6/6/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #00adb5;
    }

    .container {
      width: 80%;
      margin: auto;
      overflow: hidden;
      padding: 20px 0;
    }

    section {
      margin: 40px 0;
      padding: 20px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      margin-bottom: 15px;
      color: #00adb5;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: #eee;
      padding: 15px;
      border-radius: 8px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: #fff;
      margin-top: 20px;
    }

    @media(max-width: 768px) {
      .container {
        width: 95%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>deepak.b </h1>
    <p>Web Developer | Designer | Student</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">

    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm a passionate web developer learning HTML and CSS. I love creating clean and simple websites.</p>
    </section>

    <section id="projects">
      <h2>My Projects</h2>
      <div class="projects">
        <div class="project">
          <h3>Project 1</h3>
          <p>Simple website using HTML & CSS.</p>
        </div>
        <div class="project">
          <h3>Project 2</h3>
          <p>Responsive landing page.</p>
        </div>
        <div class="project">
          <h3>Project 3</h3>
          <p>Portfolio design.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Email: deepaksudharshanb@gmail.com</p>
      <p>Phone: 7530019481</p>
    </section>

  </div>

  <footer>
    <p>© 2026 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>


```


## OUTPUT
<img width="1778" height="938" alt="image" src="https://github.com/user-attachments/assets/63301867-4509-4c81-8672-1df6b25623e1" />

<img width="1848" height="895" alt="image" src="https://github.com/user-attachments/assets/cc7aadef-8ec0-430d-bfff-830000681bae" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
