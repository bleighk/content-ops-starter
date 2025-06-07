---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: AI that works as hard as you do
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      At Collider, we build cutting-edge AI solutions to transform your business
      — so you can scale smarter, not harder.
    actions:
      - label: Book Intro Call
        altText: ''
        url: 'https://calendly.com/bradknight/30min'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: Collider
      color: text-dark
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - type: GenericSection
    title:
      type: TitleBlock
      text: Less busywork; more business
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: ''
    text: >
      At Collider, we help small and medium-sized companies turn the promise of
      AI into real-world impact for businesses.


      Whether you’re drowning in manual tasks, missing sales opportunities, or
      simply not sure where to start—Collider brings clarity and execution.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: 'https://youtu.be/JbVG7gONuQI'
      autoplay: false
      loop: false
      muted: false
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-light
          borderStyle: none
          borderWidth: 0
          borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-12
          - pb-12
          - pr-12
  - title:
      text: Our services
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - title: Lead Generation
        tagline: Find your next customer - automatically
        subtitle: ''
        text: >
          We combine AI-powered web & social scraping with enrichment and smart
          outbound outreach. The result? Warm leads that land right in your
          inbox
        image:
          url: /images/vackground-com-agUC-v_D1iI-unsplash.jpg
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: AI Agent Development
        tagline: 'Your digital team, on autopilot'
        subtitle: '  '
        text: >
          We build custom AI agents that live inside your workflows. From
          answering queries to handling repetitive tasks, our agents are trained
          to *think and do*.
        image:
          url: /images/ashwin-vaswani-JqZ7q_S3xOE-unsplash.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
              padding:
                - pt-0
                - pb-0
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Workflow Automations
        tagline: Automate the boring. Focus on what matters.
        subtitle: ''
        text: >+
          We streamline your operations using tools like Zapier, Make, and
          N8N—covering everything from sales to customer support. Think fewer
          clicks, faster responses, and zero dropped balls.

        image:
          url: /images/ferdinand-stohr-NFs6dRTBgaM-unsplash.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - type: CarouselSection
    subtitle: Testimonials
    items:
      - type: FeaturedItem
        title: >-
          “Brad went above and beyond. I’ve never come across someone who not
          only delivers more than what’s asked, but also takes the initiative to
          do extra work just to make things easier and run smoother.”
        tagline: Testimonial 1
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: Testimonial 2
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-12
          - pb-12
          - pr-12
  - type: GenericSection
    title:
      type: TitleBlock
      text: Let's explore what's possible
      color: text-dark
    subtitle: ''
    text: >
      Not sure what AI can do for your business? We know where to start.

      On your free discovery call, we’ll explore your biggest bottlenecks—and
      show you how smart automation can unlock immediate results.
    actions:
      - type: Button
        label: Book Intro Call
        altText: Book Intro Call
        url: 'https://app.netlify.com/intro'
        icon: arrowRight
        iconPosition: right
        style: primary
      - type: Button
        label: Contact Us
        altText: ''
        url: 'https://form.typeform.com/to/pofZWmNp'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    colors: bg-light-fg-dark
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-12
          - pb-12
          - pr-12
seo:
  metaTitle: Collider | AI that works as hard as you
  metaDescription: Collider | AI that works as hard as you
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
