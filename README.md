# python-tuned-sentiments
A basic sentiment analysis of the top songs of the 21st century. 
This code uses the NRC emotion lexicon library to show the sentiments and emotions associated with the top songs of 2019. It also compares these sentiments and emotions across some popular genres of songs of the 21st century and depicts how these have been changing over time. Additionaly, it predicts these trends for the next 10 years.

## Installation
To run this project, you will need an authentication key for the API call used, which can be created by registering on [musixmatch.com](https://developer.musixmatch.com/).

Enter this authentication key in the "params\["apikey"\]" in the first code block.
Enter the local location of your project in the "filepath" variable.

Run the code.

## Disclaimer
This code uses scrapping of a captcha enabled site. Eventhough the code tries to prevent it, the site may block you as a scraper. You may need a bouncing VPN to run this code. 
In case you are unable to scrap the data, a real-time data is available under the "Scraped" folder. You can run the first code block followed by all the code blocks after "Cleaning | Word Processing | Sentiment Analysis" to get the results.

