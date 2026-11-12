# Microbiome-BLAST
Script to validate OTUs identified by Kraken2 by BLAST of assembled contigs

Step 1: Select OTU at Genus level with > 100 reads/hit identified by Kraken2 (use krakentools with TaxID extracted from report)

Step 2: Normalize reads to target depth of 100 (use bbtools?)

Step 3: denovo assembly (MetaSPADES)

Step 4: BLAST contigs against based nt

Step 5: Keep Best Hit and with < 90% id match

Step 6: If 10 contigs valid these criteria -> OTUs validated
