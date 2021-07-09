---
title: Contactame
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¡Wow!  Veo que te caíste en la pagina de contacto


      ¿Quieres hablar conmigo sobre código para tu web? contáctame en
      maugfalcon1@gmail.com


      Si quieres charlar acerca de algo aquí también puedes hacerlo. No
      recibirás el contenido exclusivo ni emails.


      ***
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre y apellido
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: 'Tu correo electrónico '
        is_required: true
      - input_type: select
        name: subject
        label: Motivo
        options:
          - Charlar
          - Requiero Servicios
          - Other
        default_value: Tu razón
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
