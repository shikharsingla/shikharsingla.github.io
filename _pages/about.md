---
permalink: /
title: ""
excerpt: "Shikhar Singla"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My research agenda is to develop and use artificial intelligence techniques such as word embeddings, deep neural networks, generative models, reinforcement learning, supervised learning, debiasing, computer vision, data extraction in finance areas like regulations, gender norms and asset pricing. 

Please download my [CV here](https://shikharsingla.com/files/cv.pdf).

# Research

## Supervised Learning and Regulations


**[Regulatory Costs and Market Power](https://shikharsingla.com/files/reg_costs_market_power_ss.pdf)**\
<small>[ <a href="#/" onclick="visib('reg')">Abstract</a> ]</small>
<div id="reg" style="display: none; text-align: justify; line-height: 1.2" ><small>
Increased market power and its impacts have been well documented. However, the causes of increased market power remain unknown. We hypothesize that the phenomenal increase in social regulations has disproportionately affected the small firms due to fixed costs, which has led to a rise in market power for the large firms. Regulatory compliance costs in actual dollars, affected industries, and whether the regulations impact small firms are reported by the regulators. This data is unique and not reported in any advanced economy except the US. We use two-step supervised machine learning and data mining to create the data from regulatory documents for social regulations, e.g., environmental regulations, at the 6-digit NAICS level for small and large firms. Regulatory costs have increased by $1 trillion from 1970 to 2018. Small firms face higher costs than large firms even after massive attempts from regulators and politicians to keep the burden on small firms to a minimum. Federal regulations allow us to exploit variation within state-industry-time groups to show that increased regulatory costs result in lower (higher) sales, employment, and markups for small (large) firms. Increased regulations explain 31-37% of the rise in market power.
</small><br><br/></div>


**[The Political Economy of Financial Regulation](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4250919)**\
<a href="https://www.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/professur-haselmann/rainer-haselmann.html" style="color: gray; text-decoration: underline;">Rainer Haselmann</a>, <a href="https://sites.google.com/view/arkodiptasarkar/" style="color: gray; text-decoration: underline;">Arkodipta Sarkar</a>, Shikhar Singla and <a href="https://www.vikrantvig.com/" style="color: gray; text-decoration: underline;">Vikrant Vig</a>\
<small>[ <a href="#/" onclick="visib('pol')">Abstract</a> ]</small>
<div id="pol" style="display: none; text-align: justify; line-height: 1.2" ><small>
Using the negotiation process of the Basel Committee on Banking Supervision (BCBS), this paper studies the way regulators form their positions on regulatory issues in the process of international standard-setting and the consequences on the resultant harmonized framework. Leveraging on leaked voting records and corroborating them using machine learning techniques on publicly available speeches, we construct a unique dataset containing the positions of banks and national regulators on the regulatory initiatives of Basel II and III. We document that the probability of a regulator opposing a specific initiative increases by 30% if their domestic national champion opposes the new rule, particularly when the proposed rule disproportionately affects them. We find the effect is driven by regulators who had prior experience of working in large banks - lending support to the private-interest theories of regulation. Meanwhile smaller banks, even when they collectively have a higher share in the domestic market, do not have any impact on regulators’ stand - providing little support to public-interest theories of regulation.  Finally, we show this decision-making process manifests into significant watering down of proposed rules, thereby limiting the potential gains from harmonization of international financial regulation.
</small><br><br/></div>

## Word Embeddings and Gender Norms

**[Gender Norms Do Not Persist But Converge Across Time](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4183488)**\
Shikhar Singla and <a href="https://www.london.edu/phd/profiles/mayukh-ketan-mukhopadhyay" style="color: gray; text-decoration: underline;">Mayukh Mukhopadhyay</a>\
<small>[ <a href="#/" onclick="visib('gender')">Abstract</a> ]</small>
<div id="gender" style="display: none; text-align: justify; line-height: 1.2" ><small>
We investigate the evolution of gender norms for 160 years in the US. Socioeconomists have posited two fundamental and widely debated theories on the evolution of cultural norms across time. One argues that cultural norms should converge across time as economies become more advanced and integrated, whereas the other states that cultural traits are highly persistent, passed down from generation to generation. These theories remain untested due to a lack of granular and high-frequency data over a longer time period. We develop a novel unsupervised machine learning methodology and apply it to 193 million pages of local newspaper text to produce localised attitudes towards women on four dimensions: career vs family, attitudes towards abortion, attitudes towards feminism/suffrage, and violence against women. We establish novel facts on the evolution of attitudes across time. First, attitudes are less persistent than the existing literature hypothesises. Second, the persistence varies considerably across regions and dimensions. Third, attitudes exhibit cyclical patterns. Fourth, regional variation in attitudes decreases considerably over time and has fallen between 64% to 79%. Fifth, a decrease in transport costs that allows for easier information sharing is associated with a homogenisation of the norms.
</small><br><br/></div>

**[Machine Unlearning Human Biases: Inclusive Word Embeddings by Excluding Biased Text](https://shikharsingla.com/files/debias_ss.pdf)**<br/>
<small>[ <a href="#/" onclick="visib('debias')">Abstract</a> ]</small>
<div id="debias" style="display: none; text-align: justify; line-height: 1.2" ><small>
Word embeddings exhibit biases such as racial and gender biases due to the presence of these biases in the training corpus. Usage of these algorithms can increase the stereotypes in various contexts. We present a simple and generalizable approach of detecting the parts of a corpus that affect the bias and show how removing those parts can debias the word embeddings. The approach finds words that link the target words for a group and biased or attribute words (indirect bias). Unlike prior work, our approach a) removes the biases completely, b) removes indirect bias, and c) can be generalized to any type of bias, downstream task or word embedding model. We apply our methodology on Wikipedia and American National Corpus (ANC) for Word2Vec and GloVe models on the racial and gender biases. It is highly accurate in removing the biases without affecting the performance of the models in capturing semantic information.
</small><br><br/></div>

