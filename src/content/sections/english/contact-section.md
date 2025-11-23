---
enable: true
title: "Ready to Transform Your Dental Practice with TikTok?"
description: "Let's create viral content that brings new patients to your door. Schedule your free TikTok strategy session today!"

map:
  enable: true
  position: "right"
  title: "Find Us in Atlanta"
  url: https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=Atlanta,%20Georgia+(SmileSats)&amp;t=&amp;z=12&amp;ie=UTF8&amp;iwloc=B&amp;output=embed

contactInformation:
  - title: "Atlanta Headquarters"
    icon: "/images/icons/svg/location-filled.svg"
    description: "Atlanta, GA, USA"
    button:
      enable: true
      label: "Get Direction"
      url: "https://maps.google.com/maps?q=Atlanta,Georgia"
      target: "_blank"

  - title: "Email Address"
    icon: "/images/icons/svg/message-filled.svg"
    description: |
      fun@smilesats.com
      support@smilesats.com
    button:
      enable: true
      label: "Send Message"
      url: "mailto:fun@smilesats.com"

  - title: "Phone Number"
    icon: "/images/icons/svg/phone-filled.svg"
    description: |
      +1 404 889 5545
    button:
      enable: true
      label: "Call Us"
      url: "tel:+14048895545"

form:
  emailSubject: "New SmileSats Inquiry - TikTok Dental Marketing"
  submitButton:
    enable: true
    label: "GET MY FREE STRATEGY SESSION"
    hoverEffect: "creative-fill"
    variant: "fill"

  note: |
    Your dental practice information is confidential. We'll contact you within 24 hours to discuss your TikTok marketing strategy. <br /> Read our [Privacy Policy](/privacy-policy/).
  
  inputs:
    - label: ""
      placeholder: "Practice Name *"
      name: "Practice Name"
      required: true
      halfWidth: true
      defaultValue: ""

    - label: ""
      placeholder: "Your Name *"
      name: "Full Name"
      required: true
      halfWidth: true
      defaultValue: ""

    - label: ""
      placeholder: "Email Address *"
      name: "Email Address"
      required: true
      type: "email"
      halfWidth: true
      defaultValue: ""

    - label: ""
      placeholder: "Phone Number *"
      name: "Phone Number"
      required: true
      type: "tel"
      halfWidth: true
      defaultValue: ""

    - label: ""
      placeholder: "Current Monthly Marketing Budget"
      name: "Marketing Budget"
      required: false
      halfWidth: true
      dropdown:
        type: "select"
        items:
          - label: "Less than $1,000"
            value: "Less than $1,000"
            selected: false
          - label: "$1,000 - $3,000"
            value: "$1,000 - $3,000"
            selected: false
          - label: "$3,000 - $5,000"
            value: "$3,000 - $5,000"
            selected: false
          - label: "$5,000+"
            value: "$5,000+"
            selected: false

    - label: ""
      placeholder: "Service Interest *"
      name: "Service Interest"
      required: true
      halfWidth: true
      dropdown:
        type: "search"
        search:
          placeholder: "Select service interest"
        items:
          - label: "Starter Plan - TikTok Launch"
            value: "Starter Plan"
            selected: false
          - label: "Glo-Up Plan - TikTok Growth"
            value: "Glo-Up Plan"
            selected: false
          - label: "Elite Plan - Complete Ecosystem"
            value: "Elite Plan"
            selected: false
          - label: "Custom Enterprise Solution"
            value: "Enterprise Solution"
            selected: false
          - label: "Just Exploring Options"
            value: "Exploring Options"
            selected: false

    - label: ""
      tag: "textarea"
      defaultValue: ""
      rows: "4"
      placeholder: "Tell us about your practice and TikTok goals... *"
      name: "Practice Details"
      required: true
      halfWidth: false

    - label: "Google Search"
      name: "Referral Source"
      required: true
      groupLabel: "How did you hear about us?"
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""

    - label: "TikTok"
      name: "Referral Source"
      required: true
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""

    - label: "Referral"
      name: "Referral Source"
      required: true
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""

    - label: "Social Media"
      name: "Referral Source"
      required: true
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""

    - label: "Other"
      name: "Referral Source"
      required: true
      group: "source"
      type: "radio"
      halfWidth: true
      defaultValue: ""

    - label: "I want to receive TikTok marketing tips and practice growth strategies"
      id: "newsletter-optin"
      name: "Newsletter Opt-in"
      value: "Subscribed"
      checked: true
      required: false
      type: "checkbox"
      halfWidth: false
      defaultValue: ""

    - label: "I agree to the terms and conditions and [privacy policy](/privacy-policy/)"
      id: "privacy-policy"
      name: "Agreed Privacy"
      value: "Agreed"
      checked: false
      required: true
      type: "checkbox"
      halfWidth: false
      defaultValue: ""

    - note: success
      parentClass: "hidden text-sm message success"
      content: "Thank you! We've received your inquiry and will contact you within 24 hours to schedule your free TikTok strategy session."

    - note: deprecated
      parentClass: "hidden text-sm message error"
      content: "Something went wrong! Please email us directly at [fun@smilesats.com](mailto:fun@smilesats.com)"
---
