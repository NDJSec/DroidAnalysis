<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/NDJSec/DroidAnalysis">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">DroidAnalysis</h3>

  <p align="center">
    Compilation of various analysis tools for Android RE
    <br />
    <a href="https://github.com/NDJSec/DroidAnalysis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/NDJSec/DroidAnalysis/issues">Report Bug</a>
    ·
    <a href="https://github.com/NDJSec/DroidAnalysis/issues">Request Feature</a>
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
<br>

## Android Reverse Engineering PDF [HERE](https://github.com/NDJSec/Android-Reverse-Engineering)
<br>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

DroidAnalysis is a compilation of various tools, Android RE. This repo, is set up to be git submodules to each repo for each tool. So, you can install this repo for all the tools, or go to each tool and install them individually. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Java][Java]][Java-url]
* [![Python][Python]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
In order to get started, follow the installation instructions below. Note, installation for each tool, is linked at the bottom of the Installation section.

### Prerequisites
* Ghidra 11.0 or higher (jni-ghidra)
* Python3 
* Androguard 4.1.1 or higher (mallodroid)

### Installation
```bash
    git clone https://github.com/NDJSec/DroidAnalysis.git
    cd DroidAnalysis
    git submodule update --init --recursive
```

* [jni_ghidra](https://github.com/NDJSec/jni_ghidra)
* [mallodroid](https://github.com/NDJSec/mallodroid)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

NDJSec - [@NicolasJanis1](https://twitter.com/NicolasJanis1) - nicolas.d.janis@gmail.com

Project Link: [https://github.com/NDJSec/DroidAnalysis](https://github.com/NDJSec/DroidAnalysis)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/NDJSec/DroidAnalysis.svg?style=for-the-badge
[contributors-url]: https://github.com/NDJSec/DroidAnalysis/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/NDJSec/DroidAnalysis.svg?style=for-the-badge
[forks-url]: https://github.com/NDJSec/DroidAnalysis/network/members
[stars-shield]: https://img.shields.io/github/stars/NDJSec/DroidAnalysis.svg?style=for-the-badge
[stars-url]: https://github.com/NDJSec/DroidAnalysis/stargazers
[issues-shield]: https://img.shields.io/github/issues/NDJSec/DroidAnalysis.svg?style=for-the-badge
[issues-url]: https://github.com/NDJSec/DroidAnalysis/issues
[license-shield]: https://img.shields.io/github/license/NDJSec/DroidAnalysis.svg?style=for-the-badge
[license-url]: https://github.com/NDJSec/DroidAnalysis/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/nicolas-janis/
[product-screenshot]: images/screenshot.png
[Java]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://www.java.com/en/
[Python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/

