```mermaid

graph TB;

    LSTG[Lifescience Technology Group]-->LSTUK[Lifescience Technology LTD UK]
    LSTG[Lifescience Technology Group]-->LSSSG[Lifescience Solutions LTD APAC]

    LSTUK[Lifescience Solutions LTD SG]-->CEO-LSTUK[CEO: Neil MacRae]
    LSSSG[Lifescience Solutions LTD SG]-->CEO-LSSSG[CEO: Neil MacRae]
    
    CEO-LSTUK[CEO: Neil MacRae]-->CFO-LSTUK[CFO: Gillian Semple]
    CEO-LSTUK[CEO: Neil MacRae]-->CTO-LSTUK[CTO: Dean Didion]
    CEO-LSTUK[CEO: Neil MacRae]-->COO-LSTUK[COO: Callum Semple]
    CEO-LSTUK[CEO: Neil MacRae]-->AL-LSTUK[Admin Lead: Helen T.]

    CTO-LSTUK-->UK_Team1[UK Engineering Team 01]

    UK_Team1-->UK_FE_01[UK_FE_01: Andrew M.\\ Senior Qualification Engineer]
    UK_Team1-->UK_FE_02[UK_FE_02: Elliot B.\\ Senior Qualification Engineer]
    UK_Team1-->UK_FE_03[UK_FE_03: Dinesh P.\\ Senior Qualification Engineer]
    UK_Team1-->UK_FE_04[UK_FE_04: James P.\\ Senior Qualification Engineer]

    CTO-LSTUK-->IL_Team1[Ireland Engineering Team 01]
    IL_Team1-->IL_FE_1[IL_FE_01: Damian B]



    CEO-LSSSG[CEO: Neil MacRae]-->CFO-LSSSG[CFO: Gillian Semple]
    CEO-LSSSG[CEO: Neil MacRae]-->CTO-LSSSG[CTO: Dean Didion]
    CEO-LSSSG[CEO: Neil MacRae]-->COO-LSSSG[COO: Callum Semple]
    CEO-LSTUK[CEO: Neil MacRae]-->AL-LSTSSG[Admin Lead: Qian Zhau Lai]

    CTO-LSSSG-->SG_FE_01[APAC_Team_1: Michael L.\\ Senior Qualification Engineer]
    CTO-LSSSG-->SG_FE_02[APAC_Team_1: Tic L.\\ Senior Qualification Engineer]
    CTO-LSSSG-->SG_FE_03[APAC_Team_1: Muhammad I.\\ Senior Qualification Engineer]
    CTO-LSSSG-->SG_FE_04[APAC_Team_1: t.b.d.]





