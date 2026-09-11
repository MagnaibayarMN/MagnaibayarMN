# Magnaibayar Ganzorig

I'm a software engineer who has spent about 14 years on the quiet backend parts of financial software — a stock exchange, a credit bureau, insurance systems — mostly in Java, Go, TypeScript, PHP and PostgreSQL.

These days I'm studying cybersecurity and slowly building a small product of my own.

<hr/>

<div style="display: flex; gap: 20px;">
  <div style="flex: 0 0 20%;">
<a href="https://www.credly.com/badges/643ce4cf-9c64-4285-82db-60e7e4525511/public_url" target="_blank">
    <img src="src/ckad-certified-kubernetes-application-developer.png" width="120" alt="CKAD Badge">
  </a>
  </div>
  <div style="flex: 1;">

  #### Certified Kubernetes Application Developer (CKAD)
  - **Issuer:** Cloud Native Computing Foundation & The Linux Foundation
  - **Credential URL:** [Verify on Credly](https://www.credly.com/badges/643ce4cf-9c64-4285-82db-60e7e4525511/public_url)

  </div>
</div>

<hr/>

### 🧪 Edge Cases vs. Real World

```mermaid
flowchart TD
    A["A QA engineer walks into a bar"] --> B["Orders 1 beer"]
    A --> C["Orders 0 beers"]
    A --> D["Orders 999999999 beers"]
    A --> E["Orders -1 beers"]
    A --> F["Orders 'chocolate'"]
    A --> G["Orders '; DROP TABLE beers;--"]
    B --> H["All tests pass"]
    C --> H
    D --> H
    E --> H
    F --> H
    G --> H
    H --> I["First real customer walks in and asks where the toilet is"]
    I --> J["The bar burns down"]

    classDef start fill:#1e3a5f,stroke:#4a90d9,stroke-width:2px,color:#ffffff
    classDef test fill:#1b4332,stroke:#40916c,stroke-width:2px,color:#ffffff
    classDef pass fill:#2d6a4f,stroke:#74c69d,stroke-width:3px,color:#ffffff
    classDef chaos fill:#6a040f,stroke:#e85d04,stroke-width:3px,color:#ffffff

    class A start
    class B,C,D,E,F,G test
    class H pass
    class I,J chaos
```