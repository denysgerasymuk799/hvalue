# HVALUE

Agenda  | 
------------- | 
[How to work in this repository](https://github.com/dsc-ucu-lviv/hvalue/wiki/How-to-work.-Instruction.)  | 
[Brandbook](https://github.com/dsc-ucu-lviv/hvalue/wiki/Brandbook)  | 
[Mockups](https://github.com/dsc-ucu-lviv/hvalue/wiki/Mockups)  | 
[Database architecture](https://github.com/dsc-ucu-lviv/hvalue/wiki/Database-architecture)  |


# The main problem

Nowadays, and especially the last days, many people and animals need help. Someone does not have home, work, earnings, family, sense of safety or access to medicine. That is why there are many orphanages, shelters, charitable organizations and so on. But how many people can actually remember about 2-3 such institutions in their hometown, and can help them? A few. Our solution to this problem was to help such organizations to spread the information about their needs. Moreover, we all have something that we may share with others like our kindness, time, food or clothes.


# Solution

Our solution has 3 main technologies:
- Database Firebase 
- Python Flask framework 
- Google API

First of all, we created a web application on Flask with registration, forms of adding receiving stations (places of collecting things donated by benefactor), login function for different charity organisations, animal shelters or orphanages etc. This app has skillful design, good reliability for user data protection, clarity and simplicity.

Secondly, this service was connected to Firebase, where we save the main information of every organization. Initially, we used Google Maps API for better visualization of receiving stations.


Our option of such technologies has several reasons. 

Flask is the most policed and feature-rich micro framework. It comes with all the benefits of the fast template, strong WSGI features, and extensive documentation.

From the database we needed good speed, saving any types of information and function tools. Hence, we chose Firebase, which provided all our requirements.

What about Google maps, so it is the most convenient and used service, with which to easily interact with our application.


# Guidance on how to run our code

1. Firstly, you should open our GitHub code and install dependencies from  requirements.txt.
2. After that you should run web_server/app.py and open the link of the running app. 

Windows:
```
pip install -r requirements.txt 
python web_server/app.py
```

UNIX:
```
sudo pip install -r requirements.txt
python3 web_server/app.py
```

3. After that you can see a page with receive stations of different organizations on map. You can filter showed stations by your purposes and interests. 
4. After you have chosen some organization on the map you can get the main information about its addresses of stations to reach them. Logging and registration of organizations can be accessed from the map page. For organizations, they can create their own receive stations for benefactors’ help. 

# License:
[MIT](https://choosealicense.com/licenses/mit/)
