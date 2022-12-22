---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: sendgrid    #netlify
    formspree: 
      id: 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
    netlify: 
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true   ### i enabled the captcha, if it is not working, i wil set as false

design:
  columns: '1'
---
