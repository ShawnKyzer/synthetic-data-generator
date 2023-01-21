# synthetic-data-generator
We will create a machine learning pipeline to generate time series and other types of datasets using GAN(Generative Adversarial Networks) and LSTM models from custom sample data.

NOTE: This repository is intended for learning and research purposes. It is also worth nothing that this is a WIP and will continue to be updated.


## Some examples

[Time Series dGAN Comparison](http://htmlpreview.github.io/?https://raw.githubusercontent.com/ShawnKyzer/synthetic-data-generator/main/sample_output/original_vs_transformed_dGAN_Time_Series.html)


## Getting started

1. Install Anaconda 
   * Installation instructions by environment https://docs.anaconda.com/anaconda/install/index.html
2. Install conda environment and activate

    ```conda env create -f environment.yml```

   ```conda activate synthetic-data-generator```

4. Change into the main pipeline directory

    ```cd synthetic-data-pipeline```

5. Install the dependencies 

    ```pip install -r src/requirements.txt```

6. Setup your IDE for Kedro projects 
    * PyCharm or IntelliJ (https://kedro.readthedocs.io/en/stable/development/set_up_pycharm.html)
    * Visual Studio Code (https://kedro.readthedocs.io/en/stable/development/set_up_vscode.html)

7. Continue the next steps in this [README](synthetic-data-pipeline/README.md)

## References

* Special thanks to the amazing work done by Gretel Synthetics (https://github.com/gretelai/gretel-synthetics)