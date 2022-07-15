---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Postdoctoral Researcher, University of Liverpool

profile:
  align: right
  image: profile-pic.jpg
  image_cicular: false # crops the image to make it circular
  address: >
    <p>A213, Ashton Building</p>
    <p>Ashton Street</p>
    <p>Liverpool, L69 3BX.</p>

news: false  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am a postdoctoral researcher in the Department of Computer Science at the University of Liverpool working with [Professor Rahul Savani](https://www.liverpool.ac.uk/computer-science/staff/rahul-savani/). I am interested in designing reinforcement learning (RL) agents which can learn how to act optimally to [make markets](https://en.wikipedia.org/wiki/Market_maker). Since the agent's interaction with the financial market in turn causes the future dynamics to change, it requires a market model that is adaptive. One way of achieving this is to create a [world model](https://worldmodels.github.io/) of the financial market which generates order flow according to the history of the [limit order book](https://www.5minutefinance.org/concepts/the-limit-order-book) up to that point.

A popular choice for the world model is to use an analytical model of the orderbook dynamics with a concrete mathematical representation. However, this suffers from a variety of issues that arise due to the inability of the chosen model to reproduce "empirical facts" observed in real-life limit order books due to its simplicity. An exciting alternative is to "learn" the orderbook dynamics using a deep generative model such as a conditional [GAN](https://en.wikipedia.org/wiki/Generative_adversarial_network) or a conditional [VAE](https://en.wikipedia.org/wiki/Variational_autoencoder). This enables much more complex dynamics to by captured and the realism of the simulated orderbook to vastly improve. One can then train a reinforcement learning agent to optimally make markets in this environment.

Before joining Liverpool, I did my PhD in Statistics at the University of Warwick under the supervision of [Professor David Hobson](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/hobson/) and [Dr Martin Herdegen](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/herdegen), where I worked on problems on financial stochastic optimal control. In particular, I researched a variant of [Merton's optimal investment-consumption problem](https://en.wikipedia.org/wiki/Merton%2527s_portfolio_problem) where the agent's preferences are given by stochastic differential utility.

Here is [a link to my Liverpool webpage](https://www.liverpool.ac.uk/computer-science/staff/joseph-jerome/).