## Deep Learning and Asset Pricing

**[Human-Centred AI investor Using Deep Generative Models, Reinforcement Learning and Prospect Theory]()**\
<small>[ <a href="#/" onclick="visib('hai')">Abstract</a> ]</small>
<div id="hai" style="display: none; text-align: justify; line-height: 1.2" ><small>
Artificial intelligence (AI) driven personalised portfolio management has not become as widely adopted as some scholars and industry practitioners have predicted. The reason cited is the lack of Artificial Humanity or Human-Centered AI, i.e., the absence of an AI-driven asset manager that maximises value under more psychologically realistic frameworks, such as prospect theory (PT), instead of just focusing on the mean-variance optimisation. Thus, to fully exploit the use of AI in the asset management industry, we need a Human-Centred AI asset manager that: i) has better predictive power, ii) does not have human behavioural biases, which can lead to lower performance, and iii) can maximise utility under prospect theory. However, there are several methodological challenges in designing such an asset manager. First, portfolio optimisation under non-concave functions such as PT is an unsolved problem. Second, we can not use supervised machine-learning techniques as the actual portfolios contain behavioural biases. Third, we need to predict the entire probability distribution of returns, as PT investor cares about the entire probability distribution. I combine deep reinforcement learning with deep generative models (DGM) to overcome these challenges. Reinforcement learning allows the Human-Centred AI investor to handle complicated reward functions and learns how to predict returns through a trial-and-error search. Moreover, as DGMs are fundamentally probabilistic, they can simulate many samples from the conditional distribution of future stock returns. My paper suggests against the weak efficient market hypothesis and shows that a Human-Centred AI asset manager can be constructed that aligns with human preferences while avoiding human biases.
</small><br><br/></div>

**Economic Nowcasting Using Deep Generative Models**<br/>
<small>[ <a href="#/" onclick="visib('nowcast')">Abstract</a> | Draft Coming Soon ]</small>
<div id="nowcast" style="display: none; text-align: justify; line-height: 1.2" ><small>
Economic nowcasting aims to provide predictions that i) are consistent across spatial and temporal dimensions, ii) account for uncertainty and can be verified probabilistically, and iii) perform well on events that are rarer but critical. These characteristics are missing in commonly used deterministic nowcasting methods. Thus these models produce forecasts with higher errors at higher lead times and may not include small-scale yet important patterns. This paper overcomes these challenges by developing a novel deep generative model (DGM). The model is driven by two loss functions defined by spatial and temporal discriminators and a regularisation term. These terms guide parameter adjustment by comparing real observations with model-generated data. The first loss function ensures spatial consistency and discourages errors at higher lead times, whereas the second imposes temporal consistency and penalises jumpy predictions. The regularisation term further improves the accuracy by penalising deviations at the local level. The model architecture is based on stacked Convolutional Gated Recurrent (ConvGRU) Units.
</small><br><br/></div>

