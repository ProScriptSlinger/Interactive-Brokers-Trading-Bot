<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
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
  <a href="https://github.com/ProScriptSlinger/Interactive-Brokers-Trading-Bot">
    <img src="images/IBTB_logo.png" alt="Logo" width="120" height="180">
  </a>

  <h3 align="center">Interactive Brokers Trading Bot</h3>

  <p align="center">
    A Python library written to handle IB's Client Portal API, manage portfolio and execute trades.
    <br />
    <a href="https://github.com/ProScriptSlinger/Interactive-Brokers-Trading-Bot"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ProScriptSlinger/Interactive-Brokers-Trading-Bot">View Demo</a>
    ·
    <a href="https://github.com/ProScriptSlinger/Interactive-Brokers-Trading-Bot">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block"> 📚Table of Contents</h2></summary>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## 💡About The Project

<!--
[![Product Name Screen Shot][product-screenshot]](https://example.com)
-->

This project is built entirely on Python, it combines other Interactive Brokers libraries written by other contributors as well as my own contribution in making algorithmic trading on Interactive Brokers possible.

<!--
**To avoid retyping too much info. Do a search and replace with your text editor for the following:**
`github_username`, `repo_name`, `twitter_handle`, `email`, `project_title`, `project_description`
-->

### Built With

- [Python](https://www.python.org/)

<!-- GETTING STARTED -->

## 🎉Getting Started

To get a local copy up and running follow these simple steps.

### 🔖 Prerequisites

Before using this library, ensure you have Java installed and have an account with Interactive Brokers. Check out [Interactive Broker Client Portal Web API](https://interactivebrokers.github.io/cpwebapi/) for setting up. You can skip the download and unzip the CPI WebAPI step from the IB site as this step has been taken care off in the library.

### 🔧 Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ProScriptSlinger/Interactive-Brokers-Trading-Bot.git
   ```
2. Navigate to the working directory

3. In the terminal, run

   ```
   python setup.py build
   ```

   and then

   ```
   python setup.py install
   ```

4. Enter your IB credentials in write_config.py and run the script

5. Open run_client.py and run the script. It will download the clientportal.gw to the working directory.

6. Using Git Bash, navigate to the clientportal.gw folder and run

   ```
   "bin/run.bat" "root/conf.yaml"
   ```

7. Run run_client.py in tests and the bot should be up and running.

8. Follow the instructions on run_client.py to configure your trading bot.

<!-- USAGE EXAMPLES -->

## 📦 Usage

To use it, study the revelant libraries, namely the python objects in robot/ folder. There are also some simple instructions in the run_client.py to get you up and running quick.

<!-- ROADMAP -->

## 🚩 Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).

### ✨ Milestone Summary

| Status | Milestone                                                                                                                               | Goals |      ETA      |
| :----: | :-------------------------------------------------------------------------------------------------------------------------------------- | :---: | :-----------: |
|   🚀   | **[Implement the ability to associate tickers with different indicators and trigger levels](#implement-ticker-indicators-association)** | 1 / 1 | 15 April 2021 |

### Implement ticker indicators association

> This milestone will be done when

- Different signals can be attached to a ticker
- All the indicators' signal can be checked independently, giving correct buy/sell signals

<!-- CONTRIBUTING -->

## 💝 Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
