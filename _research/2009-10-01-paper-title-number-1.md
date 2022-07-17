---
title: "Strong Anonymity for Mesh Messaging"
collection: research
permalink: https://arxiv.org/abs/2207.04145
date: 2022-07-08
paperurl: 'https://arxiv.org/abs/2207.04145'
---
Messaging systems built on mesh networks consisting of smartphones communicating over Bluetooth have been used by protesters around the world after governments have disrupted Internet connectivity. Unfortunately, existing systems have been shown to be insecure; most concerningly by not adequately hiding metadata. This is further complicated by the fact that wireless communication such as Bluetooth is inherently a broadcasting medium. In this paper, we present a new threat model that captures the security requirements of protesters in this setting. We then provide a solution that satisfies the required security properties, hides all relevant metadata, scales to moderately sized protests, and supports group messaging. This is achieved by broadcasting all messages in a way that limits the overhead of duplicate messages, ensuring that ciphertexts do not leak metadata, and limiting what can be learned by observing user behavior. We also build a model of our system and numerically evaluate it to support our claims and analyze how many users it supports. Finally, we discuss further extensions that remove potential bottlenecks in scaling and support substantially more users. 