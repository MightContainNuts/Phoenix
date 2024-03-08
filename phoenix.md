```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#BB2528',
      'primaryTextColor': '#fff',
      'primaryBorderColor': '#7C0000',
      'lineColor': '#F8B229',
      'secondaryColor': '#006100',
      'tertiaryColor': '#fff'
    }
  }
}%%

graph LR;



    LSTG((Lifescience Technology Group))-->LSTUK[Lifescience Technology LTD UK]
    LSTG((Lifescience Technology Group))-->LSSSG[Lifescience Solutions LTD APAC]

    subgraph ide6 [Admin]
    LSTUK-->CEO-LSTUK[CEO: Neil MacRae]

    
    CEO-LSTUK-->CFO-LSTUK[CFO: Gillian Semple]
    CEO-LSTUK-->CTO-LSTUK[CTO: Dean Didion]
    CEO-LSTUK-->COO-LSTUK[COO: Callum Semple]
    CEO-LSTUK-->AL-LSTUK[Admin Lead: Helen T.]
    end

    CTO-LSTUK-->UK_Team1[UK Engineering Team 01]
    subgraph ide1 [UK]
    UK_Team1-->UK_FE_01[Senior Qualification Engineer: Andrew M.
        INST/IQ/OQ]
    UK_Team1-->UK_FE_02[Qualification Engineer: Elliot B.
        INST/IQ/OQ]
    UK_Team1-->UK_FE_03[Senior Qualification Engineer: Dinesh P.
        INST/IQ/OQ]
    UK_Team1-->UK_FE_04[Senior Qualification Engineer: James P.
        INST/IQ/OQ]
    end

    CTO-LSTUK-->IL_Team1[Ireland Engineering Team 01]
    subgraph ide2 [Ireland]
    IL_Team1-->IL_FE_1[Senior Qualification Engineer: Damian B
        INST/IQ/OQ]
    end



    CTO-LSTUK-->DE_Team1[DACH Engineering Team 01]

    subgraph ide3 [DACH]
    DE_Team1-->DE_FE_1[Qualification Engineer: Sandro R.
        INST/IQ/OQ]
    end

    subgraph ide5 [Admin]
    LSSSG-->CEO-LSSSG[CEO: Neil MacRae]

    CEO-LSSSG-->CFO-LSSSG[CFO: Gillian Semple]
    CEO-LSSSG-->CTO-LSSSG[CTO: Dean Didion]
    CEO-LSSSG-->COO-LSSSG[COO: Callum Semple]
    CEO-LSSSG-->AL-LSTSSG[Admin Lead: Qian Zhau Lai]
    end

    CTO-LSSSG-->APAC_Team1[APAC Engineering Team 01]
    subgraph ide4 [APAC]
    APAC_Team1-->SG_FE_01[Senior Qualification Engineer: Michael L.
        INST/IQ/OQ]
    APAC_Team1-->SG_FE_02[Qualification Engineer: Tic L.
        INST/IQ/OQ]
    APAC_Team1-->SG_FE_03[Qualification Engineer: Muhammad I.
        INST/IQ]
    APAC_Team1-->SG_FE_04[APAC_Team_1: t.b.d.]
    end




