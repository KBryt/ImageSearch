
# I have change the model used in the Deep Image Search to suite my work. Please refer to the original page for more details

# Deep Image Search - AI-Based Image Search Engine

<p align="center"><img src="https://github.com/TechyNilesh/DeepImageSearch/blob/main/logo/deep%20image%20search%20logo%20New.png?raw=true" alt="Brain+Machine" height="218" width="350"></p>

**Deep Image Search** is an AI-based image search engine that includes **deep transfer learning features Extraction** and **tree-based vectorized search technique.**

![Generic badge](https://img.shields.io/badge/AI-Advance-green.svg) ![Generic badge](https://img.shields.io/badge/Python-v3-blue.svg) ![Generic badge](https://img.shields.io/badge/pip-v3-red.svg)  ![Generic badge](https://img.shields.io/badge/TensorFlow-v2-orange.svg) ![Generic badge](https://img.shields.io/badge/Annoy-latest-green.svg) [![Downloads](https://static.pepy.tech/personalized-badge/deepimagesearch?period=total&units=none&left_color=grey&right_color=green&left_text=Downloads)](https://pepy.tech/project/deepimagesearch)

<h2><img src="https://cdn2.iconfinder.com/data/icons/artificial-intelligence-6/64/ArtificialIntelligence9-512.png" alt="Brain+Machine" height="38" width="38"> Creators </h2>

### [Nilesh Verma](https://nileshverma.com "Nilesh Verma")

## Features
- Faster Search **O(logN)** Complexity.
- High Accurate Output Result.
- Best for Implementing on python based web application or APIs.
- Best implementation for College students and freshers for project creation.
- Applications are Images based E-commerce recommendation, Social media and other image-based platforms that want to implement image recommendation and search.


If you are facing any VS C++ 14 related issue in windows during installation, kindly refer to following solution: [Pip error: Microsoft Visual C++ 14.0 is required](https://stackoverflow.com/questions/44951456/pip-error-microsoft-visual-c-14-0-is-required "Pip error: Microsoft Visual C++ 14.0 is required")

## Complete Code

```python
# Importing the proper classes
from ImageSearch import Index,LoadData,SearchImage
# load the Images from the Folder (You can also import data from multiple folder in python list type)
image_list = LoadData().from_folder(['images','wiki-images'])
# For Faster Serching we need to index Data first, After Indexing all the meta data stored on the local path
Index(image_list).Start()
# for searching you need to give the image path and the number of similar image you want
SearchImage().get_similar_images(image_path=image_list[0],number_of_images=5)
# If you want to plot similar images the you can use this method, It will plot 16 most similar images from the data index
SearchImage().plot_similar_images(image_path = image_list[0])
```

## License



    MIT License
    
    Copyright (c) 2021 Nilesh Verma
    
    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Please do STAR the repository, if it helped you in anyway.

**More cool features will be added in future. Feel free to give suggestions, report bugs and contribute.**
