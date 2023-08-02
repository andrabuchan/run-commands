## vcontact2 (protein clusters)
vcontact2 --raw-proteins [.faa file] --proteins-fp MAVERICLab-vcontact2-c0413a6c92e8/test_data/VIRSorter_genomes_g2g.csv --db 'ProkaryoticViralRefSeq94-Merged' --c1-bin [path to cluster_one-...jar file] --output-dir [output directory]

## checkv (checks the completeness and quality of viral genomes)
export CHECKVDB=[path to checkv database file]

checkv end_to_end [viral .fna file] [output dir] 

## genomad (Identifies viruses in sequence data)
genomad end-to-end [.fna file] [output dir] [path to database]

