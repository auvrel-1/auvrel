<!DOCTYPE html>
<html>
<head>
<title>Auvrel</title>

<style>

body{
margin:0;
font-family:Arial;
background:#0f0f0f;
color:white;
}

/* Navbar */

.navbar{
display:flex;
justify-content:space-between;
padding:20px 40px;
background:#0f0f0f;
border-bottom:1px solid #222;
}

.logo{
font-size:22px;
font-weight:bold;
letter-spacing:2px;
}

.menu a{
color:white;
text-decoration:none;
margin-left:20px;
font-size:14px;
}

/* Hero section */

.hero{
text-align:center;
padding:140px 20px;
}

.hero h1{
font-size:60px;
letter-spacing:4px;
margin-bottom:10px;
}

.hero p{
color:#aaa;
font-size:20px;
}

.hero button{
margin-top:30px;
padding:12px 30px;
font-size:16px;
border:none;
background:white;
color:black;
cursor:pointer;
border-radius:4px;
}

/* Section */

.section{
padding:80px 20px;
text-align:center;
}

.section h2{
font-size:30px;
margin-bottom:20px;
}

.section p{
max-width:600px;
margin:auto;
color:#bbb;
}

/* Footer */

.footer{
text-align:center;
padding:30px;
border-top:1px solid #222;
color:#777;
}

</style>
</head>

<body>

<!-- Navbar -->

<div class="navbar">

<div class="logo">AUVREL</div>

<div class="menu">
<a href="#">Home</a>
<a href="#">Philosophy</a>
<a href="#">Ideas</a>
<a href="#">About</a>
</div>

</div>


<!-- Hero -->

<div class="hero">

<h1>AUVREL</h1>

<p>Where ideas grow and perspectives evolve.</p>

<button onclick="scrollToSection()">Explore</button>

</div>


<!-- Section -->

<div class="section" id="section">

<h2>A Space for Thought</h2>

<p>
Auvrel adalah ruang untuk ide, refleksi, dan pertumbuhan pemikiran.
Tempat di mana filosofi, kehidupan, dan perspektif bertemu.
</p>

</div>


<!-- Footer -->

<div class="footer">

<p>© 2026 Auvrel</p>

</div>


<script>

function scrollToSection(){
document.getElementById("section").scrollIntoView({
behavior:"smooth"
});
}

</script>


</body>
</html>
