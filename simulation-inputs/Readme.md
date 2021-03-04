# simulation-inputs

## `volve-b-fluid-model.GRDECL`

Eclipse keyword Stlye Fluid model. Most of the details of this fluid model are based upon the original PVT model provided by equinor.

## `volve-b-production-history.vol`

Standardised 5-day production history for the Volve field. The original data set and the V2016 model did not include data for F-1C.

Columns are:

| Column |  Description  | Units   |
|--------|:-------------:|:-------:|
| DAY    | Day of Month          | |
| MONTH  | Month                 | |
| YEAR   | Year                  | |
| HOUR   | Hour                  | |
| MINUTE | Minute                | |
| SECOND | Second                | |
| BHP    | Bottom Hole Pressure  | bar |
| WINJ   | Water Injection Rate  | Sm<sup>3</sup> |
| GAS    | Gas Production Rate   | Sm<sup>3</sup> |
| OIL    | Oil Production Rate   | Sm<sup>3</sup> |
| WATER  | Water Production Rate | Sm<sup>3</sup> |

## `volve-b-v2020-highperm.GRDECL`

Eclipse keyword Style relative permeability model for High Permeability sands. This is a personal interpretation of the original model and avaialble data.

## `volve-b-v2020-lowperm.GRDECL`

Eclipse keyword Style relative permeability model for Low Permeability sands. This is a personal interpretation of the original model and avaialble data.

