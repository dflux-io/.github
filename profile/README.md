# dFlux Technologies

**Autonomous infrastructure for 5G Standalone networks.**

Three cloud-native products that test, deploy, and control 5G Standalone networks. Self-configuring, self-healing, and intent-driven — designed to work together or independently.

---

## Products

### FluxProtoLight
Autonomous 5G/4G core testing & validation platform.
- Full 5G SA & 4G core simulation
- Millions of concurrent subscribers
- CI/CD native with YAML test flows
- Performance, security & load testing

### FluxTinyCore
The smallest self-operating 5G Standalone core.
- Just 2 smart NFs: DMF + DPF
- Full 3GPP compliance (R16/R17/R18)
- Under 512 MB RAM footprint
- One-command Docker/K8s deploy

### FluxGate-Proxy
5G signaling security proxy (SSP) for NF protection.
- Targeted NF protection with 5G SBI support
- Built-in Diameter stack for 4G interworking
- Threat detection, persistent audit & compliance
- 10K TPS at 5.6µs latency

---

## Quick Start

Deploy a full 5G SA core with a single command:

```bash
docker run -d \
    --name flux-core \
    -p 38412:38412/sctp \
    -p 2152:2152/udp \
    dflux/tinycore:latest
```

---

## At a Glance

| | |
|---|---|
| **Memory footprint** | 512 MB |
| **Concurrent subscribers** | 1M+ |
| **Deploy to production** | < 5 minutes |
| **3GPP compliance** | R16 / R17 / R18 |
| **Throughput** | 100+ Gbps |

---

## Links

- [Website](https://dflux.io)
- [Documentation](https://dflux.io/docs)
- [Contact](mailto:contact@dflux.io)

---

<sub>&copy; 2026 DFlux Technologies. All rights reserved.</sub>
