# testing-selenium
Proof of concept tests of the Selenium WebDriver in as many web drivers as possible

## Installation
Will eventually be as standard as<br>
`pip install requirements.txt`<br>
But for now, one can use the additional drivers currently commited in the Drivers directory

You must have an up to date version of each web browser installed in a standard location for each test to work

All tests can be run from a command line

These files are based on the examples [here](http://www.seleniumhq.org/docs/03_webdriver.jsp#selenium-webdriver-s-drivers)

## Chrome test
Opens a new chrome browser and creates a search for "cheese!"

Run this command from the root of this repository:<br>
`python selenium2ExampleChrome.py`

A new browser window will open and close quickly.  Back on the command line you should see:<br>
`Google`<br>
`cheese! - Google Search`<br>
