# Drug Response Prediction
Code behind the Drug Response Prediction in Cancer Cell Lines
with a CLIP-Inspired Transformer Framework Exploration

## Table of Contents

* [Requirements](#requirements)
* [Usage](#usage)
* [Contact](#contact)
* [License](#license)

## Requirements

In the `requirements.txt` all required pip packages are listed.


To install the packages, execute the following:
1. Open a terminal or command prompt
2. Navigate to the folder with your `requirements.txt`
3. ``` pip3 install -r requirements.txt```
4. You are done installing dependencies

Additional conda packages may be required. If there are problems with certain package versions, 
all packages of the environment are listed in the `package_list.txt` file.


## Usage:

Below is the suggested order in which the Jupyter Notebooks files should be executed.

1. `STEP00_DataProcessor.ipynb`
2. `STEP01_SPE.ipynb`
3. `STEP01_SMILES_Encoder.ipynb`
4. `STEP02_Autoencoder.ipynb`
5. `STEP02_Transformer.ipynb`
6. `STEP02_Eval.ipynb`
7. `STEP03_DRP.ipynb`

An detailed explanation of additional required files is provided in the respective Jupyter Notebooks.

Most of the required data sets are already available in the `data` folder, but some files have to be downloaded manually 
as they are too large. The missing files can also be downloaded via [Google Drive](https://drive.google.com/drive/folders/114uhpWGNqdOHqL5OGqHRruhUhJh2eXLm?usp=sharing).

The `model` folder only contains one pre-trained model as GitHub does not allow files larger than 25MB.


## Contact

For questions or problems, please feel free to write an email and I will get back to you as soon as possible.

[msohn@techfak.uni-bielefeld.de](mailto:msohn@techfak.uni-bielefeld.de)
.

## License
* This repository is licensed under the [MIT license](https://github.com/masohn/DRP/blob/main/LICENSE).
