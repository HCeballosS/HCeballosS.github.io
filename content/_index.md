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
        url: uploads/resume.pdf?v=20260923
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

          Learning representations from medical and histopathology images.

        - **Multimodal Learning**

          Integrating imaging, molecular, spatial, and clinical data.

        - **Foundation & Representation Models**

          Adapting pretrained models for data-efficient biomedical applications.

        - **Spatial Transcriptomics**

          Predicting spatial gene expression from tissue morphology.
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
      # The local card partial is styled as the horizontal research showcase.
      view: card
      columns: 1

  # ============================================================
  # EXPERIENCE
  # ============================================================
  - block: markdown
    id: experience
    content:
      title: Experience
      subtitle: ''
      text: |-
        ### Graduate Research Assistant
        **Biomedical Computer Vision Group (BCV), Universidad de los Andes**  
        *Aug. 2024 — Present*

        Research in biomedical artificial intelligence spanning **spatial transcriptomics, medical image computing, multimodal learning, foundation models, and representation learning**. My M.Sc. research focuses on developing multimodal and representation-learning methods for **spatial gene-expression prediction from histopathology**, integrating histological, gene-expression, and spatial representations across heterogeneous datasets.

        ### Junior Researcher
        **Minciencias — Orquídeas Program**  
        *Jul. 2026 — Present*

        Retrain **Microsoft-developed species-classification models** in **Sparrow Studio/SPARROW** to incorporate jaguar as a target class, curate camera-trap imagery, and support the integration of the updated models into **SPARROW devices deployed in the Magdalena Medio region**.

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
        #### Academic Distinctions

        ### Selected Representative — Undergraduate Thesis Abstract Series
        **Universidad Nacional de Colombia**  
        *2026*

        ### Magna Cum Laude — Biomedical Engineering
        **Universidad de los Andes**  
        *2025*

        ### Top 10 Academic Performance — Biomedical Engineering
        **Universidad de los Andes**  
        *Four consecutive semesters*

        ### Top 15 Academic Performance — Instrumental Music
        **Universidad Nacional de Colombia**\
        *Four semesters*

        #### Music Awards

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
        Alongside my work in biomedical AI, I am completing a **Bachelor of Music in Piano Performance at Universidad Nacional de Colombia** under the guidance of **Professor Miyer Garvin**. I am currently preparing my graduation recital, featuring works by **Bach, Beethoven, Schubert, and Ravel**. Beyond solo performance, I have worked primarily as a collaborative pianist with singers and have participated in ensemble projects. My musical training has shaped the way I approach complex problems through discipline, analytical thinking, creativity, and attention to detail.
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
        [h.ceballos@uniandes.edu.co](mailto:h.ceballos@uniandes.edu.co)
    design:
      columns: '1'



---
