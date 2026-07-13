---
layout: post
title:  "Mapping islet cell identity with transcriptomics"
tags: [ Bioinformatics, RNA-seq ]
featured_image: assets/images/posts/2018/7.jpg
author: shristi
---

A big part of my research life has been spent trying to answer a deceptively simple question: what makes a pancreatic islet cell *itself*? Alpha cells make glucagon, beta cells make insulin, and both sit side by side in the same tiny organ - yet their transcriptional programs are strikingly different, and in diabetes those programs start to blur.

## Why transcriptomics

Bulk RNA-seq gave us the first clear picture of how alpha and beta cell gene expression diverges, and how that divergence breaks down in type 1 and type 2 diabetes. But bulk data averages over thousands of cells, which hides the heterogeneity that turns out to matter most - the handful of cells that are losing their identity, or the rare subpopulations that respond differently to stress.

That's where single-cell and combinatorial transcription factor profiling come in. By layering transcription factor combinations on top of expression data, we've been able to predict which cells are "mature and functional" alpha or beta cells versus cells drifting toward a less committed state. It's one of the more satisfying kinds of analysis: the computational result maps directly back onto a biological question a bench scientist actually asked.

## What keeps this interesting

Every new dataset - a new donor, a new disease state, a new sequencing modality - reopens the same question with a bit more resolution. It's part of why I enjoy this work at Creative Data Solutions: the tools change (bulk to single-cell to spatial), but the underlying puzzle of cell identity keeps getting richer.
