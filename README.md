# Sigma Delta Quantized Networks

Here is the code mentioned in our paper, [Sigma Delta Quantized Networks](http://openreview.net/pdf?id=HkNRsU5ge).  You can use this to replicate the experiments in the paper.

To Setup (OSX/Linux):
```
git clone https://github.com/petered/sigma-delta.git
cd sigma-delta
source setup.sh
```

Or to use a Conda environment instead of a virtualenv:
```
conda env create -f environment.yml
conda activate sigma-delta
```

To run the experiments:
```
python sigma_delta/all_experiments.py
```
Then choose a number and press enter.

Please report any problems or errors.
