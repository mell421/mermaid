
```mermaid
flowchart TD
    J[ALEA] --> A[home]
    D(Réponses au formulaire 2) --> B[dashboard]
    D --> C[search]
    K[param] --> D
    BS[categories] --> D
    D --> F[dataALL]
    F --> G[data]
    G --> H[LD]
    I[LDALL] --> H
    J --> H
    F --> I
    BB[nbTpsP] --> J
    BW[levels] --> J
    BY[TRS] --> J
    D --> K
    F --> K
    AK[liste desc] --> K
    J --> L[menu]
    BM[TVTIME] --> L
    BW --> L
    J --> M[menu2]
    P[copy by script] --> M
    AE[ep suiv] --> M
    AH[en cours occ] --> M
    AS[affODD] --> M
    AZ[smra] --> M
    M --> N[menu2b]
    P --> N
    S[PA] --> N
    AF[epSuiv2] --> N
    P --> O[cps]
    AL[listes complete] --> O
    M --> P
    AK --> P
    P --> Q[max]
    AE --> Q
    H --> R[copyGraph]
    P --> R
    BN[tracker] --> R
    AH --> S
    AI[OCC_ec] --> S
    AM[premDerAll] --> S
    AP[ODD_ssChgmt] --> S
    AS --> S
    AZ --> S
    J --> U[cal23]
    G --> V[rest]
    W[resteData] --> V
    X[EC/FIN] --> V
    BB --> V
    G --> W
    V --> W
    AK --> W
    W --> X
    BS --> Y[BL]
    AS --> AA[choixdate]
    F --> AB[list finished]
    H --> AB
    BS --> AB
    G --> AC[list ongoing]
    W --> AC
    BS --> AC
    V --> AD[all_config]
    X --> AD
    AC --> AD
    AE --> AD
    H --> AE
    AK --> AE
    AE --> AF
    H --> AG[ECocc]
    I --> AG
    AK --> AG
    AL --> AG
    AN[duree] --> AG
    J --> AH
    AG --> AH
    J --> AI
    X --> AI
    AG --> AI
    AK --> AI
    H --> AJ[listes]
    J --> AJ
    U --> AJ
    V --> AJ
    AK --> AJ
    AM --> AJ
    AZ --> AJ
    BB --> AJ
    BD[tpsEnMin] --> AJ
    H --> AK
    H --> AL
    I --> AL
    AK --> AL
    H --> AM
    AK --> AM
    H --> AN
    H --> AO[ODD_all]
    AR[ODD] --> AO
    J --> AP
    AN --> AP
    H --> AQ[ODD_ter]
    AR --> AQ
    H --> AR
    AA --> AR
    AS --> AR
    J --> AS
    AO --> AS
    AQ --> AS
    AR --> AS
    F --> AT[favoris]
    V --> AU[ordoConf]
    AV[ordo] --> AU
    AW[planning] --> AU
    AU --> AV
    J --> AW
    AU --> AW
    AV --> AW
    AX[calMonth] --> AW
    U --> AX
    AA --> AX
    P --> AY[tisaep]
    T --> AY
    X --> AY
    AL --> AY
    J --> AZ
    P --> AZ
    AL --> AZ
    H --> BB
    J --> BB
    BC[nbTpsPbis] --> BB
    H --> BC
    I --> BC
    J --> BC
    H --> BD
    J --> BD
    BE --> BD
    H --> BE[tpsEnMinConf]
    I --> BE
    J --> BE
    I --> BF[rew]
    F --> BG[rewindALLa]
    I --> BG
    I --> BH[rewindALLb]
    BG --> BH
    H --> BI[rewind23a]
    BJ[rewind23b] <--> BI
    H --> BJ
    BG --> BK[rewindALL]
    BH --> BK
    BI --> BL[rewind23]
    BJ --> BL
    J --> BM
    V --> BM
    BB --> BM
    BD --> BM
    BG --> BM
    BH --> BM
    BY --> BM
    V --> BN
    X --> BN
    AE --> BN
    X --> BO[toTab]
    AY --> BO
    AZ --> BO
    H --> BP[nb31jRec]
    J --> BP
    AE --> BP
    H --> BQ[nb7]
    J --> BQ
    V --> BQ
    AE --> BQ
    AH --> BQ
    AI --> BQ
    BO --> BQ
    BP --> BR[graphNb]
    BQ --> BR
    F --> BW
    BM --> BW
    BU[char] --> BW
    H --> BY
    I --> BY
    J --> BY
    E[old]
    Z[toCome]
    BA[URL]
    BT[journal]
    BV[badge]
    BX[mail]
```

