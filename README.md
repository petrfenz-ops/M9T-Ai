# M9T-Ai — workshop atlas M9T 2.3 dCi

Lokální scaffold pro doplňování a ověřování **Kompletního atlasu M9T** (Renault–Nissan M9T 2.3 dCi).

Živý atlas (read-only): [9t-la-merde.grok.me](https://9t-la-merde.grok.me) (workshop heslo — necommitovat do veřejného repa).

## Účel repozitáře

Atlas už existuje; tady je prostor pro **mezery**:

- použitelné **fotky a schémata** (dílna, pinouty, hydraulika),
- **ověření** faktů proti TIS / VIN a kartám v atlasu,
- strukturované podklady pro sekce atlasu.

Toto NENÍ náhrada oficiální dokumentace (TIS). Jsou to pracovní materiály k doplnění a kontrole.

## Mapování složek → sekce atlasu

| Složka | Sekce atlasu |
|--------|----------------|
| `docs/skripta/` | Skripta |
| `docs/kody/` | Kódy motoru |
| `docs/snimace/` | Snímače |
| `docs/aktory/` | Akční členy |
| `docs/turbo/` | Přeplňování |
| `docs/ecu/` | ECU |
| `docs/dtc/` | Matice DTC |
| `docs/poruchy/` | Fyzika selhání |
| `docs/postupy/` | Postupy (dílna) |
| `docs/prevodovky/` | Převodovky |
| `assets/images/` | Fotografie z dílny |
| `assets/schemata/` | Schémata (zapojení, pinouty, hydraulika) |
| `verification/` | Checklisty ověření před merge |

## Priorita práce

1. Obrázky a schémata bez watermarků, v použitelné kvalitě  
2. Ověření vůči TIS / VIN a atlasovým kartám (`verification/`)  
3. Doplnění textových stubů v `docs/`

Viz [CONTRIBUTING.md](CONTRIBUTING.md).

## Remote

[github.com/petrfenz-ops/M9T-Ai](https://github.com/petrfenz-ops/M9T-Ai)
