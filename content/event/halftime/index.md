---
title: Efficient Linearizability Monitoring
event: Halftime Seminar
# event_url: https://example.org

location: Uppsala University

# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# summary: An example talk using Hugo Blox Builder's Markdown slides feature.
abstract: 'We present efficient and novel algorithms for checking the linearizability of executions of concurrent data structure libraries such as stacks queues and sets. Linearizability is the standard correctness condition for such concurrent objects, and is routinely taught at the undergraduate level. Despite the simplicity of the concept, designing linearizability algorithms has shown to be notoriously difficult. In fact, it is so difficult that we have found that all previous works on polynomial-time algorithms either (i) are unsound, (ii) have unsound correctness proofs, or (iii) are missing correctness arguments altogether. Furthermore, the algorithms in (ii) or (iii) have cubic complexity. We present a new family of algorithms with better time complexity, as well as provide proofs of their correctness. For stacks, we construct a linearization recursively by detecting patterns that correspond to intervals of time during which the stack is populated or may be empty, and obtain an algorithm that is quadratic in the length of the input. For queues, we have proven a small-model theorem, from which we can extract an algorithm that is O(n log n). For (multi)sets, we show that it is sufficient to count certain events at each step, and thus obtain an algorithm that is O(n). We have implemented these algorithms in a tool, LiMo (LInearizability MOnitor). In this talk, I will present these algorithms, and relay the key ideas in their correctness proofs.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-01-14T14:15:00Z'
date_end: '2030-06-01T16:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [ Linearizability ]

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/grahnen/slides'
# url_pdf: ''
url_slides: 'https://grahnen.github.io/slides/halftime/'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - Linearizability Monitoring
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.


