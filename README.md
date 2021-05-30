# UpInARMS

An ARMS dispatch database scraper and exporter

## Installation

Move to any folder
You need `requests` installed.

## Usage

`upinarms.py [Agency IDs]`

Example: To download the dispatch databases of:
1. *Wiggins, MS Police Department* [26]
2. *University of Oklahoma* [58]
3. *University of North Georgia* [64]

simply run `upinarms.py 26 58 64`.

The outputs will be saved in the `output/` folder under the names `agencyID-**.json`

_A list of Agency IDs can be generated by running the script initially._

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)