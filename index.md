![Image](resources/fig1.png)


# Abstract

Chest computed tomography (CT) is an effective tool in various disease diagnoses, such as pneumonia and lung cancer. Recently, along with the outbreak of COVID-19, CT technology has been getting growing attention due to its practical capability in mass testing. Leveraging the rapid development of AI-assisted diagnosis, deep-learning-based diagnostic approaches use CT scans to bring encouraging results in different medical applications. However, data scarcity is always challenging in training a robust AI-assistant diagnostic model. In this paper, we propose a radiology reports-driven diffusion architecture to solve the data scarcity problem by generating high-quality synthetic CT images. An improved Contrastive Language-Image Pretraining (CLIP) with a dual-transformer structure is introduced for guiding the diffusion process. Therefore, the proposed method can synthesize various lung lesions on healthy CT images by bridging natural language processing (NLP) and computer vision models guided by radiology reports. Experimental results show that our method outperforms the state-of-the-art (SOTA) image synthesis approaches on different image quality metrics. Furthermore, we can also observe significant performance improvements emerging after introducing the synthetic CT images to different CT-based diagnostic approaches, which proves that the proposed synthetic data can be vitally helpful to the downstream diagnostic tasks.

# This work is under preprinting.
