---
type: PageLayout
title: BRICS PAY - Decentralised multi-currency digital international payments system
colors: colors-a
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: UNIFIED MONETARY SETTLEMENT ECOSYSTEM - BRICS PAY
    subtitle: "Decentralised multi-currency digital international payments system\_between the BRICS countries for any user of all types of payments from individuals to corporations."
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: |+
      **Open to innovations**

      *   for all countries

      *   for all forms of money

      *   for all of humanity

  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: TextSection
    colors: colors-d
    variant: variant-b
    title: Official documents
    text: ''
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: HeroSection
    title: 5th BRICS Business CouncilAnnual Report 2018
    subtitle: ''
    actions:
      - type: Link
        label: OPEN TO READ
        altText: ''
        url: 'https://drive.google.com/file/d/1L5m5uw2_pab20DkrG9xYsKVa-00ASUxh/view'
        showIcon: true
        icon: arrowUpRight
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/1.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: ''
  - type: HeroSection
    title: 7th BRICS Business CouncilAnnual Report 2020
    subtitle: ''
    actions:
      - type: Link
        label: OPEN TO READ
        altText: ''
        url: 'https://eng.brics-russia2020.ru/images/114/83/1148368.pdf'
        showIcon: true
        icon: arrowUpRight
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/2.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: HeroSection
    title: 8th BRICS Business CouncilAnnual Report 2021
    subtitle: ''
    actions:
      - type: Link
        label: OPEN TO READ
        altText: ''
        url: 'https://brics2021.gov.in/brics/public/uploads/docpdf/getdocu-57.pdf'
        showIcon: true
        icon: arrowUpRight
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/3.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Send a request to connect... \U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: 'Full Name, position'
          label: Full Name
          hideLabel: true
          placeholder: Full Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: Company / Organization
          label: Company
          hideLabel: true
          placeholder: Company / Organization
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - type: TextFormControl
          name: 'Phone number '
          label: 'Phone number '
          hideLabel: true
          placeholder: Phone number (whatsapp / telegram)
          width: 1/2
          isRequired: true
        - type: SelectFormControl
          name: Product or topic
          label: 'Product or topic:'
          hideLabel: false
          defaultValue: Press to select...
          options:
            - BRICS PAY QR
            - BRICS Loyalty
            - BRICS PAY B2B
            - BRICS CBDC
            - BRICS ID
            - Consultation
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: false
          placeholder: Type your message or question here
          width: full
          isRequired: false
        - name: updates Consent
          label: I agree to the processing of my personal data.
          isRequired: true
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
backgroundImage:
  type: BackgroundImage
  url: /images/Covers.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 30
---
