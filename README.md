# nlptakehome
## Toy data for BRCA genomic biomarker classification task.

BRCA1 and BRCA2 are genes that help repair damaged DNA and suppress tumor growth. Mutations in these genes significantly increase the risk of developing breast, ovarian, and other cancers, and are therefore useful 'biomarkers'. Genetic testing can identify pathogenic variants (harmful mutations) in these genes, allowing individuals to make informed decisions about screening. Sometimes testing discovers a "Variant of Uncertain Significance" (VUS), which is a genetic change whose impact on cancer risk is currently unknown. The datasets contain a set of synthetic (fake) genomic results, that report on BRCA testing.

1) Using `train.json`, please write a pipeline that fine-tunes a model to predict the correct label(s). Save training metrics to a readable file.
2) Please use the model to predict on `predict.json`, and save the outputs.
3) Pipeline components should be triggered via `.py` files

You do *not* need to reach any minimum performance metrics for this task!

Please upload your code onto GitHub in a new public repository, and share the link. There is no need to upload your model weights.
