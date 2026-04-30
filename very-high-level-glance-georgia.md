---
source_url: https://dbnsa.sharepoint.com/sites/ComplianceOfficers93/Regulatory Repository/Rest of World/Georgia/5. Other Documents/VERY HIGH LEVEL GLANCE - GEORGIA.pdf
country: Georgia
document_name: VERY HIGH LEVEL GLANCE - GEORGIA
source_file: VERY HIGH LEVEL GLANCE - GEORGIA.pdf
source_url: https://dbnsa.sharepoint.com/sites/ComplianceOfficers93/Regulatory%20Repository/Rest%20of%20World/Georgia/5.%20Other%20Documents/VERY%20HIGH%20LEVEL%20GLANCE%20-%20GEORGIA.pdf
extracted_date: 2026-04-30
jurisdiction: Georgia
description: Very high-level overview of Georgia regulatory requirements, implementation considerations, and operational concerns for gaming.
regulatory_body: Revenue Service of Georgia
---

# VERY HIGH LEVEL GLANCE – GEORGIA

## REGULATION REFERENCE

We have little to no legislation in documented form. Have worked of a decree circa 2013

http://bluepoint.mgsops.net/sites/regulatedmarkets/Georgia/Forms/AllItems.aspx?RootFolder=%2Fsites%2Fregulatedmarkets%2FGeorgia%2F01%2E%20Legislation&FolderCTID=0x0120003F74EA9502DF68459268EB0C8674CA66&View=%7BBC071EDC-7FD4-4A3C-8B9E-727EA058D28A%7D

## SUMMARY

- Minimal/no regulatory technical requirements around responsible gaming and limits
- No restrictions on marketing known. Awaiting feedback on draft bill that might restrict marketing (mid November – December)
- Complexity comes through need to integrate bespoke content and integrate into unique/unknown payment service
  - EGT and Yggdrasil are needed (can be provided by iForium)
  - Localised content needed (backgammon, dominoes, bura)

**Major Concerns:**

- Technical complexity through need to integrate bespoke content and integrate into unique/unknown payment service
- Brand new adaptation of sports front end layout would be required (work effort unknown)

**Comparative Complexity:** High (not due to regulatory requirements but due to bespoke integrations required in games and banking)

## HIGH LEVEL REQUIREMENTS

## REGISTRATION AND LOGIN

### Feature Requirements Comments

#### Information for Player

Article 12: For arrangement through internet – web address, rules for registering the player; regulations for managing deposit/balance; the website must contain the information in Georgian language about the organizer name, legal address, telephone number, permit number, list of games, detailed rules of the game, information about prohibition of gaming for persons under 18 years of age;

Information only and access to game rules

#### No minors (under 18)

Article 12: For arrangement through internet – web address, rules for registering the player; regulations for managing deposit/balance; the website must contain the information in Georgian language about the organizer name, legal address, telephone number, permit number, list of games, detailed rules of the game, information about prohibition of gaming for persons under 18 years of age;

Information and age confirmation will be compliant. No prescriptive method to ban these players

#### Registration Fields

Article 29: In case of a systemic-electronic arrangement of gambling and/or games of chance ensure registration of each gambler according to personal identification data; (9.12.2011. N5448 to enter into force from January 3, 2012)

Not clear what this is but just ensure correct ID fields required in registration

## GAMES

### Feature Requirements Comments

#### 80% RTP

Article 23: At least 80 percent of the wager should be considered as a profit at a gambling machine.

#### Helpfiles

Article 27: Rules of a game should be placed where the game is held and presented to a gambler upon an initial request.

Standard

#### Changes to rules of game or game maths

Article 13: Organizer of games of chance (except sweepstakes) must make announcement about any changes in the rules of systemic-electronic games on the website of the game (in case of internet arrangement) and within two business days of amendments, inform the revenue service. (9.12.2011. N5448 to enter into force from January 3, 2012)

Article 21: The game organizer must make announcement about any changes in the rules of systemic-electronic games on the website of the game (in case of internet arrangement) and within two business days of amendments, inform the revenue service.

Operators can publish after deployment or help files can contain – we pretty much never change maths or “rules” to existing games

## DATA LOGGING/REPORTING/ARCHIVING

### Feature Requirements Comments

#### General Storage

Article 29: Keep a registration of payouts of winnings, create an electronic database and provide information to the legal entity - Georgian Financial Monitoring Service in accordance with the Georgian legislation;

Simple database maintenance. Information on request? Access to database? Nothing about replication to third party database