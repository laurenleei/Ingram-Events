# Ingram-Events
/* styles.css */

body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
  background-color: #f9f9f9;
}

header {
  background-color: #2b2e4a;
  color: white;
  padding: 2rem;
  text-align: center;
}

.hero {
  background-color: #e84545;
  color: white;
  padding: 2rem;
  text-align: center;
}

.about, .packages, .portfolio, .testimonials, .contact {
  padding: 2rem;
  max-width: 900px;
  margin: auto;
}

.package-card {
  background-color: #fff;
  border: 1px solid #ccc;
  margin-bottom: 2rem;
  padding: 1.5rem;
  border-radius: 8px;
}

.package-card.premium {
  border: 2px solid #e84545;
  background-color: #fef2f2;
}

h1, h2, h3, h4 {
  margin: 0 0 1rem;
}

ul {
  padding-left: 1.5rem;
}

.contact form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 1rem;
}

.contact input, .contact textarea {
  padding: 0.75rem;
  border: 1px solid #ccc;
  border-radius: 5px;
  width: 100%;
}

.contact button {
  background-color: #2b2e4a;
  color: white;
  padding: 0.75rem;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.contact button:hover {
  background-color: #1d1f36;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #2b2e4a;
  color: white;
  margin-top: 2rem;
}
