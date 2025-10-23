---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /Batu_Ozturkler_CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 Research Interests'
      subtitle: ''
      text: |-
        My broad research interests are improving efficiency and robustness of deep learning algorithms in medical/computational imaging, computer vision, and natural language processing. Recently, I have been working on generative models such as diffusion models, in-context learning with large language models, robustness under distribution shifts, memory-efficient learning, self-supervised learning, inverse problems, compressive sensing, and accelerated MRI reconstruction.
    design:
      columns: '1'

---
