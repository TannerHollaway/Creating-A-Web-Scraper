# Web Scraper

<h2>Description</h2>
Creating a very simple web scraper to better my skills with Python and practice data collection.
<br />

<h2>Utilities Used</h2>

- <b>Python</b>
- <b>Windows 11</b>
- <b>quotes.toscrape.com</b>

<h2>Program Walk-through:</h2>

<p align="center">
First, install BeautifulSoup, which is an HTML parsing library: <br/> 
<img src="https://i.imgur.com/LLiyv1t.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Importing the libraries needed: BeautifulSoup for HTML parsing and requests, which is used to make requests to web servers: <br/> 
<img src="https://i.imgur.com/X4eRGcv.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Using the website quotes.toscrape.com, I want to scrape the quotes and the authors. First, I have to identify how these items are marked up in HTML (The Quote and the Author): <br/> 
<img src="https://i.imgur.com/TDqQHEo.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
You can do this using the inspect element tool and checking the tags that are before and after the quote text, such as "Span class='text'": <br/> 
<img src="https://i.imgur.com/vxCsyYG.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
And it's the same for the author: <br/> 
<img src="https://i.imgur.com/BX6jVfO.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Now on to writing the code for the scraper itself. In my initial attempt, I forgot to install the requests library, which resulted in an error, among several other errors in my code that I have fixed after taking a closer look: <br/> 
<img src="https://i.imgur.com/itjLrgc.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
With the requests library installed, this is the correct output. However, I do not like the format, so I will be fixing that: <br/> 
<img src="https://i.imgur.com/by7wbWa.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
I want the author and the quote to be side by side so that there's no confusion about who said what. You can achieve this by modifying the loop (I personally like the name to be on the left): <br/> 
<img src="https://i.imgur.com/J4EIi5c.png" height="80%" width="80%" alt="Web Scraper"/>
<br />
<br />

<p align="center">
Done!: <br/> 


