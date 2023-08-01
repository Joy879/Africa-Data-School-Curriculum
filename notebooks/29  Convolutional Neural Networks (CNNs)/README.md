## CNNs
A type of neural network that works well for image processing.

All images are numbers. they are a table of pixels. Each pixel representing a color concentration.
Before working with Neural networks on images we at least need to do feature extraction. This is how CNNs work:


### Convolution
It first takes the images through _convolutions (filters)_ where it tries to extract the most important features to create a feature map

![Convolution_schematic](https://user-images.githubusercontent.com/70502261/179571885-9ee9ec20-5e03-4ce8-8b18-216167cef582.gif)

### Pooling
The new feature map is pooled down into a smaller set of pixels to reduce it's size and focus on important features.

![Pooling_schematic](https://user-images.githubusercontent.com/70502261/179571897-ed6d4b16-47f3-439e-96eb-1fba76c93aaa.gif)

### Flatten
The pooled feature is then flattened into a vector. This new vector will be fed to the hidden layer


![](https://1.bp.blogspot.com/-8izI66c0jcg/YKeD_sx55mI/AAAAAAAANjg/wg69J8ZqEucwCcTuQAtd4WJwnKdLLbjEgCLcBGAsYHQ/s0/flattening.jpg)


### Full architechture 
![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.4_IJjj1tyMsD8CIkJ9vr-gHaCd%26pid%3DApi&f=1)


### Learn more

* [MIT intro to computer vision](http://introtodeeplearning.com/2020/slides/6S191_MIT_DeepLearning_L3.pdf)
* [Deep Lizard Playlist](https://www.youtube.com/watch?v=YRhxdVk_sIs&list=PLZbbT5o_s2xq7LwI2y8_QtvuXZedL6tQU&index=19)
* [Deep Lizard Convolution Demo](https://deeplizard.com/resource/pavq7noze2)
* [Deep Lizard MaxPooling Demo](https://deeplizard.com/resource/pavq7noze3)
* [More Youtube playlists](https://www.youtube.com/results?search_query=deep+learning+for+computer+vision)
* [Applications of computer vision in Agriculture](https://viso.ai/applications/computer-vision-in-agriculture/)
*  [Case studies from Omdena](https://omdena.com/tag/object-detection/)
