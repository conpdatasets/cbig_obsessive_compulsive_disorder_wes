# OVERVIEW

- Project name: Obsessive Compulsive Disorder Whole Exome Sequencing
- Project location: The Montreal Neurological Institute and Hospital, Montreal, Quebec
- Last updated: November 2022
- Contact email address: neurobioinfo@mcgill.ca, https://neurobioinfo.github.io/

### Dataset contents
- 871.6992 GB
- FASTQ files, BAM alignments, and gVCF/VCF files
- 163 Subjects

## METHODS

### -- Recruitment --
Patients diagnosed with Obsessive Compulsive Disorder were recruited at The Montreal Neurological Institute and Hospital (The Neuro) in the clinic of Dr. Guy Rouleau. All indivduals provided informed consent.

### -- Data Acquisition --
Whole blood was obtained from all individuals and DNA was isolated. Whole exome sequencing was performed using either the Illumina NovaSeq 6000 or the Illumina HiSeq. Sequencing reads were processed using a Burrows-Wheeler Aligner (BWA) alignment, Genome Analysis Toolkit (GATK)/Picard post-alignment, and GATK HaplotypeCaller calling pipeline.

Sequencing details: 
 
                          Machine-pairing Sequencing_center Capture_type_kit       Date
                        ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2010_10_25
                        ABI_SOLID3_Single              SteJ   Exome_SS_38Mbp 2010_05_17
                        ABI_SOLID3_Single              SteJ   Exome_SS_38Mbp 2010_04_20
                        ABI_SOLID3_Single              SteJ   Exome_SS_38Mbp 2010_05_25
                        ABI_SOLID3_Single              SteJ   Exome_SS_38Mbp 2010_04_16
                        ABI_SOLID3_Single              SteJ   Exome_SS_38Mbp 2010_05_02
                    Illumina_HiSeq_Paired          Macrogen       Exome_SSV7 2020_04_10
                    Illumina_HiSeq_Paired          Macrogen      Exome_SS_V7 2020_08_21
                                  Unknown              None             None       None
