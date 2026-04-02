---
_schema: default
title: FixPro | Astro Template for CloudCannon
description: 'An Astro template built for CloudCannon with visual editing, flexible components, and an exceptional developer experience. Deploy your next project with speed and style.'
pageSections:
  - _component: page-sections/heroes/hero-center
    eyebrowIcon: {}
    eyebrowText:
    heading: Introducing<br /><span class="highlight-text">FixPro</span>
    headingSize: 4xl
    subtext: >-
      Upload your home inspection report for a fast and completely free repair
      quote. We will connect you to licensed pros to get the job done right,
      and on time!
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Get a Free Quote in ~5 Mins
        hideText: false
        link: 'https://app.cloudcannon.com/register#sites/connect/github/cloudcannon/fixpro-astro-template'
        iconName: arrow-up-right
        iconPosition: after
        variant: primary
        size: md
      - _component: building-blocks/core-elements/button
        text: View Licensed Contractor Quotes
        hideText: false
        link: 'https://github.com/CloudCannon/astro-component-starter'
        iconName: arrow-up-right
        iconPosition: after
        variant: tertiary
        size: md
    image:
      source: /src/assets/images/fixpro-dashboard-hero-img.png
      alt: Dashboard overview image rounded
      rounded: true
    icons:
      - name: globe-asia-australia
        color: '#f40f0f'
        background: true
        size: 4xl
      - name: rocket-launch
        color: '#000000'
        background: true
        size: 4xl
    backgroundDecoration: true
    sectionHeight: full
    maxContentWidth: lg
    colorScheme: inherit
    backgroundColor: highlight-grid
    contentBackground: true
    verticalOffset:
      size: nav-height
      direction: back
    rounded: false
    paddingVertical: md
  - _component: page-sections/features/logo-strip
    heading: >-
      We’ve solved repair quotes for the world’s most ambitious real estate
      teams.
    images:
      - source: /src/assets/images/apex.svg
        alt: Apex logo
      - source: /src/assets/images/aura.svg
        alt: Aura logo
      - source: /src/assets/images/business2.svg
        alt: Fake Business logo
      - source: /src/assets/images/businesss.svg
        alt: Vantage logo
      - source: /src/assets/images/dental.svg
        alt: Align logo
      - source: /src/assets/images/fake-uni.svg
        alt: Fake University logo
      - source: /src/assets/images/fintech.svg
        alt: Fintech logo
      - source: /src/assets/images/medical.svg
        alt: Omnia logo
    maxContentWidth: 2xl
    paddingVertical: 4xl
    colorScheme: light
    backgroundColor: surface-linear-gradient
    contentBackground: false
    verticalOffset:
      size: 2xl
      direction: front
    rounded: true
  - _component: page-sections/features/feature-grid
    id: services
    eyebrowIcon:
      _component: building-blocks/core-elements/icon
      name: light-bulb
      size: 3xl
      color: brand-gradient
      background: true
      iconOffset: true
      alignX: center
    eyebrowText:
    heading: 'FixPro protects what matters most: <br />your real estate deal'
    subtext: >-
      Everything you need to turn inspection reports into free quotes without
      the operational friction —&nbsp;or contacting any contractors.
    featureGrid:
      features:
        - _component: page-sections/features/feature-grid/feature-item
          link: ''
          image:
            source: /src/assets/images/card-1.svg
            alt: Dashboard accelerate
            rounded: false
          eyebrowIcon: {}
          eyebrowText:
          title: Quotes generated in 24 hours!
          description: >-
            We will have your free quote back to you in 24 hours or less. We're
            not saying we have broken the laws of physics, but our platform
            operates at speeds that stop any delays.
          columnSpan: 5
          rowSpan: 1
        - _component: page-sections/features/feature-grid/feature-item
          link: ''
          image:
            source: ''
            alt: ''
            rounded: false
          eyebrowIcon: {}
          eyebrowText: We've got this.
          title: Licensed contractor team on deck
          description: >-
            Shoddy repairs don't stand a chance against our licensed and insured
            contractors, who have been vetted for every skill and trade pattern,
            plus several we test to be thorough.
          columnSpan: 3
          rowSpan: 1
        - _component: page-sections/features/feature-grid/feature-item
          link: ''
          image:
            source: /src/assets/images/card-2.svg
            alt: Dashboard queries
            rounded: false
          eyebrowIcon: {}
          eyebrowText:
          title: Pay at escrow billing options
          description: >-
            Pay by credit card, check, or even out of escrow! Sometimes you just
            want to delay payment. Our billing team operates under the principle
            that flexibility isn't a bug — it's a feature here.
          columnSpan: 4
          rowSpan: 1
        - _component: page-sections/features/feature-grid/feature-item
          link: ''
          image:
            source: /src/assets/images/card-3.svg
            alt: Dashboard global
            rounded: false
          eyebrowIcon: {}
          eyebrowText:
          title: Automated repair cost shopping
          description: >-
            Our automated contractor pricing system sources your repair quotes
            before you even have to think about calling them. We've eliminated
            the 3am calling entirely.
          columnSpan: 3
          rowSpan: 1
        - _component: page-sections/features/feature-grid/feature-item
          link: ''
          image:
            source: /src/assets/images/card-4.svg
            alt: Dashboard uptime
            rounded: false
          eyebrowIcon: {}
          eyebrowText:
          title: Repair estimates bordering on perfect
          description: >-
            Our free quoting infrastructure responds with exact labor and material
            deals that require zero hassle to collect. Your repair quotes
            resolve before you finish asking.
          columnSpan: 7
          rowSpan: 1
      backgroundColor: highlight-radial-gradient
      gridBackgroundMaxWidth: none
      gridMaxWidth: 2xl
      rounded: false
      overhang: true
    maxContentWidth: 2xl
    paddingVertical: 4xl
    colorScheme: inherit
    backgroundColor: base
    contentBackground: false
    verticalOffset:
      size: none
      direction: front
    rounded: false
