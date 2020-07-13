# Pokemon_Map_Folium
Data Frame source: https://www.kaggle.com/kveykva/sf-bay-area-pokemon-go-spawns  
API Source: https://pokeapi.co/

the data is to show the Pokemon that spawns in San Francisco Bay area, using the latitude and longitude included in the .csv provided by"kveykva" https://www.kaggle.com/kveykva/sf-bay-area-pokemon-go-spawns  

I limit to only show 3000 Pokemon at a time due to my hardware limitations  
changing the number in Line 11 will change the number of Pokemon to show up at one time   

mycode:  
```toiter = dffinal.sample(3000).values```  
can be changed into:  
```toiter = dffinal.sample(ENTER NUMBER HERE).values```  


the "#" code is the code that is not used, but i kept just in case I ever needed it  
the map is not rendered on on GitHub, but you can see the map at https://nbviewer.jupyter.org/  
just paste my Repo link
