# Sentiment-Analysis-api

Provides if the query text is *pos/ neg/ neutral*

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* git
* Python3.4
* Pip3
* Virtualenv

```
sudo add-apt-repository ppa:fkrull/deadsnakes
sudo apt update
sudo apt install python3.4
sudo apt-get install python3-pip
sudo apt-get install virtualenv

```
### Installing

```
git clone https://github.com/4sentiSentinels/Sentiment-Analysis-api.git
cd Sentiment-Analysis-api
source venev/bin/activate
```
### Running the tests

```
python3.4 server.py

```
### Console output

```
(venev) jeevan@jeevan-Lenovo-G50-70:~/labs/Sentiment-Analysis-api$ python3.4 server.py 
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger pin code: 150-042-353
```
### Usage

Open link in browser and input in following format
```
http://127.0.0.1:5000/q/<Your text here>
```
## Demo

Chekout demo at 

* [Demo](http://noobg1.pythonanywhere.com/q/sampletext) - insert your text in place of sampletext