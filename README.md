# BertViz
1. Import related tool
These tools are necessary to use bertviz

2. Import related packets and def function
These packets and function are necessary to use bertviz.
call_html(): Display visualzation helper in jupyter notebook
pred_sentence(): Get the model's prediction of sentence.
get_viz(): Visualizing attention in model.

3. Load model and device setting
PRETRAINED_MODEL_NAME: model name, like "bert-base-chinese".
NUM_LABELS, num_classes: Number of classes for model to classify.
device: The device used to run the model.
fine_tuned_bert_model.pth: The path to your model.
model_state_dict: Model checkpoint.
tokenizer: Model tokenizer.

4. For the input sentence, output it's predition and attention.
After entering the input sentence, check the prediction of the model through pred_sentence(), and then use get_viz() to understand how the model predicts.