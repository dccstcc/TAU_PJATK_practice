<!--
*** Thanks for checking out c. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
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

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![NO LICENSE][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://gdansk.pja.edu.pl/pl/">
    <img src="images/logo.jpg" alt="Logo" width="540" height="80">
  </a>

  <h2 align="center">Automated software testing</h2>

  <p align="center">
    <h3> Testing Graphics User WEB Interfaces with Selenium framework </h3>
    <!-- <br />
    <a href="https://github.com/dccstcc/TAU_PJATK_practice/tree/master/lab_6_Selenium/new"><strong>» go to CODE »</strong></a>
    <br />
    <br /> -->
    <!-- <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a> -->
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-description">Project description</a>
      <ul>
        <li><a href="#libraries-and-frameworks">Libraries / Frameworks</a></li>
      </ul>
    </li>
    <li>
      <a href="#native-deploy">Native deploy</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#how-to-use">How to use ?</a></li>
    <!-- <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li> -->
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact with me</a></li>
    <!-- <li><a href="#acknowledgements">Acknowledgements</a></li> -->
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Project description

<p> In this project I used Selenium web driver for test graphic user interface in web application. </p>

### Libraries and frameworks

This project use technology below.

- [![selenium][selenium-shield]][selenium-url]
- [![maven][maven-shield]][maven-url]

<!-- GETTING STARTED -->

## Native deploy

This is instructions on setting up this project locally.

### Prerequisites

Selenium web driver for automatic graphics interface tests use cases is need. <br />
Apache Maven project build tools is need. <br />

- Maven
  ```sh
  mkdir ~/maven
  cd ~/maven
  curl -o apache-maven-3.9.2-bin.tar.gz https://dlcdn.apache.org/maven/maven-3/3.9.2/binaries/apache-maven-3.9.2-bin.tar.gz
  tar xzvf apache-maven-3.9.2-bin.tar.gz
  nano .bashrc
  ```
  into .bashrc on the end of file paste:
  ```sh
  export M2_HOME=~/maven/apache-maven-3.9.2/bin/
  export PATH=${M2_HOME}/bin:${PATH}
  ```
  hit `Ctrl+O` to save <br />
  hit `Ctrl+X` to exit

### Installation

1. Clone the repo with Angular SPA and run this app according to instruction of installation from project page
   ```sh
   git clone https://github.com/dominik-stec/Angular.git
   ```
2. Clone the repo with selenium tests cases
   ```sh
   git clone https://github.com/dominik-stec/QA.git
   ```
3. Go to catalog with selenium maven project
   ```sh
   cd new
   ```

<!-- USAGE EXAMPLES -->

## How to use

Run selenium tests

```sh
mvn test
```

In Chrome web browser starts automatic tests which execute different cases of operations on graphics user interface for find bugs into user side usage application.

 <img src="images/test_example.png" width="500"/>
   
<!-- [![browser][browser]][browser]
 -->

When tests will end without fails we can see tests pass summary into command line.

<img src="images/test_cmd.png" width="500"/>

<!-- [![summary][summary]][summary] -->

<!-- _For more examples, please refer to the [Documentation](https://example.com)_ -->

<!-- ROADMAP
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).

-->

<!-- CONTRIBUTING
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

-->

<!-- LICENSE -->

## License

This project has not a license.
All rights are reserved and it is not Open Source or free. You cannot modify or redistribute this code without explicit permission from the copyright holder, because projects which I realised are private conception from PJATK studies.
See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Dominik Stec - dccstcc@gmail.com

[![LinkedIn][linkedin-shield]][linkedin-url]

Project URL:
<br />
`https://github.com/dominik-stec/QA.git`

<!-- ACKNOWLEDGEMENTS
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)

-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/dominik-stec/QA.svg?style=for-the-badge
[contributors-url]: https://github.com/dominik-stec/QA/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dominik-stec/QA.svg?style=for-the-badge
[forks-url]: https://github.com/dominik-stec/QA/network/members
[stars-shield]: https://img.shields.io/github/stars/dominik-stec/QA.svg?style=for-the-badge
[stars-url]: https://github.com/dominik-stec/QA/stargazers
[issues-shield]: https://img.shields.io/github/issues/dominik-stec/QA.svg?style=for-the-badge
[issues-url]: https://github.com/dominik-stec/QA/issues
[license-shield]: https://img.shields.io/badge/License-NONE-orange
[license-url]: https://github.com/dominik-stec/QA/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/dominik-stec
[product-screenshot]: images/screenshot.png
[junit-shield]: https://img.shields.io/badge/-JUnit-green
[junit-url]: https://junit.org/junit5/
[mockito-shield]: https://img.shields.io/badge/-Mockito-red
[mockito-url]: https://site.mockito.org/
[docker-shield]: https://img.shields.io/badge/-Docker-blue
[docker-url]: https://www.docker.com/
[maven-shield]: https://img.shields.io/badge/-Maven-white
[maven-url]: https://maven.apache.org/
[cucumber-shield]: https://img.shields.io/badge/-Cucumber-green
[cucumber-url]: https://cucumber.io/
[jetty-shield]: https://img.shields.io/badge/-Jetty-red
[jetty-url]: https://www.eclipse.org/jetty/
[jmeter-shield]: https://img.shields.io/badge/-Jmeter-green
[jmeter-url]: https://jmeter.apache.org/
[selenium-shield]: https://img.shields.io/badge/-Selenium-yellow
[selenium-url]: https://www.selenium.dev/
[server_run]: images/server_run.png
[client_run]: images/client_run.png
[client]: images/client.png
[jetty_run]: images/jetty_run.png
[browser]: images/browser.png
[summary]: images/summary.png
