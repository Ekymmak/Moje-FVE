# Moje FVE – prototyp 0.1

Mobilní PWA prototyp rozhraní pro monitoring GoodWe + VW ID.3.

## Co je hotové
- responzivní mobilní přehled
- dlaždice pro výrobu, spotřebu, baterii, síť a wallbox
- sekce VW ID.3
- manifest, ikona a service worker pro instalaci jako PWA

## Důležité
Zobrazené číselné hodnoty jsou pouze demonstrační. Žádné zařízení není připojeno.
Aplikace nic neovládá a neobsahuje přihlašovací údaje.

## Jak ji zpřístupnit v telefonu
Soubory je potřeba nejprve zveřejnit na HTTPS hostingu (např. GitHub Pages nebo jiný statický hosting).
Poté otevřít veřejnou HTTPS adresu v Chrome na Androidu → menu ⋮ → Přidat na plochu / Instalovat aplikaci.

## Další fáze
1. nasadit statické rozhraní na HTTPS
2. vytvořit bezpečný backend pro GoodWe
3. ověřit oprávněný datový přístup k VW
4. nahradit demonstrační hodnoty živými daty

Nikdy nevkládejte hesla GoodWe nebo Volkswagen do souborů webové aplikace ani do veřejného repozitáře.
