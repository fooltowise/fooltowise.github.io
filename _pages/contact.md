---
title: "Contact"
permalink: "/contact.html"
layout: post
noavatar: "true"
---

<div class="mt-4"></div>
<form action="https://formspree.io/{{site.email}}" method="POST">    
<p >You want to tell me something? Well, thanks a lot!</p>
<p> You can send me an email by writing to <b>fromfooltowise[at]gmail.com</b>.</p>
<p class="mb-4">You can also fill the form below:</p>

<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>