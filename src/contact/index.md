---
title: "Contact"
layout: "base.njk"
---

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
  </p>
  <p>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
  </p>
  <p>
    <label for="message">Message:</label>
    <textarea id="message" name="message" required></textarea>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>