# FRCbam-singularity
Singularity bootstrap script for the assembly evaluation program [FRCbam](https://github.com/vezzi/FRC_align) by Francesco Vezzi

# Usage
```bash
$ singularity run container.img --help
FRC version 1.3.0

Allowed options:
  --help                produce help message
  --pe-sam arg          paired end alignment file (in sam or bam format). 
                        Orientation must be -> <-
  --pe-max-insert arg   maximum allowed insert size for PE (to filter out 
                        outleyers)
  --mp-sam arg          mate pairs alignment file. (in sam or bam format). 
                        Orientation must be <- ->
  --mp-max-insert arg   maximum allowed insert size for MP (to filter out 
                        outleyers)
  --genome-size arg     estimated genome size (if not supplied genome size is 
                        believed to be assembly length
  --output arg          Header output file names (default FRC.txt and 
                        Features.txt)
  --CEstats-PE-min arg  minimum allowed CE_stats in PE library
  --CEstats-PE-max arg  maximum allowed CE_stats in PE library
  --CEstats-MP-min arg  minimum allowed CE_stats in MP library
  --CEstats-MP-max arg  maximum allowed CE_stats in MP library
```
