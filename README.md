# ELEC3400 Lab3 — final A–E simulation figures

These plots were generated from the saved Spectre transient data used in the final Lab3 report. They are plotted exports, not screenshots of the ViVA interface.

| File | Content |
| --- | --- |
| figures/A_waveforms.png | Case A, behavioural amplifier |
| figures/B_waveforms.png | Case B, corrected transistor-level amplifier |
| figures/C_waveforms.png | Case C, reduced inductance |
| figures/D_waveforms.png | Case D, retuned capacitance |
| figures/E27_waveforms.png | Case E, 27 uF output capacitor, smallest tested passing value |
| figures/E26_waveforms.png | Case E, 26 uF comparison, below the 90% threshold |
| figures/AB_comparison.png | A versus B |
| figures/BCD_comparison.png | B versus C versus D |
| figures/E_comparison.png | E capacitor comparison against the B baseline |

Each case waveform figure contains P0, P1, P2 and P3. Audio traces use 40–50 ms; P1 uses the final 20 us to resolve the carrier. B–E use the final grounded-substrate results. Uncorrected diagnostic runs are excluded.

This repository contains nine PNG figures and their checksums. It does not contain native OA schematics, PSF datasets, the PDK, simulator software or a simulation-restoration package.

## Download on Linux

Authenticate with GitHub CLI as an account with access, then run:

```sh
gh repo clone Maxnopnop/ELEC3400-Lab3-waveforms
cd ELEC3400-Lab3-waveforms
sha256sum -c SHA256SUMS
```

Alternatively, after configuring Git authentication:

```sh
git clone https://github.com/Maxnopnop/ELEC3400-Lab3-waveforms.git
```

Open the PNG files in `figures/` with an image viewer. No Cadence installation is needed to view them.