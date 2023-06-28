Putting the basics of Scrapy here. Maybe later will add a project.  
Had to upgrade pip:  
```
python -m pip install --upgrade pip
```
And use requirements.txt:  
```  
pip install -r requirements.txt  
```  
To start a project in scrapy:  
```  
scrapy startproject <name of the project>
```


We have then a new folder where you can set your spider. Each spider will have items (where you set the class,the API requests etc), pipelines (where you make the connection with the chosen storage for your data) and middleware (where you set configuration, runtime limits, etc).
