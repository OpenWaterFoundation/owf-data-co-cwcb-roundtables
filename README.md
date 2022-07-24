# owf-data-co-ibcc-roundtables #

This repository contains the [Open Water Foundation (OWF)](https://openwaterfoundation.org)
dataset files for Colorado Interbasin Compact Committee (IBCC) roundtable basins.
The IBCC was established by the Colorado Water for the
[21st Century Act](https://leg.colorado.gov/sites/default/files/images/olls/2005a_sl_314.pdf)
to facilitate conversations
among Colorado's river basins and to address statewide water issues.
Colorado is divided into eight major river basins,
with the Denver metropolitan area designated as its own basin,
separate from the South Platte Basin.
Each basin has its own roundtable to facilitate discussions on water management issues.
OWF has created and is maintaining this dataset to facilitate work on various data analysis and visualization projects in Colorado.

This repository contains the workflow to convert the
original data from zipped shapefile to GeoJSON file.
The dataset files are also published on
[`data.openwaterfoundation.org`](https://data.openwtaerfoundation.org)
and are used in data analyses and web applications.

See also the older [`owf-data-co-roundtable-basins`](https://github.com/OpenWaterFoundation/owf-data-co-roundtable-basins)
repository, which was created prior to using the spatial data layer.

The following sections provide a summary of the repository:

* [Repository Contents](#repository-contents)
* [How to Use the Data](#how-to-use-the-data)
* [License](#license)
* [Maintainers](#maintainers)

## Repository Contents ##

The repository contains the following:

```text
C:\Users\user/                              Windows user files.
/C/Users/user/                              Git Bash user files.
  owf-dev/                                  Open Water Foundation development files.
    data.openwaterfoundation.org/
      git-repos/
---------------- above folders are recommended --------------------
        owf-website-data/                   Repository that provides shared files to create dataset cloud landing page.
        owf-data-co-ibcc-roundtables/       This repository.
          .gitattributes                    Git configuration file indicate repository configuration,
                                            in particular handling of line-ending and binary files.
          .gitignore                        Git configuration file to ignore files that should not be committed to the repository.
          README.md                         This file.
          data/                             The data files for the dataset, output from the workflow.
          downloads/                        Downloaded files for the dataset, from the original source.
          workflow/                         Workflow files to process the dataset.
```

## How to Use the Data ##

The GeoJSON files in the `data` folders can be used directly by GIS and web mapping applications.

However, it is recommended to use the files served from the
[Colorado IBCC Roundatables](https://data.openwaterfoundation.org/state/co/ibcc/roundtables/) links.

## License ##

The data from the State of Colorado are public.
No restrictions are currently placed on use of the dataset.
Using attribution consistent with the following license is appreciated.

[Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

## Maintainers ##

Steve Malers (@smalers, steve.malers@openwaterfoundation.org) is the primary contact.
