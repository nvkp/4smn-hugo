---
title: Administrativní bezpečnost 2
weight: 6
---

# Administrativní bezpečnost 2

*řízení bezpečnostních incidentů — postupy organizační struktury, řízení bezpečnostních incidentů*

## Kybernetická bezpečnostní událost

událost, která může způsobit nebo vést k narušení informačních systémů a technologií a pravidel definovaných k jeho ochraně **(Jirásek a kol.)**

identifikovatelný stav systému, služby, nebo sítě, ukazující na možné porušení bezpečnostní politiky nebo selhání bezpečnostních opatření. Může se také jednat o jinou předtím nenastalou situaci, která může být důležitá z pohledu bezpečnosti informací **(ISO 27001)**

nepříznivá událost s negativním důsledkem, jako jsou havárie (pády) systému, packet flooding, neautorizované použití systémových oprávnění, neautorizovaný přístup k citlivým datům nebo spuštění škodlivého kódu, který ničí data. **(NIST)**

událost, která může způsobit narušení bezpečnosti informací v informačních systémech nebo narušení bezpečnosti služeb anebo bezpečnosti a integrity sítí elektronických komunikací. **(ZoKB § 7)**

De facto jde o událost bez zatím reálného negativního následku pro daný komunikační nebo
informační systém, ve své podstatě se jedná pouze o hrozbu, která však musí být reálná.

## Kybernetický (bezpečnostní) incident

porušení nebo bezprostřední hrozbu porušení bezpečnostních politik, bezpečnostních zásad nebo standardních bezpečnostních pravidel provozu Informační a komunikační technologie. **(Jirásek a kol.)**

jedna nebo více nechtěných nebo neočekávaných bezpečnostních událostí, u kterých existuje vysoká pravděpodobnost kompromitace činnosti organizace a ohrožení bezpečnosti informací. **(ISO 27001)**

porušení nebo bezprostřední hrozbu porušení bezpečnostních politik, politiky akceptovatelného použití (systému, služby) nebo standardní bezpečnostní praxe. **(NIST)**

narušení bezpečnosti informací v informačních systémech nebo narušení bezpečnosti služeb anebo bezpečnosti a integrity sítí elektronických komunikací v důsledku kybernetické bezpečnostní události. **(ZoKB § 7)**

Podstatné je, že dojde k narušení bezpečnosti informací, nebo služeb a informačních a komunikačních systémů s nimi spojených. Kybernetický bezpečnostní incident tak představuje skutečné narušení bezpečnosti informací v informačních systémech nebo narušení bezpečnosti služeb anebo bezpečnosti a integrity sítí elektronických komunikací, tj. narušení informačního nebo komunikačního systému s negativním dopadem. 

Za určitou část kybernetických bezpečnostních incidentů jsou zodpovědné i náhodné jevy, chyby hardwaru, softwaru, chyby učiněné při konfiguraci administrátory, chyby uživatelů systémů aj.

## SIMS (ISO 27035)

Security Incident Management System (systém zvládání bezpečnostních incidentů)
Formulace a plánování systému zvládání bezpečnostních incidentů vede k ná­vrhu systému zvládání bezpečnostních incidentů. Vychází z bezpečnostní po­litiky organizace a z bezpečnostní politiky IS/ICT organizace, respektuje i ostatní doku­menty.

### Hlavní činnosti

* sestavení a vyhlášení politiky zvládání bezpečnostních incidentů včetně přidělení příslušných pravomocí a odpovědností
* sestavení, formalizace a popis procesu zvládání bezpečnostních incidentů
* nastavení způsobu sběru dat pro vyhodnocování chodu systému zvládání bezpečnostních incidentů
nastavení základních hodnot ukazatelů pro měření úspěšnosti SIMS
* definice dokumentů a dokumentačních povinností pro pracovníky, kteř se podílejí na řešení bezpečnostního incidentu
* ověření platnosti aktuálních bezpečnostních dokumentů a dokumentace vzhledem k procesu zvládání bezpečnostních incidentů
* sestavení týmu řešení bezpečnostních incidentů (Information Security Incident Response Team - ISIRT)
* postupy pro sestavování krizových scénářů a procesů v případě krizového stavu organizace vinou bezpečnostního incidentu (organizační struktury, kompetence a odpovědnosti)
* plán proškolování pracovníků organizace v problematice bezpečnostních incidentů a jejich řešení
* plány, postupy a způsoby testování procesu řešení bezpečnostních incidentů - vazba na BCM (Business Continuity Management)


### Postup řešení bezpečnostního incidentu

#### Detekce události

Jedná se o klíčový okamžik pro úspěšné vyřešení bezpečnostního incidentu. Zde se totiž uživatel setkává poprvé s bezpečnostní událostí, kterou musí umět roz­po­znat a musí ji nahlásit příslušným organizačním strukturám – v praxi to bývá nej­častěji oddělení služby Service Desk. Je nezbytné, aby jak uživatelé, tak hlavně i pracovníci Service desku měli dobré bezpečnostní povědomí.

Další významný bod pro budoucí úspěšné řešení bezpečnostní události, resp. bez­pečnostního incidentu, je množství primárních informací, které se o incidentu po­daří zjistit. Proto musí být uživatel schopen takové informace zjistit a zajistit – zdokumentovat.

Základními dokumenty jsou for­muláře pro hlášení bezpečnostní události a bezpečnostního incidentu. Oba musí splňovat nelehkou podmínku. Tou je fakt, že musí shromáždit co nejvíce infor­mací o události nebo incidentu a zároveň je musí být schopen správně vypl­nit neodborník – běžný uživatel informačního systému. Vzory a návrhy, jak může takový formulář vypadat, jsou uvedeny v ISO 27035-1.

#### Identifikace, rozhodnutí, příprava řešení

Rozhodnutí, jedná-li se o bez­peč­nostní incident. Tuto část pra­covníci Service Desku, resp. služby pro podporu provozu informačního systému v orga­nizaci - přebírají od uživatelů hlášení o bezpečnostním incidentu a provádějí jeho první identifikaci. Hlavním úkolem pracovníků pod­pory provozu je:
* zjistit od uživatelů co nejvíce informací o incidentu,
* provést primární identifikaci incidentu,
* přesně zdokumentovat zjištěná data,
* uvědomit tým řešení bezpečnostních incidentů a aktivovat jeho činnost,
zjištěná data předat profesionálním pracovníkům z týmu řešení bezpeč­nostních incidentů.

Významná je především činnost primární identifikace incidentu – zjišťuje se:
* příčina vzniku incidentu,
* místo jeho vzniku, případně způsob, jakým vznikl,
* rozsah aktiv organizace, jež jsou incidentem ohrožena.

Při primární identifikaci incidentu používají pracovníci Service Desku obvykle, na základě analýzy bezpečnostních rizik, speciálně připravený seznam potenci­ál­ních bezpečnostních incidentů spolu s pravděpodobnými důsledky jejich do­padu pro jednotlivé části organizace nebo pro organizaci jako celek. Vazby na RA -  organizační struktury.


#### Řešení bezpečnostního incidentu

Základní zjištěné informace o bezpečnostním incidentu spolu s jeho primární identifikací jsou předány týmu řešení bezpečnostních incidentů. Ten má za úkol dostat incident nejprve pod kontrolu a ve finále jej vy­řešit. Jeho členové provedou jeho konečnou klasifikaci. Při analýze je možné, že bude tým potřebovat pomoc externích expertů. Na základě zjištěných faktů navrhuje tým vlastní řešení bezpečnostního incidentu. Přijatá řešení potom uvádějí v organizaci do života linioví manažeři a manažeři bezpečnosti. 

Jiná situace nastane v okamžiku, kdy tým řešení bezpečnostních incidentů není schopen situaci vyřešit. Tehdy je nutné vyhlásit krizový stav v organizaci. To může znamenat např. omezení podpory některých činností organizace informač­ním systémem nebo přerušení dodávek všech služeb, které informační systém po­skytuje. Pro takové případy je nutné mít v organizaci připravené nouzové scé­náře v rámci tzv. řízení kontinuity činností organizace a návazně i procesy zajištění obnovy činností po ha­várii (Disaster Recovery Planning). 

