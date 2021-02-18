# selenium_python_automation
Scrap and Automate things using selenium web driver using python...


# Installation Of Selenium in Python.

### prerequisite
1. python 
2. selinum
3. browser driver

## Selenium Installation Step
1. Open terminal and write command python --version.
2. write command pip install selenium or in case of python3 write pip3 install selenium.
3. write pip list it will show all module that are install in python.
4. In case have any error take help from this link https://selenium-python.readthedocs.io/ 

## Selenium Chrome Browser Installation in Ubuntu
1. open terminal and write command whereis google-chrome it will show google chrom path that is install or not like.
    ```
    whereis google-chrome
    google-chrome: /usr/bin/google-chrome /usr/share/man/man1/google-chrome.1.gz
    
    ```

3. write command for install browser driver for python-selenium binding

    ```
    $ LATEST=$(wget -q -O - http://chromedriver.storage.googleapis.com/LATEST_RELEASE)
    $ wget http://chromedriver.storage.googleapis.com/$LATEST/chromedriver_linux64.zip
    $ unzip chromedriver_linux64.zip && sudo ln -s $PWD/chromedriver /usr/local/bin/chromedriver
    
    ```
    
4. Try below Example to open 'http://www.google.com/' in google-chrome browser:
    ```
    from selenium import webdriver

    browser = webdriver.Chrome()
    browser.get('http://www.ubuntu.com/')
    ```
here is the link for firefox driver https://askubuntu.com/questions/851401/where-to-find-geckodriver-needed-by-selenium-python-package

