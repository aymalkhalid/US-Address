

# US Address and Area Codes

This repository contains JSON files used for mapping and standardizing various data fields. These files include mappings for street suffixes, secondary unit designations, and area codes to regions.

## Table of Contents
- [ZOHO CRM FB Lead Data Files](#zoho-crm-fb-lead-data-files)
  - [Table of Contents](#table-of-contents)
  - [Files and Their Descriptions](#files-and-their-descriptions)
    - [units_secondary_designatory.json](#units_secondary_designatoryjson)
    - [street_suffix.json](#street_suffixjson)
    - [area_code_region.json](#area_code_regionjson)

## Files and Their Descriptions

### units_secondary_designatory.json
This file contains mappings for secondary unit designations commonly used in addresses. Each key represents a type of unit (e.g., Apartment, Basement), and the value is an array of possible abbreviations or variations for that unit type.

Example:
```json
{
    "Apartment": ["APT", "Apartment", "Apartmnt", "Apt", "Apt.", "Apts"],
    "Basement": ["BSMT", "Base,", "Basemnt", "Bsmt", "Bsmt."]
}
```

### 

street_suffix.json


This file contains mappings for street suffixes. Each key represents a street suffix (e.g., Alley, Avenue), and the value is an array of possible abbreviations or variations for that suffix.

Example:
```json
{
    "ALLEY": ["ALLEY", "ALLEE", "ALY"],
    "AVENUE": ["AVENUE", "AV", "AVE", "AVEN", "AVENU", "AVN", "AVNUE"]
}
```

### 

area_code_region.json


This file contains mappings of area codes to their respective regions within the United States. Each entry includes the area code, region, a detailed description, and geographical coordinates (latitude and longitude).

Example:
```json
{
    "201": {
        "region": "New Jersey",
        "description": "X 201 - New JerseyHackensack, Jersey City, Union City, Rutherford, Leonia",
        "lang": 40.0757384,
        "lat": -74.4041622
    }
}
```
