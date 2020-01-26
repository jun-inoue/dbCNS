# dbCNS
dbCNS (http://yamasati.nig.ac.jp/dbcns/) is a database and an identification pipeline for conserved noncoding sequences (CNSs) of vertebrates. Its database contains more than 800,000 published CNSs and 170 vertebrate genome sequences.   
Users can 
- find CNSs near interested genes from the database by uploading keywords.
- construct multiple sequence alignments and CNS trees by uploading CNS sequences as queries.

<b>Japanese instruction (日本語の説明):</b> [http://yamasati.nig.ac.jp/dbcns/instructions.html](http://yamasati.nig.ac.jp/dbcns/instructions.html)

---
## Analyses using output files


### Count the number of blast hits from multiple results

Using the downloaded pipeline, the number of blast hits can be counted from multiple results:

1. Download and decompress [get_num_positions_blasthits.zip](images/get_num_positions_blasthits.zip). 

2. From you terminal, cd into get_num_positions_blasthits directory.

3. Run the pipeline.
```
python3 010get_num_pos.py
```
4. Open 020out_num_blasthits.txt file by your Excel.


![get_num_positions_blasthits.jpg](images/get_num_positions_blasthits.jpg)

<br />  
