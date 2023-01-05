# Wowmedia Application

As mentioned in mini task performs JWT authentication and allows user to send images through an api with throttle limit of 5 request per minute.

This App is Hosted in GCP

# Application Guide

<b> Default start 

![Screenshot (159)](https://user-images.githubusercontent.com/46764087/210887754-8a2e245f-61a7-4459-8e08-aba7bbaf09b1.png)

<b> -> User Registration

![Screenshot (160)](https://user-images.githubusercontent.com/46764087/210888973-5f6a6a4e-a5e7-43a6-8a06-7379c95e72bb.png)

In the above screenshot we can see on successfull registration user recieves an access code (authentication token) and 
a refresh code (for use when authentication code expires).
Note: Authentication Token generated expires within 5-15 minutes.

<b> View All Users available

![Screenshot (161)](https://user-images.githubusercontent.com/46764087/210890180-8b70667c-3de1-46e3-8300-a1f060d3be8e.png)
For checking all the Users registered in database we can use the following url, Here is the live working:

<b> User Login - After Login user recieves fresh set of tokens

![Screenshot (160)](https://user-images.githubusercontent.com/46764087/210889873-dcd13a71-c581-4750-a5b9-9c0b5f6d2af2.png)

<b> Remove all available users

![Screenshot (163)](https://user-images.githubusercontent.com/46764087/210890532-7e83545f-368f-4f55-89c3-45de9d41ffc3.png)

<b> User Logout/Revoke Access

![Screenshot (164)](https://user-images.githubusercontent.com/46764087/210890732-1f7fb618-9618-4b18-bfcc-4ecc3534a545.png)

<b> Refresh Access Token - In order to refresh access token

![Screenshot (167)](https://user-images.githubusercontent.com/46764087/210891299-b1df29fd-668c-4a7a-8f8a-9d2f17dc8174.png)

<b> Image Upload

![Screenshot (165)](https://user-images.githubusercontent.com/46764087/210899359-45bb62e4-4f2e-4720-aeba-2075b5b0e835.png)

As throttle limit is 3 request per minute. If we exceed the limit it will display following error:

![Screenshot (166)](https://user-images.githubusercontent.com/46764087/210899435-96846ad6-06cf-4427-be6f-9a539bdf61c4.png)

# Conclusion:

Hence the task is completed, looking for your reviews.

All the micro services importable postman collection is present in repository.

In case you wish to run the code on your system, simply clone the code and install requirement.

For Windows execution of Code commands:

set FLASK_APP=run.py

set FLASK_DEBUG=1

flask run

For Linux execution of Code:

sudo Python3 run.py
