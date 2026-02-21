
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sameer Ali - Official Website</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    scroll-behavior:smooth;
}
nav{
    background:#111;
    padding:15px;
    text-align:center;
    position:fixed;
    width:100%;
}
nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}
nav a:hover{
    color:yellow;
}
section{
    padding:100px 20px;
    text-align:center;
}
#home{
    background:linear-gradient(to right, #4facfe, #00f2fe);
    color:white;
}
#about{background:#f4f4f4;}
#skills{background:#e0f7fa;}
#services{background:#fce4ec;}
#gallery{background:#f3e5f5;}
#contact{background:#eeeeee;}

.card{
    background:white;
    padding:20px;
    margin:15px;
    display:inline-block;
    width:250px;
    box-shadow:0 0 10px gray;
    border-radius:10px;
}

button{
    padding:10px 20px;
    border:none;
    background:black;
    color:white;
    cursor:pointer;
}
button:hover{
    background:orange;
}
input, textarea{
    width:80%;
    padding:10px;
    margin:10px;
}
footer{
    background:black;
    color:white;
    padding:20px;
}
</style>
</head>

<body>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>

<section id="home">
<h1>Welcome to Sameer Ali's Website</h1>
<p>Web Developer | Student | Freelancer</p>
<button onclick="showMessage()">Click Me</button>
</section>

<section id="about">
<h2>About Me</h2>
<p>Hello! I am Sameer Ali. I am learning Web Development and Programming.</p>
</section>

<section id="skills">
<h2>My Skills</h2>
<div class="card">HTML</div>
<div class="card">CSS</div>
<div class="card">JavaScript</div>
<div class="card">C++</div>
</section>

<section id="services">
<h2>My Services</h2>
<div class="card">
<h3>Website Design</h3>
<p>I create modern websites.</p>
</div>
<div class="card">
<h3>Programming Help</h3>
<p>I help in coding projects.</p>
</div>
</section>

<section id="gallery">
<h2>Gallery</h2>
<img src="https://via.placeholder.com/200" alt="">
<img src="https://via.placeholder.com/200" alt="">
<img src="https://via.placeholder.com/200" alt="">
</section>

<section id="contact">
<h2>Contact Me</h2>
<input type="text" placeholder="Your Name"><br>
<input type="email" placeholder="Your Email"><br>
<textarea placeholder="Your Message"></textarea><br>
<button>Send Message</button>
</section>

<footer>
<p>© 2026 Sameer Ali | All Rights Reserved</p>
</footer>

<script>
function showMessage(){
    alert("Welcome to Sameer Ali's Website!");
}
</script>

</body>
</html>
