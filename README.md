<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** HarshaAbeyvickrama, Infine, twitter_handle, harshaabeyvickrama@gmail.com, Infine, project_description
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/HarshaAbeyvickrama/Infine.git">
    <img src="images/Infine.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Infine</h3>

  <p align="center">
    Infine is a project created to analyze YouTube videos and channels. This project can monitor the changes in a youtube video or a channel added to the database or the videos of the user uploads.
    <br />
    <a href="https://github.com/HarshaAbeyvickrama/Infine/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/HarshaAbeyvickrama/Infine">View Demo</a>
    ·
    <a href="https://github.com/HarshaAbeyvickrama/Infine/issues">Report Bug</a>
    ·
    <a href="https://github.com/HarshaAbeyvickrama/Infine/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

### Built With

* [Google Apps Script](https://www.google.com/script/start/)
* [YouTube Data API V3](https://developers.google.com/youtube/v3)
* [Google Sheets API V4](https://developers.google.com/sheets/api)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Spreadsheet setup

1. Make of copy of the spreadsheet <a href="" class="button primary">here</a>. It already contains the Apps Script code from this repository.
2. Change the name of the Project to aything you want.

### YouTube Advanced Service setup

1. From the spreadsheet, open the script editor by selecting Extensions > Apps Script.
2. In the left-hand navigation pane, select + next to Services.
3. Choose the YouTube Data API service, and click Add.
4. Then Choose the Google Sheets API service, and click Add.

### Making a local copy

Clone the repo
```sh
  git clone https://github.com/HarshaAbeyvickrama/Infine.git
```
<!-- USAGE EXAMPLES -->
## Usage

### Functions

1. <strong>addUserVideos() : </strong> <i>Add your uploads to the sheet to track.</i>
2. <strong>getUserVideos() : </strong> Returns a JSON response of all user uploaded videos.
3. <strong>addPublicVideo(url,type) : </strong> Add a video with the link to the sheet to track.
4. <strong>getPublicVideos() : </strong> Returns a JSON response of all videos that are added to the sheet with addPublicVideo() function
5. <strong>getVideoStats(videoID) : </strong> Returns a JSON response of a particular video that is currently available in the database
6. <strong>addNewChannel(ChannelLink) : </strong> Add a YouTube channel to the sheet to monitor. This function will add all videos in that channel to the database and it will monitor their views, comments & like count seperately.
6. <strong>getChannel(channelID) : </strong> Returns a JSON response with the details a particular channel

<strong>Here,  a separate sheet will be created with the name of the video ID for every video added to the sheet. This is applicable for all user videos and addition of channels<strong>





<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/HarshaAbeyvickrama/Infine/issues) for a list of proposed features (and known issues).



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

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - harshaabeyvickrama@gmail.com

Project Link: [https://github.com/HarshaAbeyvickrama/Infine](https://github.com/HarshaAbeyvickrama/Infine)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/HarshaAbeyvickrama/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/HarshaAbeyvickrama/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/HarshaAbeyvickrama/repo.svg?style=for-the-badge
[forks-url]: https://github.com/HarshaAbeyvickrama/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/HarshaAbeyvickrama/repo.svg?style=for-the-badge
[stars-url]: https://github.com/HarshaAbeyvickrama/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/HarshaAbeyvickrama/repo.svg?style=for-the-badge
[issues-url]: https://github.com/HarshaAbeyvickrama/repo/issues
[license-shield]: https://img.shields.io/github/license/HarshaAbeyvickrama/repo.svg?style=for-the-badge
[license-url]: https://github.com/HarshaAbeyvickrama/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/HarshaAbeyvickrama
