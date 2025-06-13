# Field Operations and Sampling Protocols for Net Tows
During dedicated Northeast U.S. Shelf Long-Term Ecological Research (NES-LTER) transect cruises, zooplankton sampling is conducted at each standard transect station (L1 – L11) and near the Martha’s Vineyard Coastal Observatory (MVCO). Zooplankton are collected with a 61-cm diameter Bongo net, equipped with two nets of different mesh sizes (335-µm and 150-µm). Each net is 3.2 m in length, conically shaped, and tapers down to a detachable codend, with porosities of 45% and 46%, respectively. A General Oceanics mechanical flowmeter is mounted at the center of each net’s mouth to quantify the volume of water filtered. A Star-Oddi DST centi-TD temperature-depth recorder (TDR) is attached to the bongo frame to record the net’s maximum depth, tow trajectory, and water temperature at a 1-second recording interval. TDR data is downloaded after the tow is completed. For select cruises, a SeaBird SBE 9plus CTD is mounted on the Bongo wire above the nets to obtain real-time depth data. While towing, the net’s depth is checked by monitoring wire angle using a handheld inclinometer and amount of wire paid out. Zooplankton sampling tows are conducted as single oblique (descending and ascending once) at a speed through the water of 1.5 to 2.0 knots. The target net depth is 5 m above the seafloor or 200 m when bottom depth exceeds 200 m. Winch pay-out and retrieval speeds follow NOAA’s EcoMon protocol and vary depending on the target sampling depth. For depths greater than 60 m, the maximum pay-out speed is 30 m/min, and the retrieval speed is 20 m/min. Pay-out speed is always faster than retrieval speed. The bongo frame is secured to the end of the wire using a shackle, and a 1.5 ft chain section and 45 kg weight are attached to the bottom of the frame. 

Upon retrieval, the nets are rinsed on the outside with seawater to ensure that all plankton are collected in the cod ends. Once the water level is below the opening, the cod ends are carefully removed, and the nets are placed in labeled buckets designated for each mesh size (335-µm and 150-µm). These labeled cod ends are then brought to the wet lab for processing. Samples are split using a Folsom splitter, following an established splitting protocol, with aliquots preserved in a 5% buffered formalin-seawater solution, 95% ethanol, or frozen, according to the specific analysis to be performed. 
For samples collected with the 335-µm mesh net, the split is as follows:
* ¾ split for morphological identification by the Plankton Sorting and Identification Center in Poland, as part of a collaboration with NOAA Fisheries.
* ¼ split for DNA barcoding, sent to the Rynearson Laboratory at the University of Rhode Island. 
This package includes data of samples from the ¾ morphological identification fraction of the 335 µm mesh net, which are preserved in a 5% buffered formalin-seawater solution. 
Samples from the 150-µm mesh net, which serve different purposes, will be published as a separate data package. Additionally, a small ring net attached to the same wire above the Bongo is used to collect size-fractionated samples for stable isotope analysis, which will be included in a separate package.

Four data files are included in this package, providing detailed sample information in different formats:

* nes-lter-zooplankton-abundance-335um-unstaged10m2.csv: Contains aerial abundance data for zooplankton collected with the 335-µm mesh net, standardized to 10 square meters.
* nes-lter-zooplankton-abundance-335um-unstaged100m3.csv: Contains volumetric abundance data for zooplankton collected with the 335-µm mesh net, standardized to 100 cubic meters.
* nes-lter-zooplankton-abundance-335um-staged10m2.csv: Contains stage-specific abundance data standardized to 10 square meters.
* nes-lter-zooplankton-abundance-335um-staged100m3.csv: Contains stage-specific abundance data, standardized to 100 cubic meters.

The staged data include only the 15 taxa that are staged. 

Cruise dates and research vessel information are in the file nes-lter-zp-cruises-metadata.csv. 

Event logs of Bongo net tows were recorded onboard using the Rolling Deck to Repository (R2R) event logger (elog) software and are published in: 
Northeast U.S. Shelf LTER, H.M. Sosik, and E.T. Crockford. 2025. Event logs from Northeast U.S. Shelf Long Term Ecological Research (NES-LTER) Transect cruises, ongoing since 2017 ver 2. Environmental Data Initiative. https://doi.org/10.6073/pasta/0cde75ba26923d87e107a1c440613209 

