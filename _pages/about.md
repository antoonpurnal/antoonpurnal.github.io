---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Silicon Security Engineer at Google. Before that, I was a Senior Product Security Analyst at [PQShield](https://pqshield.com/).
Before that, I obtained my PhD degree, entitled ["Cache Side-Channel Attacks on Existing and Emerging Computing Platforms"]({{ site.url }}/files/pdf/PhDThesis.pdf), at the [COSIC](https://esat.kuleuven.be/cosic/) group at [KU Leuven](https://kuleuven.be/english/) in June 2023. During the summer of 2022, I interned at Intel Labs.

My professional interests are centered around {microarchitectural,software,hardware} security, as well as engineering efficient and secure cryptographic implementations.

In 2024, I found an exploitable (compiler-introduced) timing side-channel vulnerability in several implementations of ML-KEM ([blog](https://pqshield.com/pqshield-plugs-timing-leaks-in-kyber-ml-kem-to-improve-pqc-implementation-maturity/), [code](https://github.com/antoonpurnal/clangover)).

# Selected Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
# Reviewing
- TCHES 2024
- External: USENIX Security 2023, 2022, 2021, 2020, 2019
- External: COSADE 2022
- External: IEEE EuroS&P 2021
- External: HOST 2020
- External: ESSCIRC 2019
