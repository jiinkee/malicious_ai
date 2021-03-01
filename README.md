# Malicious AI: Adversarial Perturbations Fool Deepfake Detector
This project was part of the assignments of FIT3183 Adversarial AI & Dark Side Security in 2020, S2. It was a work completed by me and another teammate. 

## Motivation
This is an era where technology flourishes and information spreads at blinding speed, but how can we ensure the authenticity of every image or video that we have received? Hence, we cannot disregard the significance of robust deepfake detectors, and this is the reason we find this research intriguing. Understanding our enemies while also recognizing our own strengths will make every battle a victorious one. In order to build a strong defense system, we must first know the penetration techniques that an adversary might try. Our team’s goal is to extend the research work and explore more techniques to generate perturbed deepfake images that can fool deepfake detectors. We would also like to explore the transferability of this attack on other CNN architectures. 

## Attack Techniques
Gandhi and Jain (2020) has demonstrated in their [paper](https://arxiv.org/pdf/2003.10596v2.pdf) that they're able to generate adversarial deepfake images in order to fool deepfake detectors in both black-box and white-box settings. They used two techniques, namely, the Fast Gradient Sign Method and the Carlini and Wagner L2 norm attack, to add adversarial perturbations to deepfake images and succeed in fooling the VGG-16 and ResNet-18 CNN deepfake detection model.

In the Colab, me and my teammate explored more techniques that can be used to perturb benign images and their efficiencies. We trained our own deepfake detector which uses the XceptionNet architecture and tested the attack techniques on it. We've chosen XceptionNet architecture because it’s a well-known architecture which has an exceptional performance in image classification.

The perturbation techniques that are presented in the Colab include:
- Fast Gradient Sign Method (FGSM)
- Fast Gradient Value Method (FGVM)
- One Pixel Attack
- Least Significant Bit Steganography

## How to run the code?
You can create a new notebook in [Google Colaboratory](https://colab.research.google.com/), and upload the IPYNB to your notebook. GPU usage is highly recommended.

