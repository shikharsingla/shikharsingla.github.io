---
permalink: /
title: ""
excerpt: "Shikhar Singla"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My research agenda is to use Artificial Intelligence techniques such as word embeddings, deep neural networks, generative models, reinforcement learing, supervised learning, entity recognition into finance areas like regulations, norms and human biases and asset pricing. 

Please download my [CV here](https://shikharsingla.com/files/cv.pdf).

# Research

## Supervised Learning and Regulations


**[Regulatory Costs and Market Power](https://shikharsingla.com/files/reg_costs_market_power_ss.pdf)** 

**[The Political Economy of Financial Regulation](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4250919)**\
<a href="https://www.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/professur-haselmann/rainer-haselmann.html" style="color: gray; text-decoration: underline;">Rainer Haselmann</a>, <a href="https://sites.google.com/view/arkodiptasarkar/" style="color: gray; text-decoration: underline;">Arkodipta Sarkar</a>, Shikhar Singla and <a href="https://www.vikrantvig.com/" style="color: gray; text-decoration: underline;">Vikrant Vig</a>

## Word Embeddings and Gender Norms

**[Gender Norms Do Not Persist But Converge Across Time](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4183488)**\
Shikhar Singla and <a href="https://www.london.edu/phd/profiles/mayukh-ketan-mukhopadhyay" style="color: gray; text-decoration: underline;">Mayukh Mukhopadhyay</a>

**[Machine Unlearning Human Biases: Inclusive Word Embeddings by Excluding Biased Text](https://shikharsingla.com/files/debias_ss.pdf)**


## Deep Learning and Asset Pricing

**[Human-Centred AI investor Using Deep Generative Models, Reinforcement Learning and Prospect Theory]()**

**Economic Nowcasting Using Deep Generative Adversarial Models**<br/>
<small>[ <a href="#/" onclick="visib('nowcast')">Abstract</a> | [Draft Coming Soon]]</small>

<div id="nowcast" style="display: none; text-align: justify; line-height: 1.2" ><small>
Economic nowcasting aims to provide predictions that i) are consistent across spatial and temporal dimensions, ii) account for uncertainty and can be verified probabilistically, and iii) perform well on events that are rarer but critical. These characteristics are missing in commonly used deterministic nowcasting methods and thus these models produce forecasts with higher errors at higher lead times and may not include small-scale yet important patterns. This paper overcomes these challenges by developing a novel deep generative model (DGM). The model is driven by two loss functions defined by spatial and temporal discriminators and a regularisation term. These terms guide parameter adjustment by comparing real observations with model-generated data. The first loss function ensures spatial consistency and discourages errors at higher lead times, whereas the second imposes temporal consistency and penalises jumpy predictions. The regularisation term further improves the accuracy by penalising deviations at the local level. The model architecture is based on stacked Convolutional Gated Recurrent (ConvGRU) Units.
</small><br><br/></div>

**High-Resolution Satellite Imagery, Deep Learning, and Return Predictability**<br/>
<small>[ <a href="#/" onclick="visib('image')">Abstract</a> | [Draft Coming Soon]]</small>

<div id="image" style="display: none; text-align: justify; line-height: 1.2" ><small>
The literature has shown that satellite imagery can be used to measure economic conditions. This paper extends this approach by applying convolutional neural networks on establishment-level high-resolution satellite images to predict real-time firm-level sales, profitability and cash flows. The paper leverages recently available high-resolution satellite images made publicly available by Google and innovations in neural network architecture to extract the relevant features from the images that predict firms’ cash flows.
</small><br><br/></div>



## Financial Regulation

**[Capital Requirements, Market-Making, and Liquidity](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4250896)**\
<a href="https://www.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/professur-haselmann/rainer-haselmann.html" style="color: gray; text-decoration: underline;">Rainer Haselmann</a>, <a href="https://www.bundesbank.de/en/thomas-kick" style="color: gray; text-decoration: underline;">Thomas Kick</a>, Shikhar Singla and <a href="https://www.vikrantvig.com/" style="color: gray; text-decoration: underline;">Vikrant Vig</a>


**[Supranational Supervision]()**\
<a href="https://www.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/professur-haselmann/rainer-haselmann.html" style="color: gray; text-decoration: underline;">Rainer Haselmann</a>, Shikhar Singla and <a href="https://www.vikrantvig.com/" style="color: gray; text-decoration: underline;">Vikrant Vig</a>


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
