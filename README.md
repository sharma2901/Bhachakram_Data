# Bhachakram Data

Data files for the Bhachakram Engine (Vedic astrology calculation engine). This repository holds **data only, no
code**. The files are published as release assets, one release per data version (`data-v1`, …). Apps download
them over HTTPS and check each file's size and SHA-256 before use.

| File | Contents | Source and licence |
|---|---|---|
| `de441_1800_2200.jeph` | Planetary ephemeris, years 1800–2200 | NASA JPL DE441 — public domain |
| `de441_full.jeph` | Planetary ephemeris, years −13 200 to 17 190 | NASA JPL DE441 — public domain |
| `atlas_core.jatl` | Places: population ≥ 15 000, capitals; India ≥ 1 000 and district seats | GeoNames (geonames.org), CC-BY 4.0 |
| `atlas_full.jatl` | All populated places | GeoNames (geonames.org), CC-BY 4.0 |
| `tzmap.jtzm` | Time-zone boundaries | timezone-boundary-builder (© OpenStreetMap contributors), ODbL 1.0 |

The files are in Bhachakram's own compact binary formats (JEPH, JATL, JTZM), converted from the sources above.

## Credits

- Ephemeris: NASA Jet Propulsion Laboratory, DE441 (Park et al. 2021). Public domain.
- Atlas: "GeoNames (geonames.org), CC-BY 4.0" — https://creativecommons.org/licenses/by/4.0/
- Time zones: "Time zone boundaries: timezone-boundary-builder (© OpenStreetMap contributors), ODbL" —
  https://opendatacommons.org/licenses/odbl/1-0/. The `tzmap.jtzm` file is a derived database under ODbL 1.0.