Updated event logs, detailed field operations, station-specific metadata, sample allocation information, and inventory of samples designated for morphological identification (PI recipient: David Richardson) can be found in:
Cabanelas, A.C., M. Ferguson, J.K. Llopiz, and M. Sato. 2025. Zooplankton sample inventory for Northeast U.S. Shelf Long Term Ecological Research (NES-LTER) Transect cruises, ongoing since 2018 ver 2. Environmental Data Initiative. https://doi.org/10.6073/pasta/8ff3d6baebd5e10cf59c527da0081e4b 

# Morphological identification
Zooplankton collected with the 335 µm mesh net are divided into two fractions: ¾ of the sample is designated for morphological identification, and the remaining ¼ is used for DNA barcoding. The ¾ fraction for morphological identification is processed by staff at the Morski Instytut Rybacki (National Marine Fisheries Institute) Plankton Sorting and Identification Center in Szczecin, Poland, following Northeast Fisheries Science Center (NEFSC) sorting protocols. Samples are reduced to approximately 500 organisms by subsampling with a modified box splitter, after which zooplankton are sorted, counted, and identified to the lowest possible taxonomic level. Counts for each taxon are multiplied by the number of aliquots to estimate total sample abundance, which is then adjusted using standard haul factors. 

Note: Copepoda refers to copepods that are not specifically named in the data table. A value of zero indicates absence in the sample. This version of the data package includes staged data, and both 100m³ and 10m² abundance values.

Only selected taxa are staged, including: Calanus finmarchicus, Centropages typicus, Metridia lucens, Paracalanus parvus, Pseudocalanus minutus, Temora longicornis, Centropages hamatus, Nannocalanus minor, Clausocalanus arcuicornis, Euphausia krohnii, Thysanoessa gregaria, Thysanoessa longicaudata, Nematoscelis megalops, Thysanoessa raschii, Meganyctiphanes norvegica.

These samples are processed following MARMAP NEFSC Sorting Protocols 5.3.1 ECOSYSTEM MONITORING - ZOOPLANKTON.
Jossi, J. W., Griswold, C. A., Prezioso, J., Taylor, M., & O’Reilly, J. Ecosystem Monitoring Program: Survey Operations Manual. http://globec.whoi.edu/BCO-DMO/Reports/Bongo-OperationsManual-2005.doc [details]
https://demo.bco-dmo.org/publication/841674

# Calculations
## Abundance
For Abundance per 10m2:
A =  (C × Q × Z) / (V × 10) × (1 / Sf)
For Abundance per 100m3:
A =  (C × Q) / (V × 100) × (1 / Sf)
Where:
- A = abundance of organisms (individuals per 10 m² or 100 m³, depending on the equation)
- C = number of organisms counted in the aliquot
- Q = aliquot factor
- Z = maximum tow depth (in meters)
- V = volume of water filtered (in cubic meters)
- Sf = sample split factor

## Abundance Standardization 

Abundances were normalized by incorporating the appropriate haul factor directly into the formulas for A (above). The haul factor standardizes organism counts to a consistent sampling unit: 10 m2 of surface area or 100 m3 of water volume. This standardization accounts for variations in tow depth and volume of water filtered across samples.
### Haul Factor
For 10 m2: (Z × 10) / V
For 100 m3: 100 / V
Where:
- Z = maximum tow depth (in meters) 
- V = volume of water filtered (in meters cubed) 

## Volume of Water Filtered
The volume of water filtered was calculated with a flowmeter using the following equation:
V = (R)(Ff)(A),
Where:
- V = calculated volume of water filtered (in meters cubed)
- R = number of flowmeter revolutions during tow
- Ff = factory calibration factor (in meters per revolution) = 0.26873
- A = area of net mouth (in meters squared) = 0.2922
When flowmeters malfunctioned, such as in EN627, the volume of water sampled was calculated as: 
V=(A) (T) (S)
 
Where:
- V = calculated volume of water filtered (in meters cubed)
- A = area of net mouth (in meters squared) = 0.2922
- T = duration of tow (in seconds)
- S = ship speed during tow (in meters per second)

