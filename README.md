# Web Scraper

<h2>Description</h2>
Creating a webscraper to better my skills with python and practise data collection
<br />


<h2>Utilities Used</h2>

- <b>Python 3</b> 
- <b>Windows 10 desktop</b>

<h2>Program walk-through:</h2>

<p align="center">
Fist install beautifulsoup which is an HTML parsing library: <br/> 
<img src="https://i.imgur.com/LLiyv1t.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Importing the libraries needed. BeautifulSoup for HTML parsing and "requests" which is used to make requests to web servers: <br/> 
<img src="https://i.imgur.com/X4eRGcv.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Using the webside quotes.to.scrape.com I'm wanting to scrape the quotes and the authors. First I have to identify how these items are identified in HTML (The Quote and the Author): <br/> 
<img src="https://i.imgur.com/TDqQHEo.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Which you can do so using inspect element and checking the tags that are before and after the quote text. "Span class="text": <br/> 
<img src="https://i.imgur.com/vxCsyYG.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
And it's the same for the author: <br/> 
<img src="https://i.imgur.com/BX6jVfO.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Now on to writing the code for the scraper itself. In my initial attempt I forgot to install the requests library which resulted in an error among several other errors in my code that I have fixed after taking a closer look.: <br/> 
<img src="https://i.imgur.com/itjLrgc.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
With the request library installed, this is the correct output. Wowever I do not like the format, so I wll be fixing that: <br/> 
<img src="https://i.imgur.com/by7wbWa.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
I want the author and the quote to be side by side so that there's no confusion on who said what. Which you do by combining the loop (I personally like the name to be on the left): <br/> 
<img src="https://i.imgur.com/J4EIi5c.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
What is happening: <br/> 
<img src="https://i.imgur.com/M9fZFjR.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

