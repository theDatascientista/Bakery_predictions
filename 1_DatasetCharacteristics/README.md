# Dataset Characteristics

Provide information on the following issues:

- **Dataset Overview**
-  Shape: 10,103 rows × 9 columns
-  Rows: Datum, Bewoelkung, Temperatur, Windgeschwindigkeit, Wettercode, id, Warengruppe, Umsatz, KielerWoche

- **Missing Values**
| Column                  | Missing Values | Percentage (%) |
| ----------------------- | -------------- | -------------- |
| **KielerWoche**         | 9,853          | 97.53%         |
| **Wettercode**          | 2,522          | 24.96%         |
| **id**                  | 785            | 7.77%          |
| **Warengruppe**         | 785            | 7.77%          |
| **Umsatz**              | 785            | 7.77%          |
| **Bewoelkung**          | 55             | 0.54%          |
| **Datum**               | 0              | 0.00%          |
| **Temperatur**          | 0              | 0.00%          |
| **Windgeschwindigkeit** | 0              | 0.00%          |

- **Feature Distributions**
- Bewoelkung: Mostly concentrated at higher values (around 6–8)
- Temperatur: Bell-shaped distribution, possibly normal, centered around 7–10°C
- Windgeschwindigkeit: Skewed right — most values are moderate, with a few high wind speeds
- Wettercode: Shows several distinct peaks due to being categorical
- id, Warengruppe: categorical
- Umsatz: right-skewed, with many entries near zero and some high outliers
- KielerWoche: extreme sparsity, since it's only a short event

- **Correlations**
- All Weather related features are correlated (Windgeschwindigkeit, Temperatur, Wettercode)
- During new years eve a peak in Kuchen can be observed


