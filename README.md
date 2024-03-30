# **Glassdoor-Web-scraping-Using-Selenium**

# Data Jobs in Morocco: Glassdoor Web Scraping Using Selenium

This repository contains a Kaggle Notebook that demonstrates how to scrape data job listings in Morocco from Glassdoor using Selenium. The notebook utilizes Python libraries such as BeautifulSoup, pandas, and Selenium to extract job details and save them into an Excel file.

## Dependencies

To run the notebook, please follow these steps:

### **Update & Fix (for Linux and macOS):**
```
!apt-get update -y
!apt-get install -y \
!apt --fix-broken install -y
```
### **Install Google Chrome**
#### For Linux:
```
!wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
!dpkg -i google-chrome-stable_current_amd64.deb
!google-chrome --version
```
#### For Windows and macOS:
* Download and install Google Chrome from [here](https://www.google.com/chrome/).
  
### **Install Chromedriver**
* Make sure that google chrome and the chrome driver have the same version.
  
#### For Linux:
```
!wget https://edgedl.me.gvt1.com/edgedl/chrome/chrome-for-testing/121.0.6167.85/linux64/chromedriver-linux64.zip	
!unzip chromedriver-linux64.zip -d /usr/local/bin/
```
#### For Windows and macOS:
* Download the appropriate Chromedriver version for your operating system from [here](https://chromedriver.chromium.org/downloads).
* Extract the downloaded file and move the chromedriver executable to a directory included in your system's PATH.
  
### **Install selenium library (for all operating systems):**
```
!pip install selenium
```

## Usage

Simply execute the notebook cells to scrape data job listings from Glassdoor in Morocco. The notebook will extract job details such as company name, job title, location, and job description and save them into an Excel file.

## Disclaimer

Please note that web scraping may be against the terms of service of some websites. Ensure compliance with relevant guidelines and laws before scraping any website.

## Author

This notebook was created by Toufik B. for educational and demonstration purposes.

Happy scraping! 🚀
