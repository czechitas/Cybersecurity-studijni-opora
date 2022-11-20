---
description: Postup pro nastavení aplikace Twilio Authy
---

# 2FA

## Nastavení

Tento návod bude (s drobnými odlišnostmi) fungovat i pro jiné aplikace (Google Authenticator, Microsoft Authenticator, Okta,...)

Potřebujete chytrý telefon s Android/iOS případně YubiKey. Aplikace do které chcete zabezpečit přístup zpravidla disponuje návodem (použijte ho), např. [Facebook](https://www.facebook.com/help/148233965247823). Nicméně můžete využít i návodu, který je k dispozici [zde](https://authy.com/guides/)

Začněte od služby, kde máte důležité věci (e-mail, sociální síť,...) a ztrátou přístupu by mohlo dojít k velké škodě. Dál už postupujte podle návodu:

* Nainstalujte si aplikaci **Authy**
  * Authy 2-Factor Authentication (Android)
  * Authy (iOS)
* **Zaregistrujte** si vaše telefonní číslo, ověřte ho (pomůže vám v případě obnovy, přenosu na nový telefon,...)

![Twilio Authy Account Setup](../.gitbook/assets/authy-reg=number.png)

![Twilio Authy Registration](../.gitbook/assets/authy-verification.png)

* Zálohu vyřešíme posléze, přeskočte ji (potřebovali by jste si někam poznačit heslo, vhodnější až po nastavení správce hesel)
* **Klikněte** v pravém dolním rohu na **+** (přidáte si tak nový účet)

![Twilio Authy Add Account ](../.gitbook/assets/Authy-Add-Account-w-arrow\_4d470f76dc99e18ad75087b1b8410ea9.webp)

* Klikněte na **Scan QR Code** (aplikace bude potřebovat přístup k fotoaparátu)/Opište iniciační vektor manuálně

![Twilio Authy Scan QR Code](../.gitbook/assets/how-to-setup-authy-on-multiple-devices-03-338x600.jpg)

* **Namiřte** na obrazovku kde se nachází QR kód vygenerovaný službou (Facebook, Google, Microsoft,...)
* **Pojmenujte** si nově vytvořený účet a uložte
* Služba, kterou nastavujete bude chtít **ověření** (opište kód, který vám Authy generuje).

Doporučujeme nastavit zabezpečení Authy (PIN, TouchID,...).

## Záloha a synchronizace

1. Otevřete aplikaci **Authy**.
2. Klikněte na **Nastavení/.../ikona ozubeného kola**
3. Přes záložku Účty se nastavte **záloha autentikátoru,** povolte/zakažte
4. Pro **povolení** zálohy a synchronizace zadejte heslo k záloze

![Twilio Authy Backup & Sync](../.gitbook/assets/authy-backup.png)

## Povolení více zařízení

* Otevřete aplikaci Authy
* Klikněte na **Nastavení/.../ikona ozubeného kola**
* Přes záložku **Zařízení** se dostanete k zatržítku **Povolit více zařízení**

![Twilio Authy Multi-device](../.gitbook/assets/authy-multidevice.png)



