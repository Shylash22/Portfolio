# Ex01 Portfolio
## Date:20/7/2026

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
~~~
index.html
~~~
~~~
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>My Portfolio</h1>
      <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section id="home" class="hero">
      <h2>Hello, I'am shylash A</h2>
      <p>Computer Science Engineering Student</p>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <p>
        I am a Computer Science Engineering student interested in web
        development, programming, and learning new technologies. I enjoy
        creating websites and solving coding problems.
      </p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>C Programming</li>
        <li>Python</li>
        <li>Java</li>
      </ul>
    </section>

    <section id="projects">
      <h2>Projects</h2>

      <div class="project">
        <h3>Portfolio Website</h3>
        <p>A personal website created using HTML and CSS.</p>
      </div>

      <div class="project">
        <h3>Student Management System</h3>
        <p>A simple C program to manage student records.</p>
      </div>

      <div class="project">
        <h3>Calculator</h3>
        <p>A basic calculator designed using HTML, CSS, and JavaScript.</p>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: shythee@123gmail.com</p>
      <p>Phone: +91 8870181840</p>
    </section>

    <footer>
      <p>&copy; 2026 My Portfolio. All Rights Reserved.</p>
    </footer>
  </body>
</html>

~~~
~~~
style.css
~~~
~~~
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f1f1;
    color:#333;
}

header{
    background:#222;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    margin-top:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}

nav a:hover{
    color:orange;
}

.hero{
    text-align:center;
    padding:50px;
    background:#4f94b9;
    color:white;
}

.hero img{
    width:150px;
    height:150px;
    border-radius:50%;
    border:4px solid white;
    margin-bottom:20px;
}

section{
    padding:40px;
}

h2{
    margin-bottom:20px;
    color:#0077b6;
}

ul{
    list-style-type:square;
    margin-left:20px;
}

.project{
    background:white;
    padding:20px;
    margin-bottom:20px;
    border-radius:8px;
    box-shadow:0 0 8px rgba(0,0,0,0.2);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}

@media(max-width:768px){
    nav a{
        display:block;
        margin:10px;
    }

    .hero img{
        width:120px;
        height:120px;
    }
}
~~~

## OUTPUT


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
