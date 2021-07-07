# Random

A REDCap external module providing random numbers, strings, guids that are filled when data entry forms or surveys are saved.

## Installation

- Clone this repo into `<redcap-root>/modules/redcap_random_<version-number>`, or
- Obtain this module from the Consortium [REDCap Repo](https://redcap.vanderbilt.edu/consortium/modules/index.php) via the Control Center.
- Go to _Control Center > Technical / Developer Tools > External Modules_ and enable **Random**.

## Requirements

- REDCAP 10.1.0 or newer (tested on REDCap 11.1.3)

## Configuration

- TODO - All config may happen in module settings

## Action Tag

TODO: This may not even have an action tag.

`@RANDOM="config-name"`

## Use case

- You might want to have a random bit of data generated for each record. 

## Notes & Limitations

- Codes are not automatically guaranteed to be unique.
- If you want to ensure uniqueness, designate the field with the random content as a Secondary Unique Field. The module will (try to) obey this.
- Generation occurs on save only. No way to have a code already generated on (the first page of) a public survey.

## Changelog

Currently this is still in development. Do not install unless there is an offical release ;p

Version | Description
------- | ------------------
v1.0.0  | Initial release.
