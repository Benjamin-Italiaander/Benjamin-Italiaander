<h3 align="left">👋 Linux fanatic | Builder of things that should probably exist already</h3>

<p>
📍 Based in Western Europe, collaborating with research institutes, universities, and government organizations across the Netherlands, Belgium, and Germany.
</p>

<p>
I spend most of my time designing and building open, secure, and self-hosted infrastructures.  
When life gets too predictable, I happily disappear into Linux, break things on purpose, and rebuild them better.
</p>

<p>
Inventor of <a href="https://github.com/Benjamin-Italiaander/My_Notes/blob/main/slices_of_life/reminders/EN/joy_of_missig_out.md"> The Joy of Missing Out (JOMO) </a>, because not every notification deserves your attention.
</p>

<h2 align="right">🇪🇺</h2>

<h3> Enabling organizations to take back control of their data using open-source</h3>

> Over the past decade, companies like Google, Microsoft, and Amazon Web Services have centralized an enormous amount of the world's data.
>
> Governments, research institutions, and universities are increasingly aware of the risks this brings, especially around data sovereignty, control, and long-term independence.
>
> My work focuses on designing and building alternatives,fully self-hosted, open, and transparent digital infrastructures.
>
> This includes strategic architecture and hands-on implementation of collaboration platforms, email systems, and secure enterprise services.
>
> I’m fortunate to contribute to this vision at [the National Research Institute for Mathematics and Computer Science](https://www.cwi.nl/en/)
>
---

### Post-Quantum Cryptography

With the rise of quantum computing and increasingly powerful AI systems, we are entering a period where rethinking security is no longer optional, it is an opportunity to build stronger and more future-resistant systems.

The *Quantum Threat Timeline Report 2023*, authored by Michele Mosca and Marco Piani, provides a comprehensive analysis of when quantum computers may become capable of breaking today’s cryptographic systems. Based on a survey of 37 experts from academia and industry, the report offers an informed perspective on the proximity of the quantum threat and the rapid development of quantum technologies. You can find the referenced image [here](https://postquantum.com/post-quantum/q-day-crqc-predictions/#expert-opinion).

Although the report dates from 2023, the pace of development since then suggests that the post-quantum transition is no longer a distant concern, it has already begun.
> Their findings make one thing increasingly clear: the post-quantum era is no longer theoretical it has already begun.
*Opinion-based estimates of the likelihood that a digital quantum computer will be able to break RSA-2048 within 24 hours over time.*

I am currently exploring practical implementations of post-quantum (PQ) cryptography, with a focus on real-world usability rather than theory alone.

This includes experimenting with hybrid SSH key exchange mechanisms such as:

* [ML-KEM Hybrid Key Exchange for SSH](https://datatracker.ietf.org/doc/draft-ietf-sshm-mlkem-hybrid-kex/)
* [NTRU Prime for SSH](https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-ssh/)

As part of this journey, I also explored post-quantum possibilities around **OpenPGP** and **age**, ultimately finding *age* to offer a cleaner, simpler, and more modern approach to encryption workflows.

At the same time, OpenPGP appears to have a relatively slow development and implementation path toward post-quantum support, despite ongoing efforts such as the [OpenPGP PQC draft](https://datatracker.ietf.org/doc/draft-ietf-openpgp-pqc/). I also found some of the approaches around persistent symmetric keys in certain OpenPGP implementations difficult to fully understand and evaluate from a usability and security perspective.


# OpenPGP vs. age — A Practical Perspective

| OpenPGP | age |
|---|---|
| Mature ecosystem | Modern and minimalist |
| Slow PQ transition path | Easier to understand and experiment with |
| Complex implementation details | Clean and practical design |
| Difficult concepts such as Persistent Symmetric Keys (PSKs) | Flexible foundation for modern encryption workflows |
| Fragmented implementations | Simpler tooling and better usability |

As part of this exploration, I tested both **OpenPGP** and **age**.

While OpenPGP remains extremely powerful, its post-quantum transition path currently feels slow and complex. The ongoing [OpenPGP PQC draft](https://datatracker.ietf.org/doc/draft-ietf-openpgp-pqc/) is promising, but concepts such as Persistent Symmetric Keys (PSKs), [including implementations by Protons developer Daniel Huigens](https://gitlab.com/twisstle/openpgp-persistent-symmetric-keys), can still be difficult to reason about from a usability perspective.

At the same time, **age** provides a much simpler and more understandable approach to encryption. Although still evolving, it already offers a flexible foundation for experimenting with post-quantum concepts in real-world workflows.


> While the ecosystem is still evolving,  
> **age currently feels leaner, clearer, and easier to build modern post-quantum workflows around.**

---


### Philosophy

- Keep systems understandable  
- Prefer open over opaque  
- Automate the boring parts  
- Break things -> learn -> rebuild better  
- Own your data, or someone else will  

---

<p align="center">
🛠️ Always building • Always learning • Occasionally overengineering
</p>
