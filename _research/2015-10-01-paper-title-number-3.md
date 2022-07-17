---
title: "Reproducing and Extending Methodically Modeling Tor"
collection: research
permalink: https://reproducingnetworkresearch.files.wordpress.com/2020/06/wilson_perry.pdf
date: 2020-04-01
paperurl: 'https://reproducingnetworkresearch.files.wordpress.com/2020/06/wilson_perry.pdf'

---
This report documents the reproduction of Methodically Modeling the Tor Network for CS 244. While the techniques for generating Tor network models have evolved since 2012, the model presented in the original paper and the reported performance results in Shadow were successfully replicated. We found that the model remains fairly accurate when generated using modern data, and once generated, the model can continue to accurately simulate Tor network performance for up to a year. After reproducing the initial results, we experiment with a much larger download size and find that larger downloads are less accurate than smaller downloads using their model. We then extend their work to account for the increased percentage of video traffic observed on the Internet. By replacing half of the default clients in the simulated network with video clients, we improve model accuracy for larger downloads with little to no adverse effect on smaller downloads.