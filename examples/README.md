# QuaKe Examples

## Pipelines

The commands in this section launch utility jobs from the DeepLAr directory to reproduce a full pipeline.

In the following, it is assumed that the output folder (i.e. `../../output/tmp`)
already exists and can be created by `mkdir`.


- data generation + attention training + cnn training

    ```bash
    source examples/datagen_attention_cnn_pipeline.sh ../output/tmp
    ```
    
## Classification accuracy of Convolutional and Attention NN

Folder `performance_images` contains the models classification accuracies for different spatial resolutions and energy thresholds.