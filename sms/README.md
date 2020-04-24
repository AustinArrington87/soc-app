# soc-app
Soil organic carbon (SOC) calculator - Flask/Twilio web app

This Flask app handles SMS/MMS data using the Twilio api.  

The farmer texts an image of soil taken from the field, on the backend a computer vision algorithm runs to estimate SOC based on image hue, and the farmer recieves a SOC prediction back.

To run the script locally: 

Change file paths
Download ngrok 
Run the script and activate ngrok
Input the ngrok URL in Twilio's SMS webhook field