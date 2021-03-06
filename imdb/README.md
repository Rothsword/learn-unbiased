# IMDB Experiment
Code to reproduce results for the IMDB dataset.

## Instructions

- Download the imdb cropped faces dataset from [here](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/imdb_crop.tar) and store it into the ./data folder
- Download the resnet_v1_50.ckpt checkpoint for ResNet-50 pretrained on ImageNet and store it into the ./data folder
- Extract auxiliary.zip files into the ./data folder  
- To run the code, execute the imdb_main.py file. 
- Command line parameters are detailed in imdb_parser.py.

## Example of usage

```
# run baseline model
python3 imdb_main.py --exp_name'eb1' --lmb 0

# run our model
python3 imdb_main.py --exp_name'eb1' --lmb 0.9
```
