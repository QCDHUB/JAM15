[![jamlogo](../gallery/jam.jpg)](http://www.jlab.org/jam)

# LHAPDF grids 

## Overview

Grids can be downlaoded in two ways:

* Choose your grids and download the corresponding link in the first column (or click on "View raw" if you get a new page).
* Clone the JAM15 repo, and get all the available grids:  `$ git https://github.com/QCDHUB/JAM15.git`. With this option you can get the latest version by issuing `$ git pull`

Either way, you need to (unzip and) copy the grids to your local LHAPDF grid folder. The default location can be found, e.g., in the output of the `$ lhapdf` command. Further info on the LHAPDF interface installation and usage can be found on the [LHAPDF project web page](https://lhapdf.hepforge.org/).

## Grids

| Name                                         | Info                                            | Reference                                                      | Status | Notes                                       |
| :--:                                         | :--:                                            | :--:                                                           | :--:   | :--:                                        |
| [JAM15_PPDF_Ceven](zip/JAM15_PPDF_Ceven.zip) | [.info](GRIDS/JAM15_PPDF_Ceven/JAM15_PPDF_Ceven.info) | [Phys.Rev. D93 (2016) 074005](http://inspirehep.net/record/1418180?ln=en) | v.-1  PRELIMINARY   | q+ (=q+qbar) & glue polarized PDFs at NLO     |
| [JAM15_T3PPDF_Ceven](zip/JAM15_PPDF_Ceven.zip) | [.info](GRIDS/JAM15_T3PPDF_Ceven/JAM15_T3PPDF_Ceven.info) | [Phys.Rev. D93 (2016) 074005](http://inspirehep.net/record/1418180?ln=en) | v.-1  PRELIMINARY   | q+ (=q+qbar) & glue polarized twist-3 PDFs  at NLO     |

## Questions/bugs

Send feedback or questions using the github 
[issue tracker system](https://github.com/QCDHUB/JAM15/issues).


## Acknowledgments

Maintainer:
* Alberto Accardi

Many thanks to the following testers:
* Juan Guerrero (Hampton U. and Jefferson Lab)
* ... and all the other JAM15 authors!
