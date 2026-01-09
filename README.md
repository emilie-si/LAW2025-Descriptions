# LAW2025-Descriptions
Data and Code of Annotating Spatial Descriptions in Literary and Non-Literary Text Submission

The files in this repository contain the sentences we annotated with human labels and LLM predictions. 

Only "ja" ('yes') annotations of the human annotators were considered as positive samples. Partial descriptions (annotated as "teilweise" ('partially') and samples annotated with "nein" ('no') were considered as negative samples.)

## Columns
- ID: sentence identifier
- SENTENCE: the annotated sentence exctracted from the corpora
- ANNOTATION: annotation of the curated data ("ja", "nein" or "teilweise")
- LABEL: binary label of the curated data
- ANNOTATOR_1: annotations of annotator 1, if annotations were collected systematically in this subset of the data
- ANNOTATOR_2: annotations of annotator 2
- ANNOTATOR_3: annotations of annotator 3
- SET: subset of the data that was annotated in one iteration
- IN_DEV_SET: if TRUE, used for developing the prompt and not considered in evaluation of the LLMs
- all further columns: predictions of the LLMs (LLM + prompt as reported in paper's appendix)


## Citation

If you use this dataset in your research, please cite our [paper](https://aclanthology.org/2025.law-1.26/):

@inproceedings{sitter2025annotating,
  title={Annotating Spatial Descriptions in Literary and Non-Literary Text},
  author={Sitter, Emilie and Momen, Omar and Steig, Florian and Herrmann, J Berenike and Zarrie{\ss}, Sina},
  booktitle={Proceedings of the 19th Linguistic Annotation Workshop (LAW-XIX-2025)},
  pages={308--325},
  year={2025}
}