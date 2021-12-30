# EIRN
effective query-key mechanism for image restoration
# Abstract
With the aim of retrieving high-quality images from corrupted versions, image restoration meets the extensive demand of application scenarios. State-of-the-art methods solve this problem by means of designing convolution blocks in multistage architectures. However, scaling and randomly discarding features like existing methods cannot retain the crucial feature information. In this paper, we propose an effective query-key mechanism with the goal of identifying the importance of the information and providing crucial feature information. Our query-key mechanism includes (i) a key map with feature representations, and (ii) a query map with the importance degree of pixel information in the corrupted images. The query-key mechanism takes full advantage of degraded images to calculate the importance degree and acquire momentous feature representation. Compared with existing attention mechanisms, our query-key mechanism can focus more attention on crucial feature information in the images and perform multiple image restoration tasks, including image deblurring, denoising and deraining. Furthermore, we design a multistage feature fusion block with the query-key mechanism. Due to the novel design of the network, we successfully implement various image restoration tasks with just one network, including image deblurring, denoising and deraining. Abundant quantitative and qualitative experiments demonstrate that our proposed effective image restoration network (EIRN) outperforms existing state-of-the-art algorithms on ten datasets across a series of image restoration tasks.
# Supplement
We have submitted our paper to IEEE TRANSACTIONS ON CIRCUITS AND SYSTEMS FOR VIDEO TECHNOLOGY (TCSVT) for review, after which we will publish our code AND three training models FOR image restoration.

# Experiment
![image](https://user-images.githubusercontent.com/71067558/147733512-d09de396-3cee-4cd4-b441-4813f9b5b804.png)
![image](https://user-images.githubusercontent.com/71067558/147733614-680929a0-2f4a-4212-bee3-6b1cbdd72454.png)

![image](https://user-images.githubusercontent.com/71067558/147733637-076e1299-6951-4b14-9cc5-e881accb9719.png)
![image](https://user-images.githubusercontent.com/71067558/147733650-c9e66a92-8db4-4861-858b-fffbc072ba6d.png)

![image](https://user-images.githubusercontent.com/71067558/147733660-bb6c46cd-583a-47e8-9e97-b63540bb3d31.png)
![image](https://user-images.githubusercontent.com/71067558/147733672-19347a3a-ef6e-45e7-bb0d-b265f055e613.png)
