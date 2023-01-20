# synthetic-data-generator
We will create a machine learning pipeline to generate time series and other types of datasets using GAN(Generative Adversarial Networks) and LSTM models from custom sample data.



## Getting started

1. Install Anaconda 
   * Installation instructions by environment https://docs.anaconda.com/anaconda/install/index.html
2. Install conda environment

    ```conda env create -f environment.yml```

3. Change into the main pipeline directory

    ```cd synthetic-data-pipeline```

4. Install the dependencies 

    ```pip install -r src/requirements.txt```

5. Setup your IDE for Kedro projects 
    * PyCharm or IntelliJ (https://kedro.readthedocs.io/en/stable/development/set_up_pycharm.html)
    * Visual Studio Code (https://kedro.readthedocs.io/en/stable/development/set_up_vscode.html)

6. Continue the next steps in this [README](synthetic-data-pipeline/README.md)

## References

* Special thanks to the amazing work done by Gretel Synthetics (https://github.com/gretelai/gretel-synthetics)