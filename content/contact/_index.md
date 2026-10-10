---
isPage: true
draft: false
title: Contact
blocks:
  - type: title
    heading:
      title: Information
      text: '**_« En soumettant ce formulaire, vous acceptez que les informations saisies soient traitées par le biais du service Netlify Forms afin de répondre à votre demande. Pour en savoir plus sur la gestion de vos données et exercer vos droits, consultez notre Politique de Confidentialité. »_**'
    ui:
      theme: accent
      grid: medium
      offset: center
      align: center
  - type: form
    ui:
      theme: dark
      grid: medium
      offset: center
      align: center
    items:
      - name: nom
        label: Nom
        type: text
        required: true
        full: false
        placeholder: John Doe
        autocomplete: name
      - name: email
        label: Email
        type: email
        required: true
        full: false
        placeholder: john.doe@domain.com
        autocomplete: email
      - name: message
        label: Message
        type: textarea
        required: true
        full: true
        placeholder: Votre message…
    name: contact
    submit: Envoyer le message
---
