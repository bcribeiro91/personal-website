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
  email: coutoribeiro@campus.tu-berlin.de
  phone: +49 176 6699 0470
  address:
    street: Straße des 17. Juni 135
    city: Berlin
    region: Germany
    postcode: '10623'
    country: Germany
    country_code: DE
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 10:00 to 13:00'
#  appointment_url: 'https://calendly.com'

design:
  columns: '2'
---
