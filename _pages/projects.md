---
title: "Projects"
layout: single
permalink: /projects/
author_profile: True
---
<!-- # Projects -->

### Selected Projects


- **Processing Pipeline for HCP Data**  
  I developed a high-throughput processing pipeline for Human Connectome Project (HCP) data using SLURM job scheduling. The pipeline allows users to submit parallel processing jobs for multiple subjects, scaling efficiently with the number of available cores. Since each subject requires time-intensive steps—such as FreeSurfer’s `recon-all` and parcellation onto the Glasser atlas, which can take up to 12 hours—parallelism is essential for timely analysis across large datasets.

    <img src="{{ '/assets/images/figureproject2.png' | relative_url }}" alt="HCP Pipeline Diagram" width="100%">


- **Graph High-Pass Neural Networks**  
  I implemented a Graph Neural Network (GNN) that incorporates a high-pass filter kernel based on a Chebyshev rational filter framework. Unlike conventional methods that rely on costly eigendecomposition, this approach offers computational efficiency with complexity scaling quadratically rather than cubically. This makes it practical for applying graph signal processing techniques to large-scale data while preserving the benefits of spectral filtering.

<img src="{{ '/assets/images/gnn.png' | relative_url }}" alt="GNN Anomaly Detection ROC" width="100%">


- **VergeIO** — EOG-based smart glasses enabling depth-aware interaction  
  I created a video to showcase VergeIO shortly after our paper submission. The video provides a concise demonstration of our core innovations and potential applications. It is narrated by Professor Justin Chan and serves as an accessible introduction to the system’s design and capabilities.

  <video autoplay loop muted playsinline width="100%" poster="{{ '/assets/images/vergeio-thumbnail.png' | relative_url }}">
    <source src="{{ '/assets/videos/Vergeio_finalcut.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  🎬 [Watch Full Video]( {{ '/assets/videos/Vergeio_finalcut.mp4' | relative_url }} ){:target="_blank"}

