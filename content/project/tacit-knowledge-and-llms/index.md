---
title: Do large language models have conceptual knowledge? 
summary: Using tacit knowledge to study what large language models learn from the data and whether this might be considered conceptual knowledge. 
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Conceptual knowledge as learning associations between concepts and corresponding properties. 
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Large language models (LLMs), such as GPT-3 (Brown et al., 2020) and ChatGPT (OpenAI, 2022) are exhibiting increasingly impressive and arguably human-like behavior: they can translate and generate text and seem to engage in generally realistic dialogue with human users. This behavior has led to questions regarding the cognitive and linguistic capacities of these models. Language has long been associated with intelligence, think for example of the Turing test (Turing, 1950). Since we now have artificial systems that generate language, what does it mean for these systems to ‘know’ language and to what extent should we attribute any cognitive and linguistic capacities like knowledge and understanding to them? 

In this project, I aim to defend two claims. Firstly, I argue that it is insufficient to merely consider behavior when determining whether LLMs should be attributed any cognitive or linguistic capacities. Instead, we should develop explanations that show how a network actually works by looking at the internal processing of the model (Block, 1981; Zednik, 2021), i.e. how it mediates transitions from inputs to outputs. This could show what regularities the network picks up from the input data, what representations are learned, and what structures underlie generalization to new inputs. These kinds of explanations seem necessary to evaluate whether LLMs have an internal structure that supports robust linguistic capacities (See e.g. Piantadosi & Hill, 2022) or are mere ‘stochastic parrots’ that cannot capture meaning (Bender et al., 2021; Bender & Koller, 2020). 
 
Due to the opacity and scale of these networks, however, it is unclear how these explanations should be developed. Drawing on work from Davies (1987, 1990) and a recent paper by Lam (2022), my second claim is that tacit knowledge could be a promising theoretical posit for developing how-explanations of LLMs. In the context of neural networks, tacit knowledge is defined as implicitly represented rules that are used by the network to guide its behavior. To be ascribed tacit knowledge, Davies proposes that networks should, amongst others, meet the constraint of causal systematicity, which requires that there is a pattern of causal common factors that mediates transitions from similar inputs to similar outputs. The problem is, however, that this is not directly applicable to contemporary LLMs due to their distributed nature. To show that tacit knowledge might nevertheless be helpful for developing how-explanations, I critically reflect on Davies’ conception of tacit knowledge and argue that it could in fact be used to explain the behavior of LLMs to some extent. 
 
In summary, I have the following aims: a) to introduce and nuance the current discussions regarding the potential cognitive and linguistic capacities of LLMs, b) to argue that attribution of such capacities requires a suitable internal structure, c) to propose that tacit knowledge is one way to conceptualize such a structure, and d) to critically evaluate and adapt Davies’ account of tacit knowledge to make it suitable for contemporary LLMs. 

{style="text-align: justify;"}
