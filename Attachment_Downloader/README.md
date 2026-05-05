# Attachment Downloader

The script downloads gmail atttachment(s) in no time!


# Setup Instructions

The script uses ezgmail module (to know more visit https://pypi.org/project/EZGmail/). To install please type the following command in your bash.

```bash
pip install EZGmail
```

Once the module is installed you will need to download credentials.json file by going to [developers.google.com](https://developers.google.com/gmail/api/quickstart/python) and clicking the Enable the Gmail API button (select "Desktop app" as OAuth Client in second step).

Once you have credentials.json (in root directory of project folder), the first time you run the script it will open up a browser window asking you to log in to your Gmail account and allow "Quickstart" app to access it. A token.json file will be generated (in root directory of project folder) which your script can use to access your account.
