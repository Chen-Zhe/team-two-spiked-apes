# Unsupevised Scene Change Detection using Beta-VAE
Our project report can be found [here](11_785_Team_23_two_spiked_apes_Project_Final_Report.pdf)

## by Project Two Spiked Apes
This is the repository for the 11785 spring 2021 course project of Project Two Spiked Apes. The topic is using beta-VAE for automatic scene change detection on Kimi No Na Wa dataset.
The codes are integrated into different notebooks here, categorized by model architectures or functions:
- baseline-*: Vanilla beta-VAE model used for providing baseline accuracy and ablation study.
- many2one-*: Model that uses a window of images instead of a single image as input.
- seq-to-seq-RNN: Model that uses CRNN as encoder and decoder based on many-to-one input.
- Model Validation: Codes for running model on 142p validation dataset and get its accuracy.
