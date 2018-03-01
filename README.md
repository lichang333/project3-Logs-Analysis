# Full Stack Web Developer Nanodegree Project 3 - Log Anlysis

### Introduction
This project is for Udacity Full Stack Web Developer Nanodegree. In this project, there have a large database with nearly a million rows. The target is to collect the useful informations and generate a business report from thoes data.


### Envirnment
Make sure you had already installed the following stuffs:
* Python 3
* VirtualBox
* Vagrant


### To run this program

1. Clone the configuration from: https://github.com/udacity/fullstack-nanodegree-vm

2. Download [newsdata.zip](https://s3.amazonaws.com/video.udacity-data.com/topher/2016/August/57b5f748_newsdata/newsdata.zip).

3. Type following command to your terminal to run this program:

* To lunch the virtual machine, type  ```vagrant up```, then login with command ```vagrant ssh```

* Use ```psql -d news -f newsdata.sql ``` to load data.

* Type ```python3 main.py ``` to run.



### Resources
fullstack-nanodegree-vm：https://github.com/udacity/fullstack-nanodegree-vm

### License
The content of this repository is licensed under a Creative Commons Attribution License.
