# PPI_Prediction_Maize

## Dataset Description
* Plant Name: ***Zea mays (Maize)***
* Dataset Size: ***50,983 &times; 5***
* Online Repository: ***IntAct***
* Interaction Types: ***Positive Interactions Only*** [Will be updated soon]

## Script Description
* ***merge_batches.py*** script merges the batch files. 103 batches were created for 50,983 &times; 5 data while downloading. They were merged into one single file with this script.
* ***remove_UniProt.py*** script removes the 'UniProt' text from the UniProt identifier of each protein. 
* ***replace_tick.py*** script replaces the tick mark (&#10004;) with '1'.
