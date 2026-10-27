# STEH pro Android, Windows a Linux

Instalační soubory a aktualizace aplikace STEH — CAD pomocníka pro svářeče.

## Windows 11

**[Stáhnout instalátor STEH 0.7.37 pro Windows 11 x64](https://github.com/arkeeas/steh-updates/releases/download/windows-latest/STEH-0.7.37-Windows11-x64-Setup.exe)**

Spusťte instalátor a dokončete průvodce. Aplikace se instaluje pro aktuálního uživatele
a najdete ji v nabídce Start. Instalační soubor není podepsaný certifikátem vydavatele.

**Bez instalace:** [stáhněte přenosný ZIP](https://github.com/arkeeas/steh-updates/releases/download/windows-latest/STEH-0.7.37-Windows11-x64.zip),
celý ho rozbalte a spusťte `STEH.exe`. Zachovejte DLL a složku `knihovna` vedle programu.

Aktualizace najdete v **Aktualizace → Zkontrolovat aktualizace** (v úzkém okně v nabídce **Více**).
Novější verze nabídne stažení aktualizace. Před instalací uložte rozpracovanou sestavu.
Kontrola porovnává nainstalovanou verzi s nejnovějším dostupným instalátorem.

[Windows vydání a soubory](https://github.com/arkeeas/steh-updates/releases/tag/windows-latest) ·
[Kontrolní součty SHA-256](https://github.com/arkeeas/steh-updates/releases/download/windows-latest/STEH-0.7.37-Windows11-SHA256.txt)

## Co přináší 0.7.37

- **Přehlednější volba místa zámku:** vybrané místo má ve 3D číslo 1, díl s čepem je oranžový a díl s otvorem modrý. Další místa stejného dílu lze vybrat kliknutím.
- **Karta Vybrané místo:** volba zámku pro vybrané místo nebo všechna místa dílu a pohled na celé místo či detail.
- **Knihovna profilů:** přehlednější zobrazení s kalkulačkou tyčí a upraveným rozložením plátna.

Android má verzi **0.7.37 / code 46 / data 8**. Windows a Linux mají stejnou verzi **0.7.37**.

## Linux x86_64

[Stáhnout STEH 0.7.37 pro Linux](https://github.com/arkeeas/steh-updates/releases/download/linux-latest/STEH-0.7.37-Linux-x86_64.tar.gz).
Archiv rozbalte a spusťte `STEH`, případně `install.sh` pro instalaci do nabídky aplikací.
Vyžaduje x86_64 / glibc 2.43+ (Ubuntu 26.04). Zachovejte přiloženou složku `knihovna`;
ukázkové sestavy jsou v `Priklady`. [Kontrolní součet SHA-256](https://github.com/arkeeas/steh-updates/releases/download/linux-latest/STEH-0.7.37-Linux-SHA256.txt).

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

Windows používá samostatné vydání `windows-latest`, Linux `linux-latest`; Android používá `releases/latest`.
Windows vydání není označeno jako globální latest, aby odkazy pro Android dál fungovaly.

Tento repozitář slouží pouze k distribuci instalačních balíčků a údajů o vydáních. Neobsahuje zdrojový projekt ani podpisový klíč.
