---
title: "Tuning Wowza Streaming Engine for High-Concurrency CPU-Based Transcoding"
url: "https://www.wowza.com/blog/tuning-wowza-streaming-engine-for-high-concurrency-cpu-based-transcoding"
date: "2026-08-20"
author: "Tim Dougherty"
feed_url: "https://www.wowza.com/feed"
---
Five checks for transcoding many concurrent streams to WebRTC on CPU-only Wowza Streaming Engine deployments, covering decoder implementation, codec pairing, resolution sizing, JVM and allocator tuning, and horizontal scaling. What makes or breaks a high-concurrency WebRTC streaming workflow? A containerized Wowza Streaming Engine instance can run on 4 vCPUs and 8 GB of RAM with no GPU attached.
