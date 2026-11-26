# Engineering Tools · Saga Electrics

A single-file, mobile-first engineering toolbox (`index.html`). Pure HTML/CSS/JS, with no external dependencies, so it works offline: save the page or open the file directly.

Live: https://sagae92.github.io/engineering_toolbox.github.io/

## Tabs

### Electrical

- **Wire Sizing**: Spec 55 (XL-ETFE) and TR16 (Thermorad / XLPO) wire-size calculator, matching sagaelectrics.eu. It uses R20 compensated for temperature (α = 0.00393/°C from 20 °C), and Length is the total conductor length (no doubling). It shows the recommended size, plus nearby sizes with mV, % and g/m.
- **IDENT**: MIL-STD-681 colour-code decoder (tap colours, closest to the connector first, up to 3) and encoder (number → colours), with a reference table.
- **Ohm's Law**: enter any two of V, I, R, P; the other two are solved live.
- **Battery**: chemistry usable-% defaults, Ah ↔ kWh (nameplate and usable), C-rate, series/parallel pack helper, runtime and charge-time estimates, plus typical/rough chemistry presets for max continuous/peak/charge C-rate (with current-limit warnings), IR drop under load, and pack mass/volume from Wh/kg and Wh/L.
- **Divider**: voltage divider — fill any three of Vin, R1, R2, Vout; live Vout, current and power in each resistor.
- **RC**: first-order time constant, cutoff frequency and ½CV² energy, with short automotive notes (ECU/sensor input filter and inductive-load snubber).
- **GNSS**: Haversine distance and initial bearing (R = 6371.0088 km; km / mi / nmi), and a GGA / RMC NMEA decoder with checksum verification.
- **Radio / RF**: frequency → wavelength, ¼ / ½-wave antenna lengths with velocity factor, free-space path loss, SWR → return loss / reflected power / mismatch loss.

### Mechanical

- **Adhesives**: bond-area force calculator (N / kgf / lbf, optional safety factor); material notes (CTE, typical max temperature, surface prep); a Loctite + 3M library and a substrate-pair suggester. Library values are typical manufacturer TDS figures — verify for the application.
- **Torque**: metric coarse M3–M24 (plus a few UNC sizes) torque helper, T = K × F × d, default preload 75 % of ISO 898-1 proof load (ISO 3506-1 yield for A2-70 / A4-70). Dry K ≈ 0.20, oiled K ≈ 0.15, all editable. The drawing or manufacturer torque is the real target.
- **Materials**: potting-compound library (epoxies, polyurethanes, silicones/gels, including typical automotive classes). Hardness, thermal conductivity, temperature, cure, uses and notes — typical/rough values, all editable and saved in the browser.
- **Strain**: strain-gauge bridge calculator (quarter, half-bending, full-bending, torque/shear ±45°). GF and excitation, material E library, input as µε, stress, or force/torque + geometry (cantilever, axial bar, solid shaft). Output mV, mV/V and sensitivity, with a short instrumentation note.

Metric by default; use the Imperial toggle in the header. Results are estimates; verify against datasheets and the applicable standards.
