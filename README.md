
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>Myportofolio</title>
<meta name="generator" content="Jekyll v3.10.0" />
<meta property="og:title" content="Myportofolio" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://akarshms06.github.io/Myportofolio/" />
<meta property="og:url" content="https://akarshms06.github.io/Myportofolio/" />
<meta property="og:site_name" content="Myportofolio" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="Myportofolio" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"Myportofolio","name":"Myportofolio","url":"https://akarshms06.github.io/Myportofolio/"}</script>


    <link rel="stylesheet" href="/Myportofolio/assets/css/style.css?v=42728aed85f0875397d3caf0ca02907a148a29e3">

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://akarshms06.github.io/Myportofolio/">Myportofolio</a></h1>
      

     
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="user-scalable=no, width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0" />

    <title>Akarsh: Code &amp; Creativity that Captivates</title>
    <link rel="stylesheet" href="styles.css" />
    <style>
  /* Basic CSS styling */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0; /* Light Gray Background Color */
    overflow-x: hidden; /* Prevent horizontal scroll */
}

/* Updated Header Style */
header {
    background: #323e4e; /* Gradient Background */
    color: #fff;
    padding: 20px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Adds subtle shadow */
    opacity: 0; /* Start hidden */
    transform: translateY(-20px); /* Start position for animation */
    animation: fadeIn 0.5s forwards; /* Fade-in animation */
    animation-delay: 0.5s; /* Delay before the header appears */
}

@keyframes fadeIn {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

header h1 {
    margin: 0;
    font-size: 2rem; /* Adjusted font size for better responsiveness */
    font-weight: bold;
    text-align: left;
    padding-left: 20px;
    display: inline-block;
}

nav {
    float: right;
    padding-right: 20px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

/* Round Button Styling */
.round-button {
    display: inline-block;
    background-color: #8916d6; /* Button background color */
    color: #fff; /* Text color */
    padding: 5px 20px; /* Padding for button size */
    border-radius: 50px; /* Makes the button round */
    text-decoration: none; /* Remove underline */
    font-size: 1rem; /* Adjusted font size for better responsiveness */
    transition: background-color 0.3s ease, transform 0.3s ease; /* Smooth hover effect */
}

.round-button:hover {
    background-color: #555; /* Hover background color */
    transform: scale(1.05); /* Slightly enlarge on hover */
}

nav ul li {
    display: inline-block;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(to right, #00FF5B, #0014FF);
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #8fcfcc;
    gap: 40px;
    flex-wrap: wrap;
    opacity: 0; /* Start hidden */
    transform: translateY(20px); /* Start position for animation */
    animation: slideIn 0.8s forwards; /* Slide-in animation */
    animation-delay: 1s; /* Delay before the hero section appears */
}

@keyframes slideIn {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.hero-text {
    font-weight: bold;
    max-width: 500px;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    color: #555;
}

.hero img {
    width: 250px; /* Adjusted width for smaller screens */
    height: 250px; /* Adjusted height for smaller screens */
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    opacity: 0; /* Start hidden */
    transform: translateX(-20px); /* Start position for animation */
    animation: fadeInImage 0.8s forwards; /* Fade-in animation for the image */
    animation-delay: 1.3s; /* Delay before the image appears */
}

@keyframes fadeInImage {
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

/* Projects Section */
.projects {
    padding: 50px 20px;
    background-color: #838181;
}

.projects h2 {
    text-align: center;
    margin-bottom: 40px;
    font-size: 2.2rem;
}

.project-grid {
    display: flex;
    justify-content: center; /* Center items on smaller screens */
    flex-wrap: wrap;
}

.project-item {
    background-color: #fff;
    padding: 20px;
    margin: 15px;
    width: 300px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* Smooth hover effect */
}

.project-item:hover {
    transform: translateY(-5px); /* Lift effect */
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2); /* Enhanced shadow */
}

.project-item h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
}

/* Footer */
footer {
    background-color: #474444;
    color: #ffffff;
    text-shadow: #555;
    text-align: center;
    padding: 20px;
    opacity: 0; /* Start hidden */
    transform: translateY(20px); /* Start position for animation */
    animation: slideInFooter 0.5s forwards; /* Slide-in animation for footer */
    animation-delay: 1.5s; /* Delay before the footer appears */
}

@keyframes slideInFooter {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

footer a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}

footer a:hover {
    text-decoration: underline;
}

/* Media Queries for Responsive Design */
@media (max-width: 768px) {
    header h1 {
        font-size: 1.5rem; /* Adjust header font size for mobile */
    }

    .hero h2 {
        font-size: 2rem; /* Adjust hero heading size */
    }

    .hero p {
        font-size: 1rem; /* Adjust hero paragraph size */
    }

    .project-item {
        width: 90%; /* Full width on mobile */
    }
}

    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Akarsh: Code &amp; Creativity</h1>
        <nav>
            <ul>
                <li><a href="#" class="round-button">About</a></li>
                <li><a href="#" class="round-button">Projects</a></li>
                <li><a href="#" class="round-button">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <img src="https://i.pinimg.com/474x/65/e6/35/65e6352d40424e8ccc86a7e7e604effd.jpg" alt="Akarsh Image" />
        <div class="hero-text">
            <h2>Welcome to My Portfolio!</h2>
            <p style="color: #fff;">
                Akarsh is an Information Science student at PES Engineering College, passionate about coding, UI/UX design, and creative problem-solving.
            </p>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="projects">
        <h2>My Projects</h2>
        <div class="project-grid">
            <div class="project-item">
                <h3>Project 1</h3>
                <p>A short description of the project goes here.</p>
            </div>
            <div class="project-item">
                <h3>Project 2</h3>
                <p>A short description of the project goes here.</p>
            </div>
            <div class="project-item">
                <h3>Project 3</h3>
                <p>A short description of the project goes here.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow me on:</p>
        <p>
            <a href="https://www.linkedin.com/in/akarsh-venkatesha-ms-174779283/" class="round-button">LinkedIn</a>
            
            <a href="https://github.com/Akarshms06" class="round-button">GitHub</a>
        </p>
        <p>&copy; 2024 Akarsh. All Rights Reserved.</p>
        
    </footer>

</body>
</html>


      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  </body>
</html>
