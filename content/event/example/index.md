---
title: Tacit knowledge for explaining how large language models work

event: Meeting of the Society for Philosophy of Psychology
event_url: https://www.socphilpsych.org/meetings.html

location: Pittsburgh, US
# address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: In this talk, I will explore how we can use tacit knowledge as proposed by Davies to explain the behavior of current large language models. 
# abstract: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-06-21T13:00:00Z'
date_end: '2023-06-21T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/cebudding
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

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
  - tacit-knowledge-and-llms
---
In this talk, I will explore how we can use tacit knowledge to explain the behavior of current large language models. In particular, I argue that large language models might learn something beyond just predicting the next word during training. One way to determine what these models learn is to look at their model internals. However, due to the black box problem it is not straightforward to interpret these parameters. Therefore, I propose that we can conceptualize waht LLMs learn as _tacit knowledge_ as proposed by Martin Davies. This account of tacit knowledge introduces a particular causal structure that would support attribution of some kind of knowledge. In the talk, I first introduce the account in more detail and discuss some potential issues when applying this to connectionist neural networks. Then, I argue that we can nevertheless apply this account for explaining current LLMs and illustrate this using an example, namely [ROME by Meng and colleagues (2022)](https://rome.baulab.info/). I end with some recommendations for further research. 

{{< gdocs src="https://docs.google.com/presentation/d/e/2PACX-1vTDmugRGLTnQMpRs1cQGpxquL87GznTKcAVvZIXzHfbe88sBdZ4amau3RuYlBywm00cXw46nmpDCzJw/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>}}

# {{% callout note %}}
# Click on the **Slides** button above to view the built-in slides feature.
# {{% /callout %}}

# Slides can be added in a few ways:

# - **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
# - **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
# - **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

#Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