Významným úkolem této fáze životního cyklu řešení bezpečnostního incidentu je všechna zjištěná fakta, navržená opatření a provedené kroky, spolehlivě a hlavně přesně zdokumentovat. Přesná doku­mentace všech kroků a zjištěných faktů je také nutná pro případné následné uplatňování náhrady škody vůči pojišťovnám nebo při projednávání následků in­cidentů (resp. řešení náhrady jimi způsobené škody) u soudů.


#### Vyhodnocení incidentu

Vyhodnocováním bezpečnostního incidentu přechází řízení bezpečnosti infor­mací od pasivní úlohy k úloze proaktivní. Vyřešením incidentu jsou zažehnány akutní potíže organizace (snad). Ob­sahem etapy vyhodnocování incidentu jsou zejména:

* hlubší analýza bezpečnostního incidentu a její závěry,
* aktualizace dat o vyřešených bezpečnostních incidentech,
* poučení z incidentu pro potřeby zvyšování bezpečnostního povědomí v organizaci,
* dopady incidentu na proces i obsah zvládání bezpečnostních incidentů.

Při pravidelném vyhodnocování bezpečnosti informací v organizaci jsou pak závěry, získané z bezpečnostních incidentů, využívány pro rozvoj a zdo­konalování systému řízení bezpečnosti informací v organizaci – PDCA cyklus ISMS.


## Kategorie bezpečnostních incidentů (Vyhláška č. 82/2018 Sb., o kybernetické bezpečnosti)

* **Kategorie III – velmi významný kybernetický bezpečnostní incident**, při kterém je přímo a významně narušena bezpečnost poskytovaných služeb nebo aktiv. Jeho řešení vyžaduje neprodlené zásahy obsluhy s tím, že musí být všemi dostupnými prostředky zabráněno dalšímu ší­ření kybernetického bezpečnostního incidentu včetně minimalizace vznik­lých i potenciálních škod.
* **Kategorie II – významný kybernetický bezpečnostní incident**, při kterém je narušena bezpečnost poskytovaných služeb nebo aktiv. Jeho řešení vyžaduje neprodlené zásahy obsluhy s tím, že musí být vhodnými prostředky zabráněno dalšímu šíření kybernetického bezpečnostního in­cidentu včetně minimalizace vzniklých škod.
* **Kategorie I – méně významný kybernetický bezpečnostní incident**, při kterém dochází k méně významnému narušení bezpečnosti poskyto­vaných služeb nebo aktiv. Jeho řešení vyžaduje zásahy obsluhy s tím, že musí být vhodnými prostředky omezeno další šíření kybernetického bez­pečnostního incidentu včetně minimalizace vzniklých škod.

## NIST

### Information Security Incident LIfecycle

* Preparation
* Detection & Analysis
* Containment & Eradication & Recovery
* Post-Incident Activity

## Organizační struktury

Bezpečnostní týmy typu CERT (Computer Emergency Response Team) nebo CSIRT (Computer Security Incident Response Team) odpovídají za agendu sou­visející s řešením bezpečnostních incidentů v rámci státu, odvětví, komunity, or­ganizace či sítě. Jejich agenda je velmi široká a zahrnuje množství úkolů od pre­vence a zvyšování povědomí, detekci, sledování a řešení incidentů, až po vy­hod­nocování zkušeností. Bezpečnostní týmy vznikají zejména za účelem zajištění efektivní reakce na kybernetické bezpečnostní incidenty.

U těchto bezpečnostních týmů je klíčové zejména jejich zapojení do světové bez­pečnostní komunity a infrastruktury bezpečnostních týmů, sdílení informací s ko­munitou a stanovení formálních postupů. Bezpečnostní tým zpravidla musí ve­řejně deklarovat své kontaktní informace a pravidla činnosti – kdo jsou jeho čle­nové, způsob jak a kdy je možné tým zastihnout, jaké služby nabízí a zejména pak definovat své pravomoci a odpovědnost (např. v oblasti sítí, ICS/SCADA apod.). Na základě jeho pole působnosti je tým kontaktován (např. napadenými subjekty), které podporuje při řešení jejich kybernetických bezpečnostních inci­dentů.

