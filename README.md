# Madhvesh-Thakur 
index.html <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
   Madhvesh Thakur | Graphic Designer
  <link rel="stylesheet" href="style.css">
  <section id="hero">
    Madhvesh Thakur 
    Graphic Designer & YouTube Content Creator
  </section>

  <section id="about">
    <h2>About Me</h2>
    <> I am a passionate graphic designer focused on creating clean,
creative and effective designs for social media and digital platforms.</>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <p>My design work will appear here.</p>
  </section>

  <section id="youtube">
    <h2>YouTube</h2>
    <>Visit my YouTube channel. https://youtube.com/@designerstudio888?si=8cutT2HU2ThTGeQc  </>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <>Email : designerstudio888@gmail.com | Instagram : itz_thakur_0251 | YouTube : designerstudio888.</>
  </section>

</body>
</html>

style.css : * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #0b0f19;
  color: #e5e7eb;
  line-height: 1.6;
}

/* Common */
section {
  padding: 90px 20px;
  text-align: center;
}

h1, h2 {
  color: #ffffff;
  margin-bottom: 20px;
}

p {
  max-width: 800px;
  margin: auto;
  color: #cbd5e1;
}

/* HERO */
.hero {
  background: linear-gradient(135deg, #020617, #020617);
}

.hero h1 {
  font-size: 52px;
  letter-spacing: 1px;
}

.hero p {
  font-size: 18px;
  margin-top: 10px;
}

/* BUTTON */
.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 14px 36px;
  background: #38bdf8;
  color: #020617;
  text-decoration: none;
  border-radius: 40px;
  font-weight: bold;
  transition: 0.3s ease;
}

.btn:hover {
  background: #0ea5e9;
}

/* ABOUT / YOUTUBE / CONTACT */
.about,
.youtube,
.contact {
  background-color: #020617;
}

/* PORTFOLIO */
.portfolio {
  background-color: #020617;
}

.portfolio .grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
  margin-top: 50px;
}

.card {
  background: #0f172a;
  padding: 80px 0;
  border-radius: 16px;
  font-weight: bold;
  transition: 0.3s ease;
}

.card:hover {
  transform: translateY(-8px);
  background: #020617;
}

/* FOOTER FEEL */
.contact p {
  margin-top: 10px;
}
