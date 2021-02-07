---
title: Logická bezpečnost
weight: 4
---

# Logická bezpečnost

*řízení přístupů — autorizace, autentizace, šifrování — principy vybrané algoritmy, elektronický podpis*

Při řízení přístupu je **ověřována úroveň oprávnění a práv uživatele (Autorizace)** k určitému zdroji nebo objektu. **Zdrojem** může být připojení k síti, využití kapacity paměťového média, přístup k počítačovým systémům (serverům, síťovým prvkům, tiskárnám aj.) atd., zatímco **objektem** jsou například data uložená v určitém adresáři, nebo samostatný soubor. 

Ověřovaným objektem může být oprávnění uživatele, skupiny, ale i samotných počítačových systémů. Uživatel může mít stejná práva jako ostatní členové skupiny a zároveň i nějaká oprávnění, která má pouze dotyčný uživatel. Rozdělení uživatelů do skupin je velmi praktické, obvykle se v organizaci vyskytují určité skupiny uživatelů, kteří využívají stejné zdroje.

**Granularita nastavení práv** závisí na používaném systému. Obvykle je možné pro soubory a adresáře určit minimálně oprávnění pro čtení, zápis, odstranění, spuštění a změnu vlastníka souboru či adresáře.

Aby vůbec mohlo dojít k řízení uživatelských přístupů, musí být nejprve systémem **ověřena identita uživatele (Autentizace)**. Nejčastěji lze ověřit identitu uživatele na základě toho:
* co zná
* co vlastní
* čím je

Nejběžnějším je ověření uživatele na základě toho, co zná v podobě hesla (určitého řetězce znaků), který uživatel obvykle na základě výzvy systému zadá. Zadané heslo je následně porovnáno s heslem již dříve uloženým uživatelem do systému. Pokud se hesla shodují, je uživatel přihlášen a jsou mu přidělena oprávnění. Výhodou hesel je jejich snadné použití a snadná implementace do systému. Čím je však heslo kvalitnější, tím je obvykle pro uživatele hůře zapamatovatelné. Nevýhodou hesla je, že je lze odpozorovat či předat.

Ověření uživatele na základě vlastnictví předmětu bývá realizováno díky držení určitého tokenu uživatelem (např. čipové karty, klíče, aj.). Tuto funkci dnes může převzít například i mobilní telefon. Nevýhodou ověření na základě vlastnictví předmětu je skutečnost, že i tato zařízení je možné předat, zcizit, ztratit. Navíc jsou s jejich použitím často spojeny výrazně vyšší náklady než při ověření na základě toho, co uživatel zná.

Ověřením uživatele na základě toho čím je se zabývá biometrie, která rozpoznává jedinečné biologické charakteristiky daného uživatele. Existuje několik charakteristik, u nichž se předpokládá nebo je matematicky prokázáno, že jsou pro každého člověka unikátní. Uvedené charakteristiky jsou často využívány jinými vědními obory (např. kriminalistika) k jedinečné identifikaci člověka. 

Uživatele je možné ověřovat podle otisku prstu, podle obličeje, dynamiky při psaní, hlasu, mozkových vln, oční duhovky, krevního řečiště atd. Nicméně ne všechny tyto možnosti najdou v současné době běžné využití v praxi. Nevýhodu ověření uživatele na základě toho, čím je, představuje nutnost pořízení speciálního hardwaru, nemožnost změnit „heslo“ v případě prozrazení používaných charakteristik a možnost napodobení některých biometrických údajů.

Za vhodnou a pro většinu běžných aplikací a systémů dostatečnou, lze označit autentizaci, která využívá dva z výše uvedených způsobů a kombinuje tak například znalost hesla s vlastnictvím zařízení, nebo s biometrickými údaji. V takovém případě mluvíme o dvoufaktorové autentizaci.

## Šifrování

nezabezpečená elektronická data se převádí za pomoci kryptografie na data šifrovaná, čitelná pouze pro majitele dešifrovacího klíče

### Typy šifer

* **symetrické**: používá k šifrování i dešifrování stejný klíč. Výhodou je jejich nízká výpočetní náročnost. Nevýhodou je nutnost sdílení tajného klíče, takže se odesílate a příjemce tajné zprávy musí předem domluvit na tajném klíči
    * blokové
    * proudové
* **asymetrické**: K šifrování a dešifrování se používají odlišné klíče – veřejný a soukromý klíč. Klíč určený k šifrování je veřejný, majitel klíče ho volně uveřejní, a kdokoli jím může šifrovat jemu určené zprávy. Dešifrovací klíč je privátní (soukromý), majitel jej drží v tajnosti a pomocí něj může tyto zprávy dešifrovat

## Digitální podpis

Digitální podpis se používá pro ověření pravosti digitálního obsahu (např. PDF, Word či jiná textová/binární data). Validní podpis dává příjemci jistotu, že přijímaný soubor nebyl od jeho odeslání změněn a že byl podepsán pouze osobou, která vlastní privátní klíč k certifikátu.

### Proces vzniku podpisu

Vezme se konkrétní soubor (jeden). Ze souboru se vypočítá hash pomocí hashovací funkce. Tento hash je dále zašifrován pomocí privátního klíče podepisujícího. Výsledek šifrování spolu s certifikátem tvoří tzv. “podpis”. Podpis může být připojen přímo k souboru (formát a cílová strana to musí podporovat) nebo může vzniknout jako samostatný soubor, který je předáván spolu s originálním souborem.

### Ověření podpisu

Podpis souboru se dešifruje za pomoci veřejného klíče. Následně dojde k porovnání výše zmíněných 2 částí. Rovnají-li se, je podpis platný. V opačném případě byl soubor pravděpodobně neoprávněně změněn.

### Bezpečnost podpisu

Je důležité podotknout, že podpis nešifruje předávaný obsah. Ten je i nadále čitelný případnému útočníkovi. Dále také není žádný problém podpis odstranit (buďto smazáním samostatného souboru, nebo odstraněním podpisu přímo ze souboru). Útočník tedy může soubor vzít, podpis odstranit a upravit předávaný obsah. Pro příjemce souboru by takto upravený soubor vypadal jakože nikdy nebyl podepsán a je na jeho úsudku, zda-li bude souboru důvěřovat. (Pochopitelně pokud jsou obě strany domluveny, že všechny zprávy/soubory budou podepisovány, je to podezřelé).

### Použití podpisu
* autentizace
* zajištění integrity předávaných dat
* neodvolatelnost




