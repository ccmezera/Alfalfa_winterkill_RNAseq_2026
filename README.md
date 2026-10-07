# Alfalfa_winterkill_RNAseq_2026
This repository is for documenting the scripts used to analyze RNAseq data for a pilot study working with Medicago sativa.

The goal of this analysis is to align these sequences with the M. sativa reference genome and analyze differential gene expression between samples. The samples are from the roots and stems of two cultivars of alfalfa plants: AFX589 and 4420 Wet, which have had overwintered in the field with treatments of ice formation above the plants vs no winter cover. The plants were collected at two different times: early spring (April 2026) and early summer (June 2026).

##fastqc
The purpose of this file is to move through my stem (_S.fastqc) and root (_R.fastqc) fastq files in a loop. This is modified from Cesar Medina's Iso_Seq 1_fastp.sh code.
