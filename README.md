# Auto-Encoder
Autoencoding is a data compression algorithm where the compression and decompression functions are:

- data-specific: which means that they will only be able to compress data similar to what they have been trained on.
- lossy : which means that the decompressed outputs will be degraded compared to the original inputs
- learned automatically from examples rather than engineered by a human. It doesn’t require any new engineering, just appropriate training data.

- Application : Restore distorted images, image denoising
- unsupervised or self-supervised learning

![image](https://user-images.githubusercontent.com/77944932/164576911-a7203e7b-a18a-456c-83b4-333338812150.png)

Why we need the bottleneck model and is important?

If number of neurons in the middle layer < the number of neurons in the input layer, the network extracts the more effective information. 
The middle layer will not have any other option but to learn the most important image patterns, ignoring the noises.

If number of neurons in the middle layer > the number of neurons in the input layer, the neural network will have a higher capacity to learn the pattern, making the network lazy. It will copy and paste the input values to the output values, learn noises, and not extract any feature.



## Image Denoising 



## Anomaly Detection 
- process of finding abnormalities in data. Abnormal data means the ones that deviate significantly from general behavior of data.
- Application : fraud detection, fault detection

![image](https://user-images.githubusercontent.com/77944932/164121448-fa35db32-b80b-4a23-857a-c33e5905530d.png)

code as known as latent space/vector/variables or bottleneck.


