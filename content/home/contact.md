---
# Contact widget.
widget : "contact"  # See https://sourcethemes.com/academic/docs/page-builder/
headless : true  # This file represents a page section.
active : true# Activate this widget? true/false
weight : 130  # Order that this section will appear.

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io
email_form : 0

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
