---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Contact
subtitle:

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

  # Contact details (edit or remove options as required)
  email: a.nguyen@ascorel.com
  telephone: (+33)7 69 35 72 98
  address:
    street: 357 Rue du Champ de Course
    city: Pont-Évêque
    postcode: '38780'
    country: France
    country_code: FR
  directions: Enter ASCOREL Building
  coordinates:
    latitude: '45.5259'
    longitude: '4.9243'

design:
  columns: '2'
---
