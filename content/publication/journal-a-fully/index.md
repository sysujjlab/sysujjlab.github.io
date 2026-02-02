---
title: "A Fully Integrated Storage-Free Energy Harvesting System with Voltage Self-Regulation and Dual-Channel Power Extraction"
authors:
- JianGuan
- admin
- WenjiMo
- FengYan
- KangkangSun
- WeijieGe


author_notes: ["","*Corresponding author","","","",""]
# - "Equal contribution"
# - "Equal contribution"
date: "2025-12-30T00:00:00Z"
#doi: "10.1109/TVLSI.2025.3559669"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Very Large Scale Integration Systems*."
publication_short: "*IEEE Transactions on Very Large Scale Integration Systems*."

abstract: "With the growing demand for self-powered operation in Internet of Things (IoT) nodes and microsensors, photovoltaic energy harvesting (EH) systems have become a key research focus. Although triple-well on-chip solar cells improve photovoltaic conversion efficiency, their multiport output characteristics pose design challenges: conventional parallel output schemes cannot address the mismatch in maximum power point (MPP) voltages among ports, thereby limiting energy extraction efficiency. Moreover, fully integrated EH systems lack external storage, and input–output coupling renders traditional voltage regulation unsuitable. To address these challenges, this article presents a fully integrated dual-channel EH system that employs a dual-port, independently boosted parallel architecture combined with a frequency-driven lightweight self-regulation mechanism, eliminating the need for conventional regulators. Measurement results show that the system achieves a stable output voltage of approximately 1.22 V, a peak end-to-end efficiency of 63.97%, and a 6.31% improvement in maximum output power, while also exhibiting reliable start-up and ripple suppression, providing valuable guidance for the design of efficient power extraction and self-regulation in on-chip photovoltaic EH systems."
# Summary. An optional shortened abstract.
summary:  "To address the issues of voltage mismatch, limited power extraction, and regulation losses in triple-well on-chip solar cells, this work implements a storage-free dual-channel EH system in standard 0.18-μ m CMOS technology. The system employs a per-port independent boosting architecture with post-boost parallel merging, effectively avoiding energy losses caused by MPP voltage mismatch in conventional designs. Meanwhile, a voltage regulation mechanism based on the load characteristics of the solar cell achieves stabilization without an LDO, enabling fast power control and adaptive power distribution, which better suits the requirements of storage-free EH. Experimental results show that the system maintains a stable 1.22-V output under varying illumination and load conditions; compared with a single-channel design, the voltage ripple is reduced from 102 to 21 mV, the load capacity is improved by 6.31%, and peak circuit and system efficiencies of 63.97% and 9.63% are achieved at 100 kLux, respectively. These results verify the proposed dual-channel EH system’s optimization in power extraction and voltage regulation, highlighting its potential for self-powered microsystems and hybrid energy architectures."

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
url_source: 'https://ieeexplore.ieee.org/document/11318335'
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
