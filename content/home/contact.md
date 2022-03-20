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
  email: liujian@cnu.edu.cn
  phone: +86 15801151683
  address:
    street: No.105 West 3rd Ring Road North 
    city: Stanford
    region: Beijing, China
    postcode: '100048'
    country: China
    country_code: CA
  coordinates:
    latitude: '39.936212'
    longitude: '116.312068'
  directions: Enter Building 1 and take the stairs to Office 816 on Floor 8

design:
  columns: '2'
---
