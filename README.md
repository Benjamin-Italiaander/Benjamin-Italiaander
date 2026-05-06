<h3 align="left">👋 Linux fanatic | Building infrastructure that should already exist</h3>

<p>
📍 Based in Western Europe, collaborating with research institutes, universities, and government organizations across the Netherlands, Belgium, and Germany.
</p>

<p>
I design and build open, secure, and self-hosted infrastructure with a strong focus on transparency, sustainability, and digital sovereignty.
</p>

<p>
Most of my time is spent working with Linux, networking, identity management, automation, and modern security architectures.  
When life gets too predictable, I intentionally break systems in my homelab just to understand how to rebuild them better.
</p>

<p>
Advocate of <a href="https://github.com/Benjamin-Italiaander/My_Notes/blob/main/slices_of_life/reminders/EN/joy_of_missig_out.md">The Joy of Missing Out (JOMO)</a> — because not every notification deserves your attention.
</p>

<h2 align="right">🇪🇺</h2>

## Enabling organizations to regain control over their data using open-source

> Over the past decade, companies such as Google, Microsoft, and Amazon Web Services have centralized an enormous amount of the world’s digital infrastructure and data.
>
> Governments, research institutions, and universities are increasingly aware of the risks this creates around sovereignty, privacy, vendor lock-in, and long-term independence.
>
> My work focuses on designing and building practical alternatives:
>
> - Self-hosted collaboration platforms
> - Secure mail infrastructures
> - Identity and access management systems
> - Modern Linux and network architectures
> - Open and transparent enterprise services
>
> I’m fortunate to contribute to this vision at [CWI — the National Research Institute for Mathematics and Computer Science](https://www.cwi.nl/en/).

---

## Post-Quantum Cryptography

With the rise of quantum computing and increasingly powerful AI systems, we are entering a period where rethinking security is no longer optional — it is an opportunity to build stronger and more future-resistant systems.

The *Quantum Threat Timeline Report 2023* provides a comprehensive analysis of when quantum computers may become capable of breaking today’s cryptographic systems.

You can find the referenced image [here](https://postquantum.com/post-quantum/q-day-crqc-predictions/#expert-opinion).

> Their findings increasingly suggest that the post-quantum era is no longer theoretical — the transition has already begun.

I am currently exploring practical implementations of post-quantum cryptography, focusing on real-world usability rather than theory alone.

This includes experimenting with hybrid SSH key exchange mechanisms such as:

- [ML-KEM Hybrid Key Exchange for SSH](https://datatracker.ietf.org/doc/draft-ietf-sshm-mlkem-hybrid-kex/)
- [NTRU Prime for SSH](https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-ssh/)

As part of this research, I also explored post-quantum approaches around **OpenPGP** and **age**.

While OpenPGP remains extremely powerful, its transition toward post-quantum cryptography currently feels relatively slow and complex. The ongoing [OpenPGP PQC draft](https://datatracker.ietf.org/doc/draft-ietf-openpgp-pqc/) is promising, but some concepts — such as Persistent Symmetric Keys (PSKs) — remain difficult to reason about from both a usability and operational perspective.

At the same time, **age** offers a significantly simpler and more understandable encryption model. Although still evolving, it already provides a clean and flexible foundation for experimenting with post-quantum concepts in real-world workflows.

---

## OpenPGP vs age — A Practical Perspective

| OpenPGP | age |
|---|---|
| Mature ecosystem | Modern and minimalist |
| Complex implementation details | Easier to understand and experiment with |
| Slower PQ transition path | Clean and flexible design |
| Fragmented tooling | Simple and consistent workflows |
| Powerful but difficult to operationalize | Practical and approachable |

> While the ecosystem is still evolving,  
> **age currently feels leaner, clearer, and easier to build modern post-quantum workflows around.**

---

## Philosophy

- Keep systems understandable
- Prefer open over opaque
- Automate the boring parts
- Break things → learn → rebuild better
- Own your data, or someone else will

---

<p align="center">
🛠️ Always building • Always learning • Occasionally overengineering
</p>



