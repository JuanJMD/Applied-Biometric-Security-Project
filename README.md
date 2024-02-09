# Deep-Fake Detection Approach of GANs-based Morphing Attacks By using Benford’s Law

## Code Installation and Configuration

To run the code files, we recommend running it on an online environment, such as Google Colab or Jupyter Notebook. In our case, we ran it using Jupyter Notebook.

The following program was built during the months of **Oct-Dec of 2023**. Running it later than this date may require some modifications to the code and dependencies.

## Image Conversion (Optional)
When planning on simulating the code, we recommend to make sure that the dataset contains JPEG-type images (Preferably 600x600). This module is given if you plan on using a different dataset and the images are in PNG format, we highly recommend you convert those images to JPEG using the *ConvertPNGtoJPEG.ipynb* file. Otherwise, you do not have to run that file.

## Implementation 
Once you have your dataset prepared, or plan on using our dataset, we recommend you run the files in this order:
 - [**Benford's_Law_Divergence_Method.ipynb**](code/Benford's_Law_Divergence_Method.ipynb)
    - DCT extractor
    - First Digit Probabilities extractor
    - Classifier combining three divergences for detecting fake and real images
 - [**Chi-square Method.ipynb**](code/Chi-square-Method.ipynb)
    - Chi-Square classification implementation
## Datasets
We opted to use the following datasets from the following resources:
 - **StyleGAN3 Generated Dataset**: https://github.com/NVlabs/stylegan3 
    - Visit the referenced Github repository on how to generate your own dataset!
    - NOTE: Make sure you meet the hardware requirements from the StyleGAN git repository before using it to build your dataset.
    - FFHQ pre-trained model has been selected for our project.
 - **Kaggle Dataset**: https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection
    - Various other datasets could be used. 
    - Preferably datasets with dimensions 600x600 and in JPEG format
## Questions?
If you run into issues or need assistance running it, feel free to contact us via email:
 - Juan Martinez: junmartinez@mail.fresnostate.edu
 - Juan Marquez Diaz:  juanmark21@mail.fresnostate.edu
 - Yubo Zhou: yubozhou@mail.fresnostate.edu
