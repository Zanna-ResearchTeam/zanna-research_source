---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: laure.zanna@nyu.edu
  phone: +1 (212) 998 3180
  address:
    street: 251 Mercer St
    city: New York City
    region: NY
    postcode: '10012'
    country: United States
    country_code: US
  coordinates:
    latitude: '40.7287'
    longitude: '-73.9957'
  directions: Enter Warren Weaver Hall and take the elevators/stairs to Office 1116 on Floor 11
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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
  columns: '1'
---

Contact us
