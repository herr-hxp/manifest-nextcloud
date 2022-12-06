<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
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
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://elastx.se/en/">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Nextcloud on Elastx Virtuozzo PaaS</h3>

  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#nextcloud">Nextcloud</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- NEXTCLOUD -->
## Nextcloud

<p align="center">
  <img src="images/nextcloud-round.png" alt="Nextcloud logo">
</p>

Nextcloud puts your data at your fingertips, under your control.
Store your documents, calendar, contacts and photos on Elastx Virtuozzo PaaS platform.

More info on [https://nextcloud.com/](https://nextcloud.com/) and on [Elastx Virtuozzo PaaS](https://elastx.se/en/virtuozzo/).


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your Nextcloud on Elastx Virtuozzo PaaS.
To get your own environment up and running follow these simple steps.

### Prerequisites

[Sign up for Elastx Virtuozzo PaaS](https://elastx.se/en/signup/) to get your account.

### Installation

1. In the Virtuozzo PaaS Web GUI, click on `Import` and select the URL tab
2. Paste this URL in the input field: https://raw.githubusercontent.com/herr-hxp/manifest-nextcloud/master/manifest.jps and click `Import`
3. Provide an environment name and a display name for your new environment and then click on `Install`
4. Sit back and relax while Virtuozzo PaaS creates your new environment

A few moments later, your new Nextcloud application is fully installed and you can start to manage files with your team.

> If you need a secure connection over SSL/TLS, you can easily add a load balancer by the *topology panel* corresponding to your envrionnement and either install the Let's Encrypt Add-on or use your own certificate via the environment's *Settings* button and then head to the *Custom SSL* tab.

<!-- USAGE EXAMPLES -->
## Usage

This manifest can be fully modified to suit your own needs. For more information, please check the [documentation](https://docs.cloudscripting.com/).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Elastx - [@elastx](https://twitter.com/elastx) - hello@elastx.se

Elastx on GitHub: [https://github.com/elastx](https://github.com/elastx)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/elastx/
