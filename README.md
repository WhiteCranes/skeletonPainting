# skeletonPainting
The currently popular AI drawing method, stable diffusion, uses a massive amount of existing images for deep learning and image generation. However, its neural network's drawing process is entirely in 2D, which results in inadequate detail processing in most generated images, making the subject appear as a terrifying monster.

This project proposes a method of introducing 3D models as a drawing skeleton. It is well-known that the human body varies in appearance, including features such as facial features and skin color. However, the human body's skeleton does not vary as much. We pre-install some human body skeleton models, including tall, short, fat, thin, male, and female, and set the amplitude of the skeleton's joint movement. Then, the skin is generated from the skeleton, and clothes are generated from the skin. In this way, the main subject in the picture becomes more realistic and three-dimensional.

During 2D drawing, when generating the human body part, the posture is first recognized, then the skeleton model is set up, and then the skin is generated from the skeleton, and clothes are generated from the skin. Finally, the resulting image is placed back into the original picture.

In the future, this method could be expanded to include cars or more.
