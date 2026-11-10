# Omer Oz

- [email](mailto:to@OmerOz.fyi)
- [linkedin](https://linkedin.com/in/omer25oz)

## KubeCon NA 2026: The Hidden Critical Path

Nov 11 • 2:20 PM-2:50 PM
Salt Palace | Level 1 | Grand Ballroom H

Pod startup latency directly impacts service responsiveness, autoscaling speed, and incident recovery on Kubernetes. Yet much of that latency is dominated by the image pull step; which is mostly hidden.

Drawing on a real LinkedIn production case study — over 500K bare-metal hosts, 25M cores, and pod density averaging beyond 50 per host in our densest clusters — we’ll show how we cut the long tail of pod startup latency by 3.6x through reducing image pull latency by 72% at P99 and 75% at P50. We'll examine how container image pulls contribute to startup latency: taking a deep dive into the image pull path to identify bottlenecks and build a mental model, then covering the practical levers we have — compression, kubelet and containerd configuration, and P2P caching.

- [Slides](2026/)
- [The Hidden Critical Path: An Incremental Analysis of Container Image Pull Bottlenecks in containerd](https://github.com/omerXfaruq/the-hidden-critical-path/blob/main/PAPER.md)
- [Containerize the Weights: Simple, Lightning-Fast Model Deployment on NVIDIA DGX Clusters](https://github.com/omerXfaruq/kbcn/blob/master/misc/poster.pdf)

