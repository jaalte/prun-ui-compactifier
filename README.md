I tested each feature individually, with both PMMGe (deprecated) and its replacement [Refined Prun](https://github.com/refined-prun/refined-prun), and it seems to work well. There's a bunch of togglable features at the top of the script:

shrinkResourceIcons: true,           // From 48px to 32px, as well as shrinking the padding between icons
inventoryGridTweaks: true,           // Makes inventory icons left-aligned instead of justified
pmmgBrnSortModeCategoryBars: true,   // Makes the category headers in PMMG's BRN sort mode smaller
buttonStyling: true,                 // Makes buttons smaller, rounds the corners, and changes label colors to make them more readable
productionViewTweaks: true,          // Shrinks production font, as well as making the New Order and Details buttons wider
apexTilingTweaks: true,              // Removes gaps between panels
pmmgGraphPadding: true,              // Trims unnecessary whitespace from PMMG and Refined Prun equity graphs so they fit in small windows
materialsRoundedCorners: true,       // Rounds the corners of materials in all commands (6px border-radius)
lowerProductionDisplayWidth: true    // (Experimental, uses JS not CSS) Decrease min-width of columns in production view (from 7rem to 6rem)
