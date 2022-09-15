# Fine-tuning BERT for Classifying Question Types
We hand-label a dataset of about 850 example questions based on our taxonomy of 27 question types, then finetune DistilBERT for classification.  
  
The resulting classifier achieved an accuracy of 0.806 on the test set, but this should not be taken at face value since the original dataset was unbalanced and quite small.
  
## Taxonomy:  
<img src="images/question_types_hierarchy-transformed.png" width="600" height="200" title=""/>  

## Dataset:  
<img src="images/example_data_image.png" width="600" height="150" title=""/>  
  
## Example Output:  
<img src="images/example_image.png" width="600" height="500" title=""/>  
