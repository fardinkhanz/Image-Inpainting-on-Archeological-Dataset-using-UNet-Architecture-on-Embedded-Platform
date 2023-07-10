# Image-Inpainting-on-Archeological-Dataset-using-UNet-Architecture-on-Embedded-Platform
This repository contains the implementation and evaluation of a novel approach for enhancing the quality of picture inpainting in archaeological datasets. The proposed method focuses on enhancing the UNet architecture by incorporating the MS-SSIM loss function, which effectively denoises the output. The goal is to reconstruct damaged or missing portions of images commonly found in archaeological photographs due to the passage of time or excavation procedures.

## Introduction
Image inpainting is a widely used technique in various domains, including image editing, object removal, and image restoration. In the context of archaeological data, this technique becomes valuable for restoring and analyzing historical images. This paper presents a novel approach that significantly improves the quality of picture inpainting in archaeological datasets.
![intro_images](https://github.com/fardinkhanz/Image-Inpainting-on-Archeological-Dataset-using-UNet-Architecture-on-Embedded-Platform/assets/89691395/a3da490e-7401-4b2f-8303-b043df8906ec)

## Methodology
The proposed approach builds upon the UNet architecture, a popular deep learning model for image inpainting tasks. To enhance the restoration quality, we incorporate the MS-SSIM loss function, which effectively denoises the output by considering structural similarity. This loss function helps to preserve the important features and details during the inpainting process.

## Experimental Setup
To evaluate the effectiveness of our approach, we conducted experiments using datasets from archaeological sites. These datasets consist of photographs with missing or damaged areas caused by the passage of time or excavation procedures. We compare the results of our approach with the baseline UNet model in terms of the Structural Similarity Index (SSIM) score.

## Results
Our experimental results demonstrate that the proposed approach significantly improves the SSIM score compared to the baseline UNet model. The SSIM score increased from 0.9026 to 0.9590, indicating a substantial enhancement in the restoration quality. Moreover, we applied post-training quantization, which resulted in a remarkable 77.1% reduction in the model size. This reduction makes the model more suitable for deployment in mobile applications, thereby enhancing its usability and accessibility. In the given picture a) input image b) input mask c) output image and below that screenshot of Application is exhibited.
![Results_images](https://github.com/fardinkhanz/Image-Inpainting-on-Archeological-Dataset-using-UNet-Architecture-on-Embedded-Platform/assets/89691395/c15c21a0-b43b-42ce-a9c6-571a2a6858e3)
<img width="166" alt="new_ss" src="https://github.com/fardinkhanz/Image-Inpainting-on-Archeological-Dataset-using-UNet-Architecture-on-Embedded-Platform/assets/89691395/f792df36-6200-418b-bbaf-f739f5e9f67e">

## Conclusion
The suggested approach provides a valuable tool for academics and archaeologists working with archaeological data. By enhancing the picture restoration and analysis capabilities, our method enables researchers to effectively reconstruct damaged or missing portions of images, thereby improving the understanding and interpretation of archaeological datasets. Furthermore, by integrating the model into mobile applications, we aim to empower users to examine and restore their own archaeological images conveniently.


## Future Work
While the proposed approach shows promising results in enhancing picture inpainting for archaeological data, there are several avenues for future research and improvement. Some potential areas of exploration include:

Investigating the integration of other loss functions or regularization techniques to further improve the restoration quality.
Exploring the application of the enhanced UNet model to other domains with similar image inpainting requirements.
Conducting user studies and gathering feedback from archaeologists and academics to refine the usability and applicability of the proposed approach.
Continuously expanding the dataset with additional archaeological images to improve the generalization capabilities of the model.
## Acknowledgments
We would like to thank the archaeological community and my university for providing access to the datasets used in this research. Their contribution has been instrumental in the development and evaluation of the proposed approach.

## References
Include any references to related papers, datasets, or resources that were used in this research.

* Image Inpainting using Partial Convolution. [paper link](https://arxiv.org/abs/2108.08791)
* Dataset was provided by my university ie KLE Technological unicversity.
## License
This project is licensed under the MIT License.






