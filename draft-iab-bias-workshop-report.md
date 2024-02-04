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
  GUIFI:
    target: https://guifi.net/en
    title: Guifi.net
  APC:
    target: https://www.apc.org/
    title: The Association for Progressive Communications (APC)
  ISOC:
    target: https://www.internetsociety.org/action-plan/community-networks/
    title: Community networks help bridge the connectivity gap
  TBB:
    target: https://tribalbroadbandbootcamp.org/
    title: Tribal Broadband Bootcamp
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
  PANGEA:
    target: https://www.cloudflare.com/en-gb/pangea/
    title: Project Pangea from Cloudflare
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
  GAIA:
    target: https://www.irtf.org/gaia.html
    title: Global Access to the Internet for All Research Group
  SAMSUDIN:
    target: https://www.ietf.org/slides/slides-biasws-position-paper-by-raquel-renno-01.pdf
    title: iMAP (Internet Monitoring Action Project) 2023 Internet Censorship Report
    author:
      -
        ins:  S.  Samsudin
        name: Siti Nurliza Samsudin
    date: January 2024
  GROVER:
    target: https://datatracker.ietf.org/meeting/interim-2024-biasws-03/materials/slides-interim-2024-biasws-03-sessa-online-censorship-in-india-pakistan-and-indonesia-00
    title: Online censorship in India, Pakistan and Indonesia
    author:
      -
        ins:  G. Grover
        name: Gurshabad Grover
    date: January 2024
  Grover2023:
    target: https://archive.org/details/eaten-by-the-internet/
    title: The infrastructure of censorship in Asia
    author: 
      -
        ins:  G. Grover
        name: Gurshabad Grover
      -
        ins:  C. Cath
        name: Corinne Cath (ed.)
    date: October 2023
  Singh2020:
    target: https://dl.acm.org/doi/abs/10.1145/3394231.3397891
    title: How India Censors the Web
    author: 
      -
        ins:  K. Singh
        name: Kushagra Singh
      -
        ins:  G. Grover
        name: Gurshabad Grover
      -
        ins:  V. Bansal
        name: Varun Bansal
    date: July 2020
  BASSO:
    target: https://datatracker.ietf.org/meeting/interim-2024-biasws-03/materials/slides-interim-2024-biasws-03-sessa-online-censorship-in-india-pakistan-and-indonesia-00
    title: How Internet censorship changed in Russia during the 1st year of military conflict in Ukraine
    author:
      -
        ins:  S. Basso
        name: Simone Basso
    date: January 2024
  WANG:
    target: https://datatracker.ietf.org/meeting/interim-2024-biasws-03/materials/slides-interim-2024-biasws-03-sessa-online-censorship-in-india-pakistan-and-indonesia-00
    title: Network Measurement Methods for Locating and Examining Censorship Devices
    author:
      -
        ins:  R. S. Raman
        name: Ram Sundara Raman
      -
        ins:  M. Wang
        name: Mona Wang
      -
        ins:  J. Dalek
        name: Jakub Dalek
      -
        ins:  J. Mayer
        name: Jonathan Mayer
      -
        ins:  R. Ensafi
        name: Roya Ensafi
    date: November 2023
  RAMESH:
    target: https://datatracker.ietf.org/meeting/interim-2024-biasws-03/materials/slides-interim-2024-biasws-03-sessa-investigating-the-vpn-ecosystem-through-the-lens-of-security-privacy-and-usability-00
    title: Investigating the VPN Ecosystem through the lens of Security, Privacy, and Usability
    author:
      -
        ins:  R. Ramesh
        name: Reethika Ramesh
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

This document is a report on the proceedings of the workshop. The views and positions documented in this report are expressed during the workshop by participants and do not necessarily reflect IAB's views and positions.

Furthermore, the content of the report comes from presentations given by workshop participants and notes taken during the discussions, without interpretation or validation.  Thus, the content of this report follows the flow and dialogue of the workshop but does not attempt to capture a consensus.

# Workshop Scope and Discussion

