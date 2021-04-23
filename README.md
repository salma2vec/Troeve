<img src="https://lh3.googleusercontent.com/12GECgYu8otu_llPsXo3WbYe2yM5dvTHdpxbwosnJ-fyIv0CgDj1MXrRzPO3Y4oI_0B5LET-4klR7XTaWx7soruoH4uEhM-YXubu8gBRECDnLeBEHlPi7y4FN-EgIMxmetv7n8V2aA=w2400"> 

# Abstract

### *Firstly, Who are IDPs?*

**According to the Guiding Principles on Internal Displacement, internally displaced persons (also known as "IDPs") are "persons or groups of persons who have been forced or obliged to flee or to leave their homes or places of habitual residence, in particular as a result of or in order to avoid the effects of armed conflict, situations of generalized violence, violations of human rights or natural or human-made disasters, and who have not crossed an internationally recognized border."**

Therefore, In layman's terms- An internally displaced person (IDP) is someone who is forced to leave their home but who remains within their country's borders. They are often referred to as refugees, although they do not fall within the legal definitions of a refugee.

They have been forced from their homes for many of the same reasons as refugees, but have not crossed an international border. Often persecuted or under attack by their own governments, they are frequently in a more desperate situation than refugees. 
They also **outnumber refugees two to one.** No international agency has a formal mandate to aid them. But, they are increasingly at the forefront of the humanitarian agenda. They are sometimes called ‘internal refugees’, but are more often known as internally displaced persons.

# Problem Statement

Internally displaced persons (IDPs) are among the world’s most vulnerable people and IDPs in several countries of the world pose serious challenges for humanity. In recent months, millions of people have been internally displaced in different parts of the world. As IDPs have not crossed an international border (as is the case of refugees), they have to find sanctuary inside their home countries and remain legally under the protection of their own government, even though their own government might be responsible for uprooting them.

Now, to truly comprehend the gravity of the situation - the number of such unfortunately uprooted communties, Let's also give the stats a glance. 

According to the Global IDP Survey, there are more than 13 million internally displaced persons in Africa, 5–6 million in Asia (including the Middle East), 3 million in Europe and 3–4 million in the Americas.
<center><img src="https://www.statista.com/graphic/1/268702/number-of-refugees-and-internally-displaced-persons-worldwide-since-2000.jpg" height="300px" width="600px"></center>
The statistics on internally displaced persons generally count only those who are
displaced by conflict and persecution. 

But, **millions more have been uprooted within their own countries by natural disasters.**

There are far too many IDPs who have been displaced for decades, often living in camps or with little access to mainstream services in urban areas. The overwhelming majority of internally displaced persons are women and children who are especially at risk of abuse of their basic rights. More often than refugees, the internally displaced tend to remain close to or become trapped in zones of conflict, caught in the cross-fire and at risk of being used as pawns, targets or human shields by the belligerents.

It is high time the entire international community addresses these problems: to ensure access to all IDPs and to find solutions for IDPs as soon as is practicable. As a particularly vulnerable population, the fate of IDPs rests with the strong commitment of the international community to work with governments to ensure adequate protection, assistance and solutions. Hence,this cause calls upon all to cooperate with each other to help address these needs pursuant to the "collaborative approach".

# Proposed solution 






# Technical details
## Parts
The project is divided into 3 parts:

### 1. Cloud
The data (geolocations) of the IDP camps will be stored in a firebase database. The read, write and fetch functions on the firebase database and calculation of distance and nearest camp is done in the cloud.

### 2. User/Victim’s side
The user side application can be used in Online as well as offline modes(Usually, there are connectivity uses after natural calamities).
|  Online Mode                                         |                            Offline Mode      |                         
|:----------------------------------------------------:|:--------------------------------------------:|
| The online mode captures the geolocation of the user and sends it to the cloud VM. It directs the user to the nearest IDP Camp using Google Maps after receiving  the coordinates from the cloud.| The offline mode sends the current GPS coordinates to the SMS base station via a SMS message and shows the route directions to the nearest IDP camp.|  

### 3. SMS Base station
The SMS Base station receives the GPS coordinates of the user via SMS and sends it to the cloud. Since we are well aware of the fact that the user is offline, we are fetching route directions and sending it back via another SMS.


# Ease of deployment 


# Scope
Since ours is an emergency based application platform, we are planning to have a tie up with the government or a local NGO ready to help during these dire calamities.
## Modifications:
- In further versions of the project, we aim to develop the application for Kai OS and other feature phones to ensure that they are not deprived of their cardinal right to **Basic Humanitarian Assistance.**
- Backend Modification and implementation of load balancing to make Troeve available to more number of users at a time.

# Business model
