# Slovník

* **Autorizace**, je proces povolující uživateli určité akce. Jinými slovy jsou to oprávnění, kterými uživatel disponuje.
* **Autentizace**, je proces určující skutečnou identitu uživatele. Ověření, že uživatel je ten za koho se vydává a může: vstoupit, přihlásit se,...
* **2FA**, two-factor authentication, dvoufázové ověření identity, např. heslo a jednorázový kód
* **Botnet**, síť počítačů napadených malwarem
* **Hash**, unikátní řetězec fixní délky. Vytvořen (jednosměrnou) matematickou funkcí.
* **Phishing**, útok na uživatele s cílem získat citlivé údaje
* **Ransomware**, vyděračský software, program. Zablokuje uřivateli systém nebo zašifruje data, následně od oběti požaduje výkupné.
* **Šifrování**, proces transformace dat z čitelné do nečitelné (bez příslušného klíče) podoby.
* **Symetrické šifrování**, používá pro zašifrování zprávy ten samý klíč jako k jejímu dešifrování. Typickými zástupci jsou AES, Blowfish.
* **Asymetrické šifrování**, používá veřejný (šifrování/ověření podpisu) a privátní klíč (dešifrování/podepisování). Typickými zástupci jsou RSA nebo ECC
* **Token**, fyzické zařízení sloužící k ověření identity za účelem přístupu k zabezpečeným službám, často jako doplněk k heslu, další ověřovaný prvek
* **Integrita**, (en. integrity) integrita dat - chceme jistotu, že nám naše data nikdo nezměnil bez našeho vědomí
* **Důvěryhodnost**, (en. confidentiality) - přenášená/uložená data nemůže číst nikdo cizí
* **Dostupnost**, (en. availability) - poskytované služby jsou funkční
* **Malware**, škodlivý software - obecný název pro viry, trojské koně, červy/worm atp.
* **Hacker a jeho druhy**, původně označení zvídavého člověka, který si byl ochotný hrát s technikou a hledat použití pro které daná technika nebyla určena. Dnes často používano jako označení pro kybernetického útočníka.
* **CIA triáda**, zkratka pro Confidentiality, Integrity a Availability. Viz výše.
* **Virus**, typ malware. Dle původního rozlišení se jedná o kus počítačového kódu, který se připisuje do již existujících programů
* **boot-viry**, typ viru. Spouští se hned při zapnutí počítače. Velmi složitě se detekuje a odstraňuje.
* **makro-viry**, typ viru. Vyskytuje se u dokumentů (např. doc) pro jeho spuštění je zapotřebí "povolit makra"
* **trojské koně**, typ malware. Umožňuje útočníkům vzdálený přístup k nakaženému systému 
* **Wiper**, typ malware. Dříve pouze mazal data (bez požadavku o výkupné). Nověji je to typ ransomware, který sice žádá o výkupné i přesto, že data není možné dešifrovat ať už záměrně nebo chybnou implementací. 
* **Keylogger**, typ malware. Jeho úkolem je zachytávat úhozy na klávesnici. Umožňuje odposlech citlivých údajů, např. zadávaného hesla.
* **Insider**, typ útoku při kterém se použije (třeba za úplatu) zaměstnanec cílové firmy. Ten pak například spustí nějaký škodlivý kód. 
* **Spam**, nevyžádaná pošta.
* **Hoax**, falešná poplašná zpráva. Často doprovázená dnes již zlidovělým "Sdílejte to než to smažou".
* **Firewall**, HW nebo SW, který má za úkol řídit síťový provoz - zabraňuje nežádoucímu síťovému přístupu/provozu.
* **Network Segmentation**, používaná technika na rozdělení počítačové sítě do menších podsítí. Při vhodném nastavení omezuje útočníkům přístup k ostatním strojům v síti.
* **DMZ - demilitarized zone**, oddělená podsíť (viz. Network segmentation). Do této podsítě se umisťují služby, které jsou dostupné z internetu. Dnes se tento pojem moc nepoužívá.
* **VPN - virtual private network**, Virtuální privátní síť - bezpečné připojení do vzdálené lokality. Používá se buď k přístupu k interním firemním službám, které nejsou dostupné z internetu nebo k zabezpečení vlastního připojení u otevřených/nešifrovaných wi-fi sítí.
* **Access Management**, řízení přístupu. Ať už fyzické - přístupové karty, či síťové, či ke konkrénám službám - zadávání smluv, objednávání zboží, karty zaměstnanců
* **Rogue employee, disgruntled employee**, nespokojený zaměstnanec. Často využitý k útoku typu insider.
* **Social engineer**, útočník zaměřující se na útoky vedené sociálním inženýrstvím, například phishing
* **Internet stalker**, osoba, která někoho potají sleduje a vyhládává o něm informace, často právě nezákonými způsoby.
* **Internet predator**, - těžko vysvětlit jednou větou. viz film V Síti nebo [Linka bezpečí](https://www.linkabezpeci.cz/-/internetovi-predatori-pohledem-linky-bezpeci)
* **APT**, - Advanced persistent threat. Skupiny útočníků, často státem přímo či nepřímo podporované. Známá je například ruská APT28 Fancy Bear
* **OSINT**, - Open source intelligence - vyhledávání iformací a údajů na základě dat dostupných z veřejných zdrojů. 
* **NIST**, - "National Institute of Standards and Technology" - vydává standardy ohledně zabezpečení. Například NIST 800-63b řeší bezpečná hesla, NIST FIPS 140 - řeší fyzickou bezpečnost IT 
* **SIEM**, "Security information and event management" - softwarové řešení, které firmě/organizaci pomáhá detekovat, analyzovat a reagovat na bezpečnostní hrozby 
* **SOAR**, "Security orchestration and response" - softwarové řešení, které firmě/organizaci pomáhá automatizovat analýzu a reakce na bezpečnostní události
* **EDR**, "Endpoint detection and response" - softwarové řešení, které slouží k monitorování pracovních stanic, serverů, atp.
* **NTA**, "Network traffic analyzer" - softwarové řešení, které slouží k monitorování provozu na síti 
* **RDP**, "Remote desktop protocol" - nástroj pro vzdálený přístup, zejména na pracovní stanice Windows
* **SSH**, "Secure Shell" - nástroj pro vzdálený přístup do příkazové řádky, zejména na servery
* **Virtualizace**, spouštění (typicky operačního systému) na virtuálním hardware (namísto skutečného)
* **Sandboxing**, spouštění neznámého, možná i škodlivého kódu v bezpečném prostředí za účelem jeho studia
* **CSIRT**, "Computer security incident response team", tým pověřený reakcí na bezpečnostní incidenty
* **SOC**, "Security operations center", tým pověřený monitorováním bezpečnostních událostí a reakcí na incidenty 
* **CVE**, "Common vulnerabilities and exposures", seznam veřejně známých zranitelností
* **CWE**, "Common weakness enumeration", seznam typů zranitelností
* **CVSS**, "Common vulnerability scoring system", metoda určování závažnosti zranitelností používaná v systému CVE
* **MITRE ATT&CK**, katalog známých typů útoků, skupin útočníků a software
* **OWASP**, "Open Web Application Security Project", organizace zabývající se popisem útoků na web, viz [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
* **IOC**, "Indicator of Compromise", údaj, který lze jednoduše vyhledat, např. IP adresa nebo hash souboru. Jeho nalezení obvykle potvrzuje výskyt nějakého útoku
