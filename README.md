<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/381logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">381-Final</h3>

  <p align="center">
    381-Final Project. Using a chatbot  to automate Cisco Router.
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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot][product-screenshot]]

This project aims to automate the maintenance of a Cisco Router using a webex chatbot.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Python][Python.js]][Python-url]
* [![Ansible][Ansible.js]][Ansible-url]
* [![Docker][Docker.js]][Docker-url]
* [![Devnet][Devnet.js]][Devnet-url]
* [![Flask][Flask.js]][Flask-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get started, make sure you have Python installed. In addition you will need to install Ansible and Docker. 

### Prerequisites
<br />
Make sure that you have Python installed on your machine. <br />
Feel free to follow the tutorials listed below. <br /> 

* Windows Instructions
  ```sh
  https://www.digitalocean.com/community/tutorials/install-python-windows-10
  ```
* Linux Install
  ```sh
  https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-programming-environment-on-an-ubuntu-20-04-server
  ```
* Mac OS Install
  ```sh
  https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-macos
  ```

Download the following libraries
* pyyaml
  ```sh
  pip3 install pyyaml
  ```

* paramiko
  ```sh
  pip3 install paramiko
  ```

* webexteamsbot
  ```sh
  pip3 install webexteamsbot
  ```
This runs on a flask server, so you'll want to ensure that you have that ready to go. <br />
* Flask
  ```sh
  https://flask.palletsprojects.com/en/2.2.x/installation/
  ```
Now, make sure that you have Docker installed
* Docker
  ```sh
  https://docs.docker.com/get-docker/
  ```

You will need the following Docker image to set up the monitor
* jeremycohoe/tig_mdt
  ```sh
  https://hub.docker.com/r/jeremycohoe/tig_mdt
  ```

With that taken care of, the last prerequisite will be to download Ansible
* Ansible
  ```sh
  https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
  ```
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/FuriousBH/381-Final.git
   ```

2. Set up a webex bot.


3. Navigate to the Directory with the main.py app <br>
![PWD][PWD-screenshot]]

  <br/> 
    ```sh
    python3 main.py
    ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This is where we'll show examples of what the chatbot can do. <br>
Things like configuring an interface or pulling information from the router.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [This is optional] Let me know if we want this section



<!-- CONTRIBUTING -->
## Contributing

This is a little thing so we can all put in our own information. <br>
Thought it might be kind of nice.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/FuriousBH/381-Final
[contributors-url]: https://github.com/FuriousBH/381-Final/graphs/contributors
[product-screenshot]: images/ProductScreenshot.PNG
[Python.js]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org
[Ansible.js]: https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white
[Ansible-url]: https://www.ansible.com
[Docker.js]: https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com
[Devnet.js]: images/Devnet.png
[Devnet-url]: https://developer.cisco.com
[Flask.js]: https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white
[flask-url]: https://flask.palletsprojects.com/en/2.2.x/
[PWD-screenshot]: images/PWD.png
