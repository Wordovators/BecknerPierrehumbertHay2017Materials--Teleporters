# MTurk

Supplemental Data for Beckner, Pierrehumbert & Hay (2017), "The Emergence of Linguistic Structure in an Online Iterated Learning Task", Journal of Language Evolution 2(2), 160-176. doi: 10.1093/jole/lzx001

Description of files: 
The raw participant responses from our experiment are contained in two files in .xlsx format, Supplemental_Data_Size12 and Supplemental_Data_Size15. The two files represent the datasets for the two training size conditions in the experiment (12 items and 15 items, respectively). Each table includes all the responses for the 27 stimulus items, across 11 iterated generations (including the initial state), and encompassing 12 diffusion chains per condition.    

Data table columns are as follows: 

•	TrainingSetSize. This value (12 or 15) indicates how many items from the full set of 27 are selected as training items for the next generation.    

•	DiffusionChain. This index (between 1 and 12) is an arbitrary label used to indicate which particular iterated language history is represented. A TrainingSetSize, DiffusionChain, and Generation uniquely identify a particular participant’s language. 

•	Shape, Number, and Color. These are the semantic dimensions of the stimulus items in the experiment, with three possible values for each dimension. 

•	Form.i, where i is a Generation between 0 and 10. The listed form is the participant’s open-text response for this particular meaning configuration (Shape, Number, Color). Note that “Form.0” represents the 0th generation form, that is, a linguistic form randomly created using the syllable grammar described in Section 2.2.  

•	Seen.j, where j is a Generation between 1 and 10.  A Seen.j value of 1 means that the on the jth generation, the corresponding Form from generation (j-1) was selected as a training item. Items with a Seen value of 0 were not used in training.      
