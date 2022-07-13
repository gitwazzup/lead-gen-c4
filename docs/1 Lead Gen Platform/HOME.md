# 1 Lead Gen Platform

![diagram](https://www.plantuml.com/plantuml/svg/0/VLJ9Rjim4Bq7o3zCVIXaeBKlFVKKRyq29p4gkq5FnfYQM4GfKY0fEK7HV--Gj1mxHgkBHhEyDwkkd4VhcqfTNdoGMgYc82YzhztNuT3YRh2LlcmsZIChZFQa_K2OQeY5bQXRrTJDSFBbyqAXzglx-L2X9-TPjPwmDqfDTb17yCkB-UZdusgvVhfTtgpdi-lPmpJh1_s2h3Cweq9wOpz1Rv9u82bwh1b1XVONUI8Bna91BIbJyyUkDD7D1RMm5DZXsTZA3Nhz3dazU_5PAzqU_aUI4cvMcy0bKVL1DCwRQeyQ_HrWH8jW-QlpL6N6RJZoKIkk3NAohHG4uyR1Q74RC1VMjBBWD4WNjP7QnuGY39Ie2qMSH478Rt3xS5R3izIeMTxhZYbLvHXuJbZ0FMhSKXNQ4urKdV56fe3eyGMzD1fuSCzoszZuvKwA4G9TK8QIElaCyU051NeyYb-FJQCBjA-PsjPTYjUaWVV1XpnwVVXzUG7y7DOXso5xFj46HdMjf8X91Re7mvjtb_-dXzzciQujCKoSDA-kb-9euATChWvKkTHRHR3Wlhsd_4ueV13oqkowOOCtB1sMePK8lYJ9Qy4vRomxyawVauaufCbz3glR4-n3CSYMM0V3WL0o3D6d_KqbnEeiXHigGA25YbkYtff-GZZTP4NOn2bRD-WeSQfO6oher92BaYgCHVBMT-SHgKufUl4O0mV3fDx5KQtSyI02q5t--32yMIuNUPTLY0ZEgGan8hOoulup8kIV8hXPXOEFiBCopDMR63GTJzuJf95EIScMRpjO_uIiWxdxVxpb4Cp1ShZz57riYffqqcTgTGQKl8zkfZDUSN_YN-ul)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.