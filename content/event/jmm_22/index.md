---
title: "Deal or No Deal: Modeling a Game Show with Utility Theory and Machine Learning"

event: Joint Mathematics Meetings 2022 - Contributed Poster
event_url: https://jointmathematicsmeetings.org/meetings/national/jmm2022/2268_program_friday.html

location: Virtual

summary: Deal or No Deal, a game show that features nine rounds of high stakes player decisions, aired in the United States beginning in 2005. Utility theory helps to explain the rationale of the players at each stage of the game, as well as derive an optimal strategy for maximizing one’s winnings. Using empirical data compiled by Post et al. (2008) and a simulation of 1000 players, one can develop models to predict what amount of money the banker will offer at the end of each round and in what conditions a player will take this offer, the deal. While other supervised learning algorithms were explored, regression and neural networks yielded accuracies of at least 80% at each stage of testing. A deep neural network yielding a coefficient of determination of 0.95 and comparatively low mean error was chosen as the best for predicting the banker offer. To further explore other avenues of intelligent gameplay, reinforcement learning techniques were used to implement a deep Q-network to play the game and be compared to simulated contestants. A path-dependent utility function was implemented to describe empirical and simulated player decisions, and players chose the option with higher utility over 85% of the time. Additional improvements were also implemented; such as nesting the utility function in models of stochastic choice, like the tremble model, to account for errors in player judgement. This report will summarize the results of the CC-REU NSF summer REU experience (DMS-2050692) where these questions were explored.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-04-08T10:30:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
# featured: false

# image:
# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/ashley___mullan
url_code: ''
url_pdf: 'https://drive.google.com/file/d/1gBWy_cDklQGZ2wcI1n0JZZoUuYfInlML/view'
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
# projects:
 # - example
---


