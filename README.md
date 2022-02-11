# Palm_structure
 
## Problem

- DHHC17 palmitoylated on SNP25_human at C-85, 88, 90, 92 (UniProt P60880)

-- DHHC 17 interacts with Pro117

-- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5599134/ 

-- https://pubmed.ncbi.nlm.nih.gov/28757145/ 

- Prediction tools only used -15 to 15 aa around targeted C (for pCysMod) or 10 aa ranges (for CSS-Palm and GPS-Palm

--> Analysing correlation between amino acid sequence, secondary structure (and even territary structure) and palmytolated cystein.

## Steps:

- Obtain aa sequence and palm location from UniProt (7452 sites from SwissPalm)

- Obtain protein structure from AlphaFold DB

- Catagarized by:

-- Species

-- Catalyzed enzyme

-- Amino acid sequence (x number of amino acid upstream/downstream)

-- Related secondary structure (predicted by AlphaFold)

--- Check pLDDT of the predicted structure (> 70 would be good)

-- (Maybe related teritary structure)

-- Etc.

- Analyzed data