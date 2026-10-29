# Engineering Tools · Saga Electrics

A single-file, mobile-first engineering toolbox (`index.html`). Pure HTML/CSS/JS, with no external dependencies, so it works offline: save the page or open the file directly.

Live: https://sagae92.github.io/engineering_toolbox.github.io/

## Tabs

- **Wire Sizing**: Spec 55 (Hookup 55A011X / Airframe 55A081X) wire-size calculator. It uses R20 compensated for temperature (α = 0.00393/°C from 20 °C), and Length is the total conductor length (no doubling). It shows the recommended AWG, plus nearby sizes with mV, % and g/m.
- **IDENT**: MIL-STD-681 colour-code decoder (tap colours, closest to the connector first, up to 3) and encoder (number → colours), with a reference table.
- **Ohm's Law**: enter any two of V, I, R, P; the other two are solved live.
- **Battery**: chemistry usable-% defaults, Ah ↔ kWh (nameplate and usable), C-rate, series/parallel pack helper, runtime and charge-time estimates.
- **GNSS**: Haversine distance and initial bearing (R = 6371.0088 km; km / mi / nmi), and a GGA / RMC NMEA decoder with checksum verification.
- **Radio / RF**: frequency → wavelength, ¼ / ½-wave antenna lengths with velocity factor, free-space path loss, SWR → return loss / reflected power / mismatch loss.

Metric by default; use the Imperial toggle in the header. Results are estimates; verify against datasheets and the applicable standards.
