---
layout: page
title: Contact Me
permalink: /contact/
description: How you can say hi.
---

<style>
.content header {
    background-image: url({{ site.baseurl }}/assets/img/drone-by-clem-onojeghuo.jpg);
    background-size: cover;
    background-position: center;
    background-repeat:no-repeat;
}
</style>

Say hello on [Twitter](https://twitter.com/davisonio) or [Snapchat](https://www.snapchat.com/add/davisonio).

My email is [craig@davison.io](mailto:craig@davison.io), feel free to use the form below and I'll reply ASAP.

<form id='contact-form' action="https://formspree.io/craig@davison.io" method="POST">
    <input type="text" name="name" placeholder="Name" required>
    <input type="email" name="email" placeholder="Email" required>
    <input type="text" name="phone" placeholder="Phone (optional)">
    <textarea name="message" placeholder="Message" required></textarea>
    <input type="text" name="_gotcha" style="display:none">
    <input type="hidden" name="_next" value="{{ site.baseurl }}/contact/sent/">
    <input type="hidden" name="_subject" value="New Message">
    <input type="hidden" name="_format" value="plain">
    <input type="submit" value="Send">
</form>
