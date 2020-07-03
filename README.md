# NormalGAN
NormalGAN: Learning Detailed 3D Human from a Single RGB-D Image (ECCV 2020)

Lizhen Wang, Xiaochen Zhao, [Tao Yu](https://ytrock.com/), [Yebin Liu](http://www.liuyebin.com/) and Songtao Wang

## Abstract
We propose NormalGAN, a fast adversarial learning-based method
to reconstruct the complete and detailed 3D human from a single RGB-D image.
Given a single front-view RGB-D image, NormalGAN performs two steps: frontview
RGB-D rectification and back-view RGB-D inference. The final model was
then generated by simply combining the front-view and back-view RGB-D information.
However, inferring back-view RGB-D image with high-quality geometric
details and plausible texture is not trivial. Our key observation is: Normal maps
generally encode much more information of 3D surface details than RGB and
depth images. Therefore, learning geometric details from normal maps is superior
than other representations. In NormalGAN, an adversarial learning framework
conditioned by normal maps is introduced, which is used to not only improve
the front-view depth denoising performance, but also infer the back-view depth
image with surprisingly geometric details. Moreover, for texture recovery, we remove
shading information from the front-view RGB image based on the refined
normal map, which further improves the quality of the back-view color inference.
Results and experiments on both testing data set and real captured data demonstrate
the superior performance of our approach. Given a consumer RGB-D sensor,
NormalGAN can generate the complete and detailed 3D human reconstruction
results in 20 fps, which further enables convenient interactive experiences in
telepresence, AR/VR and gaming scenarios.

# Code and pretrained models
We will release the code and pre-trained models soon.
