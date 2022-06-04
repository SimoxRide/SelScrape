# SelScrape
A simplification of the selenium module for webscraping. Based on selenium

To Install:

```python
pip install SelScrape
```

1)Instantiate SelScrape
```python
import SelScrape
From SelScrape import SelScrape

Scrape=SelScrape("YOUR_WEBDRIVER_EXECUTABLE_PATH")
Scrape.Open()

```
2)Navigate to target site
```python
Scrape.NavTo("URL")
```
3)Scrape
```python
Data=Scrape.Get_Element_By_xpath("XPATH")
Data2=Scrape.Get_Element_By_Tag("TAG","ATTRIBUTE","ATTRIBVALUE")
#Scroll to element
Scrape.ScrollToElementXPATH("XPATH")
Scrape.ScrollToElementTag("TAG","ATTRIBUTE","ATTRIBVALUE")
#WaitElementLoad example Scrape.WaitElement(5,"//div/div[1]")
Scrape.WaitElement(TICK,"XPATH")
Scrape.WaitElementTag(TICK,"TAG","ATTRIB","ATTRIBVALUE")

```
