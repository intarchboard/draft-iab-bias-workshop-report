---
title: "IAB Barriers to Internet Access of Services (BIAS) Workshop Report"
abbrev: "BIAS Workshop Report"
category: info

docname: draft-iab-bias-workshop-report-latest
submissiontype: IAB
number:
date:
consensus: true
v: 3
keyword:
 - Internet Access
 - Censorship
 - community networks
 - digital divide
venue:
  github: "intarchboard/draft-iab-bias-workshop-report"
  latest: "https://intarchboard.github.io/draft-iab-bias-workshop-report/draft-iab-bias-workshop-report.html"

author:
 -
    fullname: "Mirja Kühlewind"
    email: "ietf@kuehlewind.net"
 -
    fullname: "Dhruv Dhody"
    email: "dd@dhruvdhody.com"
 -
    fullname: "Mallory Knodel"
    email: "mknodel@cdt.org"

normative:

informative:
  RFC7962:
  SDG:
    target: https://sdgs.un.org/goals
    title: Sustainable Development Goals
  MARTINEZ:
    target: https://www.ietf.org/slides/slides-biasws-community-networks-and-the-quest-for-quality-00.pdf
    title: Community Networks and the Quest for Quality
    author:
      -
        ins:  L. M. Martínez-Cervantes
        name: Luis Miguel Martínez Cervantes
      -
        ins:  R. Guevara-Martínez
        name: Rolando Guevara Martínez
    date: January 2024
  BENSON:
    target: https://www.ietf.org/slides/slides-biasws-a-c-in-cdn-access-service-to-and-from-the-internet-at-cost-for-community-networks-00.pdf
    title: A ‘C’ in CDN - Access service to and from the Internet at cost for community networks
    author:
      -
        ins:  T. A. Benson
        name: Theophilus A. Benson
      -
        ins:  M. Fayed
        name: Marwan Fayed
    date: January 2024
  HU:
    target: https://www.ietf.org/slides/slides-biasws-closing-the-performance-and-management-gaps-with-satellite-internet-challenges-approaches-and-future-directions-01.pdf
    title: Closing the Performance and Management Gaps with Satellite Internet - Challenges, Approaches, and Future Directions
    author:
      -
        ins:  P. Hu
        name: Peng Hu
    date: January 2024
  RENNO:
    target: https://www.ietf.org/slides/slides-biasws-position-paper-by-raquel-renno-01.pdf
    title: Maximising Connectivity - The Spectrum's Vital Role in Technology Access
    author:
      -
        ins:  R. Rennó
        name: Raquel Rennó
    date: January 2024


--- abstract

The “Barriers for Internet Access of Services (Bias)” workshop was convened by the Internet Architecture Board (IAB) from January 15-17, 2024 as a three-day online meeting.  Based on the submitted position papers, the workshop covered three areas of interest: the role of community networks in Internet Access of Services; reports and comments on the observed digital divide; and measurements of censorship and censorship circumvention. This report summarizes the workshop's discussion and serves as a reference for reports on the current barriers to Internet Access.

Note that this document is a report on the proceedings of the workshop.  The views and positions documented in this report were expressed during the workshop by participants and do not necessarily reflect IAB's views and positions.

--- middle

# Introduction

The Internet as part of the critical infrastructure affects many aspects of our society significantly, although it impacts different parts of society differently. The Internet is an important tool to reach the Sustainable Development Goals (SDG) {{SDG}} and to globally support human rights. Consequently, the lack of meaningful access to digital infrastructure and services is also a form of disenfranchisement.

Solely having Internet access is not enough. At the same time as we work to connect the next billion people and reduce the digital divide, it is also important to understand persistent and novel inequalities in the digital age when accessing content and services. There are more and more barriers to meaningful access to the services and applications that run on the Internet. Even if Internet connectivity is available, information and services access may remain challenged and unequal.

This IAB workshop has aimed

* to collect reports about barriers to accessing content and services on the Internet, e.g. based on filtering, and blocking as well as due to general inequality of technological capabilities, like device or protocol limitations.

* to help the Internet community get a better understanding of how the Internet functions in different parts of the world and which technology or techniques need to be used to gain access to content.

* to build an understanding of what “being connected” to the Internet means: What is the Internet to users? What is needed to be meaningfully connected? What are the minimum requirements to be able to access certain parts of the content and services provided over the Internet?

## About this workshop report content

This document is a report on the proceedings of the workshop. The views and positions documented in this report are expressed during the workshop by participants and do not necessarily reflect IAB views and positions.

Furthermore, the content of the report comes from presentations given by workshop participants and notes taken during the discussions, without interpretation or validation.  Thus, the content of this report follows the flow and dialogue of the workshop but does not attempt to capture a consensus.

# Workshop Scope and Discussion

The workshop was organized across three days with all-group discussion slots, one per day. The following topic areas were identified and the program committee organized paper submissions into three main themes for each of the three discussion slots. During each discussion, those papers were presented sequentially with open discussion held at the end of each day.

## Session 1: Community Networks - Their Role in Internet Access of Services

The first day of the workshop focused on the role of Community Networks {{RFC7962}} as a way to overcome the barriers to Internet Access. Community Networks are self-organized networks wholly owned by the community and thus provide an alternative mechanism to bring connectivity and internet services to those places that lack commercial interest. 

Presentations ranged from highlighting the need for measuring Quality of Experience (QoE) for Community Networks, to the potential role the Content Delivery Network (CDN) can play in Community Networks, to the role of Satellite Networks, and finally, to the vital role of the spectrum in this space.

### Community Networks and the Quest for Quality

{{MARTINEZ}}

### A ‘C’ in CDN: Access service to and from the Internet at cost for community networks

{{BENSON}}

### Closing the Performance and Management Gaps with Satellite Internet: Challenges, Approaches, and Future Directions

{{HU}}

### Maximising Connectivity: The Spectrum’s Vital Role in Technology Access 

{{RENNO}}

### Discussion

## Session 2: Digital Divide - Reports and Comments

TODO Session 2

## Session 3: Censorship - Measurements

This session focused on reports of censorship as observed during recent years in different parts of the world, as well as on the use of and expectation on censorship circumvention tools, mainly use of secure VPN services.

The censorship reports, with a focus on Asia, and specifically India, as well as Russia, as an example where censorship changes significantly recently, discussed the legal frameworks and court acts that put legal obligation on regional network providers to block traffic and also measurements to validate the blocking as well as analyses how blocking is implemented, i.e. which protocols are used but also which kind of devices are used to configure the blocking rules and where are they deployed.

Further, the possibility and prevalence for using VPNs for circumvention has been discussed including user expectation and an analysis of security short-comings of commercial VPN services. This analysis has shown various problems that lead to data leaks, not uploading user expectations especially when used in authoritarian regimes for censorship circumvention or private communication.

## Conclusions


--- back

# Position Papers

TODO Position Papers

# Workshop Participants

TODO Workshop Participants

# Workshop Program Committee

The workshop program committee members were Christopher Wood (IAB, Cloudflare), Dhruv Dhody (IAB, Huawei), Mallory Knodel (IAB, Center for Democracy and Technology), Mirja Kühlewind (IAB, Ericsson), and Tommy Pauly (IAB, Apple).

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
