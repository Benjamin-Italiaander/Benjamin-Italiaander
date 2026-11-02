<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Benjamin%20Italiaander&fontSize=50&fontColor=ffffff&fontAlignY=36&desc=Senior%20Linux%20%26%20Network%20Engineer%20%C2%B7%20Open%20Infrastructure%20%C2%B7%20Local%20AI&descAlignY=58&descSize=17&animation=fadeIn" width="100%" alt="Benjamin Italiaander — Senior Linux & Network Engineer" />

<a href="https://github.com/Benjamin-Italiaander">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=900&color=36BCF7&center=true&vCenter=true&width=680&lines=Building+the+infrastructure+that+should+already+exist.;EVPN%2FVXLAN+fabrics+%C2%B7+BGP+%C2%B7+Leaf-Spine;Linux+%C2%B7+Kubernetes+%C2%B7+Infrastructure+as+Code;NVIDIA+DGX+%C2%B7+Mellanox+%C2%B7+RoCEv2+%C2%B7+Local+AI;Post-quantum+ready.+Vendor+lock-in+free.;Own+your+data%2C+or+someone+else+will." alt="Typing SVG" />
</a>

<br/>

![Location](https://img.shields.io/badge/📍_Western_Europe-NL_·_BE_·_DE-003399?style=for-the-badge&labelColor=0d1117)
![Linux](https://img.shields.io/badge/Linux-Fanatic-FCC624?style=for-the-badge&logo=linux&logoColor=black&labelColor=0d1117)
![Open Source](https://img.shields.io/badge/Open_Source-Advocate-3DA639?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=0d1117)
![Sovereignty](https://img.shields.io/badge/🇪🇺_Digital-Sovereignty-003399?style=for-the-badge&labelColor=0d1117)
![Profile views](https://komarev.com/ghpvc/?username=Benjamin-Italiaander&style=for-the-badge&color=36BCF7&label=👀+VISITORS&labelColor=0d1117)

<br/>

<h3>
  I design and build networks, Linux platforms and AI infrastructure<br/>
  that organizations can <b>own</b> — not rent.
</h3>

</div>

<br/>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## 🐧 About Me

<img align="right" width="290" src="https://skillicons.dev/icons?i=linux,ubuntu,debian,bash,python,docker,kubernetes,git,gitlab,githubactions,jenkins,nginx,grafana,pytorch,vim&perline=5" alt="Tech icons" />

I'm a **Senior Linux & Network Engineer** who designs, builds and runs **secure, scalable, high-performance infrastructure** for **research institutes, universities and government organizations** across the Netherlands, Belgium and Germany.

From the datacenter fabric to the GPU, I work across the full stack. That means **EVPN/VXLAN leaf-spine networks**, hardened Linux platforms, virtualization and containers, identity and access management, and the automation that holds it all together.

At [**CWI**, the National Research Institute for Mathematics and Computer Science](https://www.cwi.nl/en/), I have the freedom and resources to build **experimental environments at real scale**. I use them to test new network architectures, put emerging technologies under load, and turn research ideas into infrastructure that works in production.

Right now I'm focused on **NVIDIA Mellanox networking, DGX platforms and local AI**, including combining **NVIDIA DGX Spark with Exo** to build decentralized, privacy-first AI that never leaves the building.

And when life gets too predictable, I break my homelab on purpose to learn how to rebuild it better. 🔧

<br clear="right"/>

<table>
<tr>
<td>🔭 <b>Building</b></td><td>Sovereign, self-hosted platforms for research &amp; government</td>
</tr>
<tr>
<td>🧠 <b>Exploring</b></td><td>DGX Spark + Exo for distributed, privacy-first local AI</td>
</tr>
<tr>
<td>🔐 <b>Researching</b></td><td>Post-quantum cryptography: hybrid SSH key exchange, OpenPGP &amp; age</td>
</tr>
<tr>
<td>🌐 <b>Fabric-ing</b></td><td>EVPN/VXLAN, RoCEv2 &amp; InfiniBand for GPU clusters</td>
</tr>
<tr>
<td>🌿 <b>Living by</b></td><td><a href="https://github.com/Benjamin-Italiaander/My_Notes/blob/main/slices_of_life/reminders/EN/joy_of_missig_out.md">The Joy of Missing Out (JOMO)</a></td>
</tr>
</table>

---

<!-- ═══════════════════════════ COMPETENCIES ═══════════════════════════ -->
## 🎯 Core Competencies

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Datacenter Networking
**Fabrics that don't fall over.**<br/>
Layer 2/Layer 3 design, BGP and OSPF routing, EVPN/VXLAN overlays, and resilient leaf-spine Ethernet fabrics built for high throughput and fast convergence.

</td>
<td width="50%" valign="top">

### 🐧 Linux Engineering
**From kernel to cluster.**<br/>
Enterprise Linux, virtualization, storage, distributed systems, performance tuning, and high-availability architectures that stay understandable.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Automation & DevOps
**If it's done twice, it's code.**<br/>
Containers, orchestration, configuration management, GitOps workflows, and zero-touch provisioning from bare metal up.

</td>
<td width="50%" valign="top">

### 🔐 Security & Identity
**Zero Trust by design, not as an afterthought.**<br/>
Network segmentation, MACsec and IPsec, PKI and certificate management, strong authentication, and identity-centric access control.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚀 AI Infrastructure & HPC
**GPUs need networks that keep up.**<br/>
NVIDIA DGX, Mellanox, RDMA/RoCEv2, GPU acceleration, deep learning containers, and distributed local inference.

</td>
<td width="50%" valign="top">

### 🧪 Research & Innovation
**Prototype at scale, then make it production-grade.**<br/>
Experimental environments, proof-of-concept architectures, and practical evaluation of emerging technologies.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════ FABRIC DIAGRAM ═══════════════════════════ -->
## 🕸️ The Kind of Thing I Build

```mermaid
flowchart TB
    subgraph SPINE["🧭 Spine layer — BGP EVPN control plane"]
        S1(["Spine 1"]):::spine
        S2(["Spine 2"]):::spine
    end
    subgraph LEAF["🌿 Leaf layer — VTEPs · Anycast Gateway · Symmetric IRB"]
        L1["Leaf 1"]:::leaf
        L2["Leaf 2"]:::leaf
        L3["Leaf 3"]:::leaf
        L4["Leaf 4"]:::leaf
    end
    S1 & S2 === L1 & L2 & L3 & L4
    L1 --- K["☸️ Kubernetes"]:::work
    L2 --- V["🖥️ Proxmox / KVM"]:::work
    L3 --- G["🚀 DGX · RoCEv2"]:::gpu
    L4 --- C["💾 Ceph storage"]:::work

    classDef spine fill:#203a43,stroke:#36BCF7,color:#fff,stroke-width:2px
    classDef leaf fill:#2c5364,stroke:#36BCF7,color:#fff
    classDef work fill:#0f2027,stroke:#3DA639,color:#fff
    classDef gpu fill:#0f2027,stroke:#76B900,color:#fff,stroke-width:2px
```

<p align="center"><sub>An EVPN/VXLAN leaf-spine fabric: one routed underlay with multi-tenant overlays, carrying everything from VMs to GPU clusters.</sub></p>

---

<!-- ═══════════════════════════ SKILLS ═══════════════════════════ -->
## 🧰 Technical Arsenal

<div align="center">

![NVIDIA](https://img.shields.io/badge/NVIDIA-DGX_·_Mellanox-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-K3s_·_Helm-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Ceph](https://img.shields.io/badge/Ceph-Storage-EF5C55?style=for-the-badge&logo=ceph&logoColor=white)
<br/>
![WireGuard](https://img.shields.io/badge/WireGuard-VPN-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-OCI-892CA0?style=for-the-badge&logo=podman&logoColor=white)
![Cilium](https://img.shields.io/badge/Cilium-eBPF-F8C517?style=for-the-badge&logo=cilium&logoColor=black)
![Traefik](https://img.shields.io/badge/Traefik-Proxy-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
<br/>
![Puppet](https://img.shields.io/badge/Puppet-Config-FFAE1A?style=for-the-badge&logo=puppet&logoColor=black)
![Salt](https://img.shields.io/badge/SaltStack-Automation-57BCAD?style=for-the-badge&logo=saltproject&logoColor=white)
![Forgejo](https://img.shields.io/badge/Forgejo-Git-FB923C?style=for-the-badge&logo=forgejo&logoColor=white)
![Argo](https://img.shields.io/badge/Argo_CD-GitOps-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
<br/>
![Ollama](https://img.shields.io/badge/Ollama-Local_AI-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-Models-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-Observability-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![YubiKey](https://img.shields.io/badge/YubiKey-FIDO2-84BD00?style=for-the-badge&logo=yubico&logoColor=white)

<sub>👇 Expand a category for the full stack</sub>

</div>

<details>
<summary><b>🌐 Networking & Routing</b></summary>
<br/>

`Ethernet` `IPv4` `IPv6` `VLAN` `802.1Q` `QinQ` `LACP` `LAG` `MLAG` `MC-LAG` `STP` `RSTP` `MSTP` `LLDP` `ARP` `NDP` `OSPF` `OSPFv3` `BGP` `iBGP` `eBGP` `MP-BGP` `BFD` `ECMP` `IS-IS` `VRF` `PBR` `RIB` `FIB` `ASN` `RPKI` `Anycast` `Multicast` `IGMP` `PIM`

</details>

<details>
<summary><b>🏢 Datacenter Networking & SDN</b></summary>
<br/>

`EVPN` `VXLAN` `VNI` `VTEP` `BGP EVPN` `IRB` `Symmetric IRB` `Anycast Gateway` `Route Distinguisher` `Route Target` `ARP Suppression` `BUM` `GENEVE` `MPLS` `SR-MPLS` `SRv6` `Leaf-Spine` `Clos Fabric` `SONiC` `NVIDIA Spectrum` `Mellanox`

</details>

<details>
<summary><b>🔐 Network Security & Encryption</b></summary>
<br/>

`MACsec` `MKA` `802.1X` `EAP` `IPsec` `IKEv2` `WireGuard` `OpenVPN` `TLS` `mTLS` `PKI` `X.509` `ACL` `NGFW` `IDS` `IPS` `DPI` `RADIUS` `TACACS+` `NAC` `ZTNA` `Zero Trust` `SIEM` `SOC` `MFA` `FIDO2` `YubiKey` `HSM` `TPM`

</details>

<details>
<summary><b>🐧 Linux & Systems Engineering</b></summary>
<br/>

`Linux` `Ubuntu` `Debian` `systemd` `GRUB` `UEFI` `Secure Boot` `DKMS` `cgroups` `Namespaces` `SELinux` `AppArmor` `PAM` `POSIX` `glibc` `D-Bus` `udev` `eBPF` `io_uring` `NUMA` `Bash` `Python` `SSH` `GPG`

</details>

<details>
<summary><b>💾 Virtualization, Storage & Distributed Systems</b></summary>
<br/>

`KVM` `QEMU` `Proxmox VE` `VMware ESXi` `Xen` `libvirt` `LXC` `Incus` `SR-IOV` `PCI Passthrough` `VFIO` `VirtIO` `Open vSwitch` `DPDK` `Live Migration` `HA` `LVM` `RAID` `ZFS` `Btrfs` `ext4` `XFS` `NFS` `SMB` `iSCSI` `NVMe` `NVMe-oF` `Ceph` `GlusterFS` `Lustre` `Object Storage` `S3` `Snapshots` `Deduplication`

</details>

<details>
<summary><b>📦 Containers & Orchestration</b></summary>
<br/>

`Docker` `Podman` `containerd` `CRI-O` `OCI` `Kubernetes` `K3s` `Helm` `Kustomize` `CNI` `CSI` `Calico` `Cilium` `Flannel` `MetalLB` `Istio` `Envoy` `Traefik` `NGINX` `HAProxy` `Service Mesh` `Gateway API`

</details>

<details>
<summary><b>⚙️ Automation, DevOps & Infrastructure</b></summary>
<br/>

`Puppet` `SaltStack` `Git` `Forgejo` `GitLab` `GitHub Actions` `Jenkins` `CI/CD` `GitOps` `Argo CD` `Flux CD` `Packer` `cloud-init` `PXE` `iPXE` `ZTP` `REST API` `gRPC` `NETCONF` `RESTCONF` `YANG` `Jinja2` `YAML` `JSON`

</details>

<details>
<summary><b>🚀 NVIDIA, GPU Computing & HPC</b></summary>
<br/>

`NVIDIA DGX` `DGX Spark` `Mellanox Networking` `NVIDIA Spectrum` `InfiniBand` `RDMA` `RoCEv2` `NVLink` `CUDA` `NVIDIA GPU Drivers` `NVIDIA Container Toolkit` `GPU Passthrough` `GPU Virtualization`

</details>

<details>
<summary><b>🧠 Artificial Intelligence & Machine Learning</b></summary>
<br/>

`Local AI` `Self-Hosted AI` `LLMs` `Deep Learning` `NVIDIA CUDA` `PyTorch` `Ollama` `llama.cpp` `vLLM` `Exo` `Hugging Face` `Docker AI Containers` `RAG` `Model Quantization` `Distributed Inference`

</details>

<details>
<summary><b>📊 Monitoring, Observability & Operations</b></summary>
<br/>

`Zabbix` `Grafana` `NetBox` `Syslog` `rsyslog` `NetFlow` `sFlow`

</details>

---

<!-- ═══════════════════════════ SOVEREIGNTY ═══════════════════════════ -->
## 🇪🇺 Taking Back Control of Our Data

> [!NOTE]
> In a single decade, a handful of hyperscalers (Google, Microsoft and Amazon Web Services) have come to host a staggering share of the world's digital infrastructure and data.

Governments, research institutions and universities are waking up to what that costs them: **sovereignty, privacy, freedom from vendor lock-in, and long-term independence**.

I build the alternative: **open-source, self-hosted and fully under your own control.**

<table>
<tr>
<td align="center" width="20%">🤝<br/><b>Collaboration</b><br/><sub>Self-hosted platforms</sub></td>
<td align="center" width="20%">✉️<br/><b>Mail</b><br/><sub>Secure mail infrastructure</sub></td>
<td align="center" width="20%">🪪<br/><b>Identity</b><br/><sub>IAM &amp; SSO systems</sub></td>
<td align="center" width="20%">🌐<br/><b>Networks</b><br/><sub>Modern Linux &amp; network architecture</sub></td>
<td align="center" width="20%">🔍<br/><b>Services</b><br/><sub>Open, transparent enterprise IT</sub></td>
</tr>
</table>

---

<!-- ═══════════════════════════ PQC ═══════════════════════════ -->
## 🔐 Post-Quantum Cryptography

Quantum computing and ever more powerful AI mean today's cryptography has an expiry date. I don't see that as a threat to manage. I see it as **a rare chance to rebuild security on stronger foundations.**

The *Quantum Threat Timeline Report 2023* maps out when quantum computers may be able to break today's public-key cryptography ([see the expert-opinion chart](https://postquantum.com/post-quantum/q-day-crqc-predictions/#expert-opinion)).

> [!IMPORTANT]
> The post-quantum era is no longer theoretical. **The transition has already begun.** Data harvested today can be decrypted tomorrow.

My focus is **real-world usability, not theory**. I'm running hybrid post-quantum key exchange for SSH in practice:

| Mechanism | Spec |
|---|---|
| 🔑 **ML-KEM hybrid** key exchange for SSH | [draft-ietf-sshm-mlkem-hybrid-kex](https://datatracker.ietf.org/doc/draft-ietf-sshm-mlkem-hybrid-kex/) |
| 🔑 **NTRU Prime** for SSH | [draft-josefsson-ntruprime-ssh](https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-ssh/) |

I've also put **OpenPGP** and **age** through their post-quantum paces. OpenPGP is powerful, but its PQ transition is slow and complex. The [OpenPGP PQC draft](https://datatracker.ietf.org/doc/draft-ietf-openpgp-pqc/) is promising, yet concepts such as Persistent Symmetric Keys (PSKs) remain hard to reason about, both for users and for operators. **age**, by contrast, has a clean and understandable model that already makes a solid foundation for post-quantum workflows.

<details>
<summary><b>⚖️ OpenPGP vs age: a practical comparison</b></summary>
<br/>

| 🗝️ OpenPGP | ✨ age |
|---|---|
| Mature ecosystem | Modern and minimalist |
| Complex implementation details | Easy to understand and experiment with |
| Slower PQ transition path | Clean and flexible design |
| Fragmented tooling | Simple, consistent workflows |
| Powerful but hard to operationalize | Practical and approachable |

</details>

> [!TIP]
> **Verdict:** while both ecosystems are still evolving, **age is leaner, clearer, and easier to build modern post-quantum workflows around.**

---

<!-- ═══════════════════════════ PHILOSOPHY ═══════════════════════════ -->
## 🧭 Engineering Philosophy

**Open standards, technical independence, security and relentless experimentation** are the foundations of infrastructure that lasts.

I combine proven engineering discipline with a willingness to challenge the default, so the systems I build are reliable today and ready for whatever tomorrow demands. Most of all, they **stay understandable and maintainable** long after the first deploy.

```console
benjamin@infra:~$ cat /etc/philosophy.conf
[principles]
  ✔ Keep systems understandable
  ✔ Prefer open over opaque
  ✔ Automate the boring parts
  ✔ Break things → learn → rebuild better
  ✔ Own your data, or someone else will

benjamin@infra:~$ systemctl status curiosity
● curiosity.service - Always building, always learning
     Loaded: loaded (/etc/systemd/system/curiosity.service; enabled)
     Active: active (running) since forever
```

<div align="center">

<br/>

### Open Infrastructure · Secure Networks · Distributed Computing · Local Intelligence · Digital Sovereignty

**Design. Build. Experiment. Improve.**

<sub>🛠️ Always building • Always learning • Occasionally overengineering</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" alt="footer" />

</div>
