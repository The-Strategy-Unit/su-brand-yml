# Strategy Unit Branding YAML

A repository containing SU branding and logos in `_brand.yml` file.

`_brand.yml` is [supported](https://posit-dev.github.io/brand-yml/#support) for Quarto and Shiny (R & Python). 

## For Quarto: 

See [Multiformat branding with `_brand.yml`](https://quarto.org/docs/authoring/brand.html#overview) documentation. 

## For R Shiny:
[bslib](https://rstudio.github.io/bslib/) v0.9.0+ is required to use `_brand.yml`

- For a `_brand.yml` in same directory as Shiny App add `theme = bs_theme(brand = TRUE)` to UI code to include.
- Otherwise, specify .yml file and any neccessary file paths, e.g. `theme = bs_theme(brand = "folder/your_brand_file_here.yml")`

Note: logos in `_brand.yml` are not currently supported for R Shiny. Logo files that you wish to include in your Shiny App should be placed in the `www/` folder and explicitly embedded in your App.

See also [Unified theming with brand.yml](https://rstudio.github.io/bslib/articles/brand-yml/index.html#basic-usage)


## Other Info:

- general guidance website: https://posit-dev.github.io/brand-yml/

- Live Shiny App with editable `_brand.yml`: https://bslib.shinyapps.io/brand-yml/

- NHS-R example: https://posit-dev.github.io/brand-yml/inspiration/brand-guidelines/nhsr-community/

- StrategyUnitTheme repo: https://github.com/The-Strategy-Unit/StrategyUnitTheme

- Quarto extension: https://github.com/The-Strategy-Unit/su-theme
