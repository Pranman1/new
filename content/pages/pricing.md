---
title: About
slug: pricing
sections:
  - title:
      text: About Us
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Learn more about who we are and what we do
    plans: []
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
  - type: GenericSection
    title:
      type: TitleBlock
      text: Our mission
      color: text-dark
    subtitle: What Q-Bit's all about
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/abstract-feature2.svg
      altText: Dope design preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
      - content/data/yes.json
    actions: []
    variant: mixed-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
