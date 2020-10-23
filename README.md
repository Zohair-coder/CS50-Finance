# Finance

This is a web application designed to help people who are new to the stock market. It uses data from [IEX](https://iexcloud.io/) to check real stocks' actual prices. Users can sign-up to open an account and "buy" and "sell" stocks (not with real money). Everyone starts out with $10,000. Make smart investments and earn as much as you can!   

## Installation

* Clone this repository
* Install the dependencies by typing this in your terminal:
```
pip install cs50 flask flask_session requests
```

## Usage

* Register at [IEX](https://iexcloud.io/cloud-login#/register/)
* Start your free plan
* Under the API Tokens heading, click the clipboard icon to copy the key (beginning with pk_)
    * if on Linux/Mac, execute `export API_KEY=<your-key>` in the terminal (replacing <your-key> with the key you copied)
    * if on Windows, execute `set API_KEY=<your-key>` in the terminal (replacing <your-key> with the key you copied)
* Go to the project folder and execute `flask run`
* Click the hyperlink provided in the terminal and enjoy!

## Screenshot

![website-screenshot](https://i.imgur.com/oQCA5BC.png)


For more information, go to: [CS50 pset8](https://cs50.harvard.edu/x/2020/tracks/web/finance/)