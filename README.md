# Data preprocessing for GCBM.EmeraldEdge
>The Emerald Edge is one of the most productive carbon sinks on Earth, spanning 100 million acres of forest along the Pacific Coast of **Washington**, **British Columbia**, and **Alaska**. Benefitting from long-established relationships with Indigenous First Nations, Alaska Natives and coastal tribes are leading sustainable economic and community development. Through the work of Indigenous partners in the area and leveraging local government support, the project will help to sequester 3.5 million metric tons of CO2 through permanent protection of over 100,000 hectares of old growth forest.

https://www.bezosearthfund.org/our-programs/the-emerald-edge-protecting-living-carbon-resources

![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/Eco%20Names.png)
![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/Eco%20Zones.png)
![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/Holdridge.png)
![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/temperature%20blue-white%20(0)-orange.png)

Main tree species | Scientific name | Habitat | Max Age | Disturbances |
--- | --- | --- | --- | --- |
Western hemlock | Tsuga heterophylla | 0.3-11.3 °C, coastal, humid, moist, temperate rainforest | 400-500 | fire, wind, western hemlock looper, hemlock sawfly, western blackheaded budworm, dwarf mistletoe |
Mountain hemlock | Tsuga mertensiana | cold, snowy subalpine boreal, cool temperate | 500-800 | wind, dwarf mistletoe |
Western redcedar | Thuja plicata | up to 11.7 °C, maritime, moist, wet, cool temperate rainforest | 800-1000 | fire, fungi |
Yellow-cedar | Chamaecyparis nootkatensis | coastal, subalpine boreal, cool temperate | 800-1000+ | wind |
Amabilis fir | Abies amabilis | maritime subalpine boreal | 350-500 | wind, balsam woolly adelgid, western hemlock looper, western balsam bark beetle |
Douglas-fir | Pseudotsuga menziesii | coastal or interior, cool and warm temperate | 500-1000 | fire, western spruce budworm, Douglas-fir tussock moth, fungi |
Sitka spruce | Picea sitchensis | coastal, subalpine boreal, cool temperate rainforest | 400 | wind, white pine weevil, spruce beetle |

www.for.gov.bc.ca

https://www2.gov.bc.ca/gov/content/industry/forestry/managing-our-forest-resources/silviculture/tree-species-selection/tree-species-compendium-index

www.fs.usda.gov

Carbon Sequestration Literature | Ecozone |
--- | --- |
Slow growth, long-lived trees, and minimal disturbance characterize the dynamics of an ancient, montane forest in coastal British Columbia | |
Old-growth forest structure in a low-productivity hypermaritime rainforest in coastal British Columbia, Canada | |
Managing cedar-hemlock-salal scrub forests on the north coast of British Columbia | |
Growth and yield of all-aged Douglas-fir – western hemlock forest stands: a matrix model with stand diversity effects | |
High-resolution mapping of time since disturbance and forest carbon flux from remote sensing and inventory data to assess harvest, fire, and beetle disturbance legacies in the Pacific Northwest | |
Effects of Management on Carbon Sequestration in Forest Biomass in Southeast Alaska | |

### **National Inventories Data**

**Coastal Alaska forests not including Cook Inlet**
> **Western hemlock** forests are a major component of forest structure and function throughout the inventory unit. In total, western hemlock forest types contain nearly twice the amount of aboveground biomass (~560 million tons) than any other forest type. When scaled across the landscape, western hemlock, **Sitka spruce** and **western redcedar** contribute nearly equally to the carbon mass of coastal Alaska forests. These species are considered **old-growth** and play an important role in the long-term storage of carbon in the ecosystem.

Cook Inlet has a negligible amount of the major species above so the whole data for them from Coastal Alaska forests can be used for Emerald Edge.

![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/alaska_AGB_age.png)
https://www.fs.usda.gov/pnw/pubs/pnw_gtr979.pdf

**British Columbia Pacific Maritime ecozone (Canadian classification)**

Predominant tree genus (forest land only) | Volume |  
--- | --- |
Hemlock (coastal western hemlock, mountain hemlock) | 47.6% |
Cedar (yellow-cedar, western redcedar) and other conifers | 19.5% |
Fir (Amabilis fir) | 12.7% | +1 |
Douglas-fir (coastal Douglas-fir) | 12.5% |
Spruce (Sitka spruce) | 2.6% |

https://cfs.nrcan.gc.ca/statsprofile/inventory/pacificmaritime
https://www.for.gov.bc.ca/hfd/library/documents/treebook/biogeo/ichzone1.htm
https://www.for.gov.bc.ca/hfd/library/documents/treebook/yellowcedar.htm
https://www.for.gov.bc.ca/hfd/library/documents/treebook/westernredcedar.htm
https://www.for.gov.bc.ca/hfd/library/documents/treebook/amabilisfir.htm
https://www.for.gov.bc.ca/hfd/library/documents/treebook/sitkaspruce.htm

![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/AGB5.png)
![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/AGB-A5.png)
https://nfi.nfis.org/en/standardreports
provincial

**Western Washington area**
> **Douglas-fir** is the most abundant tree species in Washington and therefore contributes the most to biomass and carbon storage across the state. **Western hemlock**, **western redcedar**, and **Sitka spruce** are found almost exclusively in temperate rainforest on the west side of the state. Hemlock/Sitka spruce forests contain the most biomass and carbon on a per-acre basis.

![alt text](https://github.com/mHienp/GCBM.EmeraldEdge.Data/blob/main/img/Washington_AGB_area.png)
Biomass from live trees. Figure for whole state of Washington not just western. Acres converted to hectares. There are 2 varieties of Douglas-fir: coastal and Interior. 

https://www.fs.usda.gov/pnw/pubs/pnw_gtr976-supplement.pdf
