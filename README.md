# Transformer_for_fault_diagnosis
A simple application of Transformer for fault diagnosis on Jiangnan University bearing dataset. 
Note that bearings of different speed were considered as one type. Four types of bearings were contained in the dataset, which are normal, inner ring fault, outer ring fault and roller fault.
Considering that position embedding and attention mask were not neccessary for fault diagnsosis (sequence length was set to 4, and the embedding dimension was set to 512), they were not applied in this model, neither was the Decoder of the original Transformer.
