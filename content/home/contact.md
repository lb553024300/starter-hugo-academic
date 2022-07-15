---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

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
  email: lb553024300@126.com
  phone: 
  address:
    street: 11 KeXiang Road, HuangPu District
    city: Guangzhou
    region: GuangDong
    postcode: '510000'
    country: China
    country_code: CHN
  coordinates:
    latitude: '23.173206832441565'
    longitude: '113.44027564767211'
  directions: The Building 3 and on Floor 3
  office_hours:
    - 'Monday to Friday 09:00 to 17:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: weibo
      icon_pack: fab
      name: follow Me
      link: 'https://m.weibo.cn/profile/1313971921'


design:
  columns: '2'
---
