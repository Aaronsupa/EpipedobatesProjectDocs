# Data and Scripts Associated with: "Time Series Analysis of Gene Expression Patterns in Epipedobates machalilla Embryos During Gastrulation" by Aditri Baditela, Aaron Johnson, Meera Nair

*Scripts are authored and indicated by Aditri Baditela, Aaron Johnson, Meera Nair*

#### Abbreviations
- E. Mach: Epipedobates Machalilla

## Gene Counts and Metadata
### Gene Counts
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/GeneCounts
- This folder contains the raw and normalized gene counts for various species used in our research
  - Xenopuslaevis_expression/: This folder contains csv files for Xenopus Laevis counts
  - Xenopustropicalis_expression/: This folder contains csv files for Xenopus Tropicalis counts
  - Dendrobatids_TagSeq2022.csv: Dendrobatid tag seq data
  - Emach_rawcounts.csv: E. Mach raw counts data csv; copied from /E_mach_devo/data directory

### Metadata
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/data
- This folder contains significant metadata for our project including features from WGCNA and prior student's outputs
  - gene_and_module.csv: This contains each gene and their associated WGCNA module
  - Emach_rawcounts.csv: E. Mach raw counts csv
  - expr_normalized_Em.csv: E. Mach normalized counts csv
  - module_membership.csv: Each gene and their module membership scores from WGCNA
  - top_5.csv: The top 5% expressed genes

## Meera's Directories

### myTAI
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/meera_myTAI_successful 
- This folder contains the scripts for running myTAI
  - myTAI4.Rmd: Code for the successful iteration of the phylostratigraphy
  - createPSmap.pl: Downloaded from phylostratigraphy tutorial and is necessary to run it.
  - ParseXMLtoPS.jar: Downloaded from phylostratigraphy tutorial and is necessary to run it.
  - phyloBlastDB_Drost_Gabel_Grosse_Quint.fa.tbz: Downloaded from phylostratigraphy tutorial and is necessary to run it.
  - XT_phylostratigraphy.xlsx: Final output of phylostratigraphy for the Xenopus Tropicalis IDs WGCNA and myTAI
  - crossover.Rmd: Comparison done with the phylostratigraphy results and previous WGCNA modules

### DTW
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/meeraFall24/dynamicTimeWarping
- distance_cost_calc.Rmd: This includes the calculations done when testing all the step patterns to find the shortest distance possible.
- dtw.Rmd: Includes all code used for calculation of alignment and creation of figures using hub genes.
- gene_alignments.RData: Collection of alignment calculations from dtw.

## Aditri's Directories
### TCSeq

## Aaron's Directories
### RAPToR
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/code/RAPToR
- This folder contains the scripts used to run RAPToR
  - testingModels.Rmd: Comparing generated RAPToR models
  - raptorImprovements.rmd: Improving upon previous generated RAPToR models
  - ultraLimited.Rmd: Limited subsets of E. Mach data with RAPToR
  - signifData.Rmd: Running RAPToR with previously identified hubgenes
  - tropCode.Rmd: RAPTOR with tropocalis counts data
  - dendro.Rmd: RAPToR with dendrobates counts data
  - axolotlFile.Rmd: RAPToR with axoltol counts data

### ImpulseDE2
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/code/Impulsede2
- This folder contains the scripts used to run ImpulseDE2
  - impulsevsWGCNA.Rmd: Comparing trajectories from impulsede2 to wgcna trajectories
  - impwgcna2.Rmd: Analyzing module membership & impulsede2
  - impDEAxol.Rmd: ImpulseDE2 with Axolotl time series data

### part
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/code/part
- This folder contains the scripts used to run part
  - partClustering.Rmd: clustering part on all raw E. Mach data
  - plottingPart2.Rmd: Generating plots from part
  - partSmallModule.Rmd: running part on subsets of E. Mach data

### gap
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/code/gap
- This folder contains the scripts used to run gap
  - entireDataGap.Rmd: Contains R code for running gap statstic on all E.Mach raw counts data
  - partialGap.Rmd: Contains R code for running gap statstic on subsets of E.Mach raw counts data 

### TMixClust
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/code/TMixClust
- This folder contains the scripts used to run TMixClust
  - tmixclust.Rmd: Contains code to run TMixClust on raw counts dataset

### tisa
#### Complete Path: /stor/work/FRI_321G_RY_Spring2024/Summer2024/E_mach_devo/StudentDirectories/aaronDir/code/tisa
- This folder contains the scripts used to run tisa
  - samples/: contains different generated samples for testing tisa
  - TiSAEmach.Rmd: Attempting tisa on E. Mach raw counts
  - TiSATester.Rmd: Testing tisa with generated samples in the samples folder

