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
  email: dangvietanh.nguyen@femto-st.fr
  address:
    street: 26 rue de l'Epitaphe
    city: Besançon
    postcode: '25000'
    country: France
    country_code: FR
  directions: Enter ENSMM Building
  coordinates:
    latitude: '47.2513'
    longitude: '5.9936'

design:
  columns: '2'
---