3  
```mermaid
flowchart TD
    D(Réponses au formulaire 2) --> B[dashboard]
    D --> C[search]
    D --> F[dataALL]
    D --> K[param]
    E[old]
    F --> G[data]
    F --> I[LDALL]
    F --> K
    F --> AB[list finished]
    F --> AT[favoris]
    F --> BG[rewindALLa]
    F --> BW[levels]
    G --> H[LD]
    G --> V[rest]
    G --> W[resteData]
    G --> AC[list ongoing]
    H --> R[copyGraph]
    H --> AB
    H --> AE[ep suiv]
    H --> AG[ECocc]
    H --> AJ[listes]
    H --> AK[liste desc]
    H --> AL[listes complete]
    H --> AM[premDerAll]
    H --> AN[duree]
    H --> AO[ODD_all]
    H --> AQ[ODD_ter]
    H --> AR[ODD]
    H --> BB[nbTpsP]
    H --> BC[nbTpsPbis]
    H --> BD[tpsEnMin]
    H --> BE[tpsEnMinConf]
    H --> BI[rewind23a]
    H --> BJ[rewind23b]
    H --> BP[nb31jRec]
    H --> BQ[nb7]
    H --> BY[TRS]
    I --> H
    I --> AG
    I --> AL
    I --> BC
    I --> BE
    I --> BF[rew]
    I --> BG
    I --> BH[rewindALLb]
    I --> BY
    J[ALEA] --> A[home]
    J --> H
    J --> L[menu]
    J --> M[menu2]
    J --> U[cal23]
    J --> AH[en cours occ]
    J --> AI[OCC_ec]
    J --> AJ
    J --> AP[ODD_ssChgmt]
    J --> AS[affODD]
    J --> AW[planning]
    J --> AZ[smra]
    J --> BB
    J --> BC
    J --> BD
    J --> BE
    J --> BM[TVTIME]
    J --> BP
    J --> BQ
    J --> BY
    K --> D
    M --> N[menu2b]
    M --> P[copy by script]
    P --> M
    P --> N
    P --> O[cps]
    P --> Q[max]
    P --> R
    P --> AY[tisaep]
    P --> AZ
    S[PA] --> N
    T --> AY
    U --> AJ
    U --> AX[calMonth]
    V --> W
    V --> AD[all_config]
    V --> AJ
    V --> AU[ordoConf]
    V --> BM
    V --> BN[tracker]
    V --> BQ
    W --> V
    W --> X[EC/FIN]
    W --> AC
    X --> V
    X --> AD
    X --> AI
    X --> AY
    X --> BN
    X --> BO[toTab]
    Z[toCome]
    AA[choixdate] --> AR
    AA --> AX
    AC --> AD
    AE --> M
    AE --> Q
    AE --> AD
    AE --> AF[epSuiv2]
    AE --> BN
    AE --> BP
    AE --> BQ
    AF --> N
    AG --> AH
    AG --> AI
    AH --> M
    AH --> S
    AH --> BQ
    AI --> S
    AI --> BQ
    AK --> K
    AK --> P
    AK --> W
    AK --> AE
    AK --> AG
    AK --> AI
    AK --> AJ
    AK --> AL
    AK --> AM
    AL --> O
    AL --> AG
    AL --> AY
    AL --> AZ
    AM --> S
    AM --> AJ
    AN --> AG
    AN --> AP
    AO --> AS
    AP --> S
    AQ --> AS
    AR --> AO
    AR --> AQ
    AR --> AS
    AS --> M
    AS --> S
    AS --> AA
    AS --> AR
    AU --> AV
    AU --> AW
    AV[ordo] --> AU
    AV --> AW
    AW --> AU
    AX --> AW
    AY --> BO
    AZ --> M
    AZ --> S
    AZ --> AJ
    AZ --> BO
    BA[URL]
    BB --> J
    BB --> V
    BB --> AJ
    BB --> BM
    BC --> BB
    BD --> AJ
    BD --> BM
    BE --> BD
    BG --> BH
    BG --> BK[rewindALL]
    BG --> BM
    BH --> BK
    BH --> BM
    BI <--> BJ
    BI --> BL[rewind23]
    BJ --> BL
    BM --> L
    BM --> BW
    BN --> R
    BO --> BQ
    BP --> BR[graphNb]
    BQ --> BR
    BS[categories] --> D
    BS --> Y[BL]
    BS --> AB
    BS --> AC
    BT[journal]
    BU[char] --> BW
    BV[badge]
    BW --> J
    BW --> L
    BY --> J 
    BY --> BM 
    BX[mail]
```

4  
```mermaid
```

