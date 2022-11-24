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
  email: tzavellal@cardiff.ac.uk
  # phone: 888 888 88 88
  address:
    street: Cardiff University Brain Research Imaging Centre, Maindy Road
    city: Cardiff
    region: Wales
    postcode: 'CF24 4HQ'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '51.49337601013873'
    longitude: '-3.184458724888451'
  # office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  appointment_url: 'calendly.com/tzavellaloukia'

design:
  columns: '2'
---
