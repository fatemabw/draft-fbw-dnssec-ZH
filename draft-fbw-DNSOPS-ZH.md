---
title: "A method to prevent Zone-walking in DNSSEC-NSEC"
abbrev: "Preventing zone-walking in DNSSEC-NSEC"
category: info

docname: draft-fbw-DNSOPS-ZH-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: AREA
workgroup: DNSOP Working Group
keyword:
 - DNSOp
 - Zone Walking
 - DNSSEC-NSEC
venue:
  group: WG
  type: Working Group
  mail: WG@example.com
  arch: https://datatracker.ietf.org/wg/dnsop/
  github: fatemabw/draft-fbw-dnssec-ZH
  latest: https://github.com/fatemabw/draft-fbw-dnssec-ZH

author:
 -
    ins: F. Wala
    fullname: Fatema Bannat Wala
    organization: Energy Sciences Network
    email: fatemebw@es.net
 -
    ins: S. Bohacek
    fullname: Stephan K Bohacek
    organization: University of Delaware
    email: bohacek@udel.edu
 -  
    ins: N. Buraglio
    fullname: Nick Buraglio
    organization: Energy Sciences Network
    email: buraglio@forwardingplane.net

normative:
  RFC2119:
informative:
  RFC9364:
  RFC4470:
  RFC5155:
  IEEE-ZoneHopping:
    target: https://dsn2024uq.github.io/Proceedings/pdfs/DSN-S2024-3LLnxbOIgEGedw7VY2pz6a/957000a104/957000a104.pdf
    title: "Zone-Hopping: Sensitive Information Leakage Prevention for DNSSEC-NSEC"

--- abstract

DNS Security Extension (DNSSEC) as defined by [RFC9364] was developed to address significant security integrity flaws in DNS. Within certain circumstances, information leakage may be possible stemming from a known DNSSEC vulnerability that facilitates a process known as zone walking, which enables the efficient collection of all FQDNs from a given environment.

--- middle

# Introduction

TODO Introduction


# Conventions and Definitions

{::boilerplate bcp14-tagged}

Zone Walking:

DNSSEC: [RFC9364]

NSEC3 White Lies:

Black Lies (BL):


# Practical Considerations:
[RFC5155]
[RFC4470]

# Security Considerations

## IP Address Discovery

## Domain Enumeration

# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
