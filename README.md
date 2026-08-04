![Banner](assets/banner.svg)
# Awesome-Zero-Trust-Network-Access

## Top Zero Trust Network Access (ZTNA) Tools Ecosystem

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

| Product | Description | Pricing | Free Tier Limit |
|---------|-------------|---------|-----------------|
| **[Cloudflare Access](https://www.cloudflare.com/zero-trust/products/access/)** | Globally distributed ZTNA service (part of Cloudflare One) that protects internal web apps, SSH, RDP, and private networks with identity-aware policies and clientless options. | $7/user/mo | Up to 50 users |
| **[Zscaler Private Access (ZPA)](https://www.zscaler.com/products/zscaler-private-access)** | Enterprise ZTNA platform that brokers app-specific access through the Zero Trust Exchange, designed for large-scale VPN replacement and strong segmentation. | Custom | N/A |
| **[Tailscale](https://tailscale.com/)** | WireGuard-based mesh networking with simple identity-aware ACLs, device posture integrations, and excellent developer experience for private connectivity. | $6/user/mo | Up to 3 users, 100 devices |
| **[NordLayer](https://nordlayer.com/)** | Business-focused ZTNA and secure network access solution from Nord Security, emphasizing ease of deployment for mid-market teams. | From $8/user/mo | N/A |
| **[Perimeter 81 (Check Point)](https://www.perimeter81.com/)** | Cloud-based zero-trust network access and SASE-oriented platform for secure remote access and network segmentation (acquired by Check Point). | From $8/user/mo | N/A |
| **[Palo Alto Prisma Access](https://www.paloaltonetworks.com/sase/prisma-access)** | Cloud-delivered ZTNA and SASE platform tightly integrated with Palo Alto security controls, GlobalProtect, and Prisma Access Browser. | Custom | N/A |
| **[Netskope Private Access](https://www.netskope.com/)** | Enterprise ZTNA component of the Netskope One platform, focused on application-level access, data security depth, and SSE convergence. | Custom | N/A |
| **[OpenVPN Cloud / CloudConnexa](https://openvpn.net/cloud-connexa/)** | Cloud-managed ZTNA and secure networking built on OpenVPN technology for private access and site-to-site connectivity. | From $3/connection/mo | Up to 3 connections |
| **[GoodAccess](https://www.goodaccess.com/)** | User-friendly ZTNA and zero-trust network access platform aimed at mid-market and distributed teams. | From $5/user/mo | Up to 100 users (Starter) |
| **[Appgate SDP](https://www.appgate.com/)** | Software-defined perimeter pioneer offering enterprise ZTNA with strong identity-centric access and on-premises/cloud deployment options. | Custom | N/A |
| **[Cisco Duo Beyond / Secure Access](https://www.cisco.com/)** | Identity and access capabilities within Cisco’s broader security portfolio for zero-trust remote access and MFA-enforced connectivity. | From $3/user/mo | Up to 10 users (Duo Free) |
| **[Teleport](https://goteleport.com/)** | Identity-aware access platform for infrastructure (SSH, Kubernetes, databases, web apps) with short-lived certificates and strong audit capabilities (commercial + open-source core). | Custom | Community Edition (Open Source) |
| **[Cato Networks](https://www.catonetworks.com/)** | Converged SASE platform that includes ZTNA as part of its cloud-native networking and security fabric. | Custom | N/A |
| **[OpenZiti / NetFoundry](https://netfoundry.io/)** | Commercial offering built on the open-source OpenZiti platform for embedded, identity-first zero-trust networking and dark services. | Custom | Up to 10 endpoints |

## Open-Source GitHub Projects

- **[Headscale](https://github.com/juanfont/headscale)** [![Stars](https://img.shields.io/github/stars/juanfont/headscale?style=social&color=white)](https://github.com/juanfont/headscale/stargazers)  
  Open-source implementation of the Tailscale control/coordination server...

- **[Authelia](https://github.com/authelia/authelia)** [![Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white)](https://github.com/authelia/authelia/stargazers)  
  The Single Sign-On Multi-Factor portal for web apps...

- **[NetBird](https://github.com/netbirdio/netbird)** [![Stars](https://img.shields.io/github/stars/netbirdio/netbird?style=social&color=white)](https://github.com/netbirdio/netbird/stargazers)  
  Fully open-source WireGuard-based mesh VPN...

- **[Authentik](https://github.com/goauthentik/authentik)** [![Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers)  
  The authentication glue you need. Open source Identity Provider...

- **[Teleport](https://github.com/gravitational/teleport)** [![Stars](https://img.shields.io/github/stars/gravitational/teleport?style=social&color=white)](https://github.com/gravitational/teleport/stargazers)  
  Open-source identity-aware access proxy...

- **[Nebula](https://github.com/slackhq/nebula)** [![Stars](https://img.shields.io/github/stars/slackhq/nebula?style=social&color=white)](https://github.com/slackhq/nebula/stargazers)  
  Lightweight, certificate-based overlay networking tool...

- **[ZeroTier](https://github.com/zerotier/ZeroTierOne)** [![Stars](https://img.shields.io/github/stars/zerotier/ZeroTierOne?style=social&color=white)](https://github.com/zerotier/ZeroTierOne/stargazers)  
  Software-defined networking platform...

- **[Netmaker](https://github.com/gravitl/netmaker)** [![Stars](https://img.shields.io/github/stars/gravitl/netmaker?style=social&color=white)](https://github.com/gravitl/netmaker/stargazers)  
  Open-source WireGuard mesh networking platform...

- **[Firezone](https://github.com/firezone/firezone)** [![Stars](https://img.shields.io/github/stars/firezone/firezone?style=social&color=white)](https://github.com/firezone/firezone/stargazers)  
  Open-source WireGuard-based remote access...

- **[Innernet](https://github.com/tonarino/innernet)** [![Stars](https://img.shields.io/github/stars/tonarino/innernet?style=social&color=white)](https://github.com/tonarino/innernet/stargazers)  
  A private network system that uses WireGuard under the hood...

- **[Pomerium](https://github.com/pomerium/pomerium)** [![Stars](https://img.shields.io/github/stars/pomerium/pomerium?style=social&color=white)](https://github.com/pomerium/pomerium/stargazers)  
  Open-source identity-aware proxy (IAP)...

- **[OpenZiti](https://github.com/openziti/ziti)** [![Stars](https://img.shields.io/github/stars/openziti/ziti?style=social&color=white)](https://github.com/openziti/ziti/stargazers)  
  Full open-source (Apache 2.0) zero-trust overlay network...


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
