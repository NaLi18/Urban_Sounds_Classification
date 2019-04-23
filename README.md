## Urban_Sounds_Classification

The automatic classification of environmental sound is growing research field with multiple applications to largescale. Content-based multimedia indexing and retrieval. In particular, the sonic analysis of urban environment is the subject of increased interest, partly enabled by multimedia sensor networks, as well as by large quantities of online multimedia content depicting urban scenes. However, while there is a large body of research in related areas such as speech, music and bioacoustics, work on analysis of urban acoustic environments is relatively scarce. Furthermore, when existent, it mostly focuses on the classification of auditory scene type, e.g. street, park, as opposed to the identification of sound sources in those scenes, e.g. car horn, engine idling, bird tweet.
There are primarily two major challenges with urban sound research namely. First, the lack of labeled audio data previous work has focuses on audio from carefully produced movies or television tracks from specific environments such as elevators or office spaces and on commercial or proprietary datasets. The large effort involved in manually annotating real=world data means datasets based on field recording tend to be relatively small. Second, the lack of common vocabulary when working on urban sounds. This means the classification of sounds into semantic groups may vary from study to study, making it hard to compare results.

Related work: 

•	Create a way to classify environment sound give an audio clip

•	Data cleaning/Processing: Convert each sound signal into a log-scaled spectrogram

•	Training Data on spectrogram (128 frequency bands by 128 frames by 2 channels)

Methods: 

•	Classify with SVM,

•	Classify with Convolutional Neural Network

•	Classify with Multilayer perceptron

Important libraries/ packages: 
•	Numpy: NumPy is the fundamental package for scientific computing with Python. Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.

•	Librosa:  Python library for audio and music analysis

•	Pysoundfile: PySoundFile can read and write sound files. File reading/writing is supported through libsndfile, which is a free, cross-platform, open-source (LGPL) library for reading and writing many different sampled sound file formats that runs on many platforms including Windows, OS X, and Unix. It is accessed through CFFI, which is a foreign function interface for Python calling C code. CFFI is supported for CPython 2.6+, 3.x and PyPy 2.0+. PySoundFile represents audio data as NumPy arrays.

•	Matplotlib: Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.

•	Scikit-learn: Simple and efficient tools for data mining and data analysis. 

•	Tensorflow: The core open source library to help you develop and train ML models.

•	Keras: Keras is an open-source neural-network library written in Python. It is capable of running on top of TensorFlow
