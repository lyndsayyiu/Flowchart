graph TD;
    A[Nutrient Cycling & Aquatic Food Chains] --> B[Starting with Plants (Producers)]
    B --> C[Submerged plants like Potamogeton and Charophytes use sunlight and nutrients to grow]
    C --> D[Plants take up nutrients (Nitrogen, Phosphorus)]
    D --> E[Plants grow and produce food]

    E --> F[Feeding the Herbivores]
    F --> G[Small animals like Pygmy Perch eat plants and algae]
    G --> H[Energy and nutrients passed to herbivores]

    H --> I[Carnivores Step In]
    I --> J[Larger fish like Western Minnow eat herbivores]
    J --> K[Birds like Australian Pelican and Long-necked Turtle eat larger fish]

    K --> L[Decomposers and Nutrient Recycling]
    L --> M[Dead plants and animals broken down by bacteria and fungi]
    M --> N[Nutrients returned to the water]

    N --> O[Nutrient Movement and Spiraling]
    O --> P[Nutrients move downstream]
    P --> Q[Nutrients picked up and used by plants and animals along the way]

    Q --> B

    subgraph Figures from PDF
        C -.->|Figure 2| img2[Autotrophs in a waterway]
        G -.->|Figure 3| img3[Heterotrophs in a waterway]
        K -.->|Figure 5| img5[Typical food web in a waterway]
        L -.->|Figure 4| img4[Detrital food chain]
        N -.->|Figure 6| img6[Phosphorus cycle]
    end

    style img2 fill:#e6f7ff,stroke:#0099cc,stroke-width:2px;
    style img3 fill:#e6f7ff,stroke:#0099cc,stroke-width:2px;
    style img4 fill:#e6f7ff,stroke:#0099cc,stroke-width:2px;
    style img5 fill:#e6f7ff,stroke:#0099cc,stroke-width:2px;
    style img6 fill:#e6f7ff,stroke:#0099cc,stroke-width:2px;

    classDef boxClass fill:#e6f7ff,stroke:#0099cc,stroke-width:2px;
    class B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q boxClass;
