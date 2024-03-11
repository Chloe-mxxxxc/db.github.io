---
layout: default
---
![](/docs/8.png)

*Ancient Dongba Buddhist Scripture: A Pictographic Heritage of the Naxi People (Captured by WB Hu, January 11, 2022, in Lijiang, Yunnan, China.)*

The Dongba script is a unique hieroglyphic writing system primarily utilized by the Naxi people in the northwestern region of Yunnan Province, China. It stands out as one of the few hieroglyphic scripts still in use globally. 
Originating from the Dongba religion—a venerable belief system of the Naxi—the script is employed by its followers, known as "Dongba." These individuals serve dual roles as priests and traditional healers, with responsibilities that include documenting history, disseminating religious knowledge, and performing medical practices.

The primary mediums for Dongba writings are paper and wooden boards, though cloth and leather are also occasionally used. This script extends beyond merely recording religious ceremonial texts; it encompasses a broad array of fields such as traditional medicine, history, literature, and astronomy. 

The pictographic nature of the Dongba script vividly captures the daily life and natural surroundings of the Naxi people, featuring an extensive collection of symbols representing flora and fauna, natural phenomena, and various human activities.

* * *
## Dataset
### Dongba Single Character Dataset
This project commenced with the Dongba characters documented in "A Dictionary of Dongba Pictographs and Phonetic Scripts  《麼些象形標音文字字典》", ISBN13：9789575476854, published by Li Lincan in 1973. This dictionary encapsulates a total of 2,122 Dongba symbols. Based on this comprehensive work, we have standardized all characters according to Chinese conventions. 

More details about our annotated Dongba character data [Link](./another-page.html).

### Dongba Natural Scene Synthetic Dataset
To expand the application scenarios of the Dongba Single Character Dataset, we have synthesized 40,000 images to serve as a training set. The synthesized data relies on the Dongba Single Character Dataset and the COCO dataset, with each image randomly including 1-10 Dongba characters. For more details, please refer to [Link](./db).

### Dongba Hieroglyphics Dataset
Dongba Hieroglyphics Dataset (DBH) is a new dataset featuring Dongba characters, an ancient script created by the Naxi minority's ancestors in China. These pictographs hold historical and literary value and have been recognized as "Memory of the World" by UNESCO. As the total number of distinct Dongba characters is unknown, text spotting in manuscripts is an open-set problem, where spotting novel characters helps decipher historical texts. We collected data from Dongba sutras, annotating and summarizing it into a dataset of 3633 bounding boxes across 253 categories. To accommodate one-shot tasks, experts hand-wrote an additional 253 characters, using them as support images. For more details, please refer to [Link](./dbh).

Reference link:
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


Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