**High-Resolution Satellite Imagery, Deep Learning, and Return Predictability**<br/>
<small>[ <a href="#/" onclick="visib('image')">Abstract</a> | Draft Coming Soon ]</small>
<div id="image" style="display: none; text-align: justify; line-height: 1.2" ><small>
The literature has shown that satellite imagery can be used to measure economic conditions. This paper extends this approach by applying convolutional neural networks on establishment-level high-resolution satellite images to predict real-time firm-level cash flows. The paper leverages recently available high-resolution satellite images made publicly available by Google and innovations in neural network architecture to extract the relevant features from the images that predict firms’ cash flows.
</small><br><br/></div>

## Financial Regulation

**[Capital Requirements, Market-Making, and Liquidity](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4250896)**\
<a href="https://www.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/professur-haselmann/rainer-haselmann.html" style="color: gray; text-decoration: underline;">Rainer Haselmann</a>, <a href="https://www.bundesbank.de/en/thomas-kick" style="color: gray; text-decoration: underline;">Thomas Kick</a>, Shikhar Singla and <a href="https://www.vikrantvig.com/" style="color: gray; text-decoration: underline;">Vikrant Vig</a>\
<small>[ <a href="#/" onclick="visib('capital')">Abstract</a> ]</small>
<div id="capital" style="display: none; text-align: justify; line-height: 1.2" ><small>
We employ a proprietary transaction-level dataset in Germany to examine how capital requirements affect the liquidity of corporate bonds. Using the 2011 European Banking Authority capital exercise that mandated certain banks to increase regulatory capital, we find that affected banks reduce their inventory holdings, pre-arrange more trades, and have smaller average trade size. While non-bank affiliated dealers increase their market-making activity, they are unable to bridge this gap - aggregate liquidity declines. Our results are stronger for banks with a higher capital shortfall, for non-investment grade bonds, and for bonds where the affected banks were the dominant market-maker.
</small><br><br/></div>







**[Supranational Supervision]()**\
<a href="https://www.wiwi.uni-frankfurt.de/abteilungen/finance/lehrstuhl/professur-haselmann/rainer-haselmann.html" style="color: gray; text-decoration: underline;">Rainer Haselmann</a>, Shikhar Singla and <a href="https://www.vikrantvig.com/" style="color: gray; text-decoration: underline;">Vikrant Vig</a>\
<small>[ <a href="#/" onclick="visib('supra')">Abstract</a> ]</small>
<div id="supra" style="display: none; text-align: justify; line-height: 1.2" ><small>
It is now common to have separate regulators for larger, more complex and cross-border active financial firms as opposed to smaller financial firms. Exploiting the establishment of a new supranational supervisor responsible for banks larger than € 30 billion in assets in Europe (the Single Supervisory Mechanism SSM), we investigate how separation of supervision impacts regulatory outcomes and risk shifting among banks under the different supervisors. We show that local national regulators are systematically more lenient as compared to the supranational supervisor. Banks under SSM supervision report higher risk weights and a higher probability of default for exposures to the same firm as compared to banks under national supervision. The supranational supervisor tends to be less informed about borrower risk but applies a more standardized treatment across banks and borrowers compared to the national regulator. The differential regulatory treatment results in higher capital charges for affected banks and has a substantial impact on their activities. Affected banks react to the stricter supervision by reducing loans and security holdings compared to banks that do not fall under the scrutiny of the SSM. This reduction is more pronounced in riskier assets which leads to a higher proportion of risky assets being held by smaller non-SSM banks. Matching the credit register with firm-level balance sheet data, we further show that firms receiving loans only from SSM banks exhibit reduced employment, sales and investment compared to other firms.
</small><br><br/></div>

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
