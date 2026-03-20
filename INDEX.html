<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Advanced Navigation Menu</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial;
}

/* Navbar */
nav {
  position: fixed;
  width: 100%;
  top: 0;
  background: transparent;
  padding: 15px 20px;
  transition: 0.3s;
  z-index: 1000;
}

nav.scrolled {
  background: #222;
}

/* Menu */
.nav-links {
  display: flex;
  justify-content: center;
  list-style: none;
}

.nav-links li {
  margin: 0 15px;
}

.nav-links a {
  text-decoration: none;
  color: white;
  font-size: 18px;
  padding: 8px 12px;
  transition: 0.3s;
}

/* Hover */
.nav-links a:hover {
  background: #ff9800;
  color: black;
  border-radius: 5px;
}

/* Active link */
.nav-links a.active {
  border-bottom: 3px solid #ff9800;
}

/* Hamburger */
.menu-toggle {
  display: none;
  font-size: 25px;
  color: white;
  cursor: pointer;
}

/* Sections */
section {
  height: 100vh;
  padding-top: 80px;
  text-align: center;
  font-size: 30px;
}

#home { background: #2196f3; }
#about { background: #4caf50; }
#services { background: #9c27b0; }
#contact { background: #f44336; }

/* Mobile */
@media (max-width: 768px) {
  .nav-links {
    position: absolute;
    top: 60px;
    left: 0;
    width: 100%;
    background: #222;
    flex-direction: column;
    display: none;
  }

  .nav-links.show {
    display: flex;
  }

  .nav-links li {
    margin: 15px 0;
    text-align: center;
  }

  .menu-toggle {
    display: block;
  }
}
</style>
</head>

<body>

<nav id="navbar">
  <span class="menu-toggle" id="menu-toggle">☰</span>
  <ul class="nav-links" id="nav-links">
    <li><a href="#home" class="active">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section id="home">Home Section</section>
<section id="about">About Section</section>
<section id="services">Services Section</section>
<section id="contact">Contact Section</section>

<script>
// Scroll navbar style
window.addEventListener("scroll", () => {
  const navbar = document.getElementById("navbar");
  navbar.classList.toggle("scrolled", window.scrollY > 50);
});

// Smooth scrolling
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener("click", function(e) {
    e.preventDefault();
    document.querySelector(this.getAttribute("href"))
      .scrollIntoView({ behavior: "smooth" });
  });
});

// Active link highlight
const sections = document.querySelectorAll("section");
const navLinks = document.querySelectorAll(".nav-links a");

window.addEventListener("scroll", () => {
  let current = "";

  sections.forEach(section => {
    const sectionTop = section.offsetTop - 100;
    if (scrollY >= sectionTop) {
      current = section.getAttribute("id");
    }
  });

  navLinks.forEach(link => {
    link.classList.remove("active");
    if (link.getAttribute("href") === "#" + current) {
      link.classList.add("active");
    }
  });
});

// Mobile toggle
const toggle = document.getElementById("menu-toggle");
const nav = document.getElementById("nav-links");

toggle.addEventListener("click", () => {
  nav.classList.toggle("show");
});
</script>

</body>
</html>
