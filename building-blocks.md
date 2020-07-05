---
layout: page
title: Building blocks
subtitle: This is what we have already built
permalink: /building-blocks/
hero_image: /assets/llavors-mutues.jpg
---

# Transactors

Transactors are holochain zomes that implement mutual-credit transaction behaviour. They include entry and links definition, their validation rules and the peer-to-peer interaction necessary for the transactions to take place.

### Private pessimistic transactor 

[**Github repository**](https://github.com/llavors-mutues/private-slow-transactor)

**Status**: working proof of concept, with a few known issues and security audits still needed.

In this zome, transactions are private between participants of the DNA, and agents validate each other's source chains only at the time of executing the transaction. 

In this peer-to-peer validation, it takes a slow or pessimistic approach about the counterparty validity, to make sure they didn't roll back their source chain.

# UI

Web Components using native custom-elements and GraphQl middleware packaged as a reusable module.

[**Github repository**](https://github.com/llavors-mutues/private-slow-transactor/blob/master/ui)

**Status**: proof of concept working, needs polishing.

You can see a demo of the UI we have already built [here](https://youtu.be/7_VhMTXxr24?t=1546).

