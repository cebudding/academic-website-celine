---
title: Tacit knowledge and explaining the behavior of LLMs 
summary: I argue that current LLMs might acquire tacit knowledge, which could be used to explain their behavior. 
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Learning semantic similarity in the data. 
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
Large language models (LLMs), such as ChatGPT (OpenAI, 2022) and Claude (Anthropic AI, 2023) have recently exhibited impressive performance in conversational AI, generating seemingly human-like and coherent texts. In contrast to earlier language modeling methods, Transformer-based LLMs do not contain any prior linguistic knowledge or rules, but are trained on next-word prediction: predicting the most likely next word in an input sequence based on large quantities of training data. Despite this seemingly simple training objective, Transformer-based LLMs far exceed the performance of earlier methods. 

Given this impressive performance, there is an increased interest in not only studying the behavior of these systems, but also investigating the underlying processing and how these systems make their predictions. That is, the focus is not only on the performance, but increasingly also on something like what Chomsky (1965) called the underlying competence. For instance, it has been proposed that LLMs might not just perform next-word prediction based on surface statistics, but that they in fact learn something akin to symbolic rules (Lepori et al., 2023; Pavlick, 2023) or even knowledge (Meng et al., 2022; Yildirim & Paul, 2023). While it might seem appealing to attribute knowledge to LLMs to explain their impressive performance, however, it remains unclear what kind of knowledge LLMs might acquire and when this could be attributed. 

Taking inspiration from earlier debates between symbolic and connectionist AI in the 1980s and 90s (e.g. Clark, 1991; Fodor & Pylyshyn, 1988), I propose that tacit knowledge, as defined by Davies  (Davies, 1990, 2015), provides a suitable way to conceptualize potential knowledge in LLMs. That is, if the constraints as set out by Davies (1990) are met by a particular LLM, that system can be said to have tacit knowledge. Tacit knowledge, in this context, refers to implicitly represented rules or structures that causally affect the system’s behavior. As connectionist systems are known not to have explicit knowledge, in contrast to earlier symbolic systems, tacit knowledge provides a promising way to nevertheless conceptualize and identify meaningful representations in the model internals. Yet, Davies himself argued that the connectionist systems he was concerned with do not meet the constraints for attributing tacit knowledge. While this objection might have held for connectionist systems in the 80s and 90s, however, I argue that current LLMs could in fact meet Davies’ constraints and be said to have tacit knowledge, due to particular innovations in the Transformer architecture (Vaswani et al., 2017). 

Taken together, the aims of this contribution are fourfold: 1) to illustrate why LLMs might be thought to learn more than next-word prediction, 2) to propose Davies’ account of tacit knowledge as way to characterize and provide conditions for attributing a form of knowledge to LLMs, 3) to address Davies’ objection to applying tacit knowledge to connectionist networks, and 4) to show that some current LLMs meet Davies’ constraints and could thus be said to have tacit knowledge. 


{style="text-align: justify;"}
