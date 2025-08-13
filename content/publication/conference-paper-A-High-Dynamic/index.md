---
title: 'A High Dynamic Range Pixel with Inverse Proportional Response'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - YuchenWang
  - WenjiMo
  - HaoningSun
  - admin

# Author notes (optional)
author_notes: ["","","","*Corresponding author"]
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-22T00:00:00Z'
doi: '10.1109/ICSICT62049.2024.10831217'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE 17th International Conference on Solid-State & Integrated Circuit Technology (ICSICT)*, 2024
publication_short: In *2024 IEEE 17th International Conference on Solid-State & Integrated Circuit Technology (ICSICT)*, 2024

abstract: This paper proposes a high dynamic range (HDR) pixel that combines linear response and inverse proportional response. This pixel achieves nonlinear compression of light intensity under inverse proportional response to improve dynamic range (DR), suitable for CMOS image sensors (CIS) with rolling shutter operation. The proposed pixel is composed of only 4 MOSFET. In HDR mode, it loads the output signal with brightness information dynamically onto the column signal bus. This pixel does not rely on the I-V characteristics of the CMOS subthreshold region and adopts a hard reset structure, overcoming the problems of poor low light SNR performance and image lagging in the traditional logarithmic pixels. The use of low threshold NMOS transistors in the pixel circuit results in the swing of the pixel output close to the power supply voltage, improving the low-voltage performance of the pixel circuit and bringing higher DR. Under a standard CMOS process, the pixel pitch is 6.6μm with a fill factor of 37.6%. The post simulation results indicate that the proposed pixel has good linear and inverse proportional responses to photocurrent. Compared to the linear mode, this pixel has a DR improvement of at least 31.9dB in the HDR mode.

# Summary. An optional shortened abstract.
summary: This paper proposes an HDR pixel combined linear and inverse proportional response.

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
