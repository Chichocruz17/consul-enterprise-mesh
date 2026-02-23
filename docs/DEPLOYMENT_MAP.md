# Deployment Map

This document provides an on-premise deployment topology mapping for the Consul Enterprise Mesh.

## Overview
- **Purpose:** To outline the structure and components involved in the on-premise deployment.
- **Components:** 
  - **Consul Server**: Manages the service discovery and configuration.
  - **Consul Client**: Runs on each node and registers with the Consul server.
  - **Services**: The individual applications or services that are being deployed.

## Topology Mapping
1. **Consul Server Nodes**
   - Node 1: IP Address / DNS
   - Node 2: IP Address / DNS
   - Node 3: IP Address / DNS

2. **Consul Client Nodes**
   - Node A: IP Address / DNS
   - Node B: IP Address / DNS

3. **Service Deployments**
   - **Service 1**: Description of Service 1
   - **Service 2**: Description of Service 2

## Notes
- All nodes should be configured with proper security settings.
- Ensure that the proper firewall rules are set to allow communication between the nodes.