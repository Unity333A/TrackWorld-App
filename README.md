# TRACKWORLD APP (Tracking certain real-world phenomena around the world)

PLATFORM: ANDROID/IOS (CROSS-PLATFORM)

TOOLS: TKINTER(PYTHON) AND OTHER PYTHON LIBRARIES AND CERTAIN APIs

LANGUAGE: PYTHON

# ABSTRACT

In this period of continuous developments around the world, sometimes it becomes difficult to keep track of important things. So, in order to keep track of important international news around us, keeping track of the current price of crypto coins and others we propose to build an app upon it in Python. The main features of the app are-

(a)Important news around the world

(b)Current price of crypto coins

(c)Sending bulk sms to individuals

(d)Tracking the current location of the phone

# APP FRAMEWORK:

This app is built in Python using a special GUI app development framework called Tkinter. In order to implement the above-mentioned features, we are using certain API servers and accessing those into our program using API keys. The other Python packages used in this app are-

(1) Requests

(2)Datetime

(3)Socket

(4)Geocoder

(5)Json

# FEATURE DEVELOPMENT IN THE APP:

(A)Important news around the world

For the development of this feature, we use the Python package request along with a NEWS API. After generating the API key we extract the news with the help of a request from the API server and display it in the app.

#[image](https://github.com/Unity333A/TrackWorld-App/assets/107807858/19674944-dd65-484e-8f25-817ea96ad196)


(B)Current price of the crypto coins

In this case, we use the request module to parse the information provided by the crypto coin API server and display the information in the app. We also use a Python package called datetime to track the current time of the crypto coin prices. Here, we use a method of canvas called after to update the price of the bitcoin at the interval of every 1000ms.

![image](https://github.com/Unity333A/TrackWorld-App/assets/107807858/d233ff4a-bd3b-4674-b7c0-cc241d922b17)


(C)Sending bulk SMS to individuals

At first, we need to create an API on a SMS server called Fast2SMS and then by requesting the server with the recipient’s phone number and the requisite message we can send the respective message to the individual. In this case, we are sending the data to access the server in the form of a dictionary which is consisting among other things the recipient’s phone number and the message.

![image](https://github.com/Unity333A/TrackWorld-App/assets/107807858/9f5567a9-1921-4e79-96ca-061eebf0655f)

(D)Tracking the current location of the phone

In this case, we use a Python package called geocoder to get the location of the phone by using the IP address of the phone.
![image](https://github.com/Unity333A/TrackWorld-App/assets/107807858/fc322e31-5460-419a-969c-661e56ba7e28)
