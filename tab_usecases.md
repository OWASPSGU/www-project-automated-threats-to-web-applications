---
title: Usecases
displaytext: Use Case Scenarios
layout: null
tab: true
order: 2
tags: oat
---

## Use Case Scenarios

The following scenarios and organisation names are completely fictitious.

### Defining application development security requirements
Cinnaminta SpA intends to build and launch a new multi-lingual and multi-currency ecommerce website. The development will be outsourced and Cinnaminta has been working on the functional design document. Among many other requirements, the application security specification requires that the website must not include any vulnerabilities identified in PCI DSS v3.1 Requirement 6.5, nor any other vulnerabilities that could affect the protection of payment cardholder data. Cinnaminta specifies that the website's payment functions must not be susceptible to the threat events **OAT-001 Carding** or **OAT-010 Card Cracking** as defined in the **OWASP Automated Threat Handbook**. In addition, the application must interact with the company's existing fraud detection system to counter **OAT-012 Cashing Out**. The requirements are specified in terms of these threat events, rather than particular product or service categories. Development houses responding to the call for bids use the ontology to focus their answers to these aspects appropriately.

###Sharing intelligence within a sector
Unlimited Innovations Inc develops and supports patient-facing software solutions to a range of healthcare providers, many of which participate in the National Health Service Cyber Intelligence Sharing Center (NHS-CISC). Unlimited Innovations already builds continuous monitoring capabilities into its software and decides to provide an optional enhancement so that customers could choose to share their misuse event data with each other, to benefit from the combined threat intelligence. Rather than sharing large quantities of low-level data, Unlimited Innovations aggregates information and broadcasts validated and categorised threat data amongst the participating organisations. Automation attacks are classified according to the threat events defined in the **OWASP Automated Threat Handbook** so that each receiving party understands the nature of the threat. Even organisations that do not want to take part in this information sharing can benefit, since their own categorised information is made available to internal business management in the form of an easy-to-comprehend monitoring dashboard. The information gathered can also be fed into their other business information management systems to help improve patient service.

###Exchanging threat data between CERTs
National Computer Emergency Response Teams (CERTs) recognise that sharing of local information can contribute to worldwide prevention of cyber attacks. Despite advances in cooperation between CERTs, anything to increase continuity and interoperability, such as standards for data exchange, is encouraged. CERT Zog is concerned about the sparsity of application-specific data it receives, and also the classification of that data. It has a particular concern about attacks and breaches that affect sectors defined in Zog's 2015 national cyber security strategy. CERT Zog and its neighbour CERT Tarset agree to tag threat events using the **OWASP Automated Threat Handbook** in order to add greater context to existing solutions being used for threat data exchange between them. The programme also collects sector metadata, so that all organisations within these can benefit from the centralised intelligence.

###Enhancing application penetration test findings
Specialist application security penetration testing firm Cherak Industries Pte Ltd works primarily for financial services companies in the banking and insurance sectors, and is looking to expand its business throughout Asia. Cherak has some innovative pen test result reporting systems which integrate with client software fault and vulnerability tracking systems, and it actively looks for methods to provide additional value to its clients. Cherak has identified that pen test clients would benefit from help to in understanding the effects of combinations of vulnerabilities, especially design flaws, and has decided to utilise the **OWASP Automated Threat Handbook** to define and explain the automation-related threats. The individual vulnerabilities were scored as normal using CVSSv2 and v3, the matching CWEs identified, and mitigations in place documented. In addition, Cherak uses the threat events defined in the **OWASP Automated Threat Handbook** to help create a new section in the executive summary that explains how combinations of the issues found could lead to automation threats and the possible technical and business impacts. For example, an assessment for one client had identified weaknesses in authentication so that there is a risk of **OAT-008 Credential Stuffing**. The defined identifier was provided to the client, so its technical staff could refer to additional information on the OWASP website.

###Specifying service acquisition needs
Falstone Paradise Inc is concerned about malicious use of their portfolio of hotel and resort websites. The majority of the websites use a shared application platform, but there are some unique applications and a large number of other micro-sites, some of which use generic content management systems such as Wordpress and Drupal. Falstone Paradise has identified that its IT operations team are spending too much time dealing with the effects of automated misuse, such as cleaning up data, resetting customer accounts and providing extra capacity during attacks. Furthermore, the unwanted automation is also causing some instabilities leading to negative feedback from customers. Therefore Falstone Paradise decides to go out to the security marketplace to identify, assess and select products or services that might help address these automation issues for all its websites. Their buying team works with their information technology colleagues to write the detailed requirements in an Invitation to Tender (ITT) document. This describes the types of attacks its web applications are receiving, their frequency of occurrence and their magnitudes. These are defined according to the **OWASP Automated Threat Handbook**, so that vendors do not misunderstand the requirements, and each vendor's offering can be assessed against the particular automation threat events of concern.

###Characterising vendor services
Better Best Ltd has developed an innovative technology to help gaming companies defend against a range of automated threats that can otherwise permit cheating and distortion of the game, leading to disruption for normal players. The solution can be deployed on premises, but is also available in the cloud as a service. But Better Best is finding difficulty explaining its solution in the market place, especially since it does not fit into any conventional product category. Better Best decide to use the terminology and threat events listed in the **OWASP Automated Threat Handbook** to define their product's capabilities. They hope this will provide some clarity about their offering, and also demonstrate how their product can be used to replace more than one other conventional security device. Additionally, Better Best writes a white paper describing how their product has been successfully used by one of their reference customers Hollybush Challenge Games to protect against **OAT-006 Expediting**, **OAT-005 Scalping**, **OAT-016 Skewing** and **OAT-013 Sniping**.