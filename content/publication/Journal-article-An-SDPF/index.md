---
title: "An SDPF RISC-V Processor with 55.9% Dhrystone Improvement Using Two-Stage Pseudo-Pipelined Architecture for IoT Applications"
authors:
- WenjiMo
- admin
- YuchenWang
- FengYan
- BingjunXiong
- JianGuan

author_notes: ["","*Corresponding author","","","",""]
# - "Equal contribution"
# - "Equal contribution"
date: "2025-02-12T00:00:00Z"
#doi: "10.1109/TVLSI.2025.3559669"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Circuit Theory and ApplicationsEarly View*."
publication_short: "*International Journal of Circuit Theory and ApplicationsEarly View*."

abstract: Embedded Internet of Things (IoT) nodes are required to perform lightweight tasks such as information monitoring and simple signal processing. A crucial component of low-power embedded IoT sensors is the low-power processor. Due to the constraints of operating conditions, there are stringent requirements on the power consumption and area of the processor. To minimize the power and area, this paper proposes a low-power RV32I processor based on the RISC-V instruction set architecture (ISA), which adheres to a serial data path. To enhance the energy efficiency of the serial data path followed (SDPF) processor, this paper proposes a pseudo-pipeline architecture. By partitioning and combining certain instruction lifecycle tasks, a two-stage pseudo-pipeline structure is implemented, thereby reducing the cycles per instruction (CPI) of the SDPF processor. The proposed processor is designed using Verilog HDL, and FPGA prototype validation demonstrates that the proposed processor achieves at least 18% fewer resource compared with the traditional parallel 32-bit RISC-V processors and 55.9% performance improvement compared with the previous SDPF processors. The proposed processor is implemented using a standard 0.18-μm CMOS process. The post-layout simulation results indicate that it has at least 9.6% less area and 37.5% lower dynamic power consumption compared with traditional parallel 32-bit processor. Additionally, it achieves a 40.9% increase in the performance to power ratio compared with the previous SDPF RV32I processor.
# Summary. An optional shortened abstract.
summary: This paper introduces a pseudo two-stage pipeline SDPF processor, which enhances the performance of SDPF RISC-V processors by reducing CPI in the serial data path through simulated pipeline structures, which achieves improved performance while maintaining low power and area overheads. 

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
url_source: 'https://onlinelibrary.wiley.com/doi/10.1002/cta.4514'
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
