```mermaid

graph TB;
    CEO[CEO: neil]-->COO[COO: callum]
    COO-->TeamAsst[TeamAsst: q]
    COO-->TeamAsst[TeamAsst: dave]
    CEO-->CFO[CFO: gillian]
    CEO-->CTO[CTO: dean]
    CTO-->gavin[Team Leader 1]
    CTO-->TBD[Team Leader 2]
    CTO-->michael[Team Leader 3]
    gavin-->dinesh[Field Engineer]
    gavin-->T1.2_tbd[Field Engineer]
    gavin-->T1.3_tbd[Field Engineer]
    TBD-->T2.1_tbd[Field Engineer]
    TBD-->T2.2_tbd[Field Engineer]
    TBD-->T2.3_tbd[Field Engineer]  
    michael-->T3.1_tbd[Field Engineer]
    michael-->T3.2_tbd[Field Engineer]
    michael-->T3.3_tbd[Field Engineer]
   
CEO[CEO: Neil ] --> CTO[CTO: Dean ]
    CEO --> CFO[CFO: Gillian ]
    CEO --> COO[COO: Callum ]
