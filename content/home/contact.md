---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

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
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697''

design:
  columns: '2'
---
