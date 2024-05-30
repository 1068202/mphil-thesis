The "code" folder contains R/Quarto codes needed to launch the results. This folder contains  three .qmd files. Running these files in order would replicate my results.

1. Running "clean4.qmd" cleans the raw data from the FFCWS dataset, and produces "df4.Rdata".
2. Running "aces4.qmd" then wrangles the data in "df4.Rdata" to produce variables needed for analysis. These data are stored in "ace4.Rdata".
3. Running the main code file, "code.qmd", analyses the data using variables created in "ace4.Rdata". 






