# Excel-Executive-Sales-Report-For-An-FMCG-Company-Manager
<p align="center">
  <a href="[https://quotes-web-app.herokuapp.com/](https://github.com/KamgangAnthony/Excel-Executive-Sales-Report-For-An-FMCG-Company-Manager/blob/main/Photos/FullDeliveredMarginSalesAndVolumeAnalysis.png)">
    <img src="https://github.com/KamgangAnthony/Excel-Executive-Sales-Report-For-An-FMCG-Company-Manager/blob/main/Photos/FullDeliveredMarginSalesAndVolumeAnalysis.png" alt="Sales-Report-For-An-FMCG-Company-Manager">
  </a>
</p>


# Project Overview

* This report provides managers with information on sales volumes, revenue, and profit margins.
* It's for Drinko, a firm in the FMCG (fast-moving consumer goods) sector.
* Which items are the most profitable?
* Which packages do clients prefer?
* What is the ideal size that customers like to purchase?
* It also gives a monthly breakdown by customer, brand, size, and pack.
* These are the key indicators that the firm must comprehend in order to optimize its product offering and marketing mix.



## Resources Used


**Microsoft Excel**


**Data From the company**



## Scraping the quotes


I used an API command to scrape exactly 110 quotes at a time that were no more than 262 words long:


*    Aim for the moon. You might hit a star if you miss. --Stone, Clement


*    We can do anything we want to if we stick to it long enough. --Helaine Keller


*    You know you're in love when you can't fall asleep because reality is finally better than your dreams. --Dr. Seuss


*    ...and many others


## Classifying the quotations and taking care of the display


Getting the quotes, transforming them, and displaying them on the web app:


*    Got quotes using requests


* Converted them to JSON before converting them to a data frame of quotes and authors


* Analyzed the quotes using the SentimentIntensityAnalyzer


* Arranged them according to their feelings


* Developed the logic to display quotes that are lighter or darker depending on the user's swipe


## Page design


* Envato Elements is where I got the bottom graphics (paid)


* Used the website Canva to create the banner


* Handled the HTML and CSS for the quotes


* Swiping was made possible through Javascript code


<p align="center">
   https://quotes-web-app.herokuapp.com/
</p>
<p align="center">
  <a href="https://quotes-web-app.herokuapp.com/">
    <img src="picture4.png" alt="Logo" width=200 height=400>
  </a>
</p>