The workshop was organized across three days with all-group discussion slots, one per day. The following topic areas were identified and the program committee organized paper submissions into three main themes for each of the three discussion slots. During each discussion, those papers were presented sequentially with open discussion held at the end of each day.

## Session 1: Community Networks - Their Role in Internet Access of Services

The first day of the workshop focused on the role of Community Networks {{RFC7962}} as a way to overcome the barriers to Internet Access. Community Networks are self-organized networks wholly owned by the community and thus provide an alternative mechanism to bring connectivity and internet services to those places that lack commercial interest.

Presentations ranged from highlighting the need for measuring Quality of Experience (QoE) for Community Networks, to the potential role the Content Delivery Network (CDN) can play in Community Networks, to the role of Satellite Networks, and finally, to the vital role of the spectrum in this space.

### The Quality of Community Networks

{{MARTINEZ}} highlighted the need to address Quality of Experience (QoE) in discussions around Community Networks. As a community-driven deployment, the knowledge and involvement of individuals can vary; therefore, there are no guarantees of connectivity or quality of service. There is a need to focus on user expectations and how they translate to measurable performance indicators. Further, it asks for better documenting best practices in deploying community networks as well as considering manageability considerations for community networks in protocol development. {{GUIFI}} as an example Community Network was discussed and some existing resources for Community Networks ({{APC}}, {{ISOC}}, and {{TBB}}) were shared by the participants.

The inconsistent quality and performance of Satellite Internet is a gap for community networks that rely on non-terrestrial networks (NTNs) for internet access {{HU}}.

### Strengthening Community Networks

{{BENSON}} focused on the prohibitive cost of the transit and Internet service for Community Networks and argued for Content Delivery Networks (CDNs) to provide transit-like and Internet services at no more than at-cost in a mutually beneficial way. Community networks still need backhaul to and from the CDN’s point of presence and models for community-backhaul and open-source CDNs were highlighted. Discussion included {{PANGEA}} project status as well as legal and commercial considerations in such use of CDNs.

{{HU}} highlighted that Satellite Internet provided by advanced LEO satellite constellations can play a pivotal role in closing the connectivity gap in the urban-rural digital divide via Satellite-dependent community networks. There existing known performance and management gaps that need focus to enable Satellite Internet to resolve the divide. Further, research directions such as multi-layer satellite networking, autonomous maintenance, and integration between Terrestrial and Non-Terrestrial networks were suggested.

{{RENNO}} called attention to the coveted 6GHz (part of the C-band with a desirable mix of coverage and capacity) as a prime choice for International Mobile Telecommunication (IMT) for 5G technology while it is in common unlicensed use in the community networks (and small ISPs). Spectrum allocations directly impact industries and market access with ramifications for community networks. Further, there was a discussion on the geopolitical tension because of it.

### Discussion

How can the technical community address the management gap and improve best practices for Community Networks? Is the increasing complexity of the Internet making it more challenging to establish connections, and should this be taken into account in the design of the Internet? Should the manageability consideration be expanded to explicitly consider Community Networks? Global Access to the Internet for All (GAIA) {{GAIA}} research group could be a venue for further discussion and research. Further discussion highlighted the need for readily available knowledge and tools for community networks as well as the tussle with market forces when commercial networks compete with community networks.

## Session 2: Digital Divide - Reports and Comments

TODO Session 2

## Session 3: Censorship - Reports and Circumvention

This session focused on reports of censorship as observed during recent years in different parts of the world, as well as on the use of and expectation on censorship circumvention tools, mainly the use of secure VPN services.

The censorship reports, with a focus on Asia, and specifically India, as well as Russia, as an example where censorship has changed significantly recently, discussed the legal frameworks and court acts that put legal obligations on regional network providers to block traffic. Further, measurements to validate the blocking as well as analyses of how blocking is implemented were discussed, i.e. which protocols are used but also which kind of devices are used to configure the blocking rules and where are they deployed.

### Censorship Orders, Measurements, and Device Analysis

