# phoneNumberInfo

### Description

This code uses some python libraries in order to get some certain information about a phone number which are:

- [phonenumbers](https://pypi.org/project/phonenumbers/): this library was used to get the phone numbers Country, Carrier name and timezone.
- [geopy](https://geopy.readthedocs.io/en/stable/): module used to get the longitude and latitude for the country associated to the phone number.
- [timezonefinder](https://pypi.org/project/timezonefinder/): to get the time zone of the longitude and latitude of the country.
- [pytz](https://pytz.sourceforge.net/): helps to perform accurate datetime calculations across different time zones.
- [tkinter](https://docs.python.org/3/library/tkinter.html): used for the graphical user interface(GUI)

### Tips

- After downloading this repo locally, in order to have all the necessary packages assuming python is already installed, you need to run this command

  `pip install -r requirements.txt`

- Then you can run the _app.py_
- if you face any error using the app, its most likely from this part of the code, so all you have to do is to do more research on other _user_agent_ that can be used asides _myGeocoder_, but as at the time of posting this, everything was working fine.

  `geolocator = Nominatim(user_agent="myGeocoder")`
