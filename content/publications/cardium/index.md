---
title: "CARDIUM: Congenital Anomaly Recognition with Diagnostic Images and Unified Medical Records"

authors:
  - Daniela Vega
  - me
  - Javier S. Vera
  - Santiago Rodriguez
  - Alejandra Perez
  - Angela Castillo
  - Maria Escobar
  - Dario Londoño
  - Luis A. Sarmiento
  - Camila I. Castro
  - Nadiezhda Rodriguez
  - Juan C. Briceño
  - Pablo Arbeláez

date: '2025-10-01T00:00:00Z'

publication_types:
  - paper-conference

publication:
  name: "Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops"
  short_name: "Poster · CVAMD Workshop at ICCV 2025"

peer_reviewed: true
open_access: true

abstract: |
  CARDIUM introduces the first publicly available multimodal dataset for prenatal
  congenital heart disease detection combining fetal ultrasound and echocardiographic
  images with maternal clinical records. The proposed multimodal transformer uses
  cross-attention to fuse visual and tabular representations for CHD classification.

summary: |
  Multimodal prenatal diagnosis integrating fetal imaging and maternal clinical
  records through cross-attention-based fusion.

tags:
  - Echocardiography
  - Multimodal Learning
  - Medical Imaging
  - Clinical Data
  - Prenatal Diagnosis
  - Computer Vision

featured: true

content_meta:
  collaboration: "In collaboration with Fundación Santa Fe de Bogotá"

links:
  - type: pdf
    url: https://openaccess.thecvf.com/content/ICCV2025W/CVAMD/papers/Vega_CARDIUM_Congenital_Anomaly_Recognition_with_Diagnostic_Images_and_Unified_Medical_ICCVW_2025_paper.pdf

  - type: code
    url: https://github.com/BCV-Uniandes/Cardium

  - type: source
    url: https://openaccess.thecvf.com/content/ICCV2025W/CVAMD/html/Vega_CARDIUM_Congenital_Anomaly_Recognition_with_Diagnostic_Images_and_Unified_Medical_ICCVW_2025_paper.html

image:
  caption: ""
  focal_point: "Center"
  preview_only: false

projects:
  - cardium

slides: ""
---

CARDIUM addresses prenatal congenital heart disease detection through multimodal
learning. The dataset combines fetal ultrasound and echocardiographic images with
26 maternal clinical variables from medical records.

I contributed to the construction of the multimodal dataset by extracting and
structuring the maternal clinical variables, and worked on the tabular encoder
and cross-attention-based fusion between clinical and visual representations.

The resulting multimodal architecture outperformed both image-only and
tabular-only baselines, demonstrating the value of combining complementary
clinical and imaging information for prenatal diagnosis.
