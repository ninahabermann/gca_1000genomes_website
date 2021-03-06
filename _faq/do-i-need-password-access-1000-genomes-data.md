---
title: "Do I need a password to access 1000 genomes data?"
faq_tags:
  - data-access
  - data-reuse
faq_related:
  - can-i-get-cell-lines-1000-genomes-samples
  - can-i-get-phenotype-gender-and-family-relationship-information-samples
  - can-i-access-databases-associated-browser
---
                    
All the 1000 genomes information is freely available without passwords.

There are 2 main sources for our raw and analysis data our ftp site which has 2 mirrored locations [EBI](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/)\|[NCBI](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/).  These are accessible using both ftp and a udp protocol called ascp which is available freely from [aspera](http://asperasoft.com/software/transfer-clients/connect-web-browser-plug-in/).  More information about these can be found on the [data access](http://www.1000genomes.org/data#DataAccess) page. Variant calls are also loaded into ensembl databases and can be browsed from [here](http://www.1000genomes.org/1000-genomes-browsers) and the mysql database can be both accessed via our [Public mysql instance](/node/517) and downloaded from our [ftp site](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/browser/)
