# Perceptual Metrics

Perceptual metrics refer to evaluation techniques used to assess the quality of images, videos, etc., as perceived by humans. Originally employed to determine whether a compressed file maintained its quality, these metrics have become invaluable for comparing differences between original and modified artwork, as they evaluate based on human perception.

## LPIPS: Learned Perceptual Image Patch Similarity

LPIPS stands for Learned Perceptual Image Patch Similarity. It represents a significant advancement over traditional methods like PSNR (Peak Signal-to-Noise Ratio). Unlike PSNR, which provides a simple numerical measure, LPIPS leverages deep neural networks to extract features from images. 

### Key Features of LPIPS:

- **Fine-Grained Analysis**: LPIPS does not compare entire images at once but focuses on patches, enabling it to capture fine-grained details.
  
- **Deep Learning Architecture**: Utilizing a deep neural network, LPIPS generates a score based on the similarity between image patches, offering a more nuanced understanding of image quality.

- **Human Perception Alignment**: By evaluating images based on how they are perceived by humans, LPIPS provides a more accurate assessment of visual quality compared to traditional metrics.

In summary, LPIPS represents a significant advancement in perceptual metrics, offering a more nuanced and accurate evaluation of image quality compared to traditional methods.

## FSIM: Feature Similarity Index Measure

FSIM, or Feature Similarity Index Measure, is a metric used to assess the similarity between images. Unlike traditional methods that compare pixel-wise differences, FSIM operates on high-level features. Instead of extracting features from images, FSIM relies on pre-defined features, which are then utilized to generate a quantitative score representing the similarity between images.

### Key Characteristics of FSIM:

- **High-Level Feature Analysis**: FSIM analyzes images based on high-level features rather than pixel-wise differences, offering a more abstract understanding of image similarity.

- **Quantitative Scoring**: FSIM produces a numerical score that quantifies the similarity between images, allowing for easy comparison and interpretation.

- **Pre-Defined Features**: Unlike some other metrics that extract features directly from images, FSIM depends on pre-defined features, which may limit its flexibility but can also provide consistent and reliable results.

- **Application**: FSIM is commonly used for testing compressed images to assess the preservation of image quality. However, it is not typically employed for evaluating Generative Adversarial Networks (GANs), which generate images rather than compressing them.


  

In summary, FSIM offers a unique approach to assessing image similarity, focusing on high-level features and producing quantitative scores. While it is well-suited for evaluating compressed images, its reliance on pre-defined features may limit its applicability in certain contexts such as GAN evaluation.

