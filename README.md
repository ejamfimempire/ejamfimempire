/* Reset and Base */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  line-height: 1.6;
  background-color: #f7f7f7;
  color: #333;
}

/* Containers */
.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  padding: 2rem 0;
}

/* Header */
header {
  background: #111;
  color: #fff;
  padding: 2rem 0;
  text-align: center;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 0.3rem;
}

header .subtitle {
  font-size: 1.1rem;
  color: #ccc;
}

nav {
  margin-top: 1.5rem;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 1rem;
  font-weight: 600;
  padding: 0.5rem 1rem;
  border-radius: 5px;
}

nav a:hover,
nav .active {
  background: #ff5722;
}

/* Hero Section */
.hero {
  background: linear-gradient(to right, #111, #444);
  color: white;
  text-align: center;
  padding: 4rem 0;
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

/* Section Styling */
.section {
  background-color: #fff;
  padding: 3rem 0;
}

.section.dark {
  background-color: #f1f1f1;
}

/* Card Grid */
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.card {
  background: #fff;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.08);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
}

/* Footer */
footer {
  background: #222;
  color: #ddd;
  text-align: center;
  padding: 1.5rem 0;
}
