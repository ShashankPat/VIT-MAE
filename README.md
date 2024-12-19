# VIT-MAE
Vision Transformers and Masked Autoencoders.

This project aims to explore the synergy between ViT and MAE and demonstrate their versatility in handling two fundamental tasks: image classification and image segmentation. By focusing on efficient pretraining strategies and fine-tuning techniques, this project aims to contribute to advancements in multi-task learning with a single architecture and this project will not only contribute to the understanding of how self-supervised pretraining via MAE can be utilized in transformer-based architectures but also explore multi-task learning, showing the versatility of ViT in both classification and segmentation.

The ViT-MAE framework demonstrated high effectiveness across a variety of image classification and segmentation tasks. Pretraining significantly enhanced representation learning, as evidenced by:
• MNIST: Achieved state-of-the-art results with 99.28% validation accuracy in classification and 94.42%
in segmentation.
• CIFAR-10: Maintained consistent high accuracy, with a peak validation accuracy of 96.72%.
• PASCAL VOC: Demonstrated scalability to complex datasets, achieving 98.19% validation accuracy
in classification and 76.09% validation accuracy in segmentation.
When compared to CNNs, ViT-MAE’s pretraining phase provided robustness and adaptability, while
CNNs demonstrated faster convergence and superior validation accuracy on PASCAL VOC classification.
This highlights the strengths and trade-offs of each approach, depending on dataset complexity and training
requirements
