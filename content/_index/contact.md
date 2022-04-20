+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Contact"
subtitle  = "Send a question"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/f/mwkyrdlb" #formspree account
email = "allan.linnau+formspree@gmail.com"
button = "Send Button" # defaults to theme default
#netlify = false

# Optional (invisible) google captcha
[recaptcha]
  sitekey = "6LdCLosfAAAAAPMv8vSGIi-NfSvdO2GJbtLIc0e2"

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Your Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Your Phone *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Your Message *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
