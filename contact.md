---
title: Contact Us
permalink: "/contact/"
position: 5
layout: page
---

<!-- TODO: move this to a layout or include -->

<form name="services-inquiry" netlify-honeypot="trick" method="POST" netlify>
    <div class="form-group d-none">
        <label>Don't fill this out if you're human: <input name="trick"></label>
    </div>
    <div class="form-group">
        <label for="inquiry-name">Your Name</label>
        <input type="text" class="form-control" name="inquiry-name" id="inquiry-name" placeholder="First and last name">
    </div>
    <div class="form-group">
        <label for="inquiry-email">Email Address</label>
        <input type="email" class="form-control" name="inquiry-email" id="inquiry-email" placeholder="name@example.com">
    </div>
    <div class="form-group">
        <label for="inquiry-message">Your Inquiry</label>
        <textarea class="form-control" name="inquiry-message" id="inquiry-message" rows="4"></textarea>
    </div>
    

  <div data-netlify-recaptcha></div>


    
    <button type="submit" class="btn btn-primary">Submit</button>
</form>