#  - _component: page-sections/info-blocks/tabbed-content
#    id: solutions
#    eyebrowIcon: {}
#    eyebrowText:
#    heading: Free repair quotes that sell themselves!
#    subtext: >-
#      We don't just provide free quotes — we provide accurate pricing that
#      understands your business. And your clients.
#    tabs:
#      - _component: building-blocks/wrappers/content-selector/content-selector-item
#        title: Buyer Agent
#        subtext: Representing buyers and negotiating repairs now
#        contentSections:
#          - _component: building-blocks/wrappers/split
#            label: ''
#            firstColumnContentSections:
#              - _component: building-blocks/core-elements/simple-text
#                text: >-
#                  We implemented our completely free quoting protocol and deployed
#                  dedicated local contractor teams with exact pricing models that
#                  won't slow a closing down.
#
#                  Buyers can see exactly what repairs should cost in real-time,
#                  and negotiations are completed at the speed of a single phone
#                  call — which, our research confirms, is how it should work.
#                alignX: start
#                size: md
#            secondColumnContentSections: []
#            distributionMode: three-quarters-quarter
#            fixedWidth:
#            minSplitWidth: 760
#            verticalAlignment: center
#            reverse: false
#            reverseOrderOnMobile: false
#            gap: lg
#          - _component: building-blocks/wrappers/split
#            label: ''
#            firstColumnContentSections:
#              - _component: building-blocks/core-elements/image
#                id: ''
#                source: /src/assets/images/medi-connect.png
#                alt: Person thinking
#                rounded: false
#                aspectRatio: none
#                positionVertical: center
#                positionHorizontal: center
#                priority: false
#            secondColumnContentSections:
#              - _component: building-blocks/core-elements/counter
#                number: 94
#                prefix:
#                suffix: '%'
#                alignX: start
#                size: xl
#              - _component: building-blocks/core-elements/text
#                text: '**Reduction in connection quality complaints**'
#                alignX: start
#              - _component: building-blocks/core-elements/counter
#                number: 340
#                prefix:
#                suffix: x
#                alignX: start
#                size: xl
#              - _component: building-blocks/core-elements/text
#                text: '**More numbers than other companies**'
#                alignX: start
#            distributionMode: three-quarters-quarter
#            fixedWidth:
#            minSplitWidth: 760
#            verticalAlignment: center
#            reverse: false
#            reverseOrderOnMobile: false
#            gap: lg
#      - _component: building-blocks/wrappers/content-selector/content-selector-item
#        title: Listing Agent
#        subtext: 'Listing real estate agent processing property sales for top clients '
#        contentSections:
#          - _component: building-blocks/wrappers/split
#            label: ''
#            firstColumnContentSections:
#              - _component: building-blocks/core-elements/simple-text
#                text: >-
#                  Sellers needed totally free repair quotes that matched buyer
#                  expectations and contractor quality that exceeded inspection
#                  paranoia. Their clients now experience rapid closing solutions
#                  while delays are neutralized before they realize they've stalled.
#                  Real estate quoting that is faster than calling and more
#                  reliable than gravity.
#                alignX: start
#                size: md
#            secondColumnContentSections: []
#            distributionMode: three-quarters-quarter
#            fixedWidth:
#            minSplitWidth: 760
#            verticalAlignment: center
#            reverse: false
#            reverseOrderOnMobile: false
#            gap: lg
#          - _component: building-blocks/wrappers/split
#            label: ''
#            firstColumnContentSections:
#              - _component: building-blocks/core-elements/image
#                id: ''
#                source: /src/assets/images/fin-trust.png
#                alt: Fintrust dashboard
#                rounded: false
#                aspectRatio: none
#                positionVertical: center
#                positionHorizontal: center
#                priority: false
#            secondColumnContentSections:
#              - _component: building-blocks/core-elements/counter
#                number: 2.3
#                prefix:
#                suffix: s
#                alignX: start
#                size: xl
#              - _component: building-blocks/core-elements/text
#                text: '**Average transaction completion time**'
#                alignX: start
#              - _component: building-blocks/core-elements/counter
#                number: 100
#                prefix:
#                suffix: '%'
#                alignX: start
#                size: xl
#              - _component: building-blocks/core-elements/text
#                text: '**Mitigation rate against 12,000+ daily attack attempts**'
#                alignX: start
#            distributionMode: three-quarters-quarter
#            fixedWidth:
#            minSplitWidth: 760
#            verticalAlignment: center
#            reverse: false
#            reverseOrderOnMobile: false
#            gap: lg
#    navigationPosition: top
#    maxContentWidth: 2xl
#    paddingVertical: 4xl
#    colorScheme: light
#    backgroundColor: highlight-grid
#    verticalOffset:
#      size: none
#      direction: ''
#    rounded: false
  - _component: page-sections/people/testimonial-section
    text: >-
      Closing delays used to be my biggest headache. Now, free repair quotes
      arrive within 24 hours.
    authorName: Sarah Jenkins
    authorDescription: Senior Realtor, Miller Home
    authorImage: /src/assets/images/testimonial.png
    maxContentWidth: xl
    paddingVertical: 2xl
    colorScheme: dark
    backgroundColor: highlight-radial-gradient
  - _component: page-sections/features/feature-grid
    eyebrowIcon:
      _component: building-blocks/core-elements/icon
      name: presentation-chart-line
      size: 3xl
      color: brand-gradient
      background: true
      iconOffset: true
      alignX: center
    eyebrowText:
    heading: Free quotes that scale with your volume
    subtext: >-
      Choose the quote style that matches your current home inspection needs,
      then execute when your inevitable closing makes it necessary. We'll be
      here, ready with contractors and affordable prices.
    featureGrid:
      features:
        - _component: page-sections/features/feature-grid/pricing-item
          title: Standard
          price:
            prefix: $
            amount: '0'
            suffix: /mo
          subtext: For homeowners who just need a free quote
          list:
            _component: building-blocks/core-elements/list
            items:
              - _component: building-blocks/core-elements/list/list-item
                text: Free quotes returned in 24 hrs
                iconName: check-circle
                iconColor: purple
              - _component: building-blocks/core-elements/list/list-item
                text: No hassle scheduling multiple quotes
                iconName: check-circle
                iconColor: purple
              - _component: building-blocks/core-elements/list/list-item
                text: "Access to our massive network of vetted\Llicensed and insured contractors"
                iconName: check-circle
                iconColor: purple
            direction: vertical
            alignX: start
            size: md
            listType: icon
          button:
            _component: building-blocks/core-elements/button
            text: Get started
            hideText: false
            link: https://cloudcannon.com/templates/jetstream/
            iconName: arrow-right
            iconPosition: after
            variant: secondary
            size: md
          columnSpan: 5
          rowSpan: 1
        - _component: page-sections/features/feature-grid/pricing-item
          title: Team
          price:
            prefix: ''
            amount: 'Custom'
            suffix: ''
          subtext: For organizations that refuse to accept the concept of downtime
          list:
            _component: building-blocks/core-elements/list
            items:
              - _component: building-blocks/core-elements/list/list-item
                text: Priority traffic routing
                iconName: check-circle
                iconColor: purple
              - _component: building-blocks/core-elements/list/list-item
                text: Dedicated customer success specialist
                iconName: check-circle
                iconColor: purple
              - _component: building-blocks/core-elements/list/list-item
                text: "Annual infrastructure health assessment conducted by our senior architects,\Lcomplete with a 40-page report bound in a collectible presentation folder"
                iconName: check-circle
                iconColor: purple
            direction: vertical
            alignX: start
            size: md
            listType: icon
          button:
            _component: building-blocks/core-elements/button
            text: Contact Us
            hideText: false
            link: https://cloudcannon.com/templates/jetstream/
            iconName: arrow-right
            iconPosition: after
            variant: secondary
            size: md
          columnSpan: 7
          rowSpan: 1
      backgroundColor:
      gridBackgroundMaxWidth: none
      gridMaxWidth: 2xl
      rounded: false
      overhang: false
    maxContentWidth: md
    paddingVertical: 4xl
    colorScheme: inherit
    backgroundColor: surface-linear-gradient
    contentBackground: false
    verticalOffset:
      size: 6xl
      direction: back
    rounded: false
  - _component: page-sections/ctas/cta-center
    eyebrowIcon: {}
    eyebrowText:
    heading: Ready for a free quote that defies conventional norms?
    subtext:
    buttonSections:
      - _component: building-blocks/core-elements/button
        text: Upload your free report
        hideText: false
        link: ''
        iconName: calendar
        iconPosition: before
        variant: primary
        size: md
    maxContentWidth: xl
    paddingVertical: 4xl
    colorScheme: dark
    backgroundColor: highlight-radial-gradient
    contentBackground: false
    rounded: true
---
