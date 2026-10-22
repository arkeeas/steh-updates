# STEH pro Android

Instalační soubory a aktualizace aplikace STEH — CAD pomocníka pro svářeče.

## Telefon nebo tablet

**[Stáhnout poslední verzi STEH pro Android](https://github.com/arkeeas/steh-updates/releases/latest/download/steh-arm64.apk)**

1. Stáhněte APK v telefonu a otevřete stažený soubor.
2. Pokud Android požádá, povolte instalaci aplikací z tohoto prohlížeče či správce souborů.
3. Potvrďte **Aktualizovat** (při první instalaci **Instalovat**).

**Pokud prohlížeč nedokončí stažení APK:** stáhněte [ZIP pro telefon](https://github.com/arkeeas/steh-updates/releases/latest/download/steh-android.zip), rozbalte ho a otevřete `steh-arm64.apk`.

Původní aplikaci neodinstalovávejte, aby zůstala zachována její data.
V nabídce **Více → Zkontrolovat aktualizace** je stav a nastavení aktualizací.
Od **0.3.1** se nové verze stahují přímo ve STEHu. Automatika funguje při otevřené aplikaci
přes neměřenou Wi-Fi a lze ji vypnout. Přenos se zastaví po opuštění aplikace nebo povolené sítě.
Ruční stažení je možné i na jiné síti.

Profily a zámky se aktualizují samostatně: přenášejí se jen změněné soubory knihovny.
Program přednostně používá menší rozdílový balíček; při neshodě nebo malé úspoře stáhne celé APK.
Instalace i přepnutí knihoven počkají na uložení rozdělané práce.
Android může požadovat jednorázové povolení instalací ze STEHu a potvrzení instalace.
Po aktualizaci může být nutné STEH znovu otevřít.

První přechod ze starší verze vyžaduje jednu celou instalaci z odkazu výše.

APK je pro zařízení **arm64-v8a**, Android 8.0 a novější. Sestavení pro emulátor x86_64 je mezi soubory vydání.

[Verze a změny](https://github.com/arkeeas/steh-updates/releases)

## Aktualizační kanál

`releases/latest/download/latest.properties` obsahuje číslo poslední verze a odkazy na konkrétní neměnné APK.
`library.properties` popisuje samostatné soubory knihovny. Každé vydání obsahuje také `SHA256SUMS`. Aktualizace používají stejný podpis jako původní APK STEH.

Tento repozitář slouží pouze k distribuci APK a údajů o vydáních. Neobsahuje zdrojový projekt ani podpisový klíč.
