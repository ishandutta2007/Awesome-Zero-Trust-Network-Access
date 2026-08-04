# Awesome-Zero-Trust-Network-Access

# Top Zero Trust Network Access (ZTNA) Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Identity-Aware Access, Software-Defined Perimeter, Mesh Networking & VPN Replacement*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Zero Trust Network Access (ZTNA)**. These tools replace or augment traditional VPNs by providing identity-based, least-privilege access to applications and resources without placing users on the full network, supporting continuous verification, device posture, and micro-segmentation.

**Examples** include Cloudflare Access, Zscaler Private Access, Tailscale, NordLayer, Perimeter 81, Palo Alto Prisma Access, Netskope Private Access, OpenVPN Cloud / CloudConnexa, GoodAccess, Appgate SDP, Cisco Duo Beyond / Secure Access, Teleport, Cato Networks, and OpenZiti (the category leaders and notable players).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting mesh VPNs, identity-aware proxies, application-embedded zero-trust overlays, and coordination servers — ideal for security teams, DevOps, and organizations seeking data sovereignty, cost control, and transparent zero-trust architectures.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cloudflare Access](https://www.cloudflare.com/zero-trust/products/access/)**  
  Globally distributed ZTNA service (part of Cloudflare One) that protects internal web apps, SSH, RDP, and private networks with identity-aware policies and clientless options.

- **[Zscaler Private Access (ZPA)](https://www.zscaler.com/products/zscaler-private-access)**  
  Enterprise ZTNA platform that brokers app-specific access through the Zero Trust Exchange, designed for large-scale VPN replacement and strong segmentation.

- **[Tailscale](https://tailscale.com/)**  
  WireGuard-based mesh networking with simple identity-aware ACLs, device posture integrations, and excellent developer experience for private connectivity.

- **[NordLayer](https://nordlayer.com/)**  
  Business-focused ZTNA and secure network access solution from Nord Security, emphasizing ease of deployment for mid-market teams.

- **[Perimeter 81 (Check Point)](https://www.perimeter81.com/)**  
  Cloud-based zero-trust network access and SASE-oriented platform for secure remote access and network segmentation (acquired by Check Point).

- **[Palo Alto Prisma Access](https://www.paloaltonetworks.com/sase/prisma-access)**  
  Cloud-delivered ZTNA and SASE platform tightly integrated with Palo Alto security controls, GlobalProtect, and Prisma Access Browser.

- **[Netskope Private Access](https://www.netskope.com/)**  
  Enterprise ZTNA component of the Netskope One platform, focused on application-level access, data security depth, and SSE convergence.

- **[OpenVPN Cloud / CloudConnexa](https://openvpn.net/cloud-connexa/)**  
  Cloud-managed ZTNA and secure networking built on OpenVPN technology for private access and site-to-site connectivity.

- **[GoodAccess](https://www.goodaccess.com/)**  
  User-friendly ZTNA and zero-trust network access platform aimed at mid-market and distributed teams.

- **[Appgate SDP](https://www.appgate.com/)**  
  Software-defined perimeter pioneer offering enterprise ZTNA with strong identity-centric access and on-premises/cloud deployment options.

- **[Cisco Duo Beyond / Secure Access](https://www.cisco.com/)**  
  Identity and access capabilities within Cisco’s broader security portfolio for zero-trust remote access and MFA-enforced connectivity.

- **[Teleport](https://goteleport.com/)**  
  Identity-aware access platform for infrastructure (SSH, Kubernetes, databases, web apps) with short-lived certificates and strong audit capabilities (commercial + open-source core).

- **[Cato Networks](https://www.catonetworks.com/)**  
  Converged SASE platform that includes ZTNA as part of its cloud-native networking and security fabric.

- **[OpenZiti / NetFoundry](https://netfoundry.io/)**  
  Commercial offering built on the open-source OpenZiti platform for embedded, identity-first zero-trust networking and dark services.

## Open-Source GitHub Projects

- **[OpenZiti](https://openziti.io/)** / [GitHub](https://github.com/openziti/ziti)**  
  Full open-source (Apache 2.0) zero-trust overlay network. Identity-based, application-embeddable SDKs, outbound-only “dark” services, no open inbound ports. Strong alternative to commercial ZTNA for app-level zero trust.

- **[NetBird](https://netbird.io/)** / [GitHub](https://github.com/netbirdio/netbird)**  
  Fully open-source WireGuard-based mesh VPN and ZTNA platform with management UI, SSO, granular ACLs, and self-hosting support. Closest complete open-source alternative to Tailscale.

- **[Headscale](https://github.com/juanfont/headscale)**  
  Open-source implementation of the Tailscale control/coordination server. Allows running official Tailscale clients against a fully self-hosted control plane (BSD-licensed).

- **[Teleport (Community / Open Source)](https://github.com/gravitational/teleport)**  
  Open-source identity-aware access proxy for SSH, Kubernetes, databases, and web applications with certificate-based auth and audit logging (Apache 2.0 core; advanced features commercial).

- **[Pomerium](https://www.pomerium.com/)** / [GitHub](https://github.com/pomerium/pomerium)**  
  Open-source identity-aware proxy (IAP) that enforces continuous verification for web applications and TCP services based on identity, device, and context.

- **[Netmaker](https://netmaker.io/)** / [GitHub](https://github.com/gravitl/netmaker)**  
  Open-source WireGuard mesh networking platform with site-to-site routing, relays, and management features for building private overlay networks.

- **[Firezone](https://www.firezone.dev/)** / [GitHub](https://github.com/firezone/firezone)**  
  Open-source WireGuard-based remote access and ZTNA solution with modern UI, SSO, and self-hosting focus.

- **[Octelium](https://octelium.com/)** / [GitHub](https://github.com/octelium/octelium)**  
  Next-generation fully open-source, self-hosted unified zero-trust platform that can act as ZTNA, remote-access VPN, API/AI gateway, and BeyondCorp-style access layer.

- **[Nebula](https://github.com/slackhq/nebula)**  
  Lightweight, certificate-based overlay networking tool (originally from Slack) for creating scalable, encrypted mesh networks with strong identity controls (MIT).

- **[ZeroTier](https://www.zerotier.com/)** / open-source components  
  Software-defined networking platform with open-source clients and self-hostable controller options for virtual L2/L3 networks and flow-based access control.

### Additional Strong Open-Source Options

- **WireGuard**-based management UIs and helpers (wg-easy and similar) for simpler self-hosted setups.
- **Pangolin** and other identity-aware reverse-proxy / tunneled access projects.
- Community coordination servers, DERP/relay alternatives, and policy engines that complement Headscale or NetBird.
- SDK-focused zero-trust libraries and embedded overlays for application-level security.
- Integration projects combining open ZTNA with OIDC/Keycloak, device posture tools, and SIEM logging.

**Frameworks for building custom systems**: Combine **OpenZiti** (app-embedded or tunnelers) or **NetBird/Headscale** (mesh) with **Pomerium/Teleport** (identity-aware proxies), **OIDC providers**, device posture agents, and policy-as-code. Add observability via OpenTelemetry and central policy engines for a complete self-hosted zero-trust stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ZTNA solutions must align with your organization’s security policies, compliance requirements (e.g., zero-trust architecture principles, NIST SP 800-207), and operational needs.
- Self-hosted open-source solutions require proper hardening, high availability, key/certificate management, logging, and ongoing maintenance. Evaluate thoroughly for production use, especially regarding identity integration, device posture, and lateral-movement controls.

---

**Made for security engineers, platform teams, DevOps, CISOs, and zero-trust practitioners.**  
Let's make secure access more open, identity-centric, and resilient.
