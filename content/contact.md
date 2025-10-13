---
title: "Contact"
type: "page"
---

<form name="contact" method="POST" data-netlify="true" netlify>
  <input type="hidden" name="form-name" value="contact" />
  
  <p>
    <label>Your Name:<br>
      <input type="text" name="name" required>
    </label>
  </p>
  <p>
    <label>Your Email:<br>
      <input type="email" name="email" required>
    </label>
  </p>
  <p>
    <label>Your Message:<br>
      <textarea name="message" rows="5" required></textarea>
    </label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
