---
layout: writing
---


<a href="/" class="site-logo">
    <img src="/s-transparent.png" alt="suriyah.dev logo">
</a>

<div class="writing-header">
    <h1>technical papers</h1>
    <div class="author-block">
        <span class="author-name">suriyah saravanan</span>
        <div class="author-creds">
            <span>BBA in management information systems, cybersecurity</span>
            <span class="divider">•</span>
            <span>florida atlantic university</span>
            <span class="divider">•</span>
            <span>3.9 department gpa</span>
        </div>
    </div>
  
</div>

welcome to my FAU research paper library. this site hosts whitepapers and deepdives into systems architecture, cybersecurity concepts, and the future of technology

---

## featured papers

### [evolution of network perimeter defense: a comprehensive analysis of firewalls and VPNs](./essays/firewall-vpn.md)
*an exploration of the shift from physical boundaries to identity-based security frameworks in the age of AI-driven persistence*

* **strategic scope:** investigates the transition from stateless packet filtering to Layer 7 Deep Packet Inspection (DPI) and the necessity of **Next-Generation Firewalls (NGFW)**
* **the zero trust pivot:** evaluates the integration of **Secure Access Service Edge (SASE)** and ZT-VPNs to neutralize generative AI-enhanced phishing and multi-stage botnet attacks
* **real-world application:** contextualizes defense-in-depth strategies through the lens of municipal public safety, focusing on the mission-critical availability of fire-rescue IT infrastructure
* **future threats:** addresses the "Harvest Now, Decrypt Later" mindset of modern threat actors and the emerging requirement for **Post-Quantum Cryptography (PQC)** standards

---

### [the vulnerabilities of virtualization: an analysis of cloud security](./essays/cloud-security.md)
*a deep-dive into the security misalignment caused by rapid cloud adoption and the transition from CapEx-heavy hardware to OpEx-driven virtual environments*

* **architectural critique:** analyzes the **Shared Responsibility Model** and the common pitfalls of migrating from on-premise infrastructure to Infrastructure as a Service (IaaS) and Software as a Service (SaaS)
* **identity as the new perimeter:** examines **Identity and Access Management (IAM)** failures, specifically the critical role of the **Principle of Least Privilege (PoLP)** and Multi-Factor Authentication (MFA) in neutralizing credential theft and privilege escalation
* **API & microservice security:** breaks down the fundamental "glue" of the cloud - Application Programming Interfaces (APIs) - with a focus on **Broken Object Level Authorization (BOLA)** and the cascading effects of supply chain risks
* **human-centric vulnerabilities:** addresses the gap between automated cloud tools and the human element, arguing that "misconfigurations" are often a symptom of organizational oversight rather than technical failure

---

### [network design proposal: H&M boutique law firm](./essays/network-design-proposal.md)
*a comprehensive infrastructure design for a specialized legal practice, prioritizing high-availability, the CIA Triad, and fiscal optimization*

* **architectural framework:** implementation of a centralized **Star Topology** and Main Distribution Frame (MDF) to ensure fault isolation and seamless organizational scalability
* **network segmentation:** utilization of **IEEE 802.1Q VLANs** to logically isolate guest wireless traffic from sensitive corporate tax records
* **redundancy & fault tolerance:** integration of **RAID 1 (Mirroring)**, Dual-WAN failover (Fiber/5G), and UPS battery bridges to achieve a "zero-downtime" mission-critical environment
* **fiscal responsibility:** successfully engineered a full-stack enterprise solution, including security gateways and Active Directory servers, within a **$10,000 capital expenditure budget**

---

## tech stack
* **infrastructure & hosting:** deployed via **GitHub Pages** on my custom domain (`suriyah.dev`)
* **markup & styling:** written in **Markdown**, processed by **Jekyll**, and styled with custom responsive **CSS**
* **version control:** continuous deployment and revision tracking managed via **Git** and **GitHub Actions**
