---
layout: page
title:  "Getting Started"
categories: docs
permalink: /vLatest/getting-started/
order: 1
---

## Table of contents
{:.no_toc}

- TOC
{:toc}

## Caliper Introduction

Caliper is a blockchain performance benchmark framework, which allows users to test different blockchain solutions with custom use cases, and get a set of performance test results.

### Supported blockchain solutions

* [Hyperledger Besu](https://github.com/hyperledger/besu)
* [Hyperledger Burrow](https://github.com/hyperledger/burrow)
* [Ethereum](https://github.com/ethereum/)
* [Hyperledger Fabric](https://github.com/hyperledger/fabric)
* [FISCO BCOS](https://github.com/FISCO-BCOS/FISCO-BCOS)
* [Hyperledger Iroha](https://github.com/hyperledger/iroha)
* [Hyperledger Sawtooth](https://github.com/hyperledger/sawtooth-core)

### Supported performance metrics

* Transaction/read throughput
* Transaction/read latency (minimum, maximum, average, percentile)
* Resource consumption (CPU, Memory, Network IO, ...)

See the [PSWG white paper](https://www.hyperledger.org/resources/publications/blockchain-performance-metrics#) for the exact definitions and corresponding measurement methods.  

## Architecture

It helps to have a basic understanding of how Caliper works before diving into the examples. Have a look at the [Architecture](./Architecture.md) page!

## Installing Caliper

Head to the [Install & Usage](./Installing_Caliper.md) page if you want to try Caliper right now. It's as simple as downloading an NPM package or starting a Docker container!

## Sample Networks

Sample benchmarks that may be used by Caliper are hosted on a companion [GitHub repository](https://github.com/hyperledger/caliper-benchmarks).

Performance reports for the provided samples are hosted on the [documentation pages of the repository](https://hyperledger.github.io/caliper-benchmarks/).

## How to Contribute

Every contribution is welcome! See the [Contributing](./CONTRIBUTING.md) page for details.

## License
The Caliper codebase is released under the [Apache 2.0 license](./LICENSE.md). Any documentation developed by the Caliper Project is licensed under the Creative Commons Attribution 4.0 International License. You may obtain a copy of the license, titled CC-BY-4.0, at http://creativecommons.org/licenses/by/4.0/.