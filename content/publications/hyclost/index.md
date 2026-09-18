---
title: "Hyperbolic Contrastive Learning with Entailment for Spatial Transcriptomics"

authors:
  - Daniela Vega
  - Paula Cárdenas
  - me
  - Leonardo Manrique
  - Pablo Arbeláez

date: '2026-09-14T00:00:00Z'

publication_types:
  - paper-conference

publication:
  name: "Medical Image Computing and Computer-Assisted Intervention"
  short_name: "MICCAI 2026"

peer_reviewed: true
open_access: true

abstract: |
  Spatial Transcriptomics enables spatial mapping of gene expression across tissue
  sections, but high operational costs, specialized equipment requirements, and
  experimental noise limit scalability. HyCLoST introduces a hyperbolic contrastive
  learning framework with a gene-to-image entailment loss to capture hierarchical
  relationships between tissue morphology and gene expression.

summary: |
  Hyperbolic representation learning for spatial gene-expression prediction from
  histopathology, capturing hierarchical and asymmetric structure in spatial
  transcriptomics data.

tags:
  - Spatial Transcriptomics
  - Histopathology
  - Hyperbolic Learning
  - Representation Learning
  - Multimodal Learning

featured: true

hugoblox:
  ids:
    arxiv: "2609.16207"

links:
  - type: pdf
    url: "https://arxiv.org/pdf/2609.16207"

  - type: source
    url: "https://arxiv.org/abs/2609.16207"

  - type: code
    url: "https://github.com/BCV-Uniandes/HyCLoST"

image:
  caption: ""
  focal_point: "Center"
  preview_only: false

projects:
  - spatial-transcriptomics

slides: ""
---

HyCLoST is a hyperbolic contrastive learning framework for spatial
transcriptomics that learns structured representations of tissue morphology and
gene expression.

The method combines hyperbolic geometry with a gene-to-image entailment loss to
model hierarchical and asymmetric relationships within spatial transcriptomics
data.

Across 26 spatial transcriptomics datasets, HyCLoST achieved a **6% reduction in
MSE** and an **8% increase in PCC** over previous methods.

The work was accepted at **MICCAI 2026**.