These values can be found in the vol\_filtered\_335 column of the corresponding data inventory package [knb-lter-nes.24.2]. 

## Day vs. Night Tow Classification

The "day_night" column indicates whether the zooplankton tow occurred during the day or night. This was determined based on local time and sampling coordinates, with the R package suncalc (v0.5.1).  For this, the `getsunlightTimes` function was applied to calculate the times of sunrise (when the top edge of the sun appears on the horizon) and sunset (when the sun disappears below the horizon, evening civil twilight starts) for each sample. 

Thieurmel B, Elmarhraoui A (2022). suncalc: Compute Sun Position, Sunlight Phases, Moon Position and Lunar Phase. R package version 0.5.1, <https://CRAN.R-project.org/package=suncalc>.

# TDR Data 

In some instances, the sampling depth (net maximum depth) was not recorded by the temperature-depth recorder (TDR) or the CTD attached to the bongo wire. Since this depth is necessary for calculating depth-integrated 10 m² abundances, when it was unavailable, maximum tow depth (in meters) was estimated using the following equation based on the straight cosine law:

Z = L * cos(α)

Where:
- Z = estimated maximum tow depth (in meters)
- L = length of wire paid out (in meters)
- α = wire angle (in radians)

Sampling depths can be found in the depth\_TDR and net\_max\_depth\_m columns in the corresponding data inventory package [knb-lter-nes.24.2].

# Sampling Issues and Considerations

Occasionally, the bongo net hits the seabed during the tow, resulting in missed samples when there is no time to redeploy. Whenever possible, the nets are rinsed and redeployed. In a few instances, the sand and/or mud was sieved, and samples preserved. These occurrences are documented in the comment columns. Every effort is made to sample all LTER transect stations (L1-L11) and MVCO, but weather conditions sometimes prevent sampling at all stations. As a result, data for certain stations may be limited or unavailable.
# Data Flags
Data quality flags were assigned following the Ocean Best Practices UNESCO 2013 IOC 54:V3 Primary Level Flagging standard. This standard uses a value system to indicate data quality:
1: Good (passed documented required QC tests)
2: Not evaluated, not available, or unknown (no QC test performed or information on quality is not available)
3: Questionable/suspect (failed non-critical documented metric or subjective test(s))
4: Bad (failed critical documented QC test(s) or as assigned by the data provider)
9: Missing data (used as a placeholder when data are missing)
Advanced Flagging Scheme
In addition to the primary level flagging, the Ocean Best Practices UNESCO 2013 IOC 54:V3 standard also describes an advanced flagging scheme. This scheme provides more detailed information about the quality of oceanographic data and includes secondary level flags for additional documentation. 
U.S. Integrated Ocean Observing System, 2020. Manual for the Use of Real-Time
Oceanographic Data Quality Control Flags, Version 1.2. 24 pp. https://doi.org/10.25923/w8y6-d298 
# Quality assurance and data package assembly
Data package assembly was completed in R. To ensure the accuracy of the entries for physical samples from zooplankton net tows, data was validated using R. This involved checking for ranges of values and unique strings in each column. All coordinates were plotted on a map to ensure that the values were within reasonable ranges. Entries were cross-referenced with the scanned Bongo/Ring Event Log sheets and the event log for each cruise. Missing values were identified, and NAs assigned. 

# Differences From Previous Version

Version 1 of this data package included only unstaged abundance of 14 taxa. This second version of the data package includes staged and unstaged abundance data in volumetric (100 m³) and aerial (10 m²) units from the 335-µm net. Supplemental tables provide metadata for the cruises and stations. 


# Related Packages 
This is the second version of the NES-LTER zooplankton abundance data package [knb-lter-nes.25.2]. The previous data package [knb-lter-nes.25.1] included zooplankton abundance data for the following cruises: EN608, EN617, AR38, EN649, EN655, and EN657. This package adds abundance data for the following cruises: AR32, EN627, EN644, EN661, EN668, AR63, AT46, EN687, EN695, HRS2303, and EN706. Total # of cruises included: 17. 

Other related packages include event log data package [knb-lter-nes.20.1], zooplankton abundance data package version 1 [knb-lter-nes.25.1], and zooplankton sample inventory [knb-lter-nes.24.2] for transect cruises. 

