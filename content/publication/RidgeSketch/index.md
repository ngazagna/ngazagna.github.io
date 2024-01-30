---
title: "RidgeSketch, A Fast sketching based solver for large scale ridge regression"

authors:
- admin
- Mark Ibrahim
- Robert M. Gower 

date: "2022-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Journal on Matrix Analysis and Applications"
publication_short: ""

abstract: We propose new variants of the sketch-and-project method for solving large scale ridge regression problems. Firstly, we propose a new momentum alternative and provide a theorem showing it can speed up the convergence of sketch-and-project, through a fast *sublinear* convergence rate. We carefully delimit under what settings this new sublinear rate is faster than the previously known linear rate of convergence of sketch-and-project without momentum. Secondly, we consider combining the sketch-and-project method with new modern sketching methods such as the count sketch, subcount sketch (a new method we propose), and subsampled Hadamard transforms. We show experimentally that when combined with the sketch-and-project method, the (sub)count sketch is very effective on sparse data and the standard subsample sketch is effective on dense data. Indeed, we show that these sketching methods, combined with our new momentum scheme, result in methods that are competitive even when compared to the Conjugate Gradient method on real large scale data. On the contrary, we show the subsampled Hadamard transform does not perform well in this setting, despite the use of fast Hadamard transforms, and nor do recently proposed acceleration schemes work well in practice. To support all of our experimental findings, and invite the community to validate and extend our results, with this paper we are also releasing an open source software package, *RidgeSketch*. We designed this object-oriented package in Python for testing sketch-and-project methods and benchmarking ridge regression solvers. *RidgeSketch* is highly modular, and new sketching methods can easily be added as subclasses. We provide code snippets of our package in the appendix. 

# Summary. An optional shortened abstract.
summary:

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2105.05565.pdf'
url_code: 'https://github.com/facebookresearch/RidgeSketch'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# ---

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).