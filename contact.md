---
layout: default
title: Contact
---
<h1>Contact Us</h1>
<p>If you have questions about programs, volunteering, or donations, please reach out.</p>

<section aria-labelledby="contact-form">
  <h2 id="contact-form">Contact form</h2>
  <!-- Replace the action with your Formspree endpoint or server endpoint -->
  <form class="contact-form" method="POST" action="https://formspree.io/f/YOUR_FORM_ID">
    <label>
      Your name
      <input type="text" name="name" required />
    </label>
    <label>
      Email
      <input type="email" name="email" required />
    </label>
    <label>
      Subject
      <input type="text" name="subject" />
    </label>
    <label>
      Message
      <textarea name="message" rows="6" required></textarea>
    </label>
    <p><button class="btn" type="submit">Send message</button></p>
  </form>
</section>

<section aria-labelledby="other-contacts">
  <h2 id="other-contacts">Other ways to reach us</h2>
  <address>
    {{ site.title }} HQ<br />
    123 School Lane<br />
    City, State ZIP<br />
    Email: <a href="mailto:{{ site.email }}">{{ site.email }}</a><br />
    Phone: (555) 555-0123
  </address>
</section>
