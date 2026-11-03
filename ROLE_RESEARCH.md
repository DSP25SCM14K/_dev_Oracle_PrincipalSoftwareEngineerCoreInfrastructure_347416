# Role and company research — Oracle requisition 347416

## Role verified

**Principal Software Engineer, Core Infrastructure** — Job ID 347416; Oracle Cloud Infrastructure Network Modeling and Control team; U.S. locations listed as Seattle, Washington and Santa Clara, California. The posting is for an individual contributor, regular employee, and asks for 7–10+ years of software engineering experience. The linked posting is Oracle's primary source: [Oracle Careers — Job 347416](https://careers.oracle.com/en/sites/jobsearch/job/347416/).

The team builds software that models physical cloud networks, turns infrastructure designs into configured networks, and coordinates expansion and safe operation. The role is an engineering control plane for physical infrastructure: the central problems are durable/consistent network state, concurrent and long-running change workflows, partial failure recovery, rollback, safe rollout, performance, and operational feedback. Its scope crosses network engineering, infrastructure delivery, operations, and adjacent software groups. This is hands-on technical ownership from design through production, plus mentorship—not a people-management position.

## Oracle and OCI context

OCI's AI infrastructure depends on coordinated compute, fabric, storage, and operations. Oracle's AI Infrastructure overview describes bare-metal GPU superclusters and RDMA cluster networking for large AI training and inference. Its published configurations explain why network modeling and lifecycle control matter: scale, bandwidth and low-latency GPU-to-GPU traffic must work as one operational system ([Oracle AI Infrastructure](https://www.oracle.com/ai-infrastructure/)). Oracle's GPU-cluster architecture guide describes the use of RDMA over converged Ethernet (RoCE) and low-latency cluster networking to connect multi-node GPU systems ([Oracle Docs — GPU cluster architecture](https://docs.oracle.com/en/solutions/deploy-bare-metal-gpu-cluster-for-ai/index.html)).

Oracle's October 2026 OCI strategy update says OCI spans more than 200 services and is expanding AI cloud capacity; its network is a foundational component alongside compute and storage ([Building the Next Decade of OCI, Oct. 27, 2026](https://www.oracle.com/news/announcement/blog/ai-world-building-the-next-decade-of-oracle-cloud-infrastructure-2026-10-27/)). In an October 2026 announcement, Oracle and NVIDIA describe the OCI Supercluster as connecting large GPU fleets through Oracle Acceleron and a resilient, multiplanar network, highlighting the continued importance of network reliability as AI infrastructure grows ([Oracle / NVIDIA, Oct. 27, 2026](https://www.oracle.com/apac/news/announcement/ai-world-nvidia-and-oracle-expand-nvidia-vera-rubin-to-multi-gigawatt-scale-2026-10-27/)).

## Role-to-resume evidence

| Role need | Resume evidence |
|---|---|
| Model network topology and intent | Go/Java network modeling service translated designs/topology into intended configuration; Java/C++ control services modeled 2,000+ plant devices. |
| Expand GPU/AI network capacity | AI network capacity turn-up lead time reduced 50%; resume identifies GPU-cluster turn-up as the measured outcome. |
| Coordinate concurrent and long-running changes | Persistent workflow state, idempotent retries, checkpoints and automatic rollback; zero failed rollouts across 300+ workflows. |
| Reconcile intended and observed infrastructure | Controller eliminated drift on 95% of managed resources. |
| Verify correctness before production | TLA+ and model-based verification caught 15+ state-transition defects; fault-injection and partition testing caught 20+ correctness defects. |
| Operate fault-tolerant infrastructure | Replication, leader election, automatic failover, zero-maintenance rolling upgrades; 99.99% availability at Resilience Inc. |
| Improve production performance and operations | Change execution down 45%, MTTR down 40%; config-push latency down 40%; on-call workload down 50%. |
| Lead projects and mentor | Led network expansion for 400+ devices from design to production support; mentored engineers and 4-person engineering group. |
| API and cross-team integration | Versioned gRPC APIs and network models, five partner teams, cross-functional delivery with network engineering and operations. |

## Portfolio content decisions

- The site foregrounds network intent, workflow state, safe rollout, reconciliation, verification, recovery, and operating feedback because those are explicit responsibilities in requisition 347416 and substantiated by the resume.
- The hero network visual is an illustrative topology/change-path graphic with animated signal nodes. It is labeled conceptual; it is not presented as Oracle's internal architecture or live telemetry.
- The project gallery contains the supplied source links and only the four explicitly supplied demo links (TradeSentinel, AskMyStore, Strangers, Oxide-HV). The resume's Keystone and Declarative Reconciliation & Safe Rollout examples receive individual project cards.
- No LinkedIn link or footer is included.

## Sources

1. [Oracle Careers — requisition 347416](https://careers.oracle.com/en/sites/jobsearch/job/347416/) (primary source for responsibilities, experience, team context, and locations).
2. [Oracle AI Infrastructure](https://www.oracle.com/ai-infrastructure/) (OCI AI infrastructure and cluster networking context).
3. [Oracle Docs — Deploy a Bare Metal GPU Cluster for AI Workloads](https://docs.oracle.com/en/solutions/deploy-bare-metal-gpu-cluster-for-ai/index.html) (technical architecture and network context).
4. [Oracle — Building the Next Decade of OCI](https://www.oracle.com/news/announcement/blog/ai-world-building-the-next-decade-of-oracle-cloud-infrastructure-2026-10-27/) (current OCI strategy and scale context).
5. [Oracle / NVIDIA — OCI Supercluster expansion, Oct. 27, 2026](https://www.oracle.com/apac/news/announcement/ai-world-nvidia-and-oracle-expand-nvidia-vera-rubin-to-multi-gigawatt-scale-2026-10-27/) (current AI infrastructure networking context).
