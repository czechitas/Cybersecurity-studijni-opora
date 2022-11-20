---
description: Co se do jiných kategorií nevešlo
---

# Ostatní otázky

## Strategické otázky

### Jaký je váš názor na Huawei vzhledem nedávné aféře ?

Rozdělil bych to na dvě části, otázka právní a řekněme reputační.

Bezpečnost je krom technické stránky věci (použité zabezpečení, audit,...) jde i o důvěru. To čemu nevěříte nechcete používat - platí to obecně a v bezpečnosti obzvlášť.

Z pohledu právní stránky věci odkážu na článek na webu Sinopsis, to podstatné jsem zkopíroval.

Žádný čínský zákon skutečně nevyžaduje povinné budování backdoorů. To by ostatně asi bylo dost nepraktické, a ovšem zbytečné. Existují nicméně zákony, které jednoznačně zakládají povinnost všech právnických i soukromých osob spolupracovat na “národních informačních operacích”. V článku 22 [zákona o kontrašpionáži](http://www.npc.gov.cn/npc/xinwen/2014-11/02/content\_1884660.htm) (čung-chua žen-min kung-che-kuo fan-ťian-tie fa中华人民共和国反间谍法) z roku 2014 se píše:

> V případě zjištění, že instituce státní bezpečností získají informace o špionážní aktivitě a shromažďují důkazy, musí dotčené instituce a jednotlivci podat pravdivé informace, nesmí odmítnout \[spolupráci].

A ještě explicitnější a pravděpodobně aplikovatelnější na zahraniční operace je článek 7 v [zákoně o státní zpravodajské činnosti](http://www.npc.gov.cn/npc/xinwen/2017-06/27/content\_2024529.htm) (čung-chua žen-min kung-che-kuo kuo-ťia čching-pao fa 中华人民共和国国家情报法) z roku 2017:

> Všechny organizace a občané musí dle zákona podporovat národní informační operace, spolupracovat \[na nich] a koordinovat \[dle nich svou aktivitu] a střežit veškerá tajemství o národních informačních operacích, která jsou jim známá.

Tyto zákony schválené v éře Si Ťin-pchinga explicitně nařizují povinnost spolupracovat s čínskými výzvědnými službami, kterou si i předtím dokázaly příslušné služby vynutit extralegálně. Povinnost se vztahuje na všechny subjekty v ČLR, ale právě u Huawei lze podle slov [českého experta na digitální bezpečnost](https://video.aktualne.cz/dvtv/firma-huawei-je-udem-cinskeho-statu-telefon-od-nich-bych-si/r\~6faea5e0021e11e9a1900cc47ab5f122/r\~46ed601802a211e9a470ac1f6b220ee8/?redirected=1545254732) předpokládat, že zajde při takové spolupráci s úřady “daleko nad rámec zákonné povinnosti”.

## Kariéra v IT Security

### Požadavky v BIS/NÚKIB na pracovní pozice

Konkrétně se můžeš podívat na web [NÚKIB](https://nukib.cz/cs/o-nukib/kariera/) anebo [BIS](https://www.bis.cz/kariera/). V obecnosti jde o technické znalosti, které můžeš získat ve škole nebo praxí.

Nicméně nahlédnout pod pokličku můžeš i na [stážích](https://nukib.cz/cs/o-nukib/kariera/staze-pro-studenty/) pro studenty, minimálně NÚKIB tu možnost měl.

## Ostatní

### Řekněte nám, co dělat, pokud jsme už na takovou stránku (phishingovou) klikli?

Vyplnila jsi nějaké údaje? Pokud ano, vše co jsi vyplnila považuj za kompromitované. Pokud se ta stránka tvářila jako tvoje banka je dobré zavolat do banky a tohle jim nahlásit, udělají všechno pro to, aby takovou stránku "shodili".

Tzn. změnit heslo všude kde jsi ho používala, pokud se jednalo o platební kartu pak si nechej vystavit novou atd.

### Překvapuje mne, že dnešní kurz je zajišťován prostřednictvím platformy Zoom. Právě ohledně této platformy „koluje“ nejvíce zpráv o problémech v zabezpečení. Jsou tedy reálné a jak se zajišťuje bezpečnost Zoomu?

Ano, Zoom měl na jaře roku 2020 problémy. Rozdělil bych to do několika částí.

#### Špatná pověst

Jako všechny aplikace (Webex, Skype,...) i Zoom obsahuje chyby, které se teď snaží co nejrychleji opravit, viz. plán uveřejněný na jejich blogu.

#### Sdílení dat s FB

Tento problém již byl vyřešen a týkal se jen uživatelů s iOS (Apple iPhone/iPad). Sdílení dat je teď velké téma, nicméně to není první ani poslední aplikace, která byla nachytána, že něco takového dělá, viz. Facebook Off

#### Zoombombing

Tento problém je daný nastavením, pokud je videokonference nedostatečně zabezpečená (bez hesla, bez kontroly přístupu) může se to stát. Podle mého názoru to není primárně problém aplikace Zoom, ale uživatelů, kteří si ho neumí správně nastavit a spoléhají, že to ve výchozím nastavení je zabezpečené (což se ukazuje jako chybný předpoklad - platí to obecně).

#### Šifrování

Zoom jako ostatní platformy používají šifrování. Problém je v tom, že Zoom end-to-end šifrování marketingově propagoval a nebyla to pravda.\
&#x20;Jako ostatní (např. Skype, anebo Webex) používájí **TLS** (stejný protokol, který se stará o zabezpečení transportní vrstvy protokolu HTTPs.\
&#x20;Použití end-to-end šifrování zpravidla limituje použití služby (_Google Hangouts/Duo_ nepodporují více než 12 účastníků, _Webex_ neumožní použít webovou aplikaci, nahrávání,...).\
&#x20;Podle mého názoru se není čeho bát, pokud člověk používá aktuální verzi aplikace a dbá doporučených nastavení.

### Jaký je váš názor na čistící programy, např. CCleaner? Případně existují nějaké účinné a zároveň bezpečné?

CCleaner měl problém ten, že do něj někdo vložil škodlivý kód (Supply Chain Attack). Nicméně po opravě jej lze považovat za bezpečný. Nicméně je v poslední době dost protkaný placenými funkcemi.

V zásadě se dá říct, že pokud člověk bude ignorovat všechna ta lákadla dá

### Apple, iOS. Jak zrušit pravidelné strhávání/fakturaci za aplikaci, pokud už o službu/aplikaci nemám nadále zájem?

Klikneš na tvůj účet > Předplatné a pak si vybereš tu, kterou chceš zrušit.

### Jak/kde přijdu na to že je potřeba aktualizovat SW?

Aplikace/systém by se měl ozvat sám. Nicméně, vždycky je někde tlačítko zjistit aktualizace (desktop). Pro mobilní aplikace platí, že musíš do "obchodu" a zkontrolovat aktualizace.

### Znáte nějaký SW kde si sami můžeme se svým výkonem těžit kryptoměny, např. Bitcoin.

Těžit Bitcoin už se nevyplatí, detaily o těžbě můžete najít [tady](https://www.alza.cz/jak-funguje-tezba-bitcoinu?layoutAutoChange=1).

### Co se stane, když odpovíte na spam?

Nemělo by se stát nic, v nejhorším případě si odesílatel potvrdí, že daná schránka je aktivní a může ji dál zásobovat spamem.

### Které aplikace jsou bezpečné a které nebezpečné pro online komunikaci? (např. Zoom, Skype apod.)

Asi se nedá říct, že by nějaka z nich byla nebezpečená - myšleno z těch známých, jako Skype, Zoom, Webex,... vždycky záleží na tom jak je ta služba nastavená, případně jestli používáš neaktuální verzi aplikace, která má nějakou zranitelnost.

Pokud budeš mít slabé heslo nebo budeš sdílet odkaz na tvou videokonferenci může dojít ke zneužití.

### Co je nejčastější nedostatek průměrného uživatele z hlediska bezpečnosti?

Řekl bych, že to je slabé heslo v kombinaci s tím, že toto heslo je použito na více službách. Typicky nějaký e-shop a pak třeba email.

### Jsou nějáké větší/záludnější nástrahy spojené s bezpečností které mohou nastat během cestování?

Určitě ano, když cestuješ a chceš se připojit na síť, využiješ například veřejnou wifi, která může být nebezpečná pro tebe - jako uživatele.

Můžeš se také setkat s útoky zaměřenými na zneužití tvé platební karty (skimming aj.)

### Jakým způsobem si útočníci vybírají oběti? Je to náhoda nebo např. pracují s nějakými databázemi?

Záleží na typu útoku, některé jsou masové (rozesílají se na tísice adres, typicky phishing), některé jsou více cílené (spear-phishing).

### Jaká je pravděpodobnost, že odkazy, které vrátí google při vyhledávání, mohou být škodlivé?

Google indexuje kde co... je možné, že tam něco škodlivého najdeš. Nicméně když na takový odkaz klikneš tvůj prohlížeč by tě měl/mohl varovat (pokud je to známé).

## OSINT

### Existuje seznam důvěryhodných domén?

Ano i ne. Můžeš zjistit reputaci k dané doméně, tzn. lze vytvořit i takový seznam.

## Penetrační testování/etický hacking

### Jaký je vhodný program pro klonování webu? Vytvoří mi kopii celého webu?

Můžeš použít například [HTTrack](https://www.httrack.com/), nicméně nástrojů je spousta (set aka Social Engineering ToolKit, součást distribuce Kali).
