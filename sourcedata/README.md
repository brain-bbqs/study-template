## `sourcedata` Instructions

TODO-FILL along the lines: This folder contains 

- all source data for the project, in original, potentially proprietary and non-standard forms.

Some or all of the materials in this folder could be used to form the BIDS raw dataset under `../rawbids/` folder.

For that, later, to satisfy the [STAMPED principle](https://stamped-principles.org/) of [Self-containment](https://examples.stamped-principles.org/stamped_principles/s/), they might be copied or otherwise efficiently linked (e.g. `git submodule` AKA ["DataLad subdataset"](https://handbook.datalad.org/en/latest/basics/101-106-nesting.html) mechanism) under `../rawbids/sourcedata/`.
So, in principle, `sourcedata/` could altogether be a "git submodule" with all sourcedata used in both places (potentially of a different version!).

....
