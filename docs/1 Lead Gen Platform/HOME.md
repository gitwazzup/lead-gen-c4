# 1 Lead Gen Platform

![diagram](https://www.plantuml.com/plantuml/svg/0/TLHDRzim3BqNw7_WSXWSO8ilE-tKDidM5caRpCcAdG95OXrXicH8Sj9Ys7ylAIMfstK-n1O_tYFvg9o5A7pi6dDwya5RQJg5i8cn3L_BqelTgDPnqwsxW5uw6z76aNHDAPJNmcvDrtRb-CldkH4sBczcfH4HGoJJQapHGblqepQ1dvxCpd_TBHUh-wl5vMes_JwzdHH3ji_H1sSBL3ew_ma6uym3sJ0Wopaqml_6YEZ1UL2uHUDQEkmsBeK5DakFp0uFpZTXD1WUa5VJnrXiTTZ3_ynV6RTe7NDfOOOWkn1TiqTDyG54GajWrLE8s2GmqMhEdbynoDoxhLR4YrQrJblAAcOt5PHmTv5-fHH1Enk6Rr3mCQwKY88mw8ZU2WCJEZDeHHKIf6v4JIzX5MZxuC1Pu0o8egwrhNk05wwpIlYdmjGjvSzGg1eja32HEnWCuS_f2T1prANOCVCzhk6yROsM8bAHp7thQ0Mkg__qHcZmRPfA8WBqQUIqGr7BtkHVCuMMgIggs23CgQMtb3zGo9ZwthZTOUeG7NqTLTbgwdk3clIXcjUU0ccv_YMJJU0b8WMMLw-mZyq8ygG-20waqRniCIzIRY5rvv6NMO4K7XeQYKcZVuTGhGcSXLkBW9dHfCxsUh8PAhd1fY_j2z5hWa6w4yn0C7boIQXbwCl0GDVLtMrvkLZCgqDDdC71UGGf8mrIxRVg_GokFsVGg5I0Zx3pcbMDBYLDBiPl2RAW4pHwIrUClN-vQdOVhl5B3UpkUtfxttSVRsW6xxkI9L-wW_cCHf7-Lvu1)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.