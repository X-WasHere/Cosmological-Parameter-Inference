# Cosmological-Parameter-Inference

## General Info

Using CAMEL multifield dataset predicts cosmological parameters giving input images from a range of astrophysical fields. Developed CNN model 'Single_Param_Inference' and reproduced a modified model from the paper that inspired this project 'Paper_Model'. <br/>

Also developed a generative model to predict (generate images) of one astrophysical field from another using U-net architecture 'Generative_Model'. <br/>

## Dependencies

The following Python packages are required for this project:

- `numpy`
- `matplotlib`
- `tensorflow`
- `keras` (included as part of TensorFlow, no separate installation required)
- `scikit-learn`

### Installation

To install the required dependencies, run the following command:

```bash
pip install -r requirements.txt bash```

## Dataset

Dataset can be found here: https://camels-multifield-dataset.readthedocs.io/en/latest/


## References

- F. Villaescusa-Navarro et. al, “The CAMELS Multifield Dataset: Learning the Universe's Fundamental Parameters with Artificial Intelligence,” arxiv, 2021. <br/>
- D. Randall Wilson and T. R. Martinez, “The general inefficiency of batch training for gradient descent learning,” Neural Networks, vol. 16, no. 10, pp. 1429-1451, 2003. <br/>
- K. Simonyan and A. Zisserman, “Very Deep Convolutional Networks for Large-Scale Image Recognition,” arxiv, 2014. <br/>
- O. Ronneberger, P. Fischer and T. Brox, “U-Net: Convolutional Networks for Biomedical Image Segmentation,” arxiv, 2015. 




