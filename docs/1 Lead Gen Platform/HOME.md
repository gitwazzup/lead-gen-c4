# 1 Lead Gen Platform

![diagram](https://www.plantuml.com/plantuml/svg/0/TLHDRzim3BqNw7_WSXWSO4ikE-tKD4c_aBR1dApOAM1aDXOcIuOa9os6_VUHSfmcBUQBPNwyH_9HlWWHVMmgStxsILjbceAWZB4EtuT3Zxl1HiUoMJU1l78saeq3vQeX5bwZtPgcReRZRr_d1crSti-61YE5oARLcADHM_A3Ee6Vdyr6lnwNYzNJxU9cDPjUJnycML_iS_B1sOmA7Pt_0hrnomEjeSUM4LJeVrCayk0y5BGbush-s9KkXGKnAq_23i_ELs7GwtV8g-bBpBOwxE5_jgSMDwkTS6aqVL1DYAxQewRu09ZG4bZ-6Y9LcGjhpdoqXdk3dFnMAuBB9i1eVYkOKrlKJjkOwaZPKA8j335tGSXl2FiiDiEpjcZvlBSTCvagCDxiFkze3XnNWYhP4LymQcU1jNdMcyQdht1Ihr8On2XLT-SEwCrGOCIZjDMbQso1_ZKpcrgg82pWcYomqb6QwlNXp_aPy7CGEjiXHpxH6aPrRRHAjGZBW-ETkilbEFTkgmlkX4x6T3LDxMo8OPA6l9HHgoCfJvb2BLIvjXj3CCSDlQVyGQYY7FBIxJeP8Je-7MJUQeHOacR1kUQrvq3UrezaAkamPXsMjoVOXsQGFQaFXWDbj6nlR3UpRI5rvqbkHm4AFLGy4lCsz1F2oJehPCScx5rZe9RJfDxGG6U6N9LKOMgIzxbR_4HrIj5Brqmu6AQTNP9g6Ow54A2x_F5XUBDOpFEkAicGu7O8AIEDCk7-DqFgRpDuM4M0px3pMdIDBYLDBiVl2Lf99sJqbc-jUFzArUBk_WnlDOXRF8TRtMOVkvAblQmVpEO3K1jzT5KwvmNF9_s__W40)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.