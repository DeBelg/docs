---
title: Privacy Explorer
---

**3in1**: a ranking system, database & comprehensive profiling to empower the general public in discerning the privacy levels, security, and reliability of Web3 projects.

![privacy dashboard june 2024](../assets/Explorer%20privacy%20dashboard%20(jun%2024).png)

- Live demo [here](https://taikai.network/ethrome/hackathons/ethrome-23/projects/clng508ts00lswu01030hpfuq/idea)
- Website is live [link](https://explorer.web3privacy.info)

**contributors**: Killushine, Ethanolo, ant, Coinmandeer, Develit, Mykola

![alt text](../assets/explorer-platform-overview.png)

Despite the foundational role that privacy is meant to play in shaping Web3, genuinely impactful initiatives remain scarce. Many projects leverage the concept of privacy as a buzzword or for public relations advantage, rather than addressing tangible issues or enacting substantial changes at the infrastructural and transactional level.

That's why a ranking system of all privacy-related projects in the Web3 could help a lot the users to discern and decide who to trust.

### Latest updates (jun 24)
-   [Merged PRs](https://github.com/web3privacy/explorer-data/pulls?q=is%3Apr+is%3Aclosed)
-   PRs from CultDAO, [Oasis Network](https://github.com/web3privacy/explorer-data/pull/609), [PSE](https://github.com/web3privacy/explorer-data/pull/632/commits/ac2cb864d86389b9be34fc2fd5759a73984c4d29)
-   Contribution guide has been published on [Mirror](https://mirror.xyz/0x0f1F3DAf416B74DB3DE55Eb4D7513a80F4841073/Za8nrM7gQhVloDJNKjSPD1d0h2bQkjyehrBelRIT9Do)
-   Fixed non-working [search](https://github.com/web3privacy/explorer-app/commit/68f73dc19d02c356ef7452e9390833a0ca9e62dd)
-   Sample project yaml [updated](https://github.com/web3privacy/explorer-data/blob/main/sample-project.yaml)

## Value

**General public**
- Find projects you can trust 
- Explore your privacy stack
- Compare projects’ privacy features
- Filter projects by scoring
- Filter projects by ecosystems
- Explore which projects match your use case (like “swap assets”)

**Devs**
- Explore projects delivering privacy
- Research on use-cases
- Improve existing solutions

**Security audit companies / white hackers**
- Find clients lacking security audit (privacy-focused)

**Investors**
- Explore early-stage projects
- Find outstanding builders
- Back critical privacy stack

## About the Scoring Mechanism
![alt text](../assets/explorer-product-features.png)

**Quick preview module**

_Value_: rapid snapshot of the privacy readiness

![alt text](../assets/explorer-quick-preview.png)

**Filtering module**

_Value_: match projects within your search or use-case (filter "zk", "stealth addresses", "Ethereum" etc)

![alt text](../assets/explorer-filtering-module.png)

**Ranking module**

_Value_: explore the most secure projects within category

![alt text](../assets/explorer-ranking-module.png)

**Activity module**

_Value_: explore latest updates from the product-readiness to the GitHub activity

![alt text](../assets/explorer-activity-block.png)

**Team module**

_Value_: explore team, it's reputation (historical privacy track record per person)

![alt text](../assets/explorer-team-block.png)

**Privacy features module**

_Value_: explore key privacy features & practices from the data collection to compliance-readiness

![alt text](../assets/explorer-privacy-features.png)

**Funding module**

_Value_: find out about funding behind the project (VCs, donations, crowdloans)

![alt text](../assets/explorer-funding-block.png)

**Recommendations module**

_Value_: explore similar services matching your search or use-case

![alt text](../assets/explorer-recommendations-block.png)

**Reviews module**

_Value_: explore or contribute with the transparent feedback by the community

![alt text](../assets/explorer-reviews-block.png)

**Additional features**

_We plan to include more modules from guides & checklists to academy & available jos in privacy_

![alt text](../assets/explorer-additional-product-features.png)

## References:
- [l2beat](https://l2beat.com/scaling/risk)
- [certik](https://www.certik.com/)
- [metacritic](https://www.metacritic.com/about-metascores)
- [Clutch](https://clutch.co/methodology)

### About the Scoring Mechanism 
It will incorporate both expert analysis and community input, to offer impartial resources for evaluating projects.

- Professional scoring would be a joint R&D with the key web3 people from protocol architects to security specialists. We are collecting feedbacks from privacy experts from the Ethereum Foundation, Railgun, Waku, NYM... 

- In parallel to the top-down scorecard method, we'll develop and implement a bottom-up community scoring platform too (think of Metacritic exters + users scorings) -> at the end of the day it's the users who have to become the real watchdogs of the industry, signaling about flaws and shortcomings of solutions.

We interviewed 100 privacy players & gathered an MVP vision — we are running a series of 1-on-1 feedback loop sessions to make the scoring model community validated.

## Delivery
* **Design**: _Explorer UI_: [GitHub](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/UI/Readme.md), [V1.0](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/UI/Readme.md#v10-eth-rome-prototype),[V1.1](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/UI/Readme.md#v11-post-ethrome-update), [V 1.1 mobile](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/UI/Readme.md#v11-post-ethrome-update-mobile-version), [V1.2](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/UI/Readme.md#v12-post-ethrome-update-basic-scoring-x-brief-sync)
* **Research**: _Privacy Explorer breaf_: [Brief](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/Brief.md). Pull requests by [Railgun_](https://github.com/web3privacy/web3privacy/pull/31), [Waku](https://github.com/web3privacy/web3privacy/pull/35), [Lit](https://github.com/web3privacy/web3privacy/pull/34), [Brume](https://github.com/web3privacy/web3privacy/pull/38), [Webb](https://github.com/web3privacy/web3privacy/pull/37)
* **Research**: _Scoring matching: Brief, Non-techies validity, MVP_: [GitHub](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/Data%20brief%20%26%20scoring%20model%20comparison.md)
* **Research**: _Privacy Explorer product features_: [GitHub](https://github.com/web3privacy/web3privacy/tree/main/Web3privacynowplatform/scoringmodel/Product%20features)
* **Research**: _Data Manifest for Privacy Explorer platform_: [GitHub](https://github.com/web3privacy/data/tree/main#readme)
* **Research**: _Privacy Explorer data survey_: [Typeform](https://gy0n92ttldn.typeform.com/to/clX8HhGi)

## Milestones

| Area | Date | Link |
| ------------- | ------------- | ------------- |
| MVP | dec, 2023 | 1. Landing. 2. DeFi category scoring benchmark. 3. Easily upgradable Project data via GitHub. 4. Basic documentation. |
| QA | jan, 2024 | 1. Bug fixing. 2. Content update. 3. Content filled by the projects themselves |
| V 1.0 | Feb, 2024 | 1. Category expansion (200 projects). 2. Scoring model major update (built by community). 2. Content update. 3. Content filled by the projects themselves (plus moderation). 5. Extended documentation. |
| V 2.0 | March, 2024 | 1. Full [database](https://github.com/web3privacy/web3privacy) synchronization (600 projects). 2. Content update (actualisation). 3. Content filled by the projects themselves (plus moderation). |

## Team
- Core project manager: Mykola Siusko [GitHub](https://github.com/Msiusko), [Twitter](https://twitter.com/nicksvyaznoy), [LinkedIn](https://www.linkedin.com/in/siusko/)
- Research track: [Mykola Siusko](https://github.com/Msiusko), [PG](https://github.com/EclecticSamurai)
- Product:[Coinmandeer](https://github.com/coinmandeer), [Tree](https://github.com/burningtree), [Cryptomar1o](https://github.com/cryptomar1o)

## Project Repositories
| Repository | Description |
| --- | --- |
| [@web3privacy/explorer](https://github.com/web3privacy/explorer) | [Privacy Explorer](/projects/privacy-explorer) project main repository |
| [@web3privacy/explorer-app](https://github.com/web3privacy/explorer-app) | [Privacy Explorer](/projects/privacy-explorer) application frontend |
| [@web3privacy/explorer-data](https://github.com/web3privacy/explorer-data) | Data repository for [Privacy Explorer](/projects/privacy-explorer) project |
