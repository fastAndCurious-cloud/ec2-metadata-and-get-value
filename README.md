challenge 2 and 3

# Challenge2 **EC2-Metadata And Get-data-Value from key**
# Challenge3 **Get-Value from nested objects**

## Requirement
- Get the metadata of ec2 instance within AWS and provide a json formatted output.
- A function in which pass the object and a key and get back the value

## How to use this code

Follow the below instructiosn to Run this code:

## Installation on AWS Linux servers(Considering already logged in to linux ec2 instance)

- Install Python 3 and git on your instance 
    - `sudo yum install python3 git`
- Clone this repository
  - `git clone https://github.com/fastAndCurious-cloud/ec2-metadata-and-get-value.git`
- Install below
  - `sudo pip3 install pipenv`
  
- Go to repository directory on your instance
  - `cd ec2-metadata-and-get-value`
- Install project dependencies
  - `pipenv install`
- Go to `src` directory
  - `cd ec2-metadata-and-get-value/src`
  - `pip3 install requests`
  
- Run Challenge2 Script:
  - `python3 get_ec2_metadata.py`
  - `python3 get_data_key.py`

- Run Challenge3 Script:
  - `python3 get_value.py`
  
## References from stackoverflow,google
