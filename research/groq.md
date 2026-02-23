# Groq

## Company Overview
| Attribute | Details |
|-----------|---------|
| **Company Name** | Groq, Inc. |
| **Founded** | 2016 |
| **Headquarters** | Mountain View, CA, USA (offices in San Jose, Liberty Lake WA, Toronto, London) |
| **Valuation** | $6.9B (Sep 2025); Nvidia licensing deal valued at ~$20B (Dec 2025) |
| **Category** | infrastructure |
| **One-Sentence Description** | AI inference chip company that designed the Language Processing Unit (LPU), a purpose-built ASIC delivering ultra-low latency and ultra-high throughput for LLM inference, now licensed to Nvidia in a landmark $20B deal. |

## Founders & Leadership
- **Jonathan Ross** -- Founder & former CEO. Creator of Google's original Tensor Processing Unit (TPU) as a 20% project. Previously worked at Google X's Rapid Eval Team. Studied under Yann LeCun at NYU Courant Institute. Now Chief Software Architect at Nvidia following the licensing deal.
- **Douglas Wightman** -- Co-Founder. Entrepreneur and former Google X engineer.
- **Sunny Madra** -- President (pre-deal). Now at Nvidia.
- **Simon Edwards** -- Current CEO of "New Groq" (post-Nvidia deal), previously CFO.

## Funding History
| Round | Date | Amount | Valuation | Lead Investor |
|-------|------|--------|-----------|---------------|
| Series A-C | 2016-2021 | ~$350M+ (cumulative) | Various | Tiger Global, Social Capital |
| Series D | Aug 2024 | $640M | $2.8B | Multiple |
| Series E | Sep 2025 | $750M | $6.9B | Disruptive Technology Advisers |
| **Total** | | **$1.75B+** | | |
| Nvidia License Deal | Dec 2025 | ~$20B (cash) | N/A | Nvidia |

Other investors include BlackRock, Neuberger Berman, Samsung, Cisco, Altimeter, 1789 Capital (Donald Trump Jr. is a partner).

## Key Metrics
- **Inference Speed:** 500-750 tokens/second (LPU); Independent tests: 877 tok/s (Llama 3 8B), 284 tok/s (Llama 3 70B) -- roughly 2x fastest alternatives
- **Employees:** ~212 (Jul 2024, pre-deal)
- **GroqCloud:** Cloud inference service offering API access to open-source models at ultra-fast speeds
- **Investment Return:** Nvidia deal yields ~2.9x in 3 months for latest investors, 11x+ for earlier backers
- **Key Investor Win:** Disruptive Technology Advisers invested ~$500M cumulatively since 2016

## Products & Features
- **LPU (Language Processing Unit)** -- Purpose-built inference ASIC that uses on-chip SRAM instead of external High Bandwidth Memory (HBM), eliminating the "memory wall" bottleneck that causes GPU latency in inference workloads.
- **GroqCloud** -- Cloud inference API service providing ultra-fast inference on open-source models (Llama, Mixtral, etc.) at competitive pricing. This business unit remains with "New Groq."
- **GroqRack** -- Data center-ready hardware systems for on-premises deployment.
- **Key Differentiator:** The LPU architecture is fundamentally different from GPUs -- it was purpose-built exclusively for inference (the phase where trained models generate responses), not training.

## Competitive Position
Competing with: Nvidia (now licensor), AMD, Intel Gaudi, Cerebras (targeting $20B+ IPO), SambaNova, Graphcore, custom silicon from Google (TPU), Amazon (Inferentia/Trainium), Microsoft (Maia)

Groq's LPU technology is now being integrated into Nvidia's roadmap, with the 2026 "Vera Rubin" platform expected to feature a hybrid GPU-LPU design.

## Strategic Notes
- The Nvidia deal is the defining event: a $20B non-exclusive licensing agreement for Groq's entire patent portfolio and software stack, with key executives (including founder Ross) joining Nvidia.
- Analyst Stacy Rasgon (Bernstein) called the deal structure "keeping the fiction of competition alive" -- the non-exclusive license technically leaves Groq independent, but the talent drain raises existential questions.
- "New Groq" (led by CFO-turned-CEO Simon Edwards) retains GroqCloud but loses the founding team and core engineering talent. The company likely transitions from a hardware innovator to a cloud service provider or patent holding entity.
- The deal validates the thesis that specialized inference hardware is strategically critical. Nvidia is hedging against its own GPUs being suboptimal for the "inference era."
- For AI hardware startups broadly, the Groq outcome is a cautionary tale: even with $1.75B raised, a $6.9B valuation, and working products with real customers, the startup was unable to reach escape velocity as a standalone public company in Nvidia's shadow.
- Cerebras (targeting Q2 2026 IPO at $20B+) is watching closely -- if it cannot IPO, a similar acquisition is likely.

## Status
Effectively Acquired (licensing deal) -- Groq's core LPU technology and founding team are now at Nvidia via a $20B licensing agreement (Dec 2025). "New Groq" continues as an independent company operating GroqCloud, but its long-term viability as an innovator is uncertain.

## Sources
- CNBC: "Nvidia buying AI chip startup Groq's assets for about $20 billion" (Dec 2025)
- CNBC: "Nvidia-Groq deal is structured to keep 'fiction of competition alive'" (Dec 2025)
- The Motley Fool: "Nvidia's Aqui-Hire of Groq Eliminates a Potential Competitor" (Dec 2025)
- IntuitionLabs: "Nvidia's $20B Groq Acquisition: Why It Paid 2.9x Valuation for LPU Tech"
- VentureBeat, TechBuzz, Medium: Various Groq deal analyses
- Wikipedia: "Groq"
