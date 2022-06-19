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
  email: admin@AllianceSCC.com
  phone: +1 810 266 0591
  address:
    street: 215 South Main St. #755
    city: Linden
    region: MI
    postcode: '48451'
    country: United States
    country_code: US
  coordinates:
    latitude: ''
    longitude: ''
  directions: 
  office_hours:
    - 'By appointment only'
  appointment_url: 'https://calendly.com/alliance_scc/free-consult'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Us
      link: 'https://twitter.com/Alliance_SCC'
    - icon: facebook
      icon_pack: fab
      name: Message Us
      link: 'https://facebook.com/AllianceSCC'
    - icon: linkedin
      icon_pack: fab
      name: Follow Us
      link: 'https://linkedin.com/company/alliancescc'

design:
  columns: '2'
---
