# Alpina Firmware Preservation

Alpina engine and transmission control unit files are rare, often hoarded, and replacement units cost far more than their BMW counterparts. This repository preserves known Alpina firmware so cars can be repaired and kept original.

📖 Background on every model, part numbers and control units: **[Alpina Firmware Preservation on the MS4X Wiki](https://www.ms4x.net/index.php?title=Alpina_Firmware_Preservation)**

## Contents

<!-- TODO: fill with the files that get uploaded; suggested structure: <chassis>/<model>/<file> -->

| Chassis | Model | Engine | ECU (Alpina #) | TCU (Alpina #) |
|---|---|---|---|---|
| E30 | B6 3.5 | M30 (B10/4) | ML3.1 (13 56 615) | – |
| E36 | B3 3.0 | M50 stroked (E3) | *wanted* (13 56 676) | GS7.11 (24 10 101) |
| E36 | B3 3.2 | S52 stroked (E4) | MS41.1 (13 56 683) | *wanted* (24 10 105) |
| E39 | B10 V8 | F3 / F4 | M5.2.1 (13 56 692), ME7.2 (13 56 691) | GS8.60.2 (24 10 611, 24 10 621) |
| E46 | B3 3.3 | E4-4 / E4-6 | MS42 (13 56 696), MS43 (13 57 650) | GS8.60.0 (24 10 620) |
| E46 | B3S 3.4 | E5/1 | MS43 (13 57 653, 13 57 656) | GS8.60.4 (24 10 644) |

The complete and up-to-date list, including WinKFP information, is on the wiki page.

## Wanted

Some files are still missing, for example Motronic M3.3.1 (E36 B6 2.8), GS8.36 (E36 B3 3.2), ME7.2 and GS8.60.2 for the Roadster V8 / B10 V8S.
If you own one of these cars or control units and can provide a read, please [open an issue](https://github.com/ms4x-net/alpina/issues) or get in touch via [ms4x.net](https://www.ms4x.net).

## File naming

`<Manufacturer>_<ECU>_<Software>_<Chassis>_<Engine>_<Displacement>_Alpina_<Model>_<Alpina part #>_<VIN>_<Full|Bootmode>.bin`

Example: `Siemens_MS42_0110C6_E46_E4.4_3.3L_Alpina_B3_1356696_WAPB333L09ME44217_Full.bin`

## Note

Files are provided for preservation, repair and research. No warranty.
<!-- TODO: decide on license/usage note for original firmware binaries (no GPL for third-party binaries) -->
