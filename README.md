# Google-Distance-Matrix--python
This is a simple python script which makes request to Google Maps API, pulls data from it and displays them.

User has to provide origins and destinations in a comma separated format.   
Please Note: All the origins and destinations should belong to the same country.    
    
Example:      
                      
    Enter origins: bangalore, chennai      
    Enter destinations: delhi, kolkata, mumbai

Have a look at the sample screenshot.

To make a request you need to have an API Key which you can get from https://developers.google.com/maps/documentation/distance-matrix/

If you want to get more details about how this API works then please refer the documentation https://developers.google.com/maps/documentation/distance-matrix/start
  
# Limitations
- As per Google's Terms and Conditions you can make 2500 free requests per day.
- Maximum of 25 origins or 25 destinations per request.

For more details about usage limits please refer : https://developers.google.com/maps/documentation/distance-matrix/usage-limits

In the script:
- Travelling mode is set to Driving
- Departure time is set to Current Time
- Traffic model is set to API default i.e, best_guess.  

However you can make changes to the above parameters and accordingly change the display part.

To stop the script press Ctrl + Z or Ctrl + C.

Python version : 3.4    
HTTP Client : requests ( pip install requests )   
Refer the documentation : http://docs.python-requests.org/en/master/


Improvements are always welcome.
