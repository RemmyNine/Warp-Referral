import requests
import time
import json
# inster amount of data you want here:
_yData = 150
# inster your userID here -- find it in: settings -> more settings -> diagsnotic  
_userID = " PUT YOUR ID HERE"

def cfref():
    return requests.post("https://api.cloudflareclient.com/v0a745/reg", data=json.dumps({"referrer": _userID}))


for i in range(_yData):
    _res = cfref()
    _json_res = _res.json()
    print("Submited!  {} Gigabyte Amounf Of Data Submited ".format(i+1))
    if (i+1)%3 == 0:
        time.sleep(60
