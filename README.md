# EMBER Project 

This is [EMBER Archive](https://emberarchive.org/) project dataset Git
repository all digital materials for the TODO-FILL-NAME study.

## Structure

It is organized as a BIDS "study" dataset following [BIDS
specification](https://bids-specification.readthedocs.io/en/stable/common-principles.html#study-dataset).

## HOWTO for project curators

`git grep TODO-FILL` could be used for a quick location of items to be changed.

Overall checklist to "check out" and potentially populate (if points to a folder).
Each folder should contain `README.md` with further details orienting user in its content

- [ ] [`docs/`](./docs) - documentation for the study (original paper,
  research plan from gran proposal, slides, etc) to be placed under 
- [ ] [`sourcedata/`](./sourcedata) - your "source data" (before NWB/BIDS-ification) in subfolders under `sourcedata/`
- [ ] `sourcedata/raw/` -  if preparing BIDS "raw" dataset, place it there ideally as a separate
  "BIDS raw" dataset formatted most appropriate for your study.
- [ ] [`derivatives/`](./derivatives) - TODO...
- [ ] [`code/`](./code) - code for managing the project data ingest under `code/` subfolder
- [ ] [`logs/`](./logs) - log files
- [ ] this dataset should pass validation using BIDS validator, e.g. via `uvx bids-validator-deno .`

## License

Overall study materials of this repository are distributed under Apache 2.0 license, whenever individual datasets linked to ths
{{ license|default('CC0') }}
