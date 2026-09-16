# Schémata

Zapojení, **pinouty**, hydraulika / vakuum — podklady ke kartám atlasu.

## Formáty

- Preferováno: **SVG** (editovatelné) nebo **PNG** (jasné, vysoké rozlišení)
- PDF jen pokud není rozumný export do SVG/PNG

## Pojmenování

```
m9t_<typ>_<díl_nebo_okruh>[_verze].{svg|png}
```

Typy (`<typ>`):

| Typ | Význam |
|-----|--------|
| `wiring` | Elektrické zapojení |
| `pinout` | Pinout konektoru / ECU |
| `hydraulic` | Hydraulika / olej |
| `vacuum` | Vakuum / boost okruh |
| `block` | Blokové schéma |

Příklady:

- `m9t_pinout_ecu_connector_a.svg`
- `m9t_wiring_glow_plug_circuit.png`
- `m9t_hydraulic_oil_circuit_01.svg`

## Konvence

- Popisky v češtině (nebo dvojjazyčně CZ/EN, pokud je to pinout z TIS)
- Uvést, jestli je schéma **ověřené** (TIS) nebo **pracovní náčrt**
- Barvy/vodiče konzistentní v rámci jedné sady schémat
- Ověření: `verification/CHECKLIST.md`
