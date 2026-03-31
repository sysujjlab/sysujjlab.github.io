---
title: "Design of a Low-noise Instrumentation Amplifier with Triple-MOS Pseudo-resistor for Bio-signal Acquisition in Consumer Electronics"
authors:
- FengYan
- admin
- KangkangSun
- BingjunXiong
- WenjiMo
- JianGuan


author_notes: ["","*Corresponding author","","","",""]
# - "Equal contribution"
# - "Equal contribution"
date: "2026-02-18T00:00:00Z"
#doi: "10.1109/TVLSI.2025.3559669"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-02-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Consumer Electronics*."
publication_short: "*TCE*."

abstract: Low input-referred noise (IRN) and low-power instrumentation amplifier (IA) with small size are crucial for consumer bio-electronic applications. This paper presents a compact, noise-efficient capacitive-coupled IA designed for bio-signal acquisition. The proposed Triple-MOSFET pseudo-resistor (PR) provides ultra-high resistance, a wide operating voltage range, and high linearity. The IA, enhanced by chopper-stabilized technology, effectively reduces noise while minimizing current consumption. An area-efficient DC servo loop with Triple-MOS devices is employed to suppress electrode DC offset. Addi-tionally, parasitic effects are minimized based on layout design, maximizing the advantages of the positive feedback loop. The proposed IA is fabricated using a standard 180 nm CMOS process with an area of 0.49 mm², and operates at a supply of 0.8 V with a current consumption of 1.29 μA. The IRN of this IA is 0.97 μVrms within the 0.5–200 Hz and 2.31 μVrms within the 0.2–5 kHz, achieving competitive noise efficiency factor (1.4) and power efficiency factor (1.56). Furthermore, for a 2 mVpp sine wave input, total harmonic distortion is below -60.2 dB. The precise value of the positive feedback capacitor ensures that the input impedance reaches 628 MΩ at 50 Hz. A prototype test system based on the IA successfully acquired high-quality ECG and EEG signals from subjects. This efficient, low-noise, low-power acquisition chip has broad applications in portable cardiac monitors, brain-machine interfaces, and other biosensors, playing a significant role in enhancing the performance and reliability of these electronic devices.
summary:  In this paper, a low-noise and low-power IA with chopper modulation topology is proposed for bioelectric signal acquisition. The operation principle, circuit implementation, noise analysis, and measurement results of the proposed IA have been described in detail. The improved Triple-MOS PR comprehensively enhance the performance of the IA chip. The DSL suppresses the electrode offset to ±50 mV with an integration capacitance of only 9.5 pF. A simple area-efficient ripple suppression technique is implemented to drastically reduce the chopping ripple. Meanwhile, a positive feedback loop that eliminates parasitic effects according to the layout increases the input impedance by a factor of 647. The proposed IA occupies 0.92 × 0.54 mm, consumes 1.032 μW, and achieves > 86 dB CMRR at 5 samples without any off-chip tuning. The IA chip with Triple-MOS PR achieves an INR of 0.97 μVrms at 0.5–200 Hz, and realizes a NEF of 2.9, ensuring the comparable input impedance and the best noise performance. The proposed IA has been validated for biologic measurements and provides a high-performance, low-cost solution for consumer-grade electronics. 

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
url_source: 'https://ieeexplore.ieee.org/document/11398358'
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
