---
layout: page
title: "Contact"
permalink: /contact/
---

# Get in Touch

I'd love to hear from you! Whether you have a question, a collaboration idea, or just want to say hello, feel free to send me a message using the form below.

<form action="https://formspree.io/f/xyylbxyz" method="POST" style="max-width: 600px;">
  <div style="margin-bottom: 1rem;">
    <label for="name" style="display:block; font-weight: bold;">Your Name:</label>
    <input type="text" id="name" name="name" required style="width:100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;">
  </div>
  <div style="margin-bottom: 1rem;">
    <label for="email" style="display:block; font-weight: bold;">Your Email:</label>
    <input type="email" id="email" name="_replyto" required style="width:100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;">
  </div>
  <div style="margin-bottom: 1rem;">
    <label for="message" style="display:block; font-weight: bold;">Message:</label>
    <textarea id="message" name="message" rows="5" required style="width:100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 4px;"></textarea>
  </div>
  <!-- The next input is a honey-pot for spam bots, which normal users won't see -->
  <input type="text" name="_gotcha" style="display:none">
  <!-- Add a subject line to emails -->
  <input type="hidden" name="_subject" value="Portfolio Contact Form Submission">
  <button type="submit" class="btn btn--primary">Send Message</button>
</form>

<p>Or reach out via email at <a href="mailto:john.doe@example.com">john.doe@example.com</a>.</p>
