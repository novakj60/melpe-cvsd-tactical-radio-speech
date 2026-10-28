# MELPe and CVSD Tactical-Radio Speech – Experimental Data

This repository contains experimental data supporting the manuscript:

**Subjective Listening Effort and Intelligibility of MELPe and CVSD Tactical-Radio Speech over a VHF/UHF Link**

**Authors:** Jiří Novák, Jan Holub, Jakub Turinský, Martin Blaha

**Journal:** Applied Acoustics (Elsevier) – manuscript submitted for publication.

## Experimental overview

The study evaluates subjective listening effort and speech intelligibility for two tactical-radio voice transmission configurations:

- MELPe speech coding over the ANW2C waveform
- CVSD speech coding over the VULOS waveform

Radio transmissions were performed between two stationary TITUS vehicles equipped with L3Harris Falcon III transceivers at three distances: 20 m, 7 km and 13 km.

The listening experiment involved 24 participants who evaluated 120 recorded Czech artillery fire-control utterances across six experimental conditions.

Listening effort was assessed using the five-point MOS-LE scale following ITU-T P.800. Speech intelligibility was evaluated using a six-option closed-set test.

## Dataset

**File:** `MELPe_CVSD_Tactical_Radio_Experimental_Data.xlsx`

The Excel workbook contains seven worksheets:

| Worksheet | Description |
|---|---|
| Raw data | Individual MOS-LE ratings (1–5) and intelligibility responses (0 = incorrect, 1 = correct) for 120 recordings and 24 listeners. |
| Results | Statistical results and aggregated measurements for the six experimental conditions. |
| MOS-LE | Listener-level mean MOS-LE scores used for Figure 1. |
| Intelligibility | Listener-level intelligibility percentages used for Figure 2. |
| Conditions | Description of the six experimental conditions, including vocoder, waveform, transmission distance and RF transmit power. |
| Summary_for_plots | Condition-level means, 95% confidence intervals and supporting information for graphical presentation. |
| Graphs | Figures 1 and 2 as presented in the manuscript. |

## Data interpretation

Each experimental condition includes 20 recorded speech stimuli, evaluated by 24 listeners, resulting in 480 listening-effort ratings and 480 intelligibility responses per condition.

The listener-level values in the `MOS-LE` and `Intelligibility` worksheets summarize each participant's responses across the 20 stimuli belonging to the respective condition.

The raw data, aggregated results and figures are provided to support transparency, independent verification and reproducibility of the reported findings.

## Corresponding author

Jiří Novák

University of Defence, Faculty of Military Leadership, Department of Fire Support, Czech Republic

Email: jiri.novak12@unob.cz
