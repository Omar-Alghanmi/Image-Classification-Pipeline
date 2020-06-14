# Image-Classification-Pipeline
Image Classification Pipeline (OpenCV Learning)

An image classifier is an algorithm that takes in an image as input and outputs a label or “class” that identifies that image. For example, a traffic sign classifier will look at different of roads and be able to identify whether that road contains humans, cars, bikes and so on. Distinguishing and classifying each image based on its contents.

There are many types of classifiers, used to recognize specific objects or even behaviors — like whether a person is walking or running — but they all involve a similar series of steps…

1. Input Data: First, a computer receives visual input from an imaging device like a camera. This is typically captured as an image or a sequence of images.

2. Pre-processing: Each image is then sent through some pre-processing steps whose purpose is to standardize each image.
Common pre-processing steps include resizing an image, or rotating it, to change its shape or transforming the image from one color to another - like from color to grayscale.
Only by standardizing each image, for example: making them the same size, can you then compare them and further analyze them in the same way.

3.Feature extracion: Next, we extract features. Features are what help us define certain objects, and they are usually information about object shape or color. For example, some features that distinguish a car from a bicycle are that a car is usually a much larger shape and that it has 4 wheels instead of two. The shape and wheels would be distinguishing features for a car. And we’ll talk more about features later in this lesson.

4. Classification model: And then, finally, these features are fed into a classification model! This step looks at any features from the previous step and predicts whether, say, this image is of a car or a pedestrian or a bike, and so on.
