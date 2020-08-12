Inspiration

Per day 1.5m gallons of fresh cow milk from dairy farms, hundreds of tons of potatoes from farmers in Washington, and even more stock from poultry farms - hog, chicken, euthanized hen - have been crippled and thrown away as waste causing the “anarchic food supply chain” to. This fall is especially hard on minority accountings of immigrant farmers, who have been the worst hit due to their undocumented status that deprives them of any economic relief. As unemployment rates begin to rise due to Covid-19, there are more hungry mouths than ever. This is, no doubt, the toughest challenge the US has faced since the Great Depression.

In light of the current events, we stand in solidarity by the sides of those whose lives have been uprooted by unprecedented conditions as a result of Covid-19. We wanted to use our skills to find a way to give people and farms the tools they need to get food on the plates of those in need, rather than in the trash. Thus, Bytes 4 All was born.


What it does

So, to help farmers gain some relief “in this monopolistic corporate food system that’s designed for profit and market control, not for sustainable or equitable farming and eating” (The Guardian), our team came up with a website that connects food pantries, local farms, and volunteers.

Bytes 4 All inputs your email address, username, and password to log on or sign-up and then allows you to choose which type of user you are: farm, food pantry, or volunteer. The web application connects local farms to volunteers in the area to help get the extra food to local food pantries.


How I built it

We used Glitch to host our project. First, mockups were made in illustrator. Most of the work was done in the front end using HTML, CSS, and JavaScript (with jQuery). The backend was written in Python and used SQL connectivity to create an interface to the local station database. This was attempted using Django as the framework, although futile. A cloud-based database (Firebase, Heroku) was also attempted, but due to time restraint, the setup is incomplete as of now.

We also utilized ArcGis, working with maps and geographic information to display the availability of food when clicked on farms/pantries, and utilized user input data to determine the distance connecting farms to nearby pantries. This information is of major use to volunteers, to give them an accurate visual and numerical representation of the work that needs to be done on their end.


Challenges I ran into

One of the biggest challenges we faced was trying to connect our web app to the cloud. A key aspect of our web app is that it can connect users of all different types, from any location, which is only doable with a database interface like Firebase or Heroku; however, with the time restraints, we were unable to set up a database that could handle multiple types of users as well as food requests.


Accomplishments that I'm proud of

The team members, despite being from different countries (USA, India) and drastically different time zones, collaborated to create an awesome project. As beginners, we used this hackathon not only as a competition but also as a learning opportunity to use cool tools and play around with the unfamiliar technologies, like Heroku and ArcGIS, that we discovered while researching for the project.


What I learned

Remote collaboration skills, ArcGis, Heroku, and the devastating impacts of COVID-19.


What's next for Bytes 4 All

Since we believe Bytes 4 All can make a major impact on our communities, we plan on continuing with this project. We plan on reaching out to farms, as well as pantries to establish a user base. We want to integrate Google Firebase into our web app to establish user data sharing, like food requests and farm availabilities, to connect volunteers to local farms and pantries through the cloud. Also, we plan to add a scheduling feature so volunteers can pick time slots to volunteer at farms to help promote social distancing by adding a maximum limit of volunteers per time slot. We also plan to implement QR codes for hands-free check-ins that send an email to users. Finally, we plan to add location services to calculate distance from farms, pantries, and volunteers, so the web app can offer resources closest to the users.


Built With

css, esri, firebase, html5, javascript


Team Members

Anjali Kumar, Sriya Pidatala, Hunter Malinowski, Maniya Dahiya


Try it out

https://bytes4all.glitch.me/


Devpost Submission

https://devpost.com/software/bytes-4-all