Kategorie týmů:
* **interní**: Např. bezpečnostní tým konkrétní organizace. Při řešení incidentů má možnost přímého zásahu (např. odpo­jení zdroje problému, rekonfigurace filtrací síťového provozu, na­sazení no­vého bezpečnostního opatření).
* **koordinační**: Např. národní bezpečnostní tým nebo bezpečnostní tým určité komu­nity nebo odvětví. Jeho působnost je často vymezena zá­kony nebo pra­vidly komunit/odvětví. Při řešení incidentů nemá možnost přímého zásahu. Soustřeďuje se na komunikaci, spolupráci a zprostředkování informací.

Z pohledu kybernetického zákona mají v České republice zákonnou oporu dva bezpečnostní týmy – Vládní CERT a Národní CERT. Vládní CERT je provozován ze strany NÚKIB, jakožto gestorem kybernetické bezpečnosti (v praxi se můžeme setkat s názvem GovCERT.CZ). Národní CERT (CSIRT.CZ) je provozován sdru­žením CZ.NIC podle veřejnoprávní smlouvy uzavřené s NÚKIB.

### Služby Vládního CERTU

* proaktivní
    * penetrační testování
    * kybernetická cvičení
    * včasné varování
    * bezpečnostní doporučení
    * zvyšování bezpečnostního povědomí
    * Zprostředkování kontaktů napříč různými institucemi za účelem zvyšování bezpečnosti
    * Sdílení a analýza dat o zranitelnostech, hrozbách, infikovaných IP adresách apod.
* reaktivní
  * koordinace
  * technická podpora
  * analýza malware

### CSIRT

**Computer Secu­rity Incident Response Team**: Skupina pro reakce na počítačové bezpečnostní incidenty: Tým odborníků na informační bezpeč­nost, jejichž úkolem je řešit bezpečnostní incidenty. CSIRT poskytuje svým klientům po­třebné služby při řešení bezpečnostních incidentů a pomáhá jim při obnově systému po bezpečnostním incidentu. 

Aby snížila rizika incidentů a mini­malizovala jejich počet, pracoviště CSIRT poskytují svým klientům také preven­tivní a vzdě­lá­vací služby. Pro své klienty poskytují informace o odhalených slabinách používa­ných hardwarových a softwarových prostředků a o možných útocích, které těchto slabin využívají, aby klienti mohli dostatečně rychle ošetřit odhalené slabiny.

### ISIRT

**interní tým řešení bezpečnostních incidentů**. Jedná se o organizační struk­turu, která se využívá výhradně pro potřeby řešení incidentů. Jeho členy se stá­vají zku­šení a důvěryhodní pracovníci organizace, kteří mají zkušenosti s řešením tako­vých situací. Ti se věnují řešení incidentů po celý jeho životní cyklus až do závě­rečné etapy vyhodnocení a zobecnění jeho závěrů a výsledků do celkové koncepce ISMS. V některých případech je tento tým posilován o ex­terní specialisty.

Pro praktické řešení je možné doporučit za vedoucího týmu osobu z vr­cholového vedení organizace. Kromě něj by se měli na práci týmu po­dílet bezpeč­nostní manažeři různých dotčených úrovní a podle charakteru inci­dentu odborníci na problém a případně i liniový manažer pracoviště, kde inci­dent vznikl. Tým ře­šení bezpečnostních incidentů má svoje trvalé členy a členy, kteří jsou do něj jme­nováni pro řešení určitých konkrétních incidentů.

### Síť CSIRT

Směrnice ji definuje jako skupinu CSIRT/CERT týmů členských států a týmu CERT-EU. Primárním úkolem této skupiny je zajišťovat výměnu informací, osvědčených postupů a pod­poru při ře­šení incidentů na úrovni Evropské unie. – makro pohled na kybernetickou bezpečnost.









