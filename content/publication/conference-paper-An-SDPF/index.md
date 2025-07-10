---
title: 'An SDPF RISC-V Processor with Two-stage Pseudo-pipelined Architecture for IoT Applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - WenjiMo
  - YuchenWang
  - HaoningSun
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-22T00:00:00Z'
doi: '10.1109/ICSICT62049.2024.10832035'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE 17th International Conference on Solid-State & Integrated Circuit Technology (ICSICT)*, 2024
publication_short: In *2024 IEEE 17th International Conference on Solid-State & Integrated Circuit Technology (ICSICT)*, 2024

abstract: Internet of Things (IoT) nodes are required to execute lightweight tasks for sensing information and simple signal processing. Thus low-power processors serve as crucial components of highly integrated IoT smart sensors. This paper proposes a low-power RISC-V instruction set architecture (ISA) based RV32I processor for embedded IoT nodes, which follows the serial data path. To enhance the performance of the serial data path followed (SDPF) processor, a pseudo-pipelined architecture is proposed. By partitioning and combining a portion of the instruction life cycle tasks into two stages, a two-stage pseudo-pipelined structure is achieved, reducing the number of cycles per instruction (CPI) of the SDPF processor. The proposed processor is designed based on Verilog HDL, the implementation results on FPGA demonstrate that the performance is improved by 58% compared to the conventional SDPF RV32I processor. Besides, the synthesis is performed using a standard 0.18 µm CMOS process technology. Post-layout simulation results demonstrate that, the System on Chip (SoC), which consists of the proposed processor, a 2 kB IMEM and a 4 kB DMEM, achieves an average CPI of 36, an area of 0.988 mm2, and an average power consumption of 182 µW/MHz.

# Summary. An optional shortened abstract.
summary:This paper proposes a method to improve the performance of RISC-V processors that follow a serial data path.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/10831599'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
