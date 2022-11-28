# GitHub Topics scrapper

- Using Selenium and Beautiful Soup

<img src = 'https://i.imgur.com/eyf9jsx.gif'>

<div style="text-align:center;">
<br>
<a href = 'https://colab.research.google.com/github/jishnukoliyadan/scrapper_github_topics//blob/master/scraping_github_topics.ipynb' target = '_blank'><img src = 'https://raw.githubusercontent.com/jishnukoliyadan/usefull_items/master/svgs/Colab_Run_In.svg' width = 23%></a>
<a href = 'https://github.com/jishnukoliyadan/scrapper_github_topics/blob/master/scraping_github_topics.ipynb' target = '_blank'><img src = 'https://raw.githubusercontent.com/jishnukoliyadan/usefull_items/master/svgs/GitHub_View_Source.svg' width = 23%></a>
<a href = 'https://www.kaggle.com/code/jishnukoliyadan/data-collection-tutorial' target = '_blank'><img src = 'https://raw.githubusercontent.com/jishnukoliyadan/usefull_items/master/svgs/Kaggle_View_On.svg' width = 23%></a>
<a href = 'https://nbviewer.org/github/jishnukoliyadan/scrapper_github_topics/blob/master/scraping_github_topics.ipynb' target = '_blank'><img src = 'https://raw.githubusercontent.com/jishnukoliyadan/usefull_items/master/svgs/NbViwer_View_In.svg' width = 23%></a>
<br>
</div>

## Data collected

* We have scrapped records of **180** topics and associating **21337** GitHub repository informations.
* The data is made available in **[Kaggle Dataset](https://www.kaggle.com/datasets/jishnukoliyadan/github-topics-star-count)** section and it will be updating in every month.
* Topics list collected (format sample :point_down:)

|    | title     | link                                | descrip                                                                                      |
|---:|:----------|:------------------------------------|:---------------------------------------------------------------------------------------------|
|  0 | 3D        | https://github.com/topics/3d        | 3D modeling is the process of virtually developing the surface and structure of a 3D object. |
|  1 | Ajax      | https://github.com/topics/ajax      | Ajax is a technique for creating interactive web applications.                               |
|  2 | Algorithm | https://github.com/topics/algorithm | Algorithms are self-contained sequences that carry out a variety of tasks.                   |
|  3 | Amp       | https://github.com/topics/amphp     | Amp is a non-blocking concurrency library for PHP.                                           |
|  4 | Android   | https://github.com/topics/android   | Android is an operating system built by Google designed for mobile devices.                  |

* Topics related repository informations collected (format sample :point_down:)

|    | topic   | user_name   | repo_name         | repo_link                                   | start_count   |
|---:|:--------|:------------|:------------------|:--------------------------------------------|:--------------|
|  0 | 3d      | mrdoob      | three.js          | https://github.com/mrdoob/three.js          | 87.1k         |
|  1 | 3d      | libgdx      | libgdx            | https://github.com/libgdx/libgdx            | 20.8k         |
|  2 | 3d      | pmndrs      | react-three-fiber | https://github.com/pmndrs/react-three-fiber | 20.5k         |
|  3 | 3d      | BabylonJS   | Babylon.js        | https://github.com/BabylonJS/Babylon.js     | 18.8k         |
|  4 | 3d      | ssloy       | tinyrenderer      | https://github.com/ssloy/tinyrenderer       | 15.3k         |

## Tools used for the process

- Selenium
- Beautiful Soup

## Getting Started

**Requirements :**

- Python used : **Python 3.10.8**
- [Required python packages](requirements.txt)

```bash
pip install -r requirements.txt --upgrade
```


# License
The license can be found in the [LICENSE](LICENSE) file.


