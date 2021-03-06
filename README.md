# linkedin-email-extractor
### A node web scraper to extract your linkedin connection emails

## Important Note
Scraping data off of LinkedIn is against their [User Agreement](https://www.linkedin.com/legal/user-agreement). This is purely intended for educational purposes.

If you would like to know the process on making this script, you can read about it [here](https://dev.to/futoricky/how-i-made-a-web-scraper-script-because-linkedin-27fc)

## Why?
LinkedIn allows you to export all of your connections' info into a csv, except for their emails. 
Additionally their API stopped allowing the extraction of emails around 2013-2014. Why don't we have access to our connections emails through their data export if we both agreed to share that info/data?

## Installation
- Clone this repo `git clone https://github.com/FutoRicky/linkedin-email-extractor.git` or download
- Move into the repo directory `cd linkedin-email-extractor`
- Install dependencies `npm install`

## How to Use
- You will need the `Connections.csv` file that LinkedIn provides with the data export. 
  - [Instructions on how to export connections from LinkedIn](https://www.linkedin.com/help/linkedin/answer/66844/exporting-connections-from-linkedin?lang=en)
- Add the `Connections.csv` file into the `linkedin-email-extractor` directory
- Run `npm start` or `node --harmony index.js`
- Enter LinkedIn Credentials when prompted
- Wait for email extraction process to finish
- An `email.txt` file will be generated with all the emails inside the `stored_data` folder.
