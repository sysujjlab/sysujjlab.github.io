---
title: "A 0.6-V 9.38-Bit 6.9-kS/s Capacitor-Splitting Bypass Window SAR ADC for Wearable 12-Lead ECG Acquisition Systems"
authors:
- KangkangSun
- admin
- FengYan
- YuanRen
- RuihuangWu
- BingjunXiong
- ZhipengLi
- JianGuan

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-04-28T00:00:00Z"
doi: "10.1109/TVLSI.2025.3559669"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "* IEEE Transactions on Very Large Scale Integration (VLSI) Systems ( Volume: 33, Issue: 7, July 2025)*. 2023;44(10): 1664-1667."
publication_short: "* IEEE Transactions on Very Large Scale Integration (VLSI) Systems ( Volume: 33, Issue: 7, July 2025)*. 2023;44(10): 1664-1667"

abstract: This article proposes a fully differential ten-bit energy-efficient successive approximation register (SAR) analog-to-digital converter (ADC) for wearable 12-lead electrocardiogram (ECG) acquisition system. The proposed ADC structure generates two bypass windows through capacitor splitting technique, which can skip unnecessary quantization steps. The judgment module of bypass windows only requires an XOR gate. By introducing redundant capacitors to participate in quantization, the total capacitance value is reduced by half. The proposed SAR ADC is fabricated using a standard 180-nm CMOS process. The measurement results show that it can achieve an effective number of bits (ENOBs) of 9.38 bits and a spurious-free dynamic range (SFDR) of 76.71 dB with a supply voltage of 0.6 V at a sampling rate ( FS ) of 6.94 kS/s. The power consumption is 15.61 nW when subjected to a 1.17- VPP 3.45 -kHz sinusoidal input, resulting in a figure of merit (FoM) of 3.38 fJ/conv.-step. The average power consumption for quantizing 12-lead ECG signals is approximately 12.66 nW, demonstrating the ability to achieve ultralow-power quantization of ECG signals.
# Summary. An optional shortened abstract.
summary:In this article, a bypass window SAR ADC structure based on multiple splits of the MSB capacitor is proposed for the characteristics of 12-lead ECG signals to minimize the power consumption.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/10233876'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
