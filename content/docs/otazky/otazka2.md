---
title: Řízení rizik informačního systému organizace
weight: 2
---

# Řízení rizik informačního systému organizace

## Hrozba

něco, co je schopno narušit běžný či řádný stav věcí a zasáhnout do práv jiných subjektů

**Definice z dikce Ministerstva vnitra ČR:** jakýkoli fenomén, který má potenciální schopnost poškodit zájmy a hodnoty chráněné státem

**Definice z výkladového slovníku kybernetické bezpečnosti:** potenciální příčina nechtěného incidentu, jehož výsledkem může být poškození systému nebo organizace

## Aktivum

cokoliv, co má určitou hodnotu pro osobu, organizaci či stát

## Zranitelnost

slabé místo aktiva, softwaru, zabezpečení, které je využito jednou nebo více hrozbami.

## Riziko

potenciál, že se hrozba stane reálnou a využije zranitelnosti aktiva

## Řízení rizik

Dle § 2 písm. d) VoKB (vyhláška o kybernetické bezpečnosti) se hodnocením rizik rozumí **celkový proces identifikace, analýzy a vyhodnocení rizik**. Na tento pojem bezprostředně navazuje § 2 písm. i) ZoKB (zákon o kybernetické bezpečnosti) definující řízení rizik, jako **činnost zahrnující hodnocení rizik, výběr a zavedení opatření ke zvládání rizik, sdílení informací o riziku a sledování a přezkoumání rizik**. Proces řízení rizik zahrnuje (§ 5 VoKB):

* stanovení metodiky pro hodnocení rizik, včetně stanovení kritérií pro akceptovatelnost rizik
* identikaci relevantní hrozby a zranitelnosti s ohledem na aktiva
* provedení hodnocení rizik v pravidelných intervalech (ZoKB):
    * alespoň 1x ročně pokud se jedná o:
        * správce a provozovatele informačního systému kritické informační infrastruktury
        * správce a provozovatele komunikačního systému kritické informační infrastruktury
        * správce a provozovatel informačního systému základní služby
    * alespoň 1x za 3 roky pokud se jedná o:
        * správce a provozovatel významného informačního systému
* zohlednění relevantní hrozby a zranitelnosti v rámci hodnocení rizik a posouzení možných dopadů na aktiva
* zpracování zprávy o hodnocení rizik
* zpracování na základě bezpečnostních potřeb a výsledků hodnocení rizik prohlášení o aplikovatelnosti. Toto prohlášení musí obsahovat přehled bezpečnostních opatření požadovaných vyhláškou o kybernetické bezpečnosti, včetně uvedení toho, která bezpečnostní opatření:
    * nebyla aplikována (včetně odůvodnění)
    * byla aplikována (včetně způsobu plnění)
* zpracování a zavedení plánu zvládání rizik. Plán zvládání rizik musí obsahovat:
    * cíle a přínosy bezpečnostních opatření pro zvládání jednotlivých rizik
    * určení osoby zajišťující prosazování bezpečnostních opatření pro zvládání rizik
    * potřebné finanční, technické, lidské a informační zdroje
    * termín jejich zavedení
    * popis vazeb mezi riziky a příslušnými bezpečnostními opatřeními
    * způsob realizace bezpečnostních opatření
* zohlednění tohoto při hodnocení rizik a v plánu:
    * významné změny
    * změny rozsahu systému řízení bezpečnosti informací
    * opatření podle § 11 ZoKB
    * kybernetické bezpečnostní incidenty, včetně dříve řešených
* zavedení bezpečnostních opatření v souladu s plánem zvládání rizik

![isms](/4smn/isms.png)

V rámci procesu **hodnocení rizik** je třeba respektovat model **PDCA**, který je však přizpůsoben pro hodnocení rizik:
1. **Plan**: vytvoření kontextu, odhad rizika, vypracování plánu zvládání rizika, přijetí rizika
2. **Do**: implementace plánu zvládání rizika
3. **Check**: Nepřetržité sledování a revize rizik
4. **Act**: udržování a zlepšování procesu hodnocení a řízení rizik, řídící proces

*Riziko = dopad * hrozba * zranitelnost*

### Úrovně hrozeb (podle přílohy č. 3 VoKB)
1. **Nízká**: neexistuje nebo je málo pravděpodobná. Předpokládaná realizace hrozby není častější než **jednou za 5 let**.
2. **Střední**: málo pravděpodobná až pravděpodobná. Předpokládaná realizace hrozby je v rozpětí od **1 roku do 5 let**.
3. **Vysoká**: pravděpodobná až velmi pravděpodobná. Předpokládaná realizace hrozby je v rozpětí od **1 měsíce do 1 roku**.
4. **Kritická**: velmi pravděpodobná až víceméně jistá. Předpokládaná realizace hrozby je častější než **jednou za měsíc**.

### Úrovně zranitelností (podle přílohy č. 3 VoKB)
1. **Nízká**: neexistuje nebo je zneužití zranitelnosti málo pravděpodobné. Jsou zavedena bezpečnostní opatření, která jsou schopna včas detekovat možné zranitelnosti nebo případné pokusy o jejich zneužití.
2. **Střední**: Zneužití zranitelnosti je málo pravděpodobné až pravděpodobné. Jsou zavedena bezpečnostní opatření, jejichž účinnost je pravidelně kontrolována. Schopnost bezpečnostních opatření včas detekovat možné zranitelnosti nebo případné pokusy o překonání opatření je omezena. Nejsou známé žádné úspěšné pokusy o překonání bezpečnostních opatření.
3. **Vysoká**: Zneužití zranitelnosti je pravděpodobné až velmi pravděpodobné. Bezpečnostní opatření jsou zavedena, ale jejich účinnost nepokrývá všechny potřebné aspekty a není pravidelně kontrolována. Jsou známé dílčí úspěšné pokusy o překonání bezpečnostních opatření.
4. **Kritická**: Zneužití zranitelnosti je velmi pravděpodobné až víceméně jisté. Bezpečnostní opatření nejsou realizována nebo je jejich účinnost značně omezena. Neprobíhá kontrola účinnosti bezpečnostních opatření. Jsou známé úspěšné pokusy překonání bezpečnostních opatření.

### Úrovně rizik (podle přílohy č. 3 VoKB)
1. **Nízké**: Riziko je považováno za akceptovatelné.
2. **Střední**: Riziko může být sníženo méně náročnými opatřeními nebo v případě vyšší náročnosti opatření je riziko akceptovatelné.
3. **Vysoké**: Riziko je dlouhodobě nepřípustné a musí být zahájeny systematické kroky k jeho odstranění.
4. **Kritické**: Riziko je nepřípustné a musí být neprodleně zahájeny kroky k jeho odstranění.