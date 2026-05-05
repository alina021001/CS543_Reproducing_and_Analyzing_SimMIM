# Multi-Epoch Mask Ratio Experiments

This folder contains Alina's SimMIM multi-epoch training experiment outputs.

## Experiment Settings

Dataset: balanced CIFAR-10 subset  
Mask ratios: 0.25, 0.50, 0.75  
Epochs: 1, 5, 10  
Backbone/config: Swin-Base SimMIM pretraining config with 192x192 input  
Batch size: 2  
Environment: Google Colab GPU

## Files

- `multi_epoch_results.csv`: summary table with final loss, average loss, training time, checkpoint path, log path, and return code.
- `logs/`: raw training logs for each experiment.

## Notes

Checkpoints are not committed to GitHub because they are large. They are stored in Google Drive under:

`/CS543/group project/simmim_multi_epoch_output/simmim_pretrain/`
