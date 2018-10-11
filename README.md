

## DisasterAid 

### The problem we are trying to solve

Natural disasters tend to result in horrible loss of human life as well as tragic environment damage every other year. Once a disaster is over, all the people, who suffered from it, are in need of immediate help. The devastation from the hurricanes, tornadoes and tsunamis is so great that world community faces with the necessity to help the victims in many different ways. Natural disasters psychologically affect family members, friends and colleagues of the victims who are constantly looking for ways to find out the state of their loved ones. 

During the occurence of any disaster, the most difficult part is identifying the location and citizens affected, and coordinating the rescue team's efforts. Any application which addresses these will greatly reduce casualties.   

### Our solution
The application will actively monitor the Internet to detect probable occurences of disasters. News websites, social media sites and weather reports will be monitored to detect disasters, and add meta data about it (Disaster type, location, donation links etc) 

For each disaster detected, the application will create a new database to keep track of people. The database will be collectively maintained by reports from the victims, rescuers, bystanders, family etc. These reports can contain pictures, identifying traits, belongings, wounds, location etc. Each report will be marked with tags like (Missing - ![#ffa500](https://placehold.it/15/ffa500/000000?text=+) , Found- ![#00f000](https://placehold.it/15/00f000/000000?text=+) , Dead- ![#000000](https://placehold.it/15/000000/000000?text=+) , Unknown- ![#cccccc](https://placehold.it/15/cccccc/000000?text=+) etc). On top of the database, using facial recognition and NLP, the application will try to match different reports to figure out the status and identification of each person affected by the disaster. 

### Technologies we plan to use

| Component | Software |
|---------|:---------|
|Platform|Android|
|Facial Recognition|Azure Face API|
|Database|MongoDB|
|Backend Server | Linux|
|NLP|NLTK|
|Server language| Python|


