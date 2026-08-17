# Épületgépész Iroda Tycoon 🏗️🔧

**Körökre osztott szimulációs játék: építs épületgépészeti tervezőirodát Magyarországon.**

*A turn-based business simulation game about building an HVAC/MEP design office in Hungary. Hungarian language only.*

▶️ **Játék indítása: [https://GITHUB-FELHASZNALONEV.github.io/hvactycoon/](https://GITHUB-FELHASZNALONEV.github.io/hvactycoon/)**

---

## Miről szól?

Épületgépész tervező vagy: nappal alkalmazott, este a konyhaasztalnál rajzolod a saját munkáidat. Egyéni vállalkozást indítasz átalányadóval, 800 ezer forint megtakarítással és egy álommal: saját tervezőiroda, saját termékekkel, stabil bevétellel.

Az út: **mellékállású EV → főállású vállalkozó → Kft. → piacvezető iroda.**

A játék a magyar piac valós (2026-os) viszonyaira épül:

- valós tervezési díjak (gázterv, családi ház gépészet, társasház, közbeszerzési tender),
- átalányadó, ÁFA alanyi mentesség (18 M Ft), Kft. + TAO, negyedéves adófizetés,
- Széchenyi-hitelek és drága piaci gyorshitel,
- **körbetartozás**: a kivitelező 60–90 napra fizet — ha fizet,
- versenyeztetés: sokszor az olcsóbb konkurens nyer,
- fizetési felszólítás és követeléskezelő (a jó viszony rovására),
- alvállalkozók, alkalmazottak, kiégés, NAV-ellenőrzés, tervhiba-reklamáció,
- termékek (Excel-csomag, típustervek, SaaS, kurzus) és belső fejlesztések (ERP prediktív cashflow-val, méretező szoftver, AI tanácsadó, AI piackutató).

## Hogyan kell játszani?

Minden kör **egy nap**. Ajánlatot írni munkaórába kerül, a maradék idődet a „Mai nap" fülön osztod be: projektmunka, termékfejlesztés, kapcsolatépítés, pihenés. Hónap végén teljes pénzügyi riport.

**Cél:** 4+ fős csapat, havi 2 M Ft+ termékbevétel, 30 M Ft tartalék és 75+ hírnév — 3 egymást követő hónapban.

**Vigyázz:** ha elfogy a pénz és a hitelkeret, csőd. A mentés a „Cég" fülön érhető el (másold ki a JSON-t, és illeszd vissza a folytatáshoz).

## Technika

Egyetlen önálló HTML fájl (`index.html`) — nincs build, nincs függőség, nincs szerver. Vanilla JavaScript + Canvas. Offline is fut, ha letöltöd.

## Licenc

MIT — lásd a [LICENSE](LICENSE) fájlt.

---

*A játékot Claude (Anthropic) segítségével készítettem. A benne szereplő cégek, nevek és események kitaláltak; az árak és szabályok a 2026-os magyar piac közelítései, nem minősülnek szakmai vagy adótanácsnak.*
