<p align="center">
  <a href="https://vfko.cz"><img src="https://vfko.cz/assets/img/logo-modry.svg" alt="VFko" height="64"></a>
</p>

<p align="center"><strong>Vydané faktury snadno.</strong><br>
Faktury, zálohy i opravné doklady pro OSVČ a malé firmy. Zdarma, bez registrace a s daty jen ve vašem počítači.</p>

<p align="center">
  <a href="../../releases/latest"><strong>Stáhnout pro macOS</strong></a> ·
  <a href="https://apps.microsoft.com/detail/9N41TP4W05VW"><strong>Microsoft Store (Windows)</strong></a> ·
  <a href="https://vfko.cz">vfko.cz</a>
</p>

---

## Co VFko umí

- Faktury, zálohové faktury, daňové doklady k přijaté platbě, opravné daňové doklady a vyúčtování záloh
- Pro plátce i neplátce DPH, včetně rekapitulace DPH podle sazeb
- QR platba na každé faktuře
- Údaje odběratelů i dodavatelů z registru ARES
- Export ISDOC a CSV pro účetní
- Více dodavatelů, šablony odběratelů a automatické číslování
- Kontrola úhrad přes API Fio banky
- Funguje i bez internetu

Podrobnosti najdete na [vfko.cz](https://vfko.cz).

## Stažení

Instalační soubory jsou u každého [vydání](../../releases) v části **Assets**.

| Systém | Soubor |
|---|---|
| macOS na Macu s Apple Silicon (M1 a novější) | `VFko-<verze>-macOS-AppleSilicon.dmg` |
| macOS na Macu s procesorem Intel | `VFko-<verze>-macOS-Intel.dmg` |
| Windows 10 a 11 (64bit) | [Microsoft Store](https://apps.microsoft.com/detail/9N41TP4W05VW) |

Typ procesoru zjistíte v nabídce Apple → **O tomto Macu** (řádek „Čip“ nebo „Procesor“).

**Požadavky:** macOS 14 Sonoma nebo novější, Windows 10 nebo 11 (64bit).

## Instalace na macOS

1. Otevřete stažený soubor `.dmg`.
2. Přetáhněte VFko do složky **Aplikace**.
3. Spusťte VFko ze složky Aplikace nebo z Launchpadu.

### První spuštění

VFko zatím není ověřené u Applu, proto ho macOS při prvním spuštění zablokuje. Povolení stačí jednou:

1. Zobrazí se hlášení, že aplikaci nelze ověřit. Klikněte na **Hotovo**.
2. Otevřete **Nastavení systému → Soukromí a zabezpečení**.
3. Dole u hlášení o VFko klikněte na **Přesto otevřít** a potvrďte heslem nebo Touch ID.

Na macOS 14 Sonoma stačí na VFko ve složce Aplikace kliknout pravým tlačítkem a zvolit **Otevřít**.

## Aktualizace

Stáhněte nový soubor `.dmg` a přetáhněte VFko do složky Aplikace. Starou verzi nahradí, doklady i nastavení zůstanou. Data jsou ve složce `~/Library/Application Support/VFko`, mimo aplikaci.

Pokud používáte kontrolu úhrad, macOS se po aktualizaci při první kontrole zeptá, zda smí VFko použít uložený token banky. Zvolte **Vždy povolit**.

Doporučujeme občas zálohovat data přes **Soubor → Exportovat data**.

## Ověření staženého souboru

U každého vydání je soubor `SHA256SUMS.txt` s kontrolními součty. GitHub je navíc zobrazuje přímo u souborů v části Assets. Shodný součet potvrzuje, že se soubor stáhl celý a beze změn.

```bash
shasum -a 256 ~/Downloads/VFko-*-macOS-*.dmg
```

Výsledek porovnejte s hodnotou v `SHA256SUMS.txt` nebo na [vfko.cz](https://vfko.cz/#stazeni).

## Soukromí

Doklady, údaje odběratelů a nastavení se ukládají jen ve vašem počítači. VFko se připojuje k internetu jen při načítání údajů z ARES, při kontrole úhrad a při odeslání hlášení o chybě, pokud ho povolíte. Podrobnosti jsou v [zásadách ochrany osobních údajů](https://vfko.cz/zasady/).

## Podpora

- Chybu nahlásíte přímo v aplikaci: **Nápověda → Nahlásit problém**.
- E-mail: [podpora@vfko.cz](mailto:podpora@vfko.cz)
- Změny v jednotlivých verzích: [Co je nového](https://vfko.cz/co-je-noveho/)

## Licence

VFko je zdarma, ale nejde o open source. Zdrojový kód není veřejný a toto úložiště slouží jen k distribuci instalačních souborů.

- [Licenční podmínky](https://vfko.cz/licencni-podminky/)
- [Licence třetích stran](https://vfko.cz/licence-tretich-stran/)

© 2026 David Raušer, IČO 09434542. Všechna práva vyhrazena.
