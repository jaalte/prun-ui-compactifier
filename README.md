I tested each feature individually, with both PMMGe (deprecated) and its replacement [Refined Prun](https://github.com/refined-prun/refined-prun), and it seems to work well. There's a bunch of togglable features at the top of the script:

| Feature                        | Description                                                                                      |
|--------------------------------|--------------------------------------------------------------------------------------------------|
| shrinkResourceIcons            | Reduces icon size from 48px to 32px, as well as shrinking the padding between icons. Mostly compatible with RP's resource icon feature, despite some overhang.|
| inventoryGridTweaks            | Makes inventory icons left-aligned instead of justified                                        |
| pmmgBrnSortModeCategoryBars    | Makes the category headers in PMMG's BRN sort mode smaller                                     |
| buttonStyling                  | Makes buttons smaller, rounds the corners, and changes label colors to make them more readable |
| productionViewTweaks           | Shrinks production font, as well as making the New Order and Details buttons wider             |
| apexTilingTweaks               | Removes gaps between panels                                                                     |
| pmmgGraphPadding               | Trims unnecessary whitespace from PMMG and Refined Prun equity graphs so they fit in small windows |
| materialsRoundedCorners        | Rounds the corners of materials in all commands (6px border-radius)                            |
| lowerProductionDisplayWidth    | (Experimental, uses JS not CSS) Decrease min-width of columns in production view (from 7rem to 6rem) |

