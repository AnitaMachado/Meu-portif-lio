---
type: PageLayout
title: Certificados
sections:
  - type: QuoteSection
    quote: ''
    name: Este site esta em processo de construção (reestruturação)
    title: ''
    colors: colors-c
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-0
          - pb-10
          - pl-4
          - pr-4
        textAlign: center
  - type: HeroSection
    title: ''
    text: >+
      # Hey I’m a developer. I’ve been born and raised in the world, and that’s
      also where I’m based. I’m currently a free agent, ex-this, ex-that,
      ex-super big name. When I’m not coding, writing or creating, I eat
      cereals. I have a dog, check her out [@mygod](https://www.stackbit.com/).

    actions: []
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
    colors: colors-f
    backgroundSize: full
    elementId: ''
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    subtitle: 'You can find me here:'
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Twitter
            url: 'https://twitter.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: CodePen
            url: 'https://codepen.io/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/'
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: React
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
    colors: colors-f
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    subtitle: 'Contact:'
    text: |
      [thisismyemail.@myemail.me](mailto:thisismyemail.@myemail.me)
    colors: colors-f
    variant: variant-a
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * freelance @freelance.me

          **2018-2021**

          * fullstack at this startup

          **2015**

          * senior front-end at this place

          **2013**

          * intern developer at a big company

          **2011**

          * flipping burgers
        actions: []
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2015-2018**

          * ba computer sciense at a semi fancy school

          **2014**

          * react certificate somewhere

          **2011**

          * my highschool
        actions: []
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    title: "Let’s talk... \U0001F4AC"
    form:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          width: 1/2
          isRequired: true
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          width: 1/2
          isRequired: false
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updatesConsent
          label: Sign me up to recieve my words
          width: full
          isRequired: false
      submitLabel: "Submit \U0001F680"
      elementId: sign-up-form
      styles:
        self:
          textAlign: center
    colors: colors-f
    backgroundSize: full
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
metaTags: []
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
---
