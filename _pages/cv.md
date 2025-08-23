---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[PDF](/files/jmuneton_resume.pdf)

## Education

**Stanford University** | *Stanford, CA*  
Master of Science in Computational Mathematics and Engineering | *Expected 2025*

**Brown University** | *Providence, RI*  
Bachelor of Science in Statistics with Honors | *2021*  
*Advisor: Jon Steingrimsson*

## Research Experience

**Research Assistant** | *SLAC National Accelerator Laboratory* | *2024–Present*  
*Advisors: Cong Wang and Matthias Kling*
- Developing transformer-based latent diffusion models for high-resolution X-ray diffraction data
- Implementing advanced generative modeling techniques for scientific data analysis
- Collaborating on machine learning applications for accelerator physics

**Research Intern** | *Adobe Research* | *Summer 2023*  
*Advisor: Nikos Vlassis*
- Optimized sub-quadratic self-attention mechanisms for long-sequence transformers
- Developed vector quantization and variational encoding techniques
- Improved computational efficiency of transformer architectures by 40-60%

**Research Assistant** | *Brown University* | *2020–2021*  
*Advisor: Jon Steingrimsson*
- Conducted statistical analysis and modeling for undergraduate honors thesis
- Applied advanced statistical methods to complex datasets
- Contributed to research in computational statistics

## Industry Experience

**Machine Learning Engineer** | *Various Projects* | *2021–2023*
- Radar image denoising and signal processing applications
- Adversarial robustness research and implementation
- Scalable data pipelines for production ML systems
- CUDA and parallel programming for high-performance computing

## Technical Skills

**Programming Languages:** Python, C++, MATLAB, R, CUDA  
**Machine Learning:** PyTorch, TensorFlow, scikit-learn, Transformers  
**Scientific Computing:** NumPy, SciPy, JAX, Pandas  
**Tools & Platforms:** Git, Docker, AWS, GCP, Jupyter, LaTeX  
**Specialized:** Generative Modeling, Diffusion Models, Attention Mechanisms, Numerical Linear Algebra

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Teaching Experience

{% for post in site.teaching reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}

## Fellowships & Awards

### Fellowships
- GEM Fellowship – Awarded through Adobe and Stanford University (2023–2025)
- SMART Fellowship – U.S. Department of Defense (2023) Offered, declined
- Amazon Fellowship – Columbia University School of Engineering (2023) Offered, declined
- Sprint Fellowship – Brown University (2020) Awarded

### Awards
- Demosthenes Award – Stanford University, ORALCOM118 Romancing the Room (2025) – Awarded in recognition of public speaking abilities and improvement
- Hispanic Scholarship Fund (HSF) Scholar Award – (2023) Awarded
- Sydney Frank Scholarship – Brown University (2017-2021) Awarded

---

*[Download PDF Resume](/files/jmuneton_resume.pdf)*
