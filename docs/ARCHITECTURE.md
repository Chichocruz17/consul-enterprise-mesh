# Consul Enterprise Service Mesh Architecture

```mermaid
graph TD;
    A["Virtual Machines (VMs)"]
    B["Mesh Gateways"]
    C["Ingress Gateways"]
    D["Egress Gateways"]
    E["HAProxy"]
    F["On-Premise Deployment Topology"]

    A --> B
    B --> C
    B --> D
    C --> E
    D --> E
    E --> F
```

## Overview
This document provides a visual representation of the architecture of the Consul Enterprise Service Mesh. The diagram illustrates how different components such as VMs, Mesh Gateways, Ingress Gateways, Egress Gateways, and HAProxy interact within an on-premise deployment.
