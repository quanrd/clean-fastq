
# clean-fastq

[![Snakemake](https://img.shields.io/badge/snakemake-5.5.2-brightgreen.svg)](https://snakemake.bitbucket.io)



A workflow designed to clean fastq files for the [SEACONNECT project](https://reefish.umontpellier.fr/index.php?article9/total-seaconnect)




# remove PHIX

The viral genome of phiX is used as a control in Illumina sequencing. While the viral libraries do not have MIDs on them, some phiX reads always creep through, possibly because the clusters “borrow” the signals from closely surrounding clusters that do. These phiX reads need to be removed.

