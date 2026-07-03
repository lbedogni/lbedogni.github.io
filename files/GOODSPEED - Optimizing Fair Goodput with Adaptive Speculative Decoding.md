---
title: "GOODSPEED: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference"
date: 2025-12-10
type: source
source: "https://arxiv.org/abs/2512.09963"
tags: [distributed-inference, speculative-decoding, llm, edge-computing, infocom2026, fairness]
---

# GOODSPEED: Optimizing Fair Goodput with Adaptive Speculative Decoding in Distributed Edge Inference

**arXiv:** 2512.09963  
**Venue:** IEEE INFOCOM 2026  
**Date:** Dec 2025  
**Authors:** Nguyen Hoang Phuong Tran et al.  
**Field:** Distributed Edge Inference, LLM Optimization, Speculative Decoding  
**URL:** https://arxiv.org/abs/2512.09963

## Summary

GOODSPEED is a distributed inference framework designed to accelerate Large Language Model (LLM) inference through **adaptive speculative decoding**. It manages a system where multiple heterogeneous "draft servers" (running small language models) generate token candidates that are then verified by a single, larger central verification server. The framework optimizes "goodput" — the effective rate of accepted tokens — while ensuring **proportional fairness** across the distributed draft servers.

## Key Contributions

- **Adaptive Speculative Decoding**: Coordinates a set of heterogeneous draft servers with a central verification server, moving beyond single-device speculative decoding to a distributed multi-server architecture.

- **Gradient Scheduling Algorithm**: Dynamically assigns verification tasks using a logarithmic utility function to maximize goodput while ensuring proportional fairness across heterogeneous edge servers. This prevents any single server from dominating the verification process.

- **Theoretical Guarantees**: Uses fluid sample path analysis to prove that the system converges to optimal goodput allocation in steady-state and maintains near-optimal performance under dynamic workloads with bounded error.

- **Heterogeneous Edge Support**: Explicitly addresses the challenge of varying computational power across edge devices, making it practical for real-world edge deployments where devices have diverse capabilities.

## Analysis & Relevance

This paper addresses a critical bottleneck in deploying LLMs at the edge: how to use distributed, heterogeneous resources to accelerate inference without sacrificing fairness or efficiency. The focus on "fair goodput" is a sophisticated addition to existing speculative decoding literature, which typically optimizes only for throughput or latency.

**Relevance to Luca's Research:** High. Directly relates to **Distributed Edge Inference** and **Split Computing** by optimizing the interaction between a heavy verifier (potentially a cloud or powerful edge node) and lightweight generators (edge devices). The gradient scheduling approach for fairness in heterogeneous environments aligns with research on resource optimization across the compute continuum.

## Key Concepts

- **Goodput**: The rate of correctly accepted tokens (not just raw throughput)
- **Proportional Fairness**: Resource allocation where no user can increase their utility without proportionally decreasing others' utility
- **Fluid Sample Path Analysis**: A theoretical framework for analyzing stochastic systems by examining their deterministic fluid limits
- **Heterogeneous Draft Servers**: Multiple edge devices with varying compute capabilities contributing speculative tokens in parallel

## Tags

#DistributedEdgeInference #LLM #SpeculativeDecoding #EdgeComputing #INFOCOM2026 #Fairness #Goodput