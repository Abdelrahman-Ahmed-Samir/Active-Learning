This project was about applying Active Deep Learning Technique

We applied different Active Learning Strategies using ModAL.

● ModAl is an active learning framework for Python 3.
● It is designed with modularity, flexibility, and extensibility in mind.
● It is built on top of Scikit-Learn, allowing you to rapidly create active
learning workflows with nearly complete freedom.
● It can easily replace parts with user-built solutions, allowing the user to
design novel algorithms with ease.

-I used 2 datasets in this project: Mnist(handwritten digits) and Cifar-10

-The project is large because I used the same 2 datasets in 2 situations ( Before applying Active Learning (using normal passive learning) , After applying Active Learning).
--> I did that to compare the results in the 2 situations.

- There is also another thing , we talked that we gonna use Deep Learning , so we were thinking to use Vgg-16 but due to it's computational power we used the same architecture of Vgg-16 but we removed some layers to speed up the process. there is an image attached showing the architecture I used.

Applied AL strategies:
- Random Sampling
- Uncertainty Sampling
- Margin Sampling
- Entropy Sampling
- Density-Based Sampling
