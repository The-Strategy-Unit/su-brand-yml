# Strategy Unit Branding YAML

A repository containing SU branding and logos in `_brand.yml` file.

`_brand.yml` is [supported](https://posit-dev.github.io/brand-yml/#support) for Quarto and Shiny (R & Python). 


## For R Shiny:
bslib v0.9.0+ is required to use `_brand.yml`

- For a `_brand.yml` in same directory as Shiny App add `theme = bs_theme(brand = T)` to UI code to include.
- Otherwise, specify .yml file and any neccessary file paths, e.g. `theme = bs_theme(brand = "folder/your_brand_file_here.yml")`
 

## Other Info:

- general guidance website: https://posit-dev.github.io/brand-yml/

- NHS-R example: https://posit-dev.github.io/brand-yml/inspiration/brand-guidelines/nhsr-community/

- StrategyUnitTheme repo: https://github.com/The-Strategy-Unit/StrategyUnitTheme

- Quarto extension: https://github.com/The-Strategy-Unit/su-theme
