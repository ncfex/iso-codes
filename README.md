# iso-codes

#### Manipulate ISO codes JSON files

* **Loads JSON data:** Reads data from a JSON file (e.g., `countries.json`).
* **Removes unnecessary fields:** Eliminates unwanted fields like `capital`, `continentName`, and `population`.
* **Renames keys:** Standardizes key names for consistency:
    * `countryCode` becomes `3166-1_alpha_2`
    * `countryName` becomes `3166-1_name`
    * `currencyCode` becomes `4217_alpha_3`
* **Saves manipulated data:** Writes the processed data to a new JSON file.

*Sample Data Source:*

Sample data [ISO country codes](https://gist.github.com/ncfex/85ec2a94dc65313a7072a4d2a758c6cf).