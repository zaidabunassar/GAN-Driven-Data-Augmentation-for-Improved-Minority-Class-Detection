# GAN-Driven-Data-Augmentation-for-Improved-Minority-Class-Detection

This report investigates the problem of class imbalance in medical datasets and demonstrates how Generative Adversarial Networks (GANs) can be used to improve machine-learning performance in such scenarios. The study is conducted on the Diabetes Dataset, which contains 600 patient records with 8 medical features and a highly skewed class distribution, where only 100 samples represent diabetic patients compared to 500 non-diabetic cases 



.

To address this imbalance, three GAN variants were implemented: Vanilla GAN, LS-GAN, and WGAN-GP. These models were trained to generate synthetic minority-class samples that mimic real diabetic patient data. The generated samples were then used to balance the dataset and train a Multi-Layer Perceptron (MLP) classifier. Performance was evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrices.

Results show that the original dataset achieved high accuracy (84%) but extremely poor recall (5%), meaning most diabetic cases were missed. After applying GAN-based augmentation, recall improved dramatically, reaching 70% with Vanilla GAN, 75% with LS-GAN, and 82% with WGAN-GP 



. LS-GAN achieved the best overall balance, while WGAN-GP was most effective at detecting diabetic patients. The report concludes that GAN-based synthetic data generation is a powerful and practical solution for imbalanced medical datasets, significantly improving minority-class detection and diagnostic reliability.
