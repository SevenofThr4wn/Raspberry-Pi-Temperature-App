

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Raspberry Pi Temperature App</h3>

  <p align="center">
    A Flask-based web application that runs on a Raspberry Pi to record and display internal temperature data from a wired temperature sensor. This app also fetches external weather data (temperature, humidity, apparent temperature) using the Australian Bureau of Meteorology API and shows everything on a simple web interface. Designed as a tool for workplace managers/supervisors to monitor indoor temperatures and help maintain healthy working conditions.
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
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
        <li><a href="#tech-stack">Teck Stack</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Features & Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#running-the-app">Running the App</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Here's a blank template to get started. To avoid retyping too much info, do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description`, `project_license`


### Tech Stack
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Flask](https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff)](#)
[![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?logo=sqlite&logoColor=white)](#)


<!-- GETTING STARTED -->
## Features & Getting Started

- **Real-time temperature logging** from a connected temperature sensor on the Raspberry aPi
- Simple web interface displaying:
  - Local sensor temperature
  - Current external temperature & humidity (via BOM API)
- Historical temperature data storage using SQL Lite database
- Built with **Python & Flask**
- Uses JSON to store sensor data

### Prerequisites

- **Raspberry Pi** setup with a compatible temperature sensor connected (eg., DS18B20 or similar).
- Python installed (Python 3 recommended).
- API Access to the **Australian BOM** for external weather data.
- Internet connection (if using BOM API)
- Basic knowledge of Flask web app operations

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/SevenofThr4wn/Raspberry-Pi-Temperature-App.git
    cd Raspberry-Pi-Temperature-App
    ```
2. Create and activate the virtual environment 
    ```sh
    python -m venv venv
    source venv/bin/activate
    ```
3. Install required python packages 
    ```sh
    pip install -r requirements.txt
    ```


### Running the App

To start the application(listening on all IP addresses):

```sh
flask run --host=0.0.0.0
```


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

If you have questions or want help expanding the project, feel free to reach out to me on Discord: sevenofthr4wn.

<!-- CONTACT -->
## Contact

John Eley - johneley798@gmail.com

Project Link: [Project](https://github.com/SevenofThr4wn/Raspberry-Pi-Temperature-App)
