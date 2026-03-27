# Python Script to auto fill Google Forms

This is a python script which can helps you to fillout the google form automatically by bot.

## Steps to make it run

1. Clone/Download this repository
```
git clone clone_path
```
2. Downlaod the required packages 
```
pip install -r requirements.txt
```

3. To run the script you need to use the following command
```
python app.py
```

4. To run this script you need to have selenium installed and you nedd to have geckodriver.
you can downlaod geckodriver from here: https://github.com/mozilla/geckodriver/releases
After downloading the geckodriver, need to set-path for that as shown below:
```
webdriver.Firefox(executable_path=
'D:\Selenium_RiponAlWasim\geckodriver-v0.18.0-win64\geckodriver.exe')
```
### working
1. You can add or delete the records in .csv file.

2. Intially the number of responses in the google-form will be null(no-entries):
 screenshot is attached below:

3. After ruuning the script, the bot will automatically take the records from .csv file and it will will the form.
