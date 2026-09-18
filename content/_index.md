---
title: ''
summary: ''
date: 2026-09-10
type: landing

sections:

  # ============================================================
  # HERO
  # ============================================================
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: lg
      avatar:
        size: large
        shape: circle


  # ============================================================
  # ABOUT
  # ============================================================
  - block: markdown
    id: overview
    content:
      title: About Me
      subtitle: ''
      text: |-
        I am a **Biomedical Engineer, Magna Cum Laude**, from **Universidad de los Andes**, where I am currently pursuing an **M.Sc. in Biomedical Engineering** with a focus on Biomedical Computer Vision under the supervision of [Prof. Pablo Arbeláez](https://scholar.google.com/citations?user=k0nZO90AAAAJ). My research interests lie at the intersection of **artificial intelligence and biomedical applications**, with particular interests in multimodal learning, computer vision, foundation models, representation learning, and spatial transcriptomics. My research experience includes work in medical image computing, histopathology, echocardiography, spatial gene-expression prediction, and multimodal biomedical data analysis. I have contributed to research accepted or published at **MICCAI 2026**, an **ICCV 2025 Workshop**, and **Osteoporosis International**, and I led the development of a foundation-model-based solution for the **EchoRisk-MICCAI Cardio-Oncology Challenge**. In parallel, I am completing a **Bachelor of Music in Piano Performance at Universidad Nacional de Colombia**, where I have developed a strong background as a classical pianist. This dual academic path has strengthened my analytical thinking, discipline, adaptability, and creativity, and has shaped the way I approach complex interdisciplinary problems.
    design:
      columns: '1'

  # ============================================================
  # RESEARCH INTERESTS
  # ============================================================
  - block: markdown
    id: research
    content:
      title: Research Interests
      subtitle: ''
      text: |-
        - **Biomedical Computer Vision**

          Learning representations from medical and histopathology images for clinically and biologically relevant prediction tasks.

        - **Multimodal Learning**

          Integrating imaging, molecular, and clinical information to model complementary signals across biomedical modalities.

        - **Foundation & Representation Models**

          Adapting pretrained models and structured representation spaces to data-efficient biomedical applications.

        - **Spatial Transcriptomics**

          Predicting and modeling spatial gene expression from tissue morphology while preserving biological and spatial structure.
    design:
      columns: '1'


  # ============================================================
  # SELECTED RESEARCH
  # ============================================================
  - block: collection
    id: publications
    content:
      title: Selected Research
      subtitle: Research at the intersection of biomedical artificial intelligence, medical imaging, and multimodal learning.
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: showcase
      columns: 1

  # ============================================================
  # RESEARCH EXPERIENCE
  # ============================================================
  - block: markdown
    id: experience
    content:
      title: Research Experience
      subtitle: ''
      text: |-
        ### Graduate Research Assistant
        **Biomedical Computer Vision Group (BCV), Universidad de los Andes**  
        *Aug. 2024 — Present*

        Research in biomedical artificial intelligence spanning **spatial transcriptomics, medical image computing, multimodal learning, foundation models, and representation learning**. My current work focuses on predicting spatial gene expression from histopathology and developing generalizable representations across heterogeneous spatial transcriptomics datasets.

        ### Junior Researcher
        **Minciencias — Orquídeas Program**  
        *Jul. 2026 — Present*

        Research on artificial intelligence for biomedical applications, contributing to the development and evaluation of computational methods for multimodal biomedical data.
    design:
      columns: '1'


  # ============================================================
  # TEACHING
  # ============================================================
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |-
        ### Graduate Teaching Assistant — Computer Vision I & II
        **Master's Program in Artificial Intelligence, Universidad de los Andes**  
        *Jan. 2026 — May 2026*

        Led laboratories, tutorials, and weekly mentoring sessions covering convolutional neural networks, Vision Transformers, object detection, segmentation, 3D reconstruction, video analysis, and generative models.
    design:
      columns: '1'


  # ============================================================
  # EDUCATION
  # ============================================================
  - block: markdown
    id: education
    content:
      title: Education
      subtitle: ''
      text: |-
        ### M.Sc. in Biomedical Engineering
        **Universidad de los Andes**  
        *2025 — Present*

        Current GPA: **4.91/5.00**  
        Research focus: Biomedical Computer Vision, Spatial Transcriptomics, Multimodal Learning, and Foundation Models.

        ### B.Sc. in Biomedical Engineering — Magna Cum Laude
        **Universidad de los Andes**  
        *2021 — 2025*

        GPA: **4.80/5.00**  
        Academic performance within the **top 1%** of the historical GPA distribution among Faculty of Engineering graduates over the previous five years.

        ### Bachelor of Music in Piano Performance
        **Universidad Nacional de Colombia**  
        *2021 — Present*

        GPA: **4.60/5.00**  
        Final-semester student in classical piano performance.
    design:
      columns: '1'


  # ============================================================
  # HONORS
  # ============================================================
  - block: markdown
    id: honors
    content:
      title: Honors & Awards
      subtitle: ''
      text: |-
        ### Magna Cum Laude — Biomedical Engineering
        **Universidad de los Andes**  
        *2025*

        ### Top 10 Academic Performance — Biomedical Engineering
        **Universidad de los Andes**  
        *Four consecutive semesters*

        ### Selected Representative — Undergraduate Thesis Abstract Series
        **Universidad Nacional de Colombia**  
        *2026*

        ### Winner — Contra Corriente University Festival
        **Universidad Nacional de Colombia**  
        *2023*

        ### Honorable Mention — IX Pianissimo Festival and Competition
        **Universidad Nacional de Colombia**  
        *2022*
    design:
      columns: '1'


  # ============================================================
  # PIANO
  # ============================================================
  - block: markdown
    id: piano
    content:
      title: Piano
      subtitle: ''
      text: |-
        Alongside my work in biomedical AI, I am completing a **Bachelor of Music in Piano Performance at Universidad Nacional de Colombia**, where I have developed a strong background as a classical pianist. My musical training has shaped the way I approach complex problems through discipline, analytical thinking, creativity, and attention to detail.

        ### Winner — Contra Corriente University Festival
        **Universidad Nacional de Colombia**  
        *2023*

        ### Honorable Mention — IX Pianissimo Festival and Competition
        **Universidad Nacional de Colombia**  
        *2022*
    design:
      columns: '1'


  # ============================================================
  # CONTACT
  # ============================================================
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        I am open to **research collaborations, academic exchanges, and future PhD or research opportunities** in biomedical artificial intelligence, computer vision, multimodal learning, foundation models, medical image computing, and spatial transcriptomics.

        **Email:** [h.ceballos@uniandes.edu.co](mailto:h.ceballos@uniandes.edu.co)

        **GitHub:** [HCeballosS](https://github.com/HCeballosS)
    design:
      columns: '1'



---
