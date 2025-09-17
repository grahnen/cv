---
title: Efficient Linearizability Monitoring
event: PLDI 2025
event_url: https://pldi25.sigplan.org/

location: Seoul, South Korea

# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# summary: An example talk using Hugo Blox Builder's Markdown slides feature.
abstract: 'This paper revisits the fundamental problem of monitoring the linearizability of concurrent stacks, queues, sets, and multisets. Given a history of a library implementing one of these abstract data types, the monitoring problem is to answer whether the given history is linearizable. For stacks, queues, and (multi)sets, we present monitoring algorithms with complexities (n2), (n log n), and (n), respectively, where n is the number of operations in the input history. For stacks and queues, our results hold under the standard assumption of data-independence, i.e., the behavior of the library is not sensitive to the actual values stored in the data structure. Past works to solve the same problems have cubic time complexity and (more seriously) have correctness issues: they either (i) lack correctness proofs or (ii) have unsound correctness proofs (we present counter-examples of the correctness proofs), or (iii) have unsound algorithms. Our improved complexity results rely on substantially different algorithms for which we provide detailed proofs of correctness. We have implemented our stack and queue algorithms in LiMo (Linearizability Monitor). We evaluate LiMo and compare it with the state-of-the-art tool Violin – whose correctness proofs we have found errors in – which checks for linearizability violations. Our experimental evaluation confirms that LiMo outperforms Violin regarding both efficiency and scalability.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-06-16T0900:00Z'
date_end: '2025-06-20T1800:00Z'
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
url_code: 'https://github.com/grahnen/LiMo'
# url_pdf: ''
url_slides: 'https://grahnen.github.io/slides/vds25/'
#url_video: 'https://www.youtube.com/watch?v=CJHvBcLe9YI'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - Linearizability Monitoring
---
