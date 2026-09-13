[Datasets to identify and map wards.md](https://github.com/user-attachments/files/32171509/Datasets.to.identify.and.map.wards.md)
# Datasets to identify and map wards in AMAC FCT-Abuja where residents have poor physical access to hospitals

\##GRID3 NGA - Operational State Boundaries (December 4, 2020) 645KB
https://data.grid3.org/datasets/c41532b720504f4799fe20438b7e3b7f\_0/explore?location=9.077959%2C8.685290%2C6
(Nigeria Operational State Boundaries (administrative level 1))
37 Features multipolygon
Column: globaid, uniq\_id, timestamp, editor, statename, statecode, capacity, source, geozone
Null data: 22 null data for statename
covers my state fully



\##GRID3 NGA - Operational LGA Boundaries (December 10, 2020) 2.62MB
https://data.grid3.org/datasets/2bb616a49ee84f409427cc2143787113\_0/explore?location=9.077959%2C8.685290%2C6
(Nigeria Operational Local Government Area (LGA) Boundaries (administrative level 2))
774 Features multipolygon 
Column:  globaid, uniq\_id, timestamp, editor, lganame, lgacode statename, statecode, source, geozone, amapcode
Null data: 44 null data for lganame
Covers my LGA fully



\##GRID3 NGA - Health Facilities v3.0 (August 13, 2026) 4.72MB
https://data.grid3.org/maps/827e3638dc204f4b9ddbbd19b00954d6
(The GRID3 NGA - Health Facilities v3.0 dataset is a non-exhaustive, non-validated geographic representation of health facility points in Abia, Adamawa, Bauchi, Bayelsa, Borno, Delta, Enugu, FCT Abuja, Gombe, Jigawa, Kaduna, Kano, Katsina, Kebbi, Kogi, Kwara, Nasarawa, Niger, Ogun, Osun, Oyo, Sokoto, Yobe, Zamfara states. This dataset is considered operational.)
41778 Features points, 262 selected
Column: unique\_id, latitude, longitude, country, iso, state\_stan, lga\_standa, ward\_stand, ward\_bdry, ward\_in\_gr, facility\_n, alt\_name, settlement, facility\_i, facility\_t, facility\_o, facility\_1, functional, date\_creat, sett\_ext\_t, mgrs\_code, input\_data, input\_da\_1, nhfr\_facil, gps\_accura, sett\_ext\_d dist\_ward\_, flag1, flag2, flag3, flag4, flag5, flag6, issues, flag\_count,
Null data: 213 null data in facility\_n



\##GRID3 NGA - Operational Wards v3.0 (June 30, 2026) 127MB
https://data.grid3.org/datasets/45cd2ef592094d12aca43113a90a6054\_0/explore?location=9.077872%2C8.670771%2C6
(The GRID3 NGA - Operational Wards v3.0 dataset provides operational ward boundary polygons for 24 states in Nigeria: Abia, Adamawa, Bauchi, Bayelsa, Borno, Delta, Enugu, FCT Abuja, Gombe, Jigawa, Kaduna, Kano, Katsina, Kebbi, Kogi, Kwara, Nasarawa, Niger, Ogun, Osun, Oyo, Sokoto, Yobe, and Zamfara. These boundaries are intended for operational use and have not yet undergone full validation by relevant government authorities.)(administrative level 3)
5872 Feature multipolygon, 12 wards selected
Column: Country, iso3, state, statecode, lga, lga\_alt\_na, ward, ward\_alt\_na, ward\_v1\_gr, multipart\_, source, date, area\_sqkm
No null data: 22 null data in lga



\#Road Data: QUICKOSM plugin in QGIS
Query: highway=\* within AMAC LGA Abuja-FCT.
Extracted: 13th sept, 2026
59,990 features lines

All data were downloaded and extracted today, 13th Sept, 2026

