---
layout: page
title: Contact
permalink: /contact/
---

<section class="contact">
  <h2>Contact Me</h2>
  <p>If you would like to reach out to me for collaboration, job opportunities, or just to chat about tech, feel free to contact me!</p>
  <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
    <label for="name">Your Name:</label>
    <input type="text" id="name" name="name" required><br>

    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email" required><br>

    <label for="message">Your Message:</label><br>
    <textarea id="message" name="message" rows="4" cols="50" required></textarea><br>

    <input type="submit" value="Send">
  </form>
</section>

<style>
.contact {
  max-width: 600px;
  margin: auto;
  padding: 2rem;
  background: #f3f4f6;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
.contact h2 {
  color: #4ade80;
  text-align: center;
}
.contact form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.contact label {
  font-weight: bold;
}
.contact input,
.contact textarea {
  padding: 0.75rem;
  font-size: 1rem;
  border-radius: 8px;
  border: 1px solid #ccc;
}
.contact input[type="submit"] {
  background-color: #4ade80;
  color: white;
  border: none;
  cursor: pointer;
}
</style>
