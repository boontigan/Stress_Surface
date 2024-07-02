# Stress Faults Rivers
This repository stores data and codes using for the manuscript: __Unraveling the Connection between Subsurface Stress and Geomorphic Features__ 

The code, __Kuhasubpasin_et_al_2024_Figure.ipynb__ is used for reproduced all figures in the manuscript.

The data file using in this study is __'Input_stress_fault_river_BK.csv'__.

The file contain these following data:

| Column        | unit      | range       | description   |
| ------------- | --------- | ----------- | ------------- |
| lat           | degree    | (-90, 90)   | Latitude      |
| lon           | degree    | (-180, 180) | Longitude     |
| azi_R         | degree    | (0, 180)*   | Interpolated azimuth of river network (interpolate without considering river order) |
| azi_r1        | degree    | (0, 180)*   | Interpolated azimuth of 1'-order river |
| azi_r2        | degree    | (0, 180)*   | Interpolated azimuth of 2'-order river |
| azi_r3        | degree    | (0, 180)*   | Interpolated azimuth of 3'-order river |
| azi_r4        | degree    | (0, 180)*   | Interpolated azimuth of 4'-order river |
| azi_r5        | degree    | (0, 180)*   | Interpolated azimuth of 5'-order river |
| Drainage_area | cell      | -           | Drainage area |
| river_order   | order     | (1, 7)      | Majority of the order river in grid cell |
| elev          | km        | (0, 5.1375) | Elevation     |
| azi_Z         | degree    | (0, 180)*   | Topographic aspect |
| azi_F         | degree    | (0, 180)*   | Interpolated azimuth of faults |
| reg_F         | -         | (0, 1)      | Regime of F |
| azi_SO        | degree    | (0, 180)*   | Interpolated azimuth of feature $\sigma_{O}$ |
| reg_SO        | -         | (0, 1)      | Regime of $\sigma_{O}$ |
| azi_SL        | degree    | (0, 180)*   | Interpolated azimuth of feature $\sigma_{L}$ |
| reg_SL        | -         | (0, 1)      | Regime of $\sigma_{L}$ |
| sp1_SL        | Pa        | -           | Magnitude of principal stress 1 for $\sigma_{L}$ |
| sp2_SL        | Pa        | -           | Magnitude of principal stress 2 for $\sigma_{L}$ |
| azi_SM        | degree    | (0, 180)*   | Interpolated azimuth of feature $\sigma_{M}$ |
| reg_SM        | -         | (0, 1)      | Regime of $\sigma_{M}$ |
| sp1_SM        | Pa        | -           | Magnitude of principal stress 1 for $\sigma_{M}$ |
| sp2_SM        | Pa        | -           | Magnitude of principal stress 2 for $\sigma_{M}$ |
| azi_ST        | degree    | (0, 180)*   | Interpolated azimuth of feature $\sigma_{T}$ |
| reg_ST        | -         | (0, 1)      | Regime of $\sigma_{T}$ |
| sp1_ST        | Pa        | -           | Magnitude of principal stress 1 for $\sigma_{T}$ |
| sp2_ST        | Pa        | -           | Magnitude of principal stress 2 for $\sigma_{T}$ |
| azi_SB        | degree    | (0, 180)*   | Interpolated azimuth of feature $\sigma_{B}$ |
| delta_SO_F    | degree    | (0, 90)     | $\Delta \sigma_{O} - F$ |
| delta_SL_F    | degree    | (0, 90)     | $\Delta \sigma_{L} - F$ |
| delta_SM_F    | degree    | (0, 90)     | $\Delta \sigma_{M} - F$ |
| delta_ST_F    | degree    | (0, 90)     | $\Delta \sigma_{T} - F$ |
| delta_SB_F    | degree    | (0, 90)     | $\Delta \sigma_{B} - F$ |
| delta_SO_R1   | degree    | (0, 90)     | $\Delta \sigma_{O} - R1$ |
| delta_SL_R1   | degree    | (0, 90)     | $\Delta \sigma_{L} - R1$ |
| delta_SM_R1   | degree    | (0, 90)     | $\Delta \sigma_{M} - R1$ |
| delta_ST_R1   | degree    | (0, 90)     | $\Delta \sigma_{T} - R1$ |
| delta_SB_R1   | degree    | (0, 90)     | $\Delta \sigma_{B} - R1$ |
| delta_F_R1    | degree    | (0, 90)     | $\Delta F - R1$ |
| delta_SO_R2   | degree    | (0, 90)     | $\Delta \sigma_{O} - R2$ |
| delta_SL_R2   | degree    | (0, 90)     | $\Delta \sigma_{L} - R2$ |
| delta_SM_R2   | degree    | (0, 90)     | $\Delta \sigma_{M} - R2$ |
| delta_ST_R2   | degree    | (0, 90)     | $\Delta \sigma_{T} - R2$ |
| delta_SB_R2   | degree    | (0, 90)     | $\Delta \sigma_{B} - R2$ |
| delta_F_R2    | degree    | (0, 90)     | $\Delta F - R2$ |
| delta_SO_R3   | degree    | (0, 90)     | $\Delta \sigma_{O} - R3$ |
| delta_SL_R3   | degree    | (0, 90)     | $\Delta \sigma_{L} - R3$ |
| delta_SM_R3   | degree    | (0, 90)     | $\Delta \sigma_{M} - R3$ |
| delta_ST_R3   | degree    | (0, 90)     | $\Delta \sigma_{T} - R3$ |
| delta_SB_R3   | degree    | (0, 90)     | $\Delta \sigma_{B} - R3$ |
| delta_F_R3    | degree    | (0, 90)     | $\Delta F - R3$ |
| delta_SO_R4   | degree    | (0, 90)     | $\Delta \sigma_{O} - R4$ |
| delta_SL_R4   | degree    | (0, 90)     | $\Delta \sigma_{L} - R4$ |
| delta_SM_R4   | degree    | (0, 90)     | $\Delta \sigma_{M} - R4$ |
| delta_ST_R4   | degree    | (0, 90)     | $\Delta \sigma_{T} - R4$ |
| delta_SB_R4   | degree    | (0, 90)     | $\Delta \sigma_{B} - R4$ |
| delta_F_R4    | degree    | (0, 90)     | $\Delta F - R4$ |
| delta_SO_R5   | degree    | (0, 90)     | $\Delta \sigma_{O} - R5$ |
| delta_SL_R5   | degree    | (0, 90)     | $\Delta \sigma_{L} - R5$ |
| delta_SM_R5   | degree    | (0, 90)     | $\Delta \sigma_{M} - R5$ |
| delta_ST_R5   | degree    | (0, 90)     | $\Delta \sigma_{T} - R5$ |
| delta_SB_R5   | degree    | (0, 90)     | $\Delta \sigma_{B} - R5$ |
| delta_F_R5    | degree    | (0, 90)     | $\Delta F - R5$ |
| delta_SO_R>1  | degree    | (0, 90)     | $\Delta \sigma_{O} - R>1$ |
| delta_SL_R>1  | degree    | (0, 90)     | $\Delta \sigma_{L} - R>1$ |
| delta_SM_R>1  | degree    | (0, 90)     | $\Delta \sigma_{M} - R>1$ |
| delta_ST_R>1  | degree    | (0, 90)     | $\Delta \sigma_{T} - R>1$ |
| delta_SB_R>1  | degree    | (0, 90)     | $\Delta \sigma_{B} - R>1$ |
| delta_F_R>1   | degree    | (0, 90)     | $\Delta F - R>1$ |
| delta_SO_Z    | degree    | (0, 90)     | $\Delta \sigma_{O} - Z$ |
| delta_SL_Z    | degree    | (0, 90)     | $\Delta \sigma_{L} - Z$ |
| delta_SM_Z    | degree    | (0, 90)     | $\Delta \sigma_{M} - Z$ |
| delta_ST_Z    | degree    | (0, 90)     | $\Delta \sigma_{T} - Z$ |
| delta_SB_Z    | degree    | (0, 90)     | $\Delta \sigma_{B} - Z$ |
| delta_F_Z     | degree    | (0, 90)     | $\Delta F - Z$ |
| MI            | -         | -           | Mantle influence index |
$\*$ The range is not (0,360) because we only consider azimuth not direction

Last modified: 07/02/24

Booontigan Kuhasubpasin
