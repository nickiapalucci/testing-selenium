# testing-selenium
#### Proof of concept tests of the Selenium WebDriver in as many web drivers as possible

## Installation
Requires Python 2.7.5 and pip

Run this command from the root of this repository (and within a virtualenv if you wish)<br>
`pip install -r requirements.txt`<br>
Additional drivers are currently commited in the Drivers directory

You must have an up to date version of each web browser installed in a standard location for each test to work

All tests can be run from a command line

These files are based on the examples [here](http://www.seleniumhq.org/docs/03_webdriver.jsp#selenium-webdriver-s-drivers)

## Chrome test
#### Opens a new chrome browser and creates a search for "cheese!"

Run this command from the root of this repository:<br>
`python selenium2ExampleChrome.py`

A new browser window will open and close quickly.  Back on the command line you should see:<br>
`Google`<br>
`cheese! - Google Search`<br>

## Firefox test
#### Opens a new firefox browser window and creates a search for "cheese!"

Run this command from the root of this repository:<br>
`python selenium2ExampleFirefox.py`

A new browser window will open and close quickly.  Back on the command line you should see:<br>
`Google`<br>
`cheese! - Google Search`<br>

This will sometimes trigger the creation of or additions to `geckodriver.log`