{{SAMSUDIN}} reported on confirmed blocking from 10 countries (Cambodia, Hong Kong (China), India, Indonesia, Malaysia, Myanmar, Philippines, Thailand, Timor-Leste, Vietnam) in the period from 1 July 2022 to 30 June 2023. The blocking was either confirmed by OONI measurements for existing blocking fingerprints, heuristics, i.e. for new blocking fingerprints as well as news reports of blocking orders, or user experiences. Most of these countries block specific content such as porn, gambling, or certain news pages. Interestingly the blocking in Hong Kong and Myanmar is focused on the military and governmental pages of foreign countries. Blocking is often realized by either DNS tampering or HTTP tampering. For DNS, either a decided IP address, a bogon IP address (127.0.0.1), or an empty domain (nxdomain) is used. In case of DNS tampering using a decided IP address or HTTP tampering some countries provide a block page that exposes the blocking, however, more transparency about blocking is requested by civil society organizations and the iMAP project.

{{GROVER}} further focused the discussion on online censorship in India, Pakistan, and Indonesia. In India, where providers are responsible for implementing the blocking but no method is mandated, the six major ISPs (covering 98.82% of all subscribers) were tested on 4379 blocked websites (based on court orders, user reports, and publicly available or leaked government orders) on DNS poisoning/injection or HTTP/SNI-based censorship. Used censorship techniques and websites blocked were different across ISPs. Multiple ISPs used two different techniques (depending on the website), and all but one provided censorship notices. Providers blocked between 1892 to 3721 (of 4379) pages with only 1115 (27.64%) of pages blocked by all ISPs. {{Singh2020}} In contrast, in Pakistan, the government can also order the IPSs to perform blocking and blocking has even been observed in the past on the IXP level. Since 2020, there is also a central Web Monitoring System deployed at lines of international connectivity. In Indonesia, initially the government guided ISPs in how to perform the blocking. The regulations were updated in 2020 to allow Indonesian ISPs to block websites at their discretion. In 2022, there was a proposal by internet service providers to centralise DNS. In Indonesia, a partial block list is publicly available, but without any indication of why something is blocked. {{Grover2023}}

{{BASSO}} reported that for Russia a high increase in additions to the Roskomnadzor’s block list was observed in March 2022 as well as in December 2022, foremost covering news pages but also covering human rights organizations and social media, where more than 3500 blocking orders were added to the list by an "Unknown body". Further, blocking of domains that are not in the official Roskomnadzor’s list has been observed as well.

An invited talk presented the work in {{WANG}} on locating censorship devices by using HTTP and TLS traceroutes, identifying device vendors through fingerprinting, and reverse-engineering censorship triggers by use of fuzzing.
E.g. for the case of Azerbaijan and Kazakhstan, they showed that a significant portion of measurements from remote countries are blocked at the endpoint, indicating local policies but connection resets are also happening in Belarus and Russia. Further, they could identify a set of commercial network devices (firewalls) that are used in these countries for censorship and show how fuzzing can be used to fingerprint and cluster behaviors as well as potentially circumvent the deployed methods.

All speakers called for more transparency by requiring blocking messages as well as publication and auditing of blocklists. Potentially even standardization could help.

### Use of VPNs for Censorship Circumvents and user expectations

Further on in the session, the possibility and prevalence of using VPNs for circumvention has been discussed including user expectations and an analysis of security shortcomings of commercial VPN services. The analysis presented in {{RAMESH}} has shown various problems that lead to data leaks such as leakage of IPv6 traffic, non-browser traffic, or tunnel failure, not upholding user expectations, especially when used in authoritarian regimes for censorship circumvention or private communication.

The question of how common the use of VPNs for circumvention is and its legal implications, as VPNs are illegal in a few countries, has been discussed. E.g. VPNs are not officially banned in India but VPN providers need to store log data and those, who haven’t complied, stopped serving India. However, more data on VPN use and blocking might be needed.

### Discussion

