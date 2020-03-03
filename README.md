# attention:

## This package has stopped updating, please see our new resposity [HSCRF](https://github.com/ZhixiuYe/HSCRF-pytorch)

## Quick Setup (Linux)

1. Assume pytorch, numpy, scipy, matplotlib installed 

2. Install and run visdom
```bash
pip install visdom --user
visdom
```
3. Copy glove files into `models` directory. http://nlp.stanford.edu/data/glove.6B.zip

4. Train the model (-g: gpu)
```bash
python train.py -g 1 --epochs 10
```


## reference:<br />

   paper:<br />
           Neural Architectures for Named Entity Recognition<br />
           End-toEnd Sequence labeling via BLSTM-CNN-CRF<br />
   code:<br />
           https://github.com/glample/tagger<br />
## usage:
   python train.py<br />

## performance

   f1 91.00%
