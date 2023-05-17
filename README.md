# Image-Captioning-using-ResNet50-and-LSTM

Image captioning, a challenging task in computer vision and natural language processing, involves creating natural language descriptions of pictures. Despite significant improvements in recent years, there are still challenges in picture captioning, such as handling specialized terminology, creating distinctive and creative captions, and overcoming long-term dependencies. By merging the LSTM model with image features retrieved from the ResNet50 model, we provide a novel approach for captioning pictures in this study that gets around these issues. We employ an LSTM to create captions based on the attributes that ResNet50 has extracted from the input image. We use a beam search method with a penalty term for creating unusual words to address the problem of rare words. We test our methodology using the Flickr8k dataset, and our model surpasses cutting-edge techniques in terms of caption quality and variety. Our method has applications in image retrieval, visual question answering, and picture captioning, among other areas. Overall, our approach offers a viable path forward for developing AI-based Image captioning.




Dataset used: Flickr8k

Link: https://www.kaggle.com/datasets/adityajn105/flickr8k