After all, there is a cat-and-mouse game between censors and circumvents, however, continued work on protocol enhancements that protect user privacy is essential.

## Conclusions


--- back

# Position Papers

19 position papers were submitted to the workshop call for papers. 11 were selected for publication. Papers that were not published either (2) only provided a very prelimited analysis of an idea that was felt to be incomprehensive for discussion at the workshop, or addressed problems that were beyond the scope as dedicated for the workshop discussion e.g. discussing cyber security threads as a barrier for participation or implication of technology in regulation that imposes blocking. Both of these topics pose a potentially severe risk on the open Internet, however, these risks might provide a high risk for all Internet users but do not necessarily imply an unbalance.

All accepted papers are available at: https://datatracker.ietf.org/group/biasws/materials/

This is the list of all published papers:

Community Networks:

* L. M. Martínez-Cervantes, R. Guevara-Martínez:	Community Networks and the Quest for Quality
* T. Benson, M. Fayed:	A ‘C’ in CDN: Access service to and from the Internet for community networks at-cost
* P. Hu:	Closing the Performance and Management Gaps with Satellite Internet: Challenges, Approaches, and Future Directions
* R. Rennó:	Maximising Connectivity: The Spectrum's Vital Role in Technology Access

Digital Divide:

* R. Holz, N. Nazemi, O. Tavallaie, A.Y. Zomaya:	Evidence for a digital divide? Measuring DNS dependencies in the context of the indigenous population of Australia
* S. Hussain:	Universal Acceptance of Domain Names and Email Addresses: A Key to Digital Inclusion
* R. Habib, S. Tanveer, A. Inam, H. Ahmed, A. Ali, Z.A. Uzmi, Z.A. Qazi, I.A. Qazi:	A Framework for Improving Web Affordability and Inclusiveness
* J. Ott, G. Bartolomeo, M.M. Bese, R. Bose, M. Bosk, D. Guzman, L. Kärkkäinen, M. Kosek, N. Mohan:	The Internet: Only for the Fast (and Furious)?
* L.Y. Ohlsen:	BIAS workshop - M-Lab Position Paper submission

Censorship:

* S. Nurliza Samsudin:	iMAP (Internet Monitoring Action Project) 2023 Internet Censorship Report
* G. Grover:	The infrastructure of censorship in Asia
* S. Basso:	How Internet censorship changed in Russia during the 1st year of military conflict in Ukraine

In addition to the submitted paper two invited talks were presented based on published papers:

* R. Sundara Raman, M. Wang, J. Dalek, J. Mayer, R. Ensafi:	Network Measurement Methods for Locating and Examining Censorship Devices
* R. Ramesh, A. Vyas, R. Ensafi:	“All of them claim to be the best”: A multi-perspective study of VPN users and VPN providers

# Workshop Participants

The workshop participants were Arnaud Taddei, Carlos Pignataro, Carsten Bormann, Cindy Morgan, Colin Perkins, Cory Myers, Dan Sexton, David Guzman, David Millman, David Schinazi, Dhruv Dhody, Gurshabad Grover, Hanna Kreitem, Jane Coffin, Jiankang Yao, Jörg Ott, Juan Peirano, Lai Yi Ohlsen, Luis Martinez, Mallory Knodel, Marwan Fayed, Matthew Bocci, Michael Welzl, Michuki Mwangi, Mirja Kühlewind, Mona Wang, Peng Hu, Ralph Holz, Raquel Renno, Reethika Ramesh, Rumaisa Habib, Sarmad Hussain, Simone Basso, Siti Nurliza Samsudin, Suresh Krishnan, Theophilus Benson, Tirumaleswar Reddy, Tommy Pauly, Vesna Manojlovic, and Wes Hardaker.

# Workshop Program Committee

The workshop program committee members were Christopher Wood (IAB, Cloudflare), Dhruv Dhody (IAB, Huawei), Mallory Knodel (IAB, Center for Democracy and Technology), Mirja Kühlewind (IAB, Ericsson), and Tommy Pauly (IAB, Apple).

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
