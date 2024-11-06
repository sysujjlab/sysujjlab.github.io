---
title: 'Modeling for Low Power Bypass Window SAR ADC Based on Highest Weight Capacitor Splitting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - KangkangSun
  - Huan Wu
  - JianGuan
  - ZhipengLi
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-10T00:00:00Z'
doi: '10.1109/ICECS58634.2023.10382910'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 30th IEEE International Conference on Electronics, Circuits and Systems (ICECS)*, 2023, pp. 1-4.
publication_short: In *2023 30th IEEE International Conference on Electronics, Circuits and Systems (ICECS)*, 2023, pp. 1-4

abstract: A 10-bit low power successive approximation register (SAR) analog-to-digital converter (ADC) with bypass window timing based on highest weight capacitor splitting is proposed. Different splitting schemes are analyzed and compared. By establishing a behavioral model in MATLAB, the power consumption of quantizing uniformly distributed signals for each splitting scheme is simulated. The results show that the lowest power consumption is 79.08 CVREF^2, which saves 94.7% and 53.5% compared with the conventional switching timing and VCM-based timing respectively. The proposed bypass window quantization scheme has more obvious advantages of low power consumption to quantize physiological signals like electrocardiogram (ECG). It can also improve the accuracy and linearity of the ADC. The paper also analyzes the influence of capacitor mismatch, comparator offset and input noise on the performance of the ADC, and evaluates their impact under different splitting schemes through MATLAB. The simulation results show that with 1% capacitor mismatch error, the "64+64" scheme can achieve an effective number of bits (ENOB) of 9.9 bit.

# Summary. An optional shortened abstract.
summary: This paper proposed a bypass window SAR ADC based on highest weight capacitor splitting.

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
url_source: 'https://ieeexplore.ieee.org/document/10382910'
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
