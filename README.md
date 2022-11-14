# Project Title

EEL4930 Project 2 - Dimensionality Reduction

## Description

This project experiments with approaches to the design process of various machine learning techniques 
with a characters dataset. Various dimensionality reduction, manifold learning techniques, and 
visualization practices for classification tasks are explored. 

## Getting Started

### Dependencies

* Python 3 is required for this code
* scikit-learn is required
	* to install, run: ```$ pip install -U scikit-learn```


### Executing program

* The code is intended to run on the University of Flordia supercomputer cluster Hipergator 3.0
* It has been tested using the UFRC Python-3.10 kernel

The code is comprised of two jupyter notebooks, training.ipynb and test.ipynb.
The former is for training and dumping the models. The latter is for testing the models.

* The final model chosen by grid search cross-validation can be found [here](https://www.dropbox.com/s/82hsv598ixx8qya/final_model.pkl?dl=0)
* Downloading this model is not necessary if training.ipynb is run before test.ipynb. 
    * However, training is expensive and time-consuming. It is recommended to use the trained model.

## Help

### Training & testing other datasets

This code should seamlessly train and test other datasets of character images with minimal changes.

To run this program using another dataset:
* replace the 2nd cell (# Loading Data) with the name of the partitioned training and test data
in their respective notebooks
* modify hard-coded values in any matplotlib functions depending on dataset size

## Authors

Shane Ferrell | [linkedin.com/ferrellshanewv](https://linkedin.com/ferrellshanewv) | [github.com/shaneferrellwv](https://github.com/shaneferrellwv)

## Version History

* 0.1
    * Initial Release

## License

MIT License

Copyright (c) 2022 Shane Ferrell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

Thank you Dr. Silva and Jackson for your patience and quick responses! 
This was a fun project and I am beginning to understand so much more 
than I was expecting beyond the basic machine learning process.