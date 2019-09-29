# Lab for working with pyspark and aws.
Examples of using pyspark and aws services.

## Requirements
 - Linux 
 - Docker

## Usage
 - Run Docker command
 ```bash
  docker run -it -p 8888:8888 \
               -v "$(pwd)"/work:/home/jovyan/work \
               -e AWS_ACCESS_KEY_ID='<your_aws_access_key>' \
               -e AWS_SECRET_ACCESS_KEY='<your_aws_secret_access_key>' \
               jupyter/pyspark-notebook
 ```
 - Copy generated link and paste it into the browser.
 - Go to work folder

 ## License
[MIT](https://choosealicense.com/licenses/mit/)