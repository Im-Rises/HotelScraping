# hotel_scraping

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="pythonLogo" style="height:50px;"/>
  <img src="https://clipground.com/images/selenium-logo-7.png" alt="seleniumLogo" style="height:50px;"/>
  <img src="https://user-images.githubusercontent.com/59691442/163533189-eca49767-276c-45d7-910b-e955b7e2856e.svg" alt="plotlyDashLogo" style="height:50px;"/>
  <img src="https://user-images.githubusercontent.com/59691442/163533178-17e9e8bf-d844-41d5-a1f2-4ca06316793e.svg" alt="pythonanywhereLogo" style="height:50px;"/>  
</p>  

## Description

Scraping project made in python using selenium.  
Project main goal is to scrap data from different website for study.
The python scripts create bots that navigate through the different hotels' website (hotels.com, booking, trivago and
kayak). It will use the research system, and it will scrap all hotels' data on every available pages (the data gathered
are stored into different csv files, one csv file for each website).  
Those data can be used by the GUI app website to search for the hotel that best suit you or for analysis.
There is specific section on the gui app that allow you to study the price of the hotel and locate them on a map.

## Scraped websites

- hotels.com
- booking.com
- trivago.fr
- kayak.fr

## Hotels' data gathered

- Name
- Address
- Price
- Number of stars
- Coordinates
- Number of persons (adults, children)
- Number of chambers

## GUI application

We implemented a GUI application made in dash and hosted on pythonanywhere : http://maaelle.pythonanywhere.com/

The website is in French. No english translation has been made.

### GUI source code

The code of the GUI available in this repository
at https://github.com/clementreiffers/HotelScraping/tree/main/HotelScraping/website isn't our final GUI, it was only a
test before coding it using Dash Python.

So if you want to check the code of the GUI, you need to go there :

https://github.com/maaelle/InterfaceHotel

### GUI description

On the website you can search a hotel by different characteristics. You can also summarize check the mean and variance
price per month of all the hotels.  
Giving you information about the most expensive month for sleeping at the hotels.

### GUI Images

| Main page                          | Research page                      |
|------------------------------------|------------------------------------|
| ![Image1](Readme_files/image1.png) | ![Image2](Readme_files/image2.png) |

| Statistics page                    | Map page                           |
|------------------------------------|------------------------------------|
| ![Image3](Readme_files/image3.png) | ![Image4](Readme_files/image4.png) |

## Other sources

The source code of the website can be found here :  
<https://github.com/maaelle/InterfaceHotel>

Flutter GUI prototype project :  
<https://github.com/clementreiffers/hotel-scraper-interface>

## APIs

Selenium :  
<https://www.selenium.dev>

Pythonanywhere :  
<http://maaelle.pythonanywhere.com>

Dash :  
<https://plotly.com/dash/>

<center>
  <img src="http://ForTheBadge.com/images/badges/built-with-love.svg">
</center>

## Contributors

Quentin Morel :

- @Im-Rises
- <https://github.com/Im-Rises>

Clément Reiffers :

- @clementreiffers
- <https://github.com/clementreiffers>

Maëlle Marcelin :

- @maaelle
- <https://github.com/maaelle>

[![GitHub contributors](https://contrib.rocks/image?repo=Im-Rises/hotel_scraping&max=3)](https://github.com/Im-Rises/hotel_scraping/graphs/contributors)
