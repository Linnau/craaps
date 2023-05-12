<!-- +++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1100
background = "light"
form_name = "defaultContact"

title = "Contact"
subtitle  = "Send a question"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/f/mwkyrdlb" #formspree account
email = "no_reply" #needed to set has.formspree variable.
button = "Send Button" # defaults to theme default
netlify = false
recapthca = true

# Optional (invisible) google captcha
[recaptcha]
  sitekey = "6LdCLosfAAAAAPMv8vSGIi-NfSvdO2GJbtLIc0e2"

[message]
  success = "Thank you, we will get in touch." # defaults to theme default
  error = "Message could not be sent" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  error = "Please enter your name" # defaults to theme default

[fields.email]
  text = "Your Email *"
  error = "Please enter your email address " # defaults to theme default

[fields.phone]
  text = "Your Phone *"
  error = "Please enter your phone number" # defaults to theme default

[fields.message]
  text = "Your Message *"
  error = "Please enter a message" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++ -->
