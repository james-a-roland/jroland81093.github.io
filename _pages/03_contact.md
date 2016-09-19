---
layout: page
title: Contact
permalink: /contact/
---

<form action="https://formspree.io/james.a.roland@gmail.com"
method="POST">
<input type="hidden" name="_next" value="{{ site.url }}/thanks" />
<div class="form-group">
	<label for="exampleInputEmail1">Email address</label>
	<input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="hello@example.com" name="_replyTo" required>
	<small id="emailHelp" class="form-text text-muted">I'll get back to you within 48 hours.</small>
</div>
<div class="form-group">
	<label for="exampleTextarea">Your Message</label>
	<textarea class="form-control" id="exampleTextarea" rows="5" name="_message" required></textarea>
</div>
<button type="submit" class="btn btn-primary">Send</button>
</form>

