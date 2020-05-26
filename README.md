# hukish gallery
[![BCH compliance](https://bettercodehub.com/edge/badge/kamauvick/PicsGarage?branch=master)](https://bettercodehub.com/) 
[![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](http://opensource.org/licenses/MIT)   
#### Author
> Hudson Hukish

## Description
Hukishgallery is a personal gallery django application that allows users display their photos for others to see.

## Setup Instructions:
### Requirements

##### 1. Clone the repository
Clone the the repository by running 

   ```bash
   git clone https://github.com/hukish/gallery_master.git
   ```
 or download a zip file of the project from github
 

Navigate to the project directory
```bash
cd PicsGarage
`
##### 2. Create a virtual environment
 Install `Virtualenv` 

   ```prettier
   pip install virtualenv
   ```

To create a virtual environment named `virtual`, run

   ```prettier
   virtualenv virtual
   ```
To activate the virtual environment we just created, run

   ```bash
   source virtual/bin/activate
   ```



##### 3. Create a database
You'll need to create a new postgress database, Type the following command to access postgress
   ```bash
    $ psql
   ```
   Then run the following query to create a new database named ```photo``` 
   ```prettier
   # create database photo
   ```
#####  4.Install dependencies
To install the requirements from `requirements.txt` file,

   ```prettier
   pip install -r requirements.txt
   ```