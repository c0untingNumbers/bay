---
layout: post
title:  "The Line Between Adversarial ML and CFAA"
date:   2024-09-12 13:37:00
blurb: "The Line Between Adversarial ML and CFAA"
og_image: /assets/img/content/adversarial-ml.png
---
<img src="{{ "/assets/img/content/adversarial-ml.png" | absolute_url }}" class="post-pic"/>
<br />

## Background
I wrote and presented this blog post for my PUBL-363 Cyber Security Policy and Law class at Rochester Institute of Technology in the Fall semester of 2024. 
## Introduction
# CAAA and CFAA
The Computer Fraud And Abuse Act (CFAA) was enacted in 1986 as part of the Comprehensive Crime Control Act (CCCA) passed by Congress in 1984. The CFAA introduced one of the earliest federal computer crime statutes which covered the conduct of a person who “accesses a computer without authorization, or, with authorization, uses the opportunity such access provides to obtain information beyond the scope of that authorization.”

The passing of CFAA expanded these statutes by providing additional penalties for fraud-related cases on connections to government computers. It was not until 1994 that Congress amended a civil cause, which allowed private parties to claim compensation for the damages, and expanded on the scope of conduct to prohibit “transmission of a program, information, code, or command.”

A key issue with the CFAA we have nowadays is that there are divided opinions on what “exceeds authorized access” really means. By dividing, there is a 4-3 split among the circuit courts of appeals across the United States. The four of them interpreted the term “exceeds authorized access” more broadly as breaching a policy, agreement, or terms of service. The other three used a strict interpretation where accessing information for an improper purpose, while no more than that, does not violate the definition of “exceeds authorized access.”
# Adversarial Machine Learning
Adversarial machine learning (Adversarial ML) is a study of the attacks on machine learning. The common issue among machine learning is that their techniques are designed to work on a problem-focused set that involves specific statistics and the users can just supply data that the machine learning model was not intended for and fail.

One example of this can be that with simple stickers, the researchers made the Tesla’s self-driving system swerve off the highway.
## Adversarial ML and CFAA
# Blurring The Line
At what point is it when adversarial ML is crossing into the legal risk boundaries of the CFAA?

Using the attack known as data poisoning where a company is scraping data to use for training its models, and someone injects malicious data into this data, this would constitute as an unauthorized manipulation. The damage, as described by the CFAA, includes “any impairment to the integrity or availability of data, a program, a system, or information.” It can also be considered a “transmission of a program, information, code, or command” if the malicious training data were to have a specially crafted backdoor.

On the other hand with data evasion, when using a fully developed machine learning model, such as a code completion or automatic programming tool, if a user requests a computer worm source code, this would not necessarily violate the strict interpretation of “exceeds authorized access,” as there was no barrier or authentication involved.
# Liability Of Adversarial ML
Another issue arises if you need to consider who is liable when machine learning breaks down. As machine learning is somewhat of a new thing and becoming mainstream, there is not an established standard framework for protecting these adversarial attacks.
## Conclusion
The intersection of adversarial ML and the CFAA does reveal a relationship between emerging technology and straggling legal frameworks. Even though adversarial machine learning techniques, such as data poisoning, can pose certain risks to system security, the legal interpretation of “exceeds authorized access” is somewhat paradoxical as other adversarial attacks, like data evasion, may not fall under the same legal interpretation. This highlights a gap in legal protections that needs to be closed and calls for a more strict legal framework that addresses these threats while additionally providing a clearer guideline for prosecution and prevention.
## References
“NACDL – CFAA Background.” _NACDL – National Association of Criminal Defense Lawyers_, 14 July 2022, [www.nacdl.org/Content/CFAABackground](http://www.nacdl.org/Content/CFAABackground).

‌Vassilev, Apostol. _Adversarial Machine Learning:_ 2024, nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf, [https://doi.org/10.6028/nist.ai.100-2e2023](https://doi.org/10.6028/nist.ai.100-2e2023).

Kumar, Ram Shankar Siva, et al. “Legal Risks of Adversarial Machine Learning Research.” _ArXiv.org_, 29 June 2020, [arxiv.org/abs/2006.16179](http://arxiv.org/abs/2006.16179).

Kumar, et al. “Law and Adversarial Machine Learning.” _ArXiv.org_, 2018, [arxiv.org/abs/1810.10731](http://arxiv.org/abs/1810.10731).

Fujiwara, Takanori, et al. “Adversarial Attacks on Machine Learning-Aided Visualizations.” _ArXiv.org_, 2024, [arxiv.org/abs/2409.02485](http://arxiv.org/abs/2409.02485).

(Image)“Adversarial Machine Learning Tutorial.” _Toptal Engineering Blog_, [www.toptal.com/machine-learning/adversarial-machine-learning-tutorial](http://www.toptal.com/machine-learning/adversarial-machine-learning-tutorial).