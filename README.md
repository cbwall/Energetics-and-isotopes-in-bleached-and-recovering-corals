# Energetics and isotopes in bleached and recovering corals
Wall C.B., Ritson-Williams R., Popp B.N., and Gates R.D. (2019) Spatial variation in the biochemical and isotopic composition of corals during bleaching and recovery. Limnology and Oceanography (in press).

This project assessed the energetic and isotopic changes in bleached and non-bleached colonies of two Hawaiian reef coral species at three reef sites in Kāne'ohe Bay, Hawai'i, following a rare archipelagic bleaching event in October 2014 and the subsequent recovery from bleaching in January 2015.

## Files and Folders
- Bleach.Recovery.Isotope.Rproj -- the R project in Rstudio
- Wall et al_LnO_markdown_publish.Rmd -- the codes and script in Rmarkdown file
- Wall_et_al_LnO_markdown_publish.html -- this is the html export from Rmd

### data
- Biological responses_BNB.final -- the biological properties of all corals. 
  _Metadata for this file can be found in Rmd file and below_. 
     - 'Time.point' -- 2014 October or 2015 January
     - 'Period' -- either Bleaching or Recover
     - 'Site' -- 3 sites HIMB (Hawai'i Institute of Marine Biology), Reef 25, and Reef 44
     - 'Species' -- MC = _Montipora capitata_, or PC = _Porites compressa_
     - 'Condition' -- B = Bleached, NB = Non-bleached
     - 'Sample.ID' -- arbitrary colony ID #
     - 'Pair' -- bleached-nonbleached pair of neighboring colonies
     - 'Depth.m' -- colony depth in meters
     - 'surface.area.cm2' -- colony surface area in cm2
     - 'blastate.ml' -- tissue extract in ml
     - 'cells.ml' -- (unused data) symbiont cells per ml blastate
     - 'AFDW.g.ml' -- g ash-free dry weight per ml blastate
     - 'mg.carb.ml' -- mg of carbohydrates per ml blastate
     - 'mg.protein.ml' -- mg of proteins per ml blastate
     - 'ug.chl.a.ml' -- μg of chlorophyll a per ml blastate
     - 'ug.chl.c2.ml' -- μg of chlorophyll a per ml blastate
     - 'g.lipids.gdw' -- g of lipids per g ash-free dry-weight
     - 'lipid.freeze.dry.g' -- (unused data) g lipid biomass as a function of freeze-dried tissue
     - 'lipid.extract.mass.g' -- g of lipids extracted from 3ml freeze-dried aliquot of holobiont tissue
     - 'AFDW.burned+lipids.g' -- total mass of AFDW and lipids in grams from lipid extractions
     - 'AFDW.freeze.ml' -- g AFDW per ml aliquot of freeze-dried tissue used in lipid extractions
     - 'host.ug.N' -- μg of nitrogen in host tissue
     - 'host.d15N' -- δ15N of host tissues in permil
     - 'host.ug.C' -- μg of carbon in host tissue
     - 'host.d13C' -- δ13C of host tissues in permil
     - 'host.C.N' -- molar ratio of carbon : nitrogen in symbiont tissues
     - 'symb.ug.N' -- μg of nitrogen in symbiont tissue
     - 'symb.d15N' -- δ15N of symbiont tissues in permil
     - 'symb.ug.C' -- μg of carbon in host tissue
     - 'symb.d13C' -- δ13C of symbiont tissues in permil
     - 'symb.C.N' -- molar ratio of carbon : nitrogen in symbiont tissues
     - 'd15N.H.S' -- difference in δ15N of host minus symbiont
     - 'd13C.H.S' -- difference in δ13C of host minus symbiont
     - 'symb.comm' -- symbiont clade where qPCR had been previously run (see Cunning et al. 2016)
     
#### API ESRI tiles
- ESRI tiles to make a DIY map without Google API
#### coastn83.shp 
- shape files to generate map -- NOTE need user Google API account as of 2019
#### environmental
- abiotic data
     - KBay_temp_1612480_20140601-20150228_phys.csv -- weather station temperature data
     - light_reef44_2014.csv -- 2014 light at Reef 44
     - light_reef44_2015.csv -- 2015 light at Reef 44
     - light_reefHIMB_2014.csv -- 2014 light at HIMB
     - light_reefHIMB_2015.csv -- 2015 light at HIMB
     - nutrients_BNB.update -- dissolved nutrients at three reef sites
     - Reefs_lat_long -- latitude and longitude of reef sites
     - sediment_long_KBay -- short-term sedimentation data
     - sediment_short_KBay -- long-term (annual) sedimentation data
     - temp_reef44_2014.csv -- 2014 temperature at Reef 44
     - temp_reef44_2015.csv -- 2015 temperature at Reef 44
     - temp_reefHIMB_2014.csv -- 2014 temperature at HIMB
     - temp_reefHIMB_2015.csv -- 2015 temperature at HIMB
      
### figures
These figures are exports from Rmarkdown (Fig 1, 3) and images of bleached and non-bleached corals (Fig 2)
- Fig1a_sitemap.png -- this is the map generated from Google with sites identified
- Fig1bc.corals.png -- bleached and non-bleached corals

#### Final Figures
Figures here are exported from Rmd and used in publication with minor edits in Illustrator
- Fig 1. Map and corals.pdf
- Fig 2 Nutrients.pdf
- Fig 3. NMDS_MCpdf
- Fig 4. NMDS_PCpdf
- Fig 5. MC.PC.chlapdf
- Fig 6. Energy reservespdf
- Fig 7. MC.PC.fig.isotopespdf
- Fig 8. Mass balance d13Cpdf
- Fig S1. Temp.PAR.colorpdf
- Fig S2. C.N hostsymbpdf
- Fig S3. Compound to d13C.pdf
