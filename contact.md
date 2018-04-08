---
title: Contact Us
permalink: "/contact/"
position: 5
layout: page
---

<!-- TODO: move this to a layout or include -->

<form name="services-inquiry" netlify>
    <div class="form-group">
        <label for="inquiry-name">Your Name</label>
        <input type="text" class="form-control" id="inquiry-name" placeholder="First and last name">
    </div>
    <div class="form-group">
        <label for="inquiry-email">Email address</label>
        <input type="email" class="form-control" id="inquiry-email" placeholder="name@example.com">
    </div>
    <div class="form-group">
        <label for="inquiry-message">Your Inquiry</label>
        <textarea class="form-control" id="inquiry-message" rows="4"></textarea>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>
