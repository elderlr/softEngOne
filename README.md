# softEngOne
Utilize the .py file for your image searches. 

#code made by Laura Elder
# I used the following sources:
#[1] https://www.geeksforgeeks.org/image-scraping-with-python/

import requests
import json
import demjson
from bs4 import BeautifulSoup

Include the above packages in your code
This will crate a JSON file at your specified location.
Function call = pullSaidImage_give(search_term, location)

example of a function call:
pullSaidImage_give("blue",'C:\\Users\\Laura\\source\\repos\\SoftwareOneWebPage-LauraElderStocks\\images.json')

Example of JSON file structure:
"[{\"Link\":[\"https://mc.yandex.ru/watch/38325715, http://static.everypixel.com/ep-libreshot/0864/3067/9846/09463/8643067984609463587.jpg, https://images.unsplash.com/photo-1590421960980-153d3cd2f78c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTI4NzN8MHwxfGFsbHw2MzI2Mnx8fHx8fDJ8fDE2MTYwNzY4MTM&ixlib=rb-1.2.1&q=80&w=400\"]}]"
