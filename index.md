---
layout: default
---

The Dongba script is a unique hieroglyphic writing system primarily utilized by the Naxi people in the northwestern region of Yunnan Province, China. It stands out as one of the few hieroglyphic scripts still in use globally. 

Originating from the Dongba religion—a venerable belief system of the Naxi—the script is employed by its followers, known as "Dongba." These individuals serve dual roles as priests and traditional healers, with responsibilities that include documenting history, disseminating religious knowledge, and performing medical practices.

![](/docs/8.png)

*Ancient Dongba Buddhist Scripture: A Pictographic Heritage of the Naxi People (Captured by WB Hu, January 11, 2022, in Lijiang, Yunnan, China.)*

The primary mediums for Dongba writings are paper and wooden boards, though cloth and leather are also occasionally used. This script extends beyond merely recording religious ceremonial texts; it encompasses a broad array of fields such as traditional medicine, history, literature, and astronomy. 

The pictographic nature of the Dongba script vividly captures the daily life and natural surroundings of the Naxi people, featuring an extensive collection of symbols representing flora and fauna, natural phenomena, and various human activities.

* * *
## Dataset
### Dongba Single Character Dataset
This project commenced with the Dongba characters documented in "A Dictionary of Dongba Pictographs and Phonetic Scripts  《麼些象形標音文字字典》", ISBN13：9789575476854, published by Li Lincan in 1973. This dictionary encapsulates a total of 2,122 Dongba symbols. Based on this comprehensive work, we have standardized all characters according to Chinese conventions. 

![](/docs/10.png)

*A Dictionary of Dongba Pictographs and Phonetic Scripts, and Selected Content from the Book*

More details about our annotated Dongba character data [Link](./another-page.html).

### Dongba Natural Scene Synthetic Dataset
To expand the application scenarios of the Dongba Single Character Dataset, we have synthesized 40,000 images to serve as a training set. The synthesized data relies on the Dongba Single Character Dataset and the COCO dataset, with each image randomly including 1-10 Dongba characters. For more details, please refer to [Link](./db).

### Dongba Hieroglyphics Dataset
Dongba Hieroglyphics Dataset (DBH) is a new dataset featuring Dongba characters, an ancient script created by the Naxi minority's ancestors in China. These pictographs hold historical and literary value and have been recognized as "Memory of the World" by UNESCO. As the total number of distinct Dongba characters is unknown, text spotting in manuscripts is an open-set problem, where spotting novel characters helps decipher historical texts. We collected data from Dongba sutras, annotating and summarizing it into a dataset of 3633 bounding boxes across 253 categories. To accommodate one-shot tasks, experts hand-wrote an additional 253 characters, using them as support images. For more details, please refer to [Link](./dbh).

* * *
## Project
### One-shot Learning-based Text Spotting
Our research introduces a novel approach to historical manuscript processing, specifically addressing the challenges of limited data and the emergence of novel classes. We present a One-shot learning-based Text Spotting (OTS) technique that efficiently recognizes new characters from minimal support samples. Inspired by cognitive studies, we incorporate a spatial alignment module to identify and learn from key spatial features in images, aided by a unique support image. To counter the imbalance issue common in low-resource text spotting, we've devised a new torus loss function, enhancing the discriminative power of our metric's embedding space. This method is not only efficient, requiring few training samples but also excels at spotting novel characters and symbols, showcasing its potential for broad applications in manuscript analysis.

![](/docs/2_1.png)

For more details, please refer to [Link](https://github.com/infinite-hwb/ots).

### Dongba Buddhist Manuscript Recognition and Translation System
The aim of this system is to achieve end-to-end translation from images of Dongba Buddhist manuscripts to Chinese results. Due to the scarcity of data on Dongba Buddhist manuscript images, we utilize One-shot Learning-based Text Spotting [Link](https://github.com/infinite-hwb/ots) for the recognition phase, and low-resource machine translation techniques for the translation phase. Examples specific to Dongba Buddhist manuscript images are provided at [link](http://118.31.111.194:5999/dongba).

* * *
## Reference
1. Dongba Glyphs with a Semantic Index
   [Link](https://duoduo-lab.github.io/)
2. Dongba symbols, Wikipedia
   [Link](https://en.wikipedia.org/wiki/Dongba_symbols)
3. Naxi Dongba, Scriptsource
   [Link](https://scriptsource.org/cms/scripts/page.php?item_id=script_detail&key=Nkdb)
4. Naxi Dongba script, Omniglot
   [Link](https://omniglot.com/writing/naxi.htm)
5. Naxi Dongba PUA Fonts
   [Link](https://www.babelstone.co.uk/Fonts/Naxi.html)
6. Naxi Manuscript Collection in The Library of Congress
   [Link](https://www.loc.gov/collections/naxi-manuscripts/about-this-collection)
7. Dongba Culture
   [Link](http://www.dongba-culture.com/)

* * *
## Contact
Email: wenbo@stu.ecnu.edu.cn
