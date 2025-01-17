Weather Dashboard Demo Setup

This project was put together by the CozyCloud Devops Crew, to build handson experience on the AWS Cloud Infrastructure.
It fetches near real time weather data from the OpenWeather API and stores it in an Amazon S3 bucket for access and analysis review in the future.

This application process was built using Python, the AWS SDK (which is boto3), integrating environmental variables to manage sensitive information like API keys and AWS credentials.

Things to know:
Before running this project, make sure you do the following:

i. Install Python 3.1 upwards
ii. Have an AWS account with CLI configured using access keys.
iii. Have a '.env' file with your OpenWeather API key and S3 bucket name.
iv. Import the necessary versions of boto3, requests, python-dotenv.

To Setup

Personally, i encountered a lot of debugging cause of uprising issues form my VS Code IDE, not until after roughly a week i tried again using the GitBash, and a litle bit of patience helped then i could finally conquer the boto3 installation process, and i got it finally.

Loved every process of this learnig phase! Kudos to CozyCloud Crew, Much Love! Cant wait for you to dive in. SEE YOU IN THE CLOUDS...

Don forget to Clone the repository:

   ```bash git clone https://github.com/Izudavo/Day1_CozyCloud_DevopsChallenge
cd weather-dashboard

