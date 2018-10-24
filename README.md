hello everyone my english is not so good but i try my best.
so here i am going to discuss my favorite libraries for learn computer vision this one is not so long and i assure you that it will help you alot if you are beginner and love to work on machine learning so here we start -----------------
and i also want to share my story with you like when i start learn computer vision six month ago that time i don't have any idea like from where i will start, i don't know which language i should use and so on. i include only some libraries that i use mostly so here we begin..



.large[ 1) NUMPY:-] NUMPY is a library for python programming language that provide support for large and multidimesional array(also other stuff).why this one is in my favorite list?. using numpy we can actually express image as multi-dimensional array. for example we have an image and now we reprsent this image as a array using numpy then the image have pixels in width and in length assume that the pixels are 500X500 and in RGB color space (every pixel have three value one for green , one for red and one for blue). Each pixel have value between 0 to 255. And when we use numpy then we can store it like (500,500,3) with 500 rows, 500 column and with 3 value.and by using NumPy’s built-in high-level mathematical functions, we can quickly perform numerical analysis on an image.

.large[ 2) SciPy:-] After numpy second one is scipy. scipy give more support in scientific and technical computing.There is some sub-package that are also my favorite like spatial, special etc. they include vast amount of function for example distance function and kd-tree implementation etc. And as we know that distance function are so important because feature extraction for describe an image. When we compare two image then rely on distance function,such as the Euclidean distance.


.large[ 3) matpotlib:-] matplotlib is a plotting library. when analyzing images, we wil make use of matplotlib.wheather plotting the overall accuracy of search system or simply image viewing the image itself. 

.large[ 4) PIL and Pillow:-] with help of these library we can do simple image manipulations such as resizing rotation etc.many project use pil or pillow  For example, the Python web-framework Django uses PIL to represent an ImageField in a database.

.large[ 5) OpenCV:-] main goal of opencv is real-time image processing. opencv written in c/c++ but Python bindings are provided when running the installer.opencv is my favorite library for computer vision but you should also ready for spend a fair amount of time learning the intricacies of the library and browsing the docs.

.large[ 6) SimpleCV:-]the aim of simplecv is to get you involved in image processing and computer vision as soon as possible.
And tagline of simple cv is “it’s computer vision made easy”.so you should go with simplecv.

.large[ 7) mahotas:-] Mahotas, just as OpenCV and SimpleCV, rely on NumPy arrays. Much of the functionality implemented in Mahotas can be found in OpenCV and/or SimpleCV, but in some cases, the Mahotas interface is just easier to use, especially when it comes to their features package. so you can go with it.


.large[ 8) scikit-learn:-] Scikit-learn isn’t an image processing or computer vision library — it’s a machine learning library. That said, you can’t have advanced computer vision techniques without some sort of machine learning, whether it be clustering, vector quantization, classification models, etc. Scikit-learn also includes a handful of image feature extraction functions as well.

.large[ 9) h5py:-] The h5py library is the de-facto standard in Python to store large numerical datasets. The best part? It provides support for NumPy arrays. So, if you have a large dataset represented as a NumPy array, and it won’t fit into memory, or if you want efficient, persistent storage of NumPy arrays, then h5py is the way to go

.large[conclusion] so you should go on with these libraries and mostly i recommand numpy, opencv, simplecv and PIL or Pillow 
