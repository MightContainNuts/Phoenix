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

    UK_Team1-->UK_FE_01[Senior Qualification Engineer: Andrew M.]
    UK_Team1-->UK_FE_02[Qualification Engineer: Elliot B.]
    UK_Team1-->UK_FE_03[Senior Qualification Engineer: Dinesh P.]
    UK_Team1-->UK_FE_04[Senior Qualification Engineer: James P.]

    CTO-LSTUK-->IL_Team1[Ireland Engineering Team 01]
    IL_Team1-->IL_FE_1[Senior Qualification Engineer: Damian B]



    CEO-LSSSG[CEO: Neil MacRae]-->CFO-LSSSG[CFO: Gillian Semple]
    CEO-LSSSG[CEO: Neil MacRae]-->CTO-LSSSG[CTO: Dean Didion]
    CEO-LSSSG[CEO: Neil MacRae]-->COO-LSSSG[COO: Callum Semple]
    CEO-LSTUK[CEO: Neil MacRae]-->AL-LSTSSG[Admin Lead: Qian Zhau Lai]

    CTO-LSTSG-->APAC_Team1[Ireland Engineering Team 01]

    APAC_Team1-->SG_FE_01[Senior Qualification Engineer: Michael L.\\ ]
    APAC_Team1-->SG_FE_02[Qualification Engineer: Tic L.\\ Senior Qualification Engineer]
    APAC_Team1-->SG_FE_03[Qualification Engineer: Muhammad I.\\ Senior Qualification Engineer]
    APAC_Team1-->SG_FE_04[APAC_Team_1: t.b.d.]





