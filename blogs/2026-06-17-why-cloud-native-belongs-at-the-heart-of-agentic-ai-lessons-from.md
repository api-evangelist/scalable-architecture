---
title: "Why cloud native belongs at the heart of agentic AI: Lessons from building a multi-agent security platform on Kubernetes"
url: "https://www.cncf.io/blog/2026/06/17/why-cloud-native-belongs-at-the-heart-of-agentic-ai-lessons-from-building-a-multi-agent-security-platform-on-kubernetes/"
date: "2026-06-17"
author: "Willem Berroubache"
feed_url: "https://www.cncf.io/blog/feed/"
---
Lessons from building an internal real-time security-operations platform protecting a regulated production environment using Kubernetes-based agents. Key practices include deploying each agent as its own workload, using cert-manager for inter-agent mTLS, enforcing safety constraints through OPA policies rather than LLM prompts, and running an anomaly-detection model as a gatekeeper before LLM invocation to control costs.
