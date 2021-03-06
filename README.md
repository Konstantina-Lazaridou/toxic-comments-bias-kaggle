<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]

<!-- Buttons
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->



<!-- PROJECT LOGO -->
<br />
<div align="center">
<h3 align="center">Classifying toxic online comments</h3>

  <p align="center">
    Reproducing the solution by <a href="https://www.kaggle.com/bminixhofer/simple-lstm-pytorch-version">Simple LSTM - PyTorch version</a>.
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Classifying toxic online comments.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* Python
* Pytorch

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

Things you need to use the software.
* Python
* Jupyter notebook
* Poetry (`pip` install did not work out on Ubuntu 20.04, [curl](https://pypi.org/project/poetry/) install worked after executing `source $HOME/.poetry/env` as well)
* Text data by [Kaggle](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/overview)
* Embeddings by [Stanford](https://nlp.stanford.edu/projects/glove/) and [Facebook](https://fasttext.cc/docs/en/english-vectors.html)

### Installation

Follow these steps to install create a virtual environment and activate it in Jupyter.
* In this project's repository, execute ``poetry install``, which creates a virtual environment based on the pyproject.toml file
* Activate the virtual environment with ``poetry shell``
* If you need any new dependecies, e.g., ``nltk``, execute `poetry add nltk`
* To run the notebook with this environment, execute ``poetry run jupyter notebook``

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP
## Roadmap

- [] Feature 1
- [] Feature 2
- [] Feature 3
    - [] Nested Feature

See the [open issues](https://github.com/KonstantinaLazaridou/toxic-comments-bias-kaggle/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>
 -->


<!-- ACKNOWLEDGMENTS
## Acknowledgments

* []()
* []()
* []()

 -->



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/KonstantinaLazaridou/toxic-comments-bias-kaggle.svg?style=for-the-badge
[contributors-url]: https://github.com/KonstantinaLazaridou/toxic-comments-bias-kaggle/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
