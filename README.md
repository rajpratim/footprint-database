# Footprint-Database

`Footprint-Database` is a dataset of footprint images of 21 individuals captured using flatbed scanner and 32 individuals with the dactloscopic images (including left and right footprint).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![image4][image-4]

## Why we made Footprint-Database
Human footprint is one of the relatively new physiological biometrics due to its stable and unique characteristics. The texture and foot shape information of footprint offers one of the powerful means in personal recognition.

## How to use this dataset

### Overview of the dataset
![image3][image-3]

### Get the dataset   
```bash
git clone git@github.com:goodrahstar/footprint-database.git
```


### Basic image pre-proceessing on the footprint images to perform feature extraction
![image1][image-1]


## To Serious Machine Learning Researchers
For those who are interested to explore the domain of biomtrics and implement a human identification system using footprint images can make uses of following research in which we used this database.

### 1.
```latex

Rohit Khokher, R.C. Singh, Rahul Kumar, 
Footprint Recognition with Principal Component Analysis and Independent Component Analysis, 
International Conference on Science and Engineering of Materials (ICSEM 2014), 
DOI: 10.1002/masy.201400045 
```

### 2.
```latex

@Inbook{Khokher2017,
author="Khokher, Rohit
and Singh, Ram Chandra",
editor="Manchanda, Pammy
and Lozi, Ren{\'e}
and Siddiqi, Abul Hasan",
title="Footprint-Based Personal Recognition Using Dactyloscopy Technique",
bookTitle="Industrial Mathematics and Complex Systems: Emerging Mathematical Models, Methods and Algorithms",
year="2017",
publisher="Springer Singapore",
address="Singapore",
pages="207--219",
isbn="978-981-10-3758-0",
doi="10.1007/978-981-10-3758-0_14",
url="https://doi.org/10.1007/978-981-10-3758-0_14"
}
```

### 3.
```latex

@article{article,
author = {Khokher, Rohit and Singh, R C},
year = {2016},
month = {11},
pages = {},
title = {Footprint-Based Personal Recognition using Scanning Technique},
volume = {9},
journal = {Indian Journal of Science and Technology},
doi = {10.17485/ijst/2016/v9i44/105167}
}
```

## Benchmark
We performed lots of correlations on the footprint images using various features on the left and right footprint. Also build relations between the height and weight using the foot image.
![image2][image-2]


## Contact
To discuss the dataset, please reachout to me at `rahul@botsupply.ai`


## License

The MIT License (MIT) Copyright © , https://hellorahulk.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[image-1]: https://github.com/goodrahstar/footprint-database/blob/master/docs/image1.png?raw=true "Preprocessing"
[image-2]: https://github.com/goodrahstar/footprint-database/blob/master/docs/image2.png?raw=true "validation"
[image-3]: https://github.com/goodrahstar/footprint-database/blob/master/docs/image3.png?raw=true "Overview"
[image-4]: https://github.com/goodrahstar/footprint-database/blob/master/docs/image4.png?raw=true "intro"
