---
title: Penetrační testování
weight: 10
---

# Penetrační testování

**Penetrační testy:** ověření bezpečnosti IS za pomoci nástrojů a postupu používaných skutečnými útočníky

## Způsoby ověření bezpečnosti
1. **Assessment** (org. pohledy, politiky, procedury): zkoumání dokumentace a uživatelů
2. **Evaluation** (systémová, síťová úroveň identifikace bezpečnostních slabin, validace implementace, dokumentace): firewall, konfigurace..
3. **Blue and red team**(reálné pokusy o průniky = penetrační testy): simulace reálného útoku

## Důvody provedení penetračního testu
* compliance
* ověření bezpečnosti v rámci vývoje/akceptace
* ověření bezpečnosti již běžícího systému
* ověření úrovně incident response
* ověření odolnosti zaměstnanců proti sociálnímu inženýrství

## Typy penetračních testů
* **Interní** (z organizace ale i z domova přes vpn) vs. **externí** (přístup jako klient atd)
* **Black box** (tester neví o IS nic) vs. **White box** (tester má všechny informace)
* **Skrytý** (tajný test) vs. **otevřený**
* **agresivní** (exploit) vs. **opatrný**
* **externí firmou** vs. **vlastními silami**
* **kompletní** vs. **omezený**

## Metodický postup dle ISSAF 

**ISSAF**: Information Systems Security Assessment Framework


1. **Pre assessment** (planning and preparation)
    * requirements identification
    * stakeholder identification
    * management team appointment
    * defining scope (+ co je out-of-scope)
    * defining rules
2. **Assessment**
    * information gathering
    * network mapping
    * vulnerability identification
    * penetration
    * gaining access and privilege escalation
    * enumerating further
    * compromise remote users/sites
    * maintaining access
    * covering tracks
3. **Post assessment**
    * cleanup
    * document analysis
    * report creation
    * report representation
    * results acceptance

## Dokumentace kolem pentestů
* NDA (non-disclosure agreement): smlouva o mlčenlivosti
* Request for Information (RFI): zjištění, jestli je to dodavatel schopný udělat
* Request for Proposal
* Agreement
* Rules of Engagement: účel, cíl, metodika, scope, časový plán, zdroj a cíl testu (IP adresy), povolené techniky a nástroje, komunikační matice…
* Stage Progress Report
* Final Report
* Lessons Learned

## Metodiky
* OSSTM: obecný rámec nejen pro pentesty
* Technical Guide to Information Security Testing and Assessment (NIST SP 800-115)
* OWASP testing guide: testování webových aplikací
* Penetration Testing Execution Standard (PTES)





