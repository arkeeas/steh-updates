# STEH pro Android, Windows a Linux

Instalační soubory a aktualizace aplikace STEH — CAD pomocníka pro svářeče.

## Windows 11

**[Stáhnout instalátor STEH 0.7.10 pro Windows 11 x64](https://github.com/arkeeas/steh-updates/releases/download/windows-latest/STEH-0.7.10-Windows11-x64-Setup.exe)**

Spusťte instalátor a dokončete průvodce. Aplikace se instaluje pro aktuálního uživatele
a najdete ji v nabídce Start. Instalační soubor není podepsaný certifikátem vydavatele.

**Bez instalace:** [stáhněte přenosný ZIP](https://github.com/arkeeas/steh-updates/releases/download/windows-latest/STEH-0.7.10-Windows11-x64.zip),
celý ho rozbalte a spusťte `STEH.exe`. Zachovejte DLL a složku `knihovna` vedle programu.

Aktualizace najdete v **Aktualizace → Zkontrolovat aktualizace** (v úzkém okně v nabídce **Více**).
Novější verze nabídne stažení instalátoru v prohlížeči. Před jeho spuštěním uložte sestavu a zavřete STEH.
Kontrola porovnává nainstalovanou verzi s nejnovějším dostupným instalátorem.

[Windows vydání a soubory](https://github.com/arkeeas/steh-updates/releases/tag/windows-latest) ·
[Kontrolní součty SHA-256](https://github.com/arkeeas/steh-updates/releases/download/windows-latest/STEH-0.7.10-Windows11-SHA256.txt)

## Co přináší 0.7.10

- **Více → Kalkulace:** rychlé ruční nacenění, vlastní sazby a položky, přirážka, DPH a historie zakázek.
- **Knihovna → Rozhraní:** Původní, Přehledné a světlá Dílna. Volba se uloží pro další spuštění.

Kalkulace používá vámi zadané sazby. Sazby a vzorce odkazované Google tabulky zatím nebyly převzaty.

## Linux x86_64

[Stáhnout STEH 0.7.10 pro Linux](https://github.com/arkeeas/steh-updates/releases/download/v0.7.10-20/STEH-0.7.10-Linux-x86_64.tar.gz).
Archiv rozbalte a spusťte `steh-viewer`. Zachovejte přiloženou složku `knihovna`;
ukázkové sestavy jsou v `Priklady`. [Kontrolní součet SHA-256](https://github.com/arkeeas/steh-updates/releases/download/v0.7.10-20/STEH-0.7.10-Linux-SHA256.txt).

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
`library.properties` popisuje samostatné soubory knihovny. Každé Android vydání obsahuje také `SHA256SUMS`. Aktualizace používají stejný podpis jako původní APK STEH.

Windows používá samostatné vydání `windows-latest`; Android nadále používá svůj kanál `releases/latest`.
Windows vydání není označeno jako globální latest, aby odkazy pro Android dál fungovaly.

Tento repozitář slouží pouze k distribuci instalačních balíčků a údajů o vydáních. Neobsahuje zdrojový projekt ani podpisový klíč.
