---
layout: article
title: "Layers"
excerpt: "OHI layers for British Columbia"
share: false
ads: false
branch_scenario: draft/region2016
toc: true
---

The following data layers are used in Ocean Health Index calculations for goal status, trend, pressures, and resilience. Values for {{ site.study_area }} were extracted from the global assessment and saved for each region to serve as a template as you gather higher-resolution data and indicators. Note that many values do not have a range because they were equally extracted from the global data layer.


## alien_species

Alien species

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | alien_species_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.625 to 0.625                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>The number and type of invasive and harmful invasive species in each marine ecoregion (Molnar et al. 2008). </p>

<p>Data sources:</p>

<ul>
<li>Molnar, J.L., Gamboa, R.L., Revenga C., Spalding, M. (2008). <strong>Assessing the global threat of invasive species to marine biodiversity</strong>. <em>Frontiers in Ecology and the Environment</em> 6(485). <a href="http://dx.doi.org/10.1890/070064">doi:10.1890/070064</a></li>
</ul>



## ao_access

Fisheries management effectiveness and opportunity

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | ao_access_gl2014.csv                                                   |
| value units       | value                                                      |
| value range       | 0.632 to 0.632                               |
| global extraction | equal: global management effectiveness scores were applied equally to all regions. |

<p>The opportunity for artisanal and recreational fishing based on the quality of management of the small- scale fishing sector (Mora et al 2009).</p>

<p>Data sources:</p>

<ul>
<li>Mora, C., Myers, R.A., Coll, M., Libralato, S., Pitcher, T.J., Sumaila, R.U., Worm, B. (2009). <strong>Management Effectiveness of the World<cc><f8><e5><c0><e5><a5>s Marine Fisheries</strong>. <em>PLoS Biol</em>, 7(6), e1000131. <a href="http://dx.doi.org/10.1371/journal.pbio.1000131">doi:10.1371/journal.pbio.1000131</a></li>
</ul>



## ao_need

Purchasing power parity as a proxy for subsistence fishing need, by region

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | ao_need_gl2014.csv                                                   |
| value units       | current international $                                                      |
| value range       | 0.2650289 to 0.3459988                               |
| global extraction | equal: global purchasing power parity information was applied equally to all regions. |

<p>The per capita purchasing power parity (PPP) adjusted gross domestic product (GDP): GDPpcPPP.</p>

<p>Data sources:</p>

<ul>
<li>The World Bank <a href="http://data.worldbank.org/indicator/NY.GDP.PCAP.PP.CD">GDP per capita, PPP (current international $)</a></li>
</ul>



## cc_acid

Ocean acidification

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cc_acid_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.6314455 to 0.6314455                               |
| global extraction | raster | equal:  |

<p>Change in current year&#39;s modeled aragonite saturation state (Feely et al. 2010) relative to historical mean (1880-1889).</p>

<p>Data sources:</p>

<ul>
<li>Feely, R., Doney, S. &amp; Cooley, S. (2009) <strong>Ocean acidification: present conditions and future changes in a high-CO2 world</strong>.
<em>Oceanography</em> 22:36-47. <a href="http://www.tos.org/oceanography/archive/22-4_feely.html">doi:10.5670/oceanog.2009.95</a></li>
<li>J. Afflerbach et al. (2015). <a href="https://github.com/OHI-Science/ohiprep/tree/master/globalprep/Pressures_OceanAcidification/v2015">Methods</a> </li>
</ul>



## cc_slr

Sea level rise

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cc_slr_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.1048945 to 0.1048945                               |
| global extraction | raster | equal:  |

<p>Modeled sea level rise (Nicholls and Cazenave 2010).</p>

<p>Data sources:</p>

<ul>
<li>Nicholls R.J. and Cazenave A. (2010). <strong>Sea-level rise and its impact on coastal zones</strong>. <em>Science</em> 328: 1517-1520. <a href="http://dx.doi.org/10.1126/science.1185782">doi:10.1126/science.1185782</a>. </li>
<li><a href="http://www.aviso.oceanobs.com/en/news/ocean-indicators/mean-sea-level/processing-corrections.html">AVISO Satellite Altimetry Data</a></li>
<li>J. Afflerbach et al. (2015). <a href="https://github.com/OHI-Science/ohiprep/tree/master/globalprep/Pressures_SeaLevelRise/v2015">Methods</a> </li>
</ul>



## cc_sst

Sea surface temperature (SST) anomalies

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cc_sst_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.1620889 to 0.1620889                               |
| global extraction | raster | equal:  |

<p>Sea surface temperature based on temperature anomolies provided by GHRSST and the US National Oceanographic Data Center.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://pathfinder.nodc.noaa.gov">AVHRR Pathfinder Version 5.0 SST data</a> </li>
<li>Casey, K. S., Brandon, T. B., Cornillon, P., and Evans, R. (2010). <strong>The past, present and future of the AVHRR Pathfinder SST Program</strong>, <em>Oceanography from Space: Revisited</em>, eds. V. Barale, J. F. R. Gower, and L. Alberotanza, Springer. <a href="http://dx.doi.org/10.1007/978-90-481-8681-5_16">doi:10.1007/978-90-481-8681-5_16</a></li>
<li>J. Afflerbach et al. (2015). <a href="https://github.com/OHI-Science/ohiprep/tree/master/globalprep/Pressures_SST">Methods</a> </li>
</ul>



## cc_uv

UV radiation

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cc_uv_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.1885856 to 0.1885856                               |
| global extraction | raster | equal:  |

<p>Modeled UV radiation based on Erythemal UV Irradiance data provided by GES DISC.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://disc.sci.gsfc.nasa.gov/data-holdings/PIP/erythemal_uv_irradiance.shtml">Goddard Earth Sciences Data and Information Services Center (GES DISC)</a></li>
<li>J. Afflerbach et al. (2015). <a href="https://github.com/OHI-Science/ohiprep/tree/master/globalprep/Pressures_UV">Methods</a> </li>
</ul>



## cites

Resilience from commitment to CITES

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cites_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 1 to 1                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Convention on International Trade in Endangered Species of Wild Fauna and Flora (CITES) signatories.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cites.org/eng/disc/parties/chronolo.php">CITES List of Contracting Parties</a></li>
</ul>



## cp_habitat_extent_rank

Habitat extent multiplied by rank, per Coastal Protection habitats

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cp_habitat_extent_rank_gl2014.csv                                                   |
| value units       | extent*rank                                                      |
| value range       | 3.493 to 2800227                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Habitat extent multiplied by habitat protection rank for: coral, mangrove (offshore and inland 1km), saltmarsh, sea ice (shoreline), and seagrass</p>



## cs_habitat_extent

Habitat extent multiplied by carbon storage capacity, per Carbon Storage habitats

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cs_habitat_extent_gl2014.csv                                                   |
| value units       | extent*CS capacity                                                      |
| value range       | 289.919 to 92400                               |
| global extraction | area_offshore_3nm: global habitat extent was applied to each region after weighting by each region's offshore area to 3nm.  |

<p>Habitat extent mulitiplied by habitat carbon storage capacity for: mangrove, saltmarsh and seagrass</p>



## cw_coastalpopn_trend

Coastal human population as a proxy for trend in trash

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cw_coastalpopn_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | 0.01387271 to 0.01387271                               |
| global extraction | equal: global trends were applied equally to all regions. |

<p>Coastal population, defined as the total population inland of 25 miles, extracted from Gridded Population of the World (GPW) Population Density Grid Future Estimates.</p>

<p>Data sources:</p>

<ul>
<li>Center for International Earth Science Information Network (CIESIN)/Columbia University </li>
<li>CIESIN &amp; CIAT (Center for International Earth Science Information Network (CIESIN)/Columbia University, &amp; Centro Internacional de Agricultura Tropical (CIAT)) (2005). <strong>Gridded Population of the World, Version 3 (GPWv3): Population Density Grid, Future Estimates</strong>. Palisades, NY. <a href="http://sedac.ciesin.columbia.edu/data/set/gpw-v3-population-density-future-estimates">NASA Socioeconomic Data and Applications Center (SEDAC)</a></li>
</ul>



## cw_fertilizer_trend

Trends in fertilizer pollution as a proxy for nutrient pollution

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cw_fertilizer_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | 0.000366153 to 0.000366153                               |
| global extraction | equal: global trends were applied equally to all regions. |

<p>Modeled data based on fertilizer consumption from the Food and Agricultural Organization (FAO; Halpern et al. 2015). </p>

<p>Data sources:</p>

<ul>
<li><a href="http://faostat3.fao.org/faostat-gateway/go/to/browse/R/*/E">FAO̢<e5><db><e5><aa>s statistical database FAOSTAT</a></li>
<li>Halpern, B. S. et al. (2015). <strong>Spatial and temporal changes in cumulative human impacts on the world&#39;s ocean</strong>. <em>Nature
Communications</em> 6(7615). <a href="http://www.nature.com/ncomms/2015/150714/ncomms8615/full/ncomms8615.html">doi: 10.1038/ncomms8615</a></li>
</ul>



## cw_pathogen_trend

Trends in access to improved sanitation as a proxy for pathogen pollution trend

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cw_pathogen_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | 8.9e-06 to 8.9e-06                               |
| global extraction | equal: global trends were applied equally to all regions. |

<p>Trends in percent of population without access to improved sanitation facilities.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wssinfo.org/data-estimates/table">World Health Organization and United Nations Children&#39;s Fund&#39;s Joint Monitoring Programme (WHO/UNICEF&#39;s JMP)</a></li>
</ul>



## cw_pesticide_trend

Trends in chemical pollution

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | cw_pesticide_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | -0.000208924 to -0.000208924                               |
| global extraction | equal: global trends were applied equally to all regions. |

<p>Modeled chemical pollution from commercial shipping traffic, ports and harbors, and pesticide use (Halpern et al. 2015).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://faostat3.fao.org/faostat-gateway/go/to/browse/R/*/E">FAO̢<e5><db><e5><aa>s statistical database FAOSTAT</a>.</li>
<li>Halpern, B. S. et al. (2015). <strong>Spatial and temporal changes in cumulative human impacts on the world&#39;s ocean</strong>. <em>Nature
Communications</em> 6(7615). <a href="http://www.nature.com/ncomms/2015/150714/ncomms8615/full/ncomms8615.html">doi: 10.1038/ncomms8615</a></li>
</ul>



## fis_b_bmsy

B/Bmsy estimates obtained using the catch-MSY method

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fis_b_bmsy_gl2014.csv                                                   |
| value units       | B / B_msy                                                      |
| value range       | 0.05435161 to 1.986959                               |
| global extraction | equal: global b_bmsy information was applied equally to all regions. |

<p>The ratio of fish population abundance compared to the abundance required to deliver maximum sustainable yield, obtained from the catch-MSY model (Martell &amp; Froese, 2013).</p>

<p>Data sources:</p>

<ul>
<li>Martell, S., &amp; Froese, R. (2013). <strong>A simple method for estimating MSY from catch and resilience</strong>. <em>Fish and Fisheries</em> 14(4): 504-514. <a href="https://dx/doi/org/10.1111/j.1467-2979.2012.00485.x">doi:10.1111/j.1467-2979.2012.00485.x</a></li>
</ul>



## fis_meancatch

Catch data for each Taxon/FAO/SAU region averaged across years

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fis_meancatch_gl2014.csv                                                   |
| value units       | metric tons                                                      |
| value range       | 8.18e-18 to 4787770                               |
| global extraction | :  |

<p>Mean catch-per-taxon values within each Sea Around Us/FAO fishing area.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/area/search/en">FAO Major Fishing Areas</a></li>
<li><a href="http://www.seaaroundus.org">Sea Around Us Project (SAUP)</a></li>
</ul>



## fis_proparea_saup2rgn

proportion area of each SAUP within each OHI reporting region

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fis_proparea_saup2rgn_gl2014.csv                                                   |
| value units       | proportion                                                      |
| value range       | 1 to 1                               |
| global extraction | :  |

<p>Lookup table of Sea Around Us Project regions to Ocean Health Index region identifiers.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.seaaroundus.org">Sea Around Us Project (SAUP)</a></li>
</ul>



## fishing_v1

CBD survey: coastal fishing v1

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fishing_v1_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5496889 to 0.5496889                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## fishing_v1_eez

CBD survey: ocean fishing v1

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fishing_v1_eez_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5496889 to 0.5496889                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## fishing_v2_eez

CBD survey: ocean fishing v2

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fishing_v2_eez_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5702666 to 0.5702666                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## fishing_v3

CBD survey: coastal fishing v3

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fishing_v3_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5659496 to 0.5659496                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## fishing_v3_eez

CBD survey: ocean fishing v3

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fishing_v3_eez_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5659496 to 0.5659496                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## fp_art_hb

High bycatch caused by artisanal fishing 

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fp_art_hb_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.03209586 to 0.03209586                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>The presence of destructive artisanal blast and poison (cyanide) fishing (Reefs at Risk Revisited).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wri.org/publication/reefs-at-risk-revisited">Reefs at Risk Revisited</a> </li>
</ul>



## fp_art_lb

Low bycatch caused by artisanal fishing 

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fp_art_lb_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.05992617 to 0.05992617                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Modeled low bycatch artisanal fishing using non-destructive practices (Halpern et al. 2008) based on FAO fisheries statistics.</p>

<p>Data sources:</p>

<ul>
<li>Halpern, B.S., Walbridge S., Selkoe, K.A., Kappel, C.V., Micheli, F., D&#39;Agrosa, C., Bruno, J.F., Casey, K.S., Ebert, C., Fox, H.E., Fujita, R., Heinemann, D., Lenihan, H.S., Madin, E.M.P., Perry, M.T., Selig, E.R., Spalding, M., Steneck, R., Watson, R. (2008) <strong>A global map of human impact on marine ecosystems</strong>. <em>Science</em>, 3199(5865): 948-952. <a href="http://dx.doi.org/10.1126/science.1149345">doi:10.1126/science.1149345</a></li>
<li><a href="http://www.fao.org/fishery/statistics/global-capture-production/en">FAO fisheries statistics</a></li>
</ul>



## fp_com_hb

High bycatch caused by commercial fishing 

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fp_com_hb_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.03798122 to 0.03798122                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Modeled destructive commercial fishing practices by 5 different gear types (Halpern et al. 2008).</p>

<p>Data sources:</p>

<ul>
<li>Halpern, B.S., Walbridge S., Selkoe, K.A., Kappel, C.V., Micheli, F., D&#39;Agrosa, C., Bruno, J.F., Casey, K.S., Ebert, C., Fox, H.E., Fujita, R., Heinemann, D., Lenihan, H.S., Madin, E.M.P., Perry, M.T., Selig, E.R., Spalding, M., Steneck, R., Watson, R. (2008) <strong>A global map of human impact on marine ecosystems</strong>. <em>Science</em>, 3199(5865): 948-952. <a href="http://dx.doi.org/10.1126/science.1149345">doi:10.1126/science.1149345</a></li>
</ul>



## fp_com_lb

Low bycatch caused by commercial fishing 

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fp_com_lb_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.03798122 to 0.03798122                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Modeled least destructive commercial fishing practices by 2 different gear types (Halpern et al. 2008).</p>

<p>Data sources:</p>

<ul>
<li>Halpern, B.S., Walbridge S., Selkoe, K.A., Kappel, C.V., Micheli, F., D&#39;Agrosa, C., Bruno, J.F., Casey, K.S., Ebert, C., Fox, H.E., Fujita, R., Heinemann, D., Lenihan, H.S., Madin, E.M.P., Perry, M.T., Selig, E.R., Spalding, M., Steneck, R., Watson, R. (2008) <strong>A global map of human impact on marine ecosystems</strong>. <em>Science</em>, 3199(5865): 948-952. <a href="http://dx.doi.org/10.1126/science.1149345">doi:10.1126/science.1149345</a></li>
</ul>



## fp_targetharvest

Targeted harvest of cetaceans and sea turtles

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fp_targetharvest_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0 to 0                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Targeted harvest of cetaceans and marine turtles, from FAO fisheries data.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-capture-production/en">FAO fisheries statistics</a></li>
</ul>



## fp_wildcaught_weight

Fisheries weighting factor

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | fp_wildcaught_weight_gl2014.csv                                                   |
| value units       | proportion                                                      |
| value range       | 0.905126 to 0.905126                               |
| global extraction | equal: global weights were applied equally to all regions.  |

<p>Proportion of wild caught fisheries yield to mariculture yield, based on FAO fisheries statistics.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-capture-production/en">FAO fisheries statistics</a></li>
</ul>



## hab_extent

Habitat extent

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hab_extent_gl2014.csv                                                   |
| value units       | km^2                                                      |
| value range       | 0 to 2721990                               |
| global extraction | raster | area_offshore:  |

<p>Habitat extent</p>

<p>Data sources:</p>

<ul>
<li>Hamilton, S. &amp; Casey, D. (2014). <strong>Creation of a high spatiotemporal resolution global database of continuous mangrove forest cover for the 21st Century (CGMFC-21): a big-data fusion approach</strong>. <a href="http://arxiv.org/ftp/arxiv/papers/1412/1412.0722.pdf">arXiv:1412.0722</a></li>
<li>Bridgham, S. D. , Megonigal, J. P. , Keller, J. K., et al. (2006). <strong>The carbon balance of North American Wetlands</strong>. <em>Wetlands</em> 26: 889-916.</li>
<li>Dahl, T. E. (2000). <strong>Status and trends of wetlands in the conterminous United States 1986 to 1997</strong>. U.S. Department of the Interior, Fish and Wildlife Service, Washington, D.C.</li>
<li>Ministry for the Environment (2007). <strong>Environment New Zealand</strong> (<a href="http://www.mfe.govt.nz/sites/default/files/environment-nz07-dec07.pdf">http://www.mfe.govt.nz/sites/default/files/environment-nz07-dec07.pdf</a>)</li>
<li>Joint Nature Conservation Committee, JNCC. (2004). <strong>UK Lowland wetland habitats</strong> (<a href="http://jncc.defra.gov.uk/page-1433">http://jncc.defra.gov.uk/page-1433</a>) </li>
<li>European Environment Agency (2008). </li>
<li>Cavalieri, D. J., Parkinson, C. L., Gloersen, P. and Zwally, H. (2014). <strong>Sea ice concentrations from Nimbus-7 SMMR and DMSP SSM/I-SSMIS passive microwave data. 1979-2014</strong>. <em>Boulder, Colorado USA: NASA National Snow and Ice Data Center Distributed Active Archive Center</em>. <a href="http://dx.doi.org/10.5067/8GQ8LZQVL0VL">http://dx.doi.org/10.5067/8GQ8LZQVL0VL</a>.</li>
<li>UNEP-WCMC (2005). <strong>Global distribution of seagrasses - points dataset</strong>.</li>
<li>Halpern, B.S., Walbridge S., Selkoe, K.A., Kappel, C.V., Micheli, F., D&#39;Agrosa, C., Bruno, J.F., Casey, K.S., Ebert, C., Fox, H.E., Fujita, R., Heinemann, D., Lenihan, H.S., Madin, E.M.P., Perry, M.T., Selig, E.R., Spalding, M., Steneck, R., Watson, R. (2008) <strong>A global map of human impact on marine ecosystems</strong>. <em>Science</em>, 3199(5865): 948-952. <a href="http://dx.doi.org/10.1126/science.1149345">doi:10.1126/science.1149345</a></li>
<li>Burke, L., Reytar, K., Spalding, M.,  et al. (2011). <strong>Reefs at Risk Revisited</strong>. <em>World Resources Institute, Washington, DC</em>.</li>
</ul>



## hab_health

Habitat health

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hab_health_gl2014.csv                                                   |
| value units       | proportion                                                      |
| value range       | 0.5 to 1                               |
| global extraction | equal: global habitat health was applied equally to all regions.  |

<p>Habitat health/condition</p>

<p>Data sources:</p>

<ul>
<li>FAO. (2007). <strong>The world&#39;s mangroves 1980-2005</strong>. <em>FAO Forestry Paper</em> 153.</li>
<li>Bridgham, S. D. , Megonigal, J. P. , Keller, J. K., et al. (2006). <strong>The carbon balance of North American Wetlands</strong>. <em>Wetlands</em> 26: 889-916.</li>
<li>Dahl, T. E. (2000). <strong>Status and trends of wetlands in the conterminous United States 1986 to 1997</strong>. U.S. Department of the Interior, Fish and Wildlife Service, Washington, D.C.</li>
<li>Ministry for the Environment (2007). <strong>Environment New Zealand</strong> (<a href="http://www.mfe.govt.nz/sites/default/files/environment-nz07-dec07.pdf">http://www.mfe.govt.nz/sites/default/files/environment-nz07-dec07.pdf</a>)</li>
<li>Joint Nature Conservation Committee, JNCC. (2004). <strong>UK Lowland wetland habitats</strong> (<a href="http://jncc.defra.gov.uk/page-1433">http://jncc.defra.gov.uk/page-1433</a>) </li>
<li>European Environment Agency (2008). </li>
<li>Cavalieri, D. J., Parkinson, C. L., Gloersen, P. and Zwally, H. (2014). <strong>Sea ice concentrations from Nimbus-7 SMMR and DMSP SSM/I-SSMIS passive microwave data. 1979-2014</strong>. <em>Boulder, Colorado USA: NASA National Snow and Ice Data Center Distributed Active Archive Center</em>. <a href="http://dx.doi.org/10.5067/8GQ8LZQVL0VL">http://dx.doi.org/10.5067/8GQ8LZQVL0VL</a>.</li>
<li>Waycott, M., Duarte, C. M., Carruthers, T. J. B., Orth, R. J. et al. (2009), <strong>Accelerating loss of seagrasses across the globe threatens coastal ecosystems</strong>. <em>Proceedings of the National Academy of Sciences</em> 106(30):12377-12381.</li>
<li>Bruno, J. F. &amp; Selig, E. R. (2007) <strong>Regional decline of coral cover in the Indo-Pacific: timing, extent, and subregional comparisons.</strong> <em>PLoS ONE</em> 2(8): e711. doi:10.1371/journal.pone.0000711</li>
<li>Schutte, V. G. W., Selig, E. R. &amp; Bruno, J. F. (2010).  <strong>Regional spatio-temporal trends in Caribbean coral reef benthic communities</strong>. <em>Marine Ecology Progress Series</em> 402: 115̢<e5><db><e5><d2>122. </li>
</ul>



## hab_presence

Habitat presence

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hab_presence_gl2014.csv                                                   |
| value units       | boolean                                                      |
| value range       | 1 to 1                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Modeled combined habitat presence</p>



## hab_trend

Habitat health trend

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hab_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | -0.05724983 to 0                               |
| global extraction | equal: global trends were applied equally to all regions. |

<p>Habitat health trend</p>

<p>Data sources:</p>

<ul>
<li>Hamilton, S. &amp; Casey, D. (2014). <strong>Creation of a high spatiotemporal resolution global database of continuous mangrove forest cover for the 21st Century (CGMFC-21): a big-data fusion approach</strong>. <a href="http://arxiv.org/ftp/arxiv/papers/1412/1412.0722.pdf">arXiv:1412.0722</a></li>
<li>Bridgham, S. D. , Megonigal, J. P. , Keller, J. K., et al. (2006). <strong>The carbon balance of North American wetlands</strong>. <em>Wetlands</em> 26: 889-916.</li>
<li>Dahl, T. E. (2000). <strong>Status and trends of wetlands in the conterminous United States 1986 to 1997</strong>. U.S. Department of the Interior, Fish and Wildlife Service, Washington, D.C.</li>
<li>Ministry for the Environment (2007). <strong>Environment New Zealand</strong> (<a href="http://www.mfe.govt.nz/sites/default/files/environment-nz07-dec07.pdf">http://www.mfe.govt.nz/sites/default/files/environment-nz07-dec07.pdf</a>)</li>
<li>Joint Nature Conservation Committee, JNCC. (2004). <strong>UK Lowland wetland habitats</strong> (<a href="http://jncc.defra.gov.uk/page-1433">http://jncc.defra.gov.uk/page-1433</a>) </li>
<li>European Environment Agency (2008). </li>
<li>Cavalieri, D. J., Parkinson, C. L., Gloersen, P. and Zwally, H. (2014). <strong>Sea ice concentrations from Nimbus-7 SMMR and DMSP SSM/I-SSMIS passive microwave data. 1979-2014</strong>. <em>Boulder, Colorado USA: NASA National Snow and Ice Data Center Distributed Active Archive Center</em> (<a href="http://dx.doi.org/10.5067/8GQ8LZQVL0VL">http://dx.doi.org/10.5067/8GQ8LZQVL0VL</a>)</li>
<li>Waycott, M., Duarte, C. M., Carruthers, T. J. B., Orth, R. J. et al. (2009). <strong>Accelerating loss of seagrasses across the globe threatens coastal ecosystems</strong>. <em>Proceedings of the National Academy of Sciences</em> 106(30):12377-12381.</li>
<li>Bruno, J. F. &amp; Selig, E. R. (2007) <strong>Regional decline of coral cover in the Indo-Pacific: timing, extent, and subregional comparisons</strong>. <em>PLoS ONE</em> 2(8): e711. doi:10.1371/journal.pone.0000711</li>
<li>Schutte, V. G. W., Selig, E.R. &amp; Bruno, J. F. (2010).  <strong>Regional spatio-temporal trends in Caribbean coral reef benthic communities</strong>. <em>Marine Ecology Progress Series</em> 402: 115̢<e5><db><e5><d2>122.</li>
</ul>



## habitat

CBD survey: habitat

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | habitat_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.8636364 to 0.8636364                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## habitat_combo

CBD survey: coastal habitat

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | habitat_combo_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5329244 to 0.5329244                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## habitat_combo_eez

CBD survey: ocean habitat

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | habitat_combo_eez_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5329244 to 0.5329244                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## hd_intertidal

Coastal population density as a proxy for intertidal habitat destruction

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hd_intertidal_sc2014-popn-inland25km.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 1.67e-06 to 0.007844983                               |
| global extraction | population_inland25km: global intertidal pressures were applied to each region after weighting by each region's coastal population. |

<p>Coastal population, defined as the total population inland of 10 miles, extracted from Gridded Population of the World (GPW) Population Density Grid Future Estimates.</p>

<p>Data sources:</p>

<ul>
<li>Center for International Earth Science Information Network (CIESIN)/Columbia University </li>
<li>CIESIN &amp; CIAT (Center for International Earth Science Information Network (CIESIN)/Columbia University, &amp; Centro Internacional de Agricultura Tropical (CIAT)) (2005). <strong>Gridded Population of the World, Version 3 (GPWv3): Population Density Grid, Future Estimates</strong>. Palisades, NY. <a href="http://sedac.ciesin.columbia.edu/data/set/gpw-v3-population-density-future-estimates">NASA Socioeconomic Data and Applications Center (SEDAC)</a></li>
<li>Halpern, B.S., Walbridge S., Selkoe, K.A., Kappel, C.V., Micheli, F., D&#39;Agrosa, C., Bruno, J.F., Casey, K.S., Ebert, C., Fox, H.E., Fujita, R., Heinemann, D., Lenihan, H.S., Madin, E.M.P., Perry, M.T., Selig, E.R., Spalding, M., Steneck, R., Watson, R. (2008) <strong>A global map of human impact on marine ecosystems</strong>. <em>Science</em>, 3199(5865): 948-952. <a href="http://dx.doi.org/10.1126/science.1149345">doi:10.1126/science.1149345</a></li>
</ul>



## hd_subtidal_hb

High bycatch artisanal fishing practices as a proxy for subtidal hard bottom habitat destruction

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hd_subtidal_hb_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.03324168 to 0.03324168                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>The presence of destructive artisanal blast fishing (Reefs at Risk Revisited).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wri.org/publication/reefs-at-risk-revisited">Reefs at Risk Revisited</a> </li>
</ul>



## hd_subtidal_sb

Demersal destructive commercial fishing practices relative to soft-bottom habitat area as a proxy for soft bottom habitat destruction

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | hd_subtidal_sb_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0 to 0                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Spatially distributed commercial catch data by fishing gear type, developed by Sea Around Us Project and habitat data.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.seaaroundus.org/">Sea Around Us Project (SAUP)</a></li>
</ul>



## ico_spp_extinction_status

IUCN extinction risk category for iconic species

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | ico_spp_extinction_status_gl2014.csv                                                   |
| value units       | category                                                      |
| value range       | NA to NA                               |
| global extraction | equal: global status was applied equally to all regions.  |

<p>International Union for Conservation of Nature (IUCN) Red List threat categories with aggregated species lists </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.iucnredlist.org/technical-documents/classification-schemes/threats-classification-scheme">International Union for Conservation of Nature (IUCN)</a></li>
</ul>



## ico_spp_popn_trend

IUCN population trend as a proxy for iconic species trend

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | ico_spp_popn_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | NA to NA                               |
| global extraction | equal: global trends were applied equally to all regions. |

<p>International Union for Conservation of Nature (IUCN) Red List threat categories with aggregated species lists </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.iucnredlist.org/technical-documents/classification-schemes/threats-classification-scheme">International Union for Conservation of Nature (IUCN)</a></li>
</ul>



## le_gdp

GDP

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_gdp_sc2014-popn-inland25km.csv                                                   |
| value units       | 2010 USD                                                      |
| value range       | 65712365 to 8.68588e+11                               |
| global extraction | population_inland25km: global GDP data were applied to each region after weighting by each region's coastal population. |

<p>Gross Domestic Product (GDP) data (reported in 2012 US dollars) from The World Bank.</p>

<p>Data sources:</p>

<ul>
<li><a href="data.worldbank.org/indicator/NY.GDP.MKTP.CD">The World Bank</a></li>
</ul>



## le_jobs_sector_year

Jobs

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_jobs_sector_year_gl2014.csv                                                   |
| value units       | jobs                                                      |
| value range       | 8.695 to 332943.4                               |
| global extraction | equal: global trends were applied equally to each region.  |

<p>gapfilled</p>



## le_popn

Total population by subregion

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_popn_gl2014.csv                                                   |
| value units       | count                                                      |
| value range       | 17909009 to 34880491                               |
| global extraction | equal:  |

<p>Population data from The World Bank</p>



## le_sector_weight

Jobs weighting

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_sector_weight_gl2014.csv                                                   |
| value units       | value                                                      |
| value range       | 1 to 1                               |
| global extraction | equal:  |

<p>Jobs weighting by sector (defaulting to 1)</p>



## le_unemployment

Unemployment

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_unemployment_gl2014.csv                                                   |
| value units       | percent unemployed                                                      |
| value range       | 6.005338 to 8.259703                               |
| global extraction | equal: global unemployment percentages were applied equally to each region.  |

<p>gapfilled</p>



## le_wage_sector_year

Wages

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_wage_sector_year_gl2014.csv                                                   |
| value units       | 2010 USD                                                      |
| value range       | 15095.15 to 79921.51                               |
| global extraction | equal: global wages were applied equally to each region.  |

<p>gapfilled</p>



## le_workforcesize_adj

Modeled Livelihoods & Economies data

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | le_workforcesize_adj_sc2014-popn-inland25km.csv                                                   |
| value units       | jobs                                                      |
| value range       | 1568.327 to 9676810                               |
| global extraction | population_inland25km: global workforce data were applied to each region after weighting by each region's coastal population. |

<p>adjusted workforce size</p>



## li_gci

GCI: competitiveness in achieving sustained economic prosperity

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | li_gci_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.7427865 to 0.7427865                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Global Competitiveness Index (GCI) scores from the World Economic Forum.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.weforum.org/issues/global-competitiveness">World Economic Forum</a></li>
</ul>



## li_sector_evenness

Sector evenness as a measure of economic diversity

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | li_sector_evenness_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.3313015 to 0.3313015                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Shannon&#39;s Diversity Index calculated sector evenness based on the total number of sectors and the proportion of jobs belonging to any sector.</p>



## lsp_prot_area_inland1km

Coastal protected areas inland 1km

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | lsp_prot_area_inland1km_gl2014.csv                                                   |
| value units       | km^2                                                      |
| value range       | 0 to 1483.5                               |
| global extraction | raster | area_inland1km:  |

<p>Coastal protected areas inland to 1km from the UN WDPA. </p>

<p>Data sources:</p>

<ul>
<li>United Nations - World Conservation Monitoring Centre̢<e5><db><e5><aa>s World Database on Protected Areas (WDPA) through <a href="http://www.protectedplanet.net">Protected Planet</a></li>
</ul>



## lsp_prot_area_offshore3nm

Coastal marine protected areas offshore 3km

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | lsp_prot_area_offshore3nm_gl2014.csv                                                   |
| value units       | km^2                                                      |
| value range       | 0 to 5273.75                               |
| global extraction | raster | area_offshore3nm:  |

<p>Coastal protected areas offshore to 3nm from the UN WDPA. </p>

<p>Data sources:</p>

<ul>
<li>United Nations - World Conservation Monitoring Centre̢<e5><db><e5><aa>s World Database on Protected Areas (WDPA) through <a href="http://www.protectedplanet.net">Protected Planet</a></li>
</ul>



## mar_coastalpopn_inland25km

Coastal population inland 25 kilometers

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | mar_coastalpopn_inland25km_sc2014-raster.csv                                                   |
| value units       | people                                                      |
| value range       | 551.468 to 2997684                               |
| global extraction | raster: spatial data was extracted for each region.  |

<p>Coastal population, defined as the total population inland of 25 kilometers, extracted from Gridded Population of the World (GPW) Population Density Grid Future Estimates.</p>

<p>Data sources:</p>

<ul>
<li>CIESIN &amp; CIAT (Center for International Earth Science Information Network /Columbia University &amp; Centro Internacional de Agricultura Tropical) (2005). <strong>Gridded Population of the World, Version 3 (GPWv3): Population Density Grid, Future Estimates</strong>. Palisades, NY. <a href="http://sedac.ciesin.columbia.edu/data/set/gpw-v3-population-density-future-estimates">NASA Socioeconomic Data and Applications Center (SEDAC)</a></li>
</ul>



## mar_harvest_species

Mariculture species harvested

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | mar_harvest_species_gl2014.csv                                                   |
| value units       | species name                                                      |
| value range       | NA to NA                               |
| global extraction | equal: global mariculture species were applied equally to each region. |

<p>Lookup table for mariculture: species Latin names and species code. </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-aquaculture-production/en">FAO global aquaculture production</a></li>
</ul>



## mar_harvest_tonnes

Mariculture harvest

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | mar_harvest_tonnes_gl2014.csv                                                   |
| value units       | tons                                                      |
| value range       | 0 to 74880                               |
| global extraction | area_offshore_3nm: global mariculture harvest (tonnes) data were applied to each region after weighting by each region's offshore area to 3nm.  |

<p>Mariculture harvest from the FAO. </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-aquaculture-production/en">FAO global aquaculture production</a></li>
</ul>



## mar_sustainability_score

Mariculture sustainability score

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | mar_sustainability_score_gl2014.csv                                                   |
| value units       | sustainability                                                      |
| value range       | 0.17 to 0.93                               |
| global extraction | equal: global mariculture sustainability scores were applied equally to each region. |

<p>Mariculture sustainability and mariculture regulations indicated by the Mariculture Sustainability Index (MSI). </p>

<p>Data sources:</p>

<ul>
<li>Trujillo P. (2008). <strong>Using a mariculture sustainability index to rank countries̢<e5><db><e5><aa> performances</strong>. In: A comparative assessment of biodiversity, fisheries and aquaculture in 53 countries̢<e5><db><e5><aa> Exclusive Economic Zones, Alder J, Pauly D, editors. <em>Fisheries Centre Research Report</em>, vol. 16(7) p. 28̢<e5><db><e5><d2>56.</li>
</ul>



## mariculture

CBD survey: mariculture

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | mariculture_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 1 to 1                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## msi_gov

 MSI sustainability and regulations

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | msi_gov_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.4785714 to 0.4785714                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Mariculture practice assessment criteria from the Mariculture Sustainability Index (MSI). </p>

<p>Data sources:</p>

<ul>
<li>Trujillo P. (2008). <strong>Using a mariculture sustainability index to rank countries̢<e5><db><e5><aa> performances</strong>. In: A comparative assessment of biodiversity, fisheries and aquaculture in 53 countries̢<e5><db><e5><aa> Exclusive Economic Zones, Alder J, Pauly D, editors. <em>Fisheries Centre Research Report</em>, vol. 16(7) p. 28̢<e5><db><e5><d2>56.</li>
</ul>



## np_blast

Areas of observed blast (dynamite) fishing

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | np_blast_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.1821841 to 0.1821841                               |
| global extraction | equal: global scores were applied equally to each region.  |

<p>Destructive artisanal blast fishing (Reefs at Risk Revisited).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wri.org/publication/reefs-at-risk-revisited">Reefs at Risk Revisited</a> </li>
</ul>



## np_cyanide

Areas of observed poison fishing

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | np_cyanide_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.1683349 to 0.1683349                               |
| global extraction | equal: global scores were applied equally to each region.  |

<p>Destructive artisanal poison (cyanide) fishing (Reefs at Risk Revisited).</p>

<p>Data sources:</p>

<ul>
<li><a href="www.wri.org/publication/reefs-at-risk-revisited">Reefs at Risk Revisited</a> </li>
</ul>



## np_harvest_product_weight

Product peak harvest divided by sum of all product peak harvest values, per region

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | np_harvest_product_weight_gl2014.csv                                                   |
| value units       | proportion                                                      |
| value range       | 0.002665857 to 0.7103696                               |
| global extraction | equal: global weights were applied equally to each region.  |

<p>Ratio of harvest of of six marine products (coral, fish oil, seaweed and plants, shells, sponges, ornamental fish) from FAO.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-commodities-production/en">FAO fisheries statistics</a></li>
</ul>



## np_harvest_tonnes

Harvest yield of marine natural products, smoothed

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | np_harvest_tonnes_gl2014.csv                                                   |
| value units       | metric tonnes                                                      |
| value range       | 0 to 13063.5                               |
| global extraction | area_offshore_3nm: global harvest (tonnes) was applied to each region after weighting by each region's offshore area to 3nm.  |

<p>Yield in metric tonnes of six marine products (coral, fish oil, seaweed and plants, shells, sponges, ornamental fish) from FAO.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-commodities-production/en">FAO fisheries statistics</a></li>
</ul>



## np_harvest_tonnes_relative

Harvest ratio to peak yield of marine natural products

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | np_harvest_tonnes_relative_gl2014.csv                                                   |
| value units       | ratio                                                      |
| value range       | 0 to 1                               |
| global extraction | equal: global scores were applied equally to each region.  |

<p>Ratio to max yield (tonnes) of product peak for six marine products (coral, fish oil, seaweed and plants, shells, sponges, ornamental fish) from FAO.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.fao.org/fishery/statistics/global-commodities-production/en">FAO fisheries statistics</a></li>
</ul>



## po_chemicals

Chemical pollution

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | po_chemicals_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.08378998 to 0.08378998                               |
| global extraction | raster: spatial data was extracted for each region.  |

<p>Modeled chemical pollution from commercial shipping traffic, ports and harbors, and pesticide use (Halpern et al. 2015).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://faostat3.fao.org/faostat-gateway/go/to/browse/R/*/E">FAO̢<e5><db><e5><aa>s statistical database FAOSTAT</a>.</li>
<li>Halpern, B. S. et al. (2015). <strong>Spatial and temporal changes in cumulative human impacts on the world&#39;s ocean</strong>. <em>Nature
Communications</em> 6(7615). <a href="http://www.nature.com/ncomms/2015/150714/ncomms8615/full/ncomms8615.html">doi: 10.1038/ncomms8615</a></li>
</ul>



## po_chemicals_3nm

Coastal chemical pollution within 3 nm offshore

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | po_chemicals_3nm_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.08004838 to 0.08004838                               |
| global extraction | raster | equal:  |

<p>Modeled chemical pollution from commercial shipping traffic, ports and harbors, and pesticide use (Halpern et al. 2015), primarily land-based chemical pollution due to 3nm offshore buffer.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://faostat3.fao.org/faostat-gateway/go/to/browse/R/*/E">FAO̢<e5><db><e5><aa>s statistical database FAOSTAT</a>.</li>
<li>Halpern, B. S. et al. (2015). <strong>Spatial and temporal changes in cumulative human impacts on the world&#39;s ocean</strong>. <em>Nature
Communications</em> 6(7615). <a href="http://www.nature.com/ncomms/2015/150714/ncomms8615/full/ncomms8615.html">doi: 10.1038/ncomms8615</a></li>
</ul>



## po_nutrients

Fertilizer pollution as a proxy for nutrient pollution

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | po_nutrients_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.001921601 to 0.001921601                               |
| global extraction | raster: spatial data was extracted for each region.  |

<p>Modeled data based on fertilizer consumption from the Food and Agricultural Organization (FAO, Halpern et al. 2015). </p>

<p>Data sources:</p>

<ul>
<li><a href="http://faostat3.fao.org/faostat-gateway/go/to/browse/R/*/E">FAO̢<e5><db><e5><aa>s statistical database FAOSTAT</a>.</li>
<li>Halpern, B. S. et al. (2015). <strong>Spatial and temporal changes in cumulative human impacts on the world&#39;s ocean</strong>. <em>Nature
Communications</em> 6(7615). <a href="http://www.nature.com/ncomms/2015/150714/ncomms8615/full/ncomms8615.html">doi: 10.1038/ncomms8615</a></li>
</ul>



## po_nutrients_3nm

Coastal fertilizer pollution as a proxy for nutrient pollution within 3nm offshore

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | po_nutrients_3nm_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.01498371 to 0.01498371                               |
| global extraction | raster | equal:  |

<p>Modeled data based on fertilizer consumption from the Food and Agricultural Organization (FAO, Halpern et al. 2015). </p>

<p>Data sources:</p>

<ul>
<li><a href="http://faostat3.fao.org/faostat-gateway/go/to/browse/R/*/E">FAO̢<e5><db><e5><aa>s statistical database FAOSTAT</a>.</li>
<li>Halpern, B. S. et al. (2015). <strong>Spatial and temporal changes in cumulative human impacts on the world&#39;s ocean</strong>. <em>Nature
Communications</em> 6(7615). <a href="http://www.nature.com/ncomms/2015/150714/ncomms8615/full/ncomms8615.html">doi: 10.1038/ncomms8615</a></li>
</ul>



## po_pathogens

Access to improved sanitation as a proxy for pathogen pollution

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | po_pathogens_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.00076147 to 0.00076147                               |
| global extraction | raster: spatial data was extracted for each region.  |

<p>Population without access to improved sanitation facilities. </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wssinfo.org/data-estimates/table">World Health Organization and United Nations Children&#39;s Fund&#39;s Joint Monitoring Programme (WHO/UNICEF&#39;s JMP)</a></li>
</ul>



## po_trash

Trash pollution

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | po_trash_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.2287456 to 0.2287456                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Global marine plastics (Eriksen et al. 2014)</p>

<p>Data sources:</p>

<ul>
<li>Eriksen M., Lebreton, L. C. M., Carson, H. S., Thiel, M., Moore, C. J. and Borerro, J. C.  (2014). 
<strong>Plastic pollution in the world̢<e5><db><e5><aa>s oceans: more than 5 trillion plastic pieces weighing over 250,000 tons afloat at sea</strong>. <em>PLoS ONE</em> 9:e111913. <a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0111913">doi:10.1371/journal.pone.0111913</a>. </li>
<li>J. Afflerbach et al. (2015). <a href="https://github.com/OHI-Science/ohiprep/tree/master/globalprep/CW_pressure_trash">Methods</a> </li>
</ul>



## rgn_area

Region area of total EEZ ocean

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_area_sc2014-area.csv                                                   |
| value units       | km^2                                                      |
| value range       | 3210.95 to 315888                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>Area of Ocean Health Index regions based on exclusive economic zones (VLIZ 2012). </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.marineregions.org/">VLIZ Maritime Boundaries Geodatabase, version 7</a></li>
</ul>



## rgn_area_inland1km

Region area 1 km inland

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_area_inland1km_gl2014.csv                                                   |
| value units       | km^2                                                      |
| value range       | 163643.7 to 163643.7                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>inland area 1 km from shore.</p>



## rgn_area_offshore3nm

Region area offshore 3nm

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_area_offshore3nm_gl2014.csv                                                   |
| value units       | km^2                                                      |
| value range       | 629255.8 to 629255.8                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>Area of Ocean Health Index regions to 3nm (VLIZ 2012). </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.marineregions.org/">VLIZ Maritime Boundaries Geodatabase, version 7</a></li>
</ul>



## rgn_georegion_labels

Georegion labels per region, at 3 georegion levels

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_georegion_labels_gl2014.csv                                                   |
| value units       | label                                                      |
| value range       | NA to NA                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>Lookup table of Ocean Health Index regions and UN georegion names at 3 georegion levels.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://unstats.un.org/unsd/methods/m49/m49regin.htm">UN geographical region and composition</a></li>
</ul>



## rgn_georegions

Georegion ids per region, at 3 georegion levels

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_georegions_gl2014.csv                                                   |
| value units       | georegion id                                                      |
| value range       | 1 to 21                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>Lookup table of Ocean Health Index regions and UN georegion identifiers at 3 georegion levels.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://unstats.un.org/unsd/methods/m49/m49regin.htm">UN geographical region and composition</a></li>
</ul>



## rgn_global

regions used in global analysis for Nature 2012, subset of regions_labels by type=eez and not deleted or disputed 

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_global_gl2014.csv                                                   |
| value units       | label                                                      |
| value range       | NA to NA                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>Regions used in global analysis for Nature 2012, subset of regions_labels by type=eez and not deleted or disputed. </p>



## rgn_labels

regions by type (eez, subocean, unclaimed) and label

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | rgn_labels.csv                                                   |
| value units       | label                                                      |
| value range       | NA to NA                               |
| global extraction | raster: spatial data was extracted for each region. |

<p>Ocean Health Index regions by type (eez, subocean, unclaimed) and label</p>



## sp_alien

Alien species

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | sp_alien_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.2597724 to 0.2597724                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>The number and type of invasive and harmful invasive species in each marine ecoregion (Molnar et al. 2008). </p>

<p>Data sources:</p>

<ul>
<li>Molnar, J. L., Gamboa, R. L., Revenga C., Spalding, M. (2008). <strong>Assessing the global threat of invasive species to marine biodiversity</strong>. <em>Frontiers in Ecology and the Environment</em> 6(485). <a href="http://dx.doi.org/10.1890/070064">doi:10.1890/070064</a></li>
</ul>



## sp_genetic

Introduced species as a proxy for genetic escapes 

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | sp_genetic_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.9213431 to 0.9213431                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Statistics on native or introduced species from the Mariculture Sustainibility Index (MSI). </p>

<p>Data sources:</p>

<ul>
<li>Trujillo P. (2008). <strong>Using a mariculture sustainability index to rank countries̢<e5><db><e5><aa> performances</strong>. In: A comparative assessment of biodiversity, fisheries and aquaculture in 53 countries̢<e5><db><e5><aa> Exclusive Economic Zones, Alder J, Pauly D, editors. <em>Fisheries Centre Research Report</em>, vol. 16(7) p. 28̢<e5><db><e5><d2>56.</li>
</ul>



## species_diversity

Ocean ecological integrity

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | species_diversity_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.838973 to 0.838973                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Marine species diversity as a proxy for ecological integrity: ocean (IUCN).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.iucnredlist.org/technical-documents/classification-schemes/threats-classification-scheme">International Union for Conservation of Nature (IUCN)</a></li>
</ul>



## species_diversity_3nm

Coastal ecological integrity

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | species_diversity_3nm_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.881435 to 0.881435                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Marine species diversity as a proxy for ecological integrity: coastal (IUCN).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.iucnredlist.org/technical-documents/classification-schemes/threats-classification-scheme">International Union for Conservation of Nature (IUCN)</a></li>
</ul>



## spp_status

Species lists and IUCN threat categories as a proxy for iconic species status

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | spp_status_gl2014.csv                                                   |
| value units       | status score                                                      |
| value range       | 0.838973 to 0.838973                               |
| global extraction | equal: global scores were applied equally to each region.  |

<p>International Union for Conservation of Nature (IUCN) Red List threat categories with aggregated species lists.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.iucnredlist.org/technical-documents/classification-schemes/threats-classification-scheme">International Union for Conservation of Nature (IUCN)</a></li>
</ul>



## spp_trend

Species lists and IUCN threat categories as a proxy for iconic species trend

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | spp_trend_gl2014.csv                                                   |
| value units       | trend score                                                      |
| value range       | -0.1775473 to -0.1775473                               |
| global extraction | equal: global trends were applied equally to each region.  |

<p>International Union for Conservation of Nature (IUCN) Red List threat categories with aggregated species lists.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.iucnredlist.org/technical-documents/classification-schemes/threats-classification-scheme">International Union for Conservation of Nature (IUCN)</a></li>
</ul>



## ss_wgi

Weakness of governance indicated with the WGI

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | ss_wgi_gl2014.csv                                                   |
| value units       | pressure score                                                      |
| value range       | 0.1780392 to 0.1780392                               |
| global extraction | equal: global pressures data were applied equally to all regions. |

<p>Inverse of World Governance Indicators (WGI) six combined scores.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://info.worldbank.org/governance/wgi/index.asp">Worldwide Governance Indicators (WGI)</a></li>
</ul>



## tourism

CBD survey: tourism

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tourism_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.9444444 to 0.9444444                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## tr_jobs_pct_tourism

Percent direct employment in tourism

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tr_jobs_pct_tourism_sc2014-popn-inland25km.csv                                                   |
| value units       | percent                                                      |
| value range       | 2.13e-06 to 0.01596725                               |
| global extraction | population_inland25km: global tourism employee data were applied to each region after weighting by each region's coastal population. |

<p>Percent direct employment in tourism (WTTC).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wttc.org/research/economic-data-search-tool/">World Travel and Tourism Council (WTTC)</a></li>
</ul>



## tr_jobs_total

Total labor force

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tr_jobs_total_sc2014-popn-inland25km.csv                                                   |
| value units       | people                                                      |
| value range       | 1568.33 to 9729054                               |
| global extraction | population_inland25km: global total labor force data were applied to each region after weighting by each region's coastal population. |

<p>Total labor force (number of people 15 years old and older who can supply labor for the production of goods and services) from World Bank assessments.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://data.worldbank.org/indicator/SL.TLF.TOTL.IN">The World Bank</a></li>
</ul>



## tr_jobs_tourism

Direct employment in tourism

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tr_jobs_tourism_sc2014-popn-inland25km.csv                                                   |
| value units       | jobs                                                      |
| value range       | 27.33382 to 247195.2                               |
| global extraction | population_inland25km: global tourism employee data were applied to each region after weighting by each region's coastal population. |

<p>Direct employment in tourism (WTTC).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.wttc.org/research/economic-data-search-tool/">World Travel and Tourism Council (WTTC)</a></li>
</ul>



## tr_sustainability

Sustainability index

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tr_sustainability_gl2014.csv                                                   |
| value units       | score                                                      |
| value range       | 5.28 to 5.28                               |
| global extraction | equal : global scores were applied equally to each region.  |

<p>Tourism Competitiveness Index (TTCI) from the World Economic Forum</p>

<p>Data sources:</p>

<ul>
<li><a href="http://reports.weforum.org/travel-and-tourism-competitiveness-report-2015/index-results-the-travel-tourism-competitiveness-index-ranking-2015/">World Economic Forum</a></li>
</ul>



## tr_travelwarnings

Travel warnings

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tr_travelwarnings_gl2014.csv                                                   |
| value units       | score                                                      |
| value range       | 0.1 to 0.1                               |
| global extraction | :  |

<p>Countries with US State Department travel warnings.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://travel.state.gov/content/passports/english/alertswarnings.html">U.S. Department of State</a></li>
</ul>



## tr_unemployment

Percent unemployment

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | tr_unemployment_gl2014.csv                                                   |
| value units       | percent                                                       |
| value range       | 0.06 to 0.114                               |
| global extraction | equal: global unemployment percentages were applied equally to each region.  |

<p>Percent unemployment (The World Bank).</p>

<p>Data sources:</p>

<ul>
<li><a href="http://data.worldbank.org/indicator/SL.UEM.TOTL.ZS">The World Bank</a></li>
</ul>



## water

CBD survey: water

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | water_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.5 to 0.5                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>Survey responses by country to the Convention on Biological Diversity (CBD) Third National Report (2005) </p>

<p>Data sources:</p>

<ul>
<li><a href="http://www.cbd.int/reports/search/default.shtml">Convention on Biological Diversity (CBD)</a></li>
</ul>



## wgi_all

Strength of governance indicated with the WGI

| metadata          | value                                                                |
|-------------------|----------------------------------------------------------------------|
| filename          | wgi_all_gl2014.csv                                                   |
| value units       | resilience score                                                      |
| value range       | 0.8219608 to 0.8219608                               |
| global extraction | equal: global resilience data were applied equally to all regions. |

<p>World Governance Indicators (WGI) six combined scores.</p>

<p>Data sources:</p>

<ul>
<li><a href="http://info.worldbank.org/governance/wgi/index.asp">Worldwide Governance Indicators (WGI)</a></li>
</ul>



