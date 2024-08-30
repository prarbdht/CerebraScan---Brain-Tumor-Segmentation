# CerebraScan---Brain-Tumor-Segmentation

## Overview
This project presents a robust brain tumor segmentation algorithm developed using the BRATS 2020 dataset, consisting of 369 MRI images with four modalities each: T1, T2, T1CE, and FLAIR. The segmentation task involved delineating four classes of tumor regions: edema, core, enhancing, and no tumor. Utilizing a UNet architecture with 28 layers, we achieved a remarkable accuracy of 99% in segmenting brain tumors.

## Model Architecture
![UNet Model](https://github.com/SayanPal27/CerebraScan---Brain-Tumor-Segmentation/blob/main/Unet_model.jpg)

## Key Features
- Utilized UNet architecture with 28 layers for segmentation
- Achieved 99% accuracy in segmenting brain tumors
- High sensitivity in detecting tumor regions, minimizing false negative cases
- Accurate localization of tumor boundaries

## Performance Evaluation
The trained model demonstrated high performance as validated using rigorous evaluation metrics, including Dice coefficient and precision-recall curves, showcasing its reliability and effectiveness in segmenting brain tumors from multi-modal MRI scans.

## Advantages Over Existing Methods
Through comprehensive analysis and comparison with existing methodologies, we have shown that our approach offers significant improvements in accuracy and robustness, underscoring its potential for clinical application. The successful integration of the segmentation algorithm into existing clinical workflows can lead to enhanced diagnostic accuracy, timely treatment planning, and improved patient outcomes in the management of brain tumors.

## Limitations and Future Directions
While our project has achieved promising results, challenges such as inter-scanner variability, data scarcity for rare tumor subtypes, and the need for real-time segmentation in clinical settings remain areas for future research and development. Furthermore, ongoing refinement and validation of the algorithm on diverse datasets and patient populations are essential to ensure its generalizability and clinical utility.

## Cloning the Project
1. To clone this repository, use the following command: 
   ```
   git clone https://github.com/SayanPal27/CerebraScan---Brain-Tumor-Segmentation.git
   ```
    
3. Navigate to the project directory:
    ```
    cd Brain-Tumor-Segmentation
    ```
    
4. If Anaconda is installed on your system, open the Python notebook and run it. Alternatively, you can import the notebook into Kaggle or Google Colaboratory.

## Conclusion
Our brain tumor segmentation project represents a significant step towards advancing medical imaging technology for precise diagnosis and treatment of brain tumors. By harnessing the power of deep learning and multi-modal MRI data, we have laid the foundation for a scalable and accurate segmentation solution with the potential to positively impact patient care and clinical decision-making in neuro-oncology.
