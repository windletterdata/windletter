# Windletter · Onshore Wind Turbine Charts

Interactive charts comparing current onshore wind turbine models by rotor diameter, rated power and specific power. Published by [Windletter](https://windletter.substack.com), a weekly newsletter on the wind energy industry ([English edition](https://windletteren.substack.com)).

## 📊 View the charts

**[Open the interactive charts →](https://windletterdata.github.io/windletter/OnshoreWTGs_Chart.html)**

- **Rated power vs rotor diameter**: where each model sits in MW for a given rotor size.
- **Specific power vs rotor diameter**: rated power per swept area (W/m²), with shaded bands for indicative IEC wind classes.

Hover over or tap any dot to see the model's rating, rotor diameter and specific power.

## Methodology

**Specific power** is the rated power divided by the rotor swept area:

```
Specific power (W/m²) = Rated power (W) / (π · D² / 4)
```

A lower specific power means a larger rotor for the same rating. Such a machine captures more energy at low wind speeds and is typically aimed at low- to medium-wind sites.

**IEC wind class bands** (indicative only, not normative):

| Band | Specific power | Typical mean wind speed |
|---|---|---|
| IEC I | > 350 W/m² | > 8.5 m/s |
| IEC II | 280–350 W/m² | 7.5–8.5 m/s |
| IEC II–III | 230–280 W/m² | 6.5–7.5 m/s |
| IEC III/S | < 230 W/m² | < 6.5 m/s |

These bands reflect common industry practice for turbine positioning. They are not part of the IEC 61400-1 standard, which classifies turbines by reference wind speed and turbulence, not by specific power.

## Dataset

29 onshore models from 9 manufacturers, rotors of 145 m and above.

| Manufacturer | Model | Rated power (MW) | Rotor (m) | Specific power (W/m²) | Indicative IEC band |
|---|---|---|---|---|---|
| Vestas | V150-4.2 | 4.2 | 150 | 238 | II–III |
| Vestas | V150-4.5 | 4.5 | 150 | 255 | II–III |
| Vestas | V150-6.0 | 6.0 | 150 | 340 | II |
| Vestas | V162-6.2 | 6.2 | 162 | 301 | II |
| Vestas | V162-7.2 | 7.2 | 162 | 349 | II |
| Vestas | V163-4.5 | 4.5 | 163 | 216 | III/S |
| Vestas | V172-7.2 | 7.2 | 172 | 310 | II |
| Vestas | V182-7.2 | 7.2 | 182 | 277 | II–III |
| Siemens Gamesa | SG 5.0-145 | 5.0 | 145 | 303 | II |
| Siemens Gamesa | SG 7.0-170 | 7.0 | 170 | 308 | II |
| Nordex | N163/5.9 | 5.9 | 163 | 283 | II |
| Nordex | N163/7.0 | 7.0 | 163 | 335 | II |
| Nordex | N175/7.3 | 7.3 | 175 | 303 | II |
| Nordex | N193/7.3 | 7.3 | 193 | 250 | II–III |
| GE Vernova | GE 6.1-158 | 6.1 | 158 | 311 | II |
| GE Vernova | GE 6.0-164 | 6.0 | 164 | 284 | II |
| Suzlon | S163-6.3 | 6.3 | 163 | 302 | II |
| Suzlon | S175-5.0 | 5.0 | 175 | 208 | III/S |
| Enercon | E-175 EP5 | 7.0 | 175 | 291 | II |
| Envision | EN-171/6.5 | 6.5 | 171 | 283 | II |
| Envision | EN-175/8.0 | 8.0 | 175 | 333 | II |
| Envision | EN-182/8.0 | 8.0 | 182 | 308 | II |
| Ming Yang | MySE 6.25-172 | 6.25 | 172 | 269 | II–III |
| Ming Yang | MySE 6.25-182 | 6.25 | 182 | 240 | II–III |
| Ming Yang | MySE 8.0-175 | 8.0 | 175 | 333 | II |
| Goldwind | GW165-6.0 | 6.0 | 165 | 281 | II |
| Goldwind | GWH170-7.2 | 7.2 | 170 | 317 | II |
| Goldwind | GWH175-7.8 | 7.8 | 175 | 324 | II |
| Goldwind | GWH182-8.0 | 8.0 | 182 | 308 | II |

**Notes**

- Ratings shown are the maximum announced for each model. Some platforms offer several power modes. For example, the Nordex N193/7.X will first enter Germany at 6.6 MW.
- Data comes from manufacturers' public product information and announcements.

## Sources & credit

Data: manufacturers' public product information. Charts and analysis: [Windletter](https://windletter.substack.com).

If you use these charts, please credit **Windletter** and link back to this page.
