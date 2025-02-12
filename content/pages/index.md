---
type: PageLayout
title: Home
colors: colors-b
backgroundImage:
  type: BackgroundImage
  url: /images/661f89a1ddd730e71bd0aa0d_shutterstock_357107174.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 59
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: Sanaa MADAD
    subtitle: "My porfolio is about: Mathematics, Data Science, and Machine Learning\U0001F393                                                                       "
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
    actions:
      - type: Button
        label: 'Contact me '
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    text: "With a strong foundation in mathematics and a master’s degree in Data Science and Big Data, I am passionate about research and innovation at the intersection of data science and artificial intelligence.\U0001F30D My international experience has shaped me, fostering open-mindedness, adaptability, and a creative approach to solving complex problems.\U0001F469‍\U0001F3EB As a teacher at heart and a researcher in spirit, I view teaching as a noble calling and data science as a tool to transform ideas into impactful solutions.\U0001F4C8 Goal: contribute to ambitious research and development projects in data science and machine learning while leveraging my dual academic expertise and passion for knowledge sharing.\U0001F4E9 Ready to innovate together? Let’s connect!\n"
    media:
      type: ImageBlock
      url: /images/WhatsApp Image 2025-01-22 at 11.35.25_394dd23a.jpg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
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
      - content/pages/projects/about-me-"cv".md
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
    subtitle: Machine learning projects
    title: 'AI Learning '
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: ''
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    title: Maths
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project or opportunity? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
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
        borderColor: border-primary
      title:
        textAlign: left
      text:
        textAlign: left
metaTitle: Sanaa Madad Portfolio
metaDescription: Let's connect
addTitleSuffix: true
socialImage: /images/Connecting-Math-and-Machine-Learning.jpg
---
