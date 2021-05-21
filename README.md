# checkvaccineslot


|  Author 			: Partha Roy
|  Date Created 		: 21-May-2021
|  Version			: 1.0.0


This application checks for available vaccine slots as per your search criteria every 5 mins and sends a WhatsApp message to your primary and alternate phone numbers.


Steps:
******

1. Open file index.html in any text editor and change the following configuration parameters

2. "district_id" - Change the district id to your district 

3. Change value for "minAgeLimit" value : 18 for 18+ group, 45 for 45+ group

3. Steps to get your district id:

		1. Go to https://www.cowin.gov.in/home
		2. Use the "Check your nearest vaccination center and slots availability" feature in the home page
		3. Select "Search by District"
		4. Select State and Select Disctrict
		5. Right click on the page and select "Inspect" or Ctrl+Shift+I
		6. Go to "Netwrok" tab
		7. Hit Search button in the web page
		8. Notive traffic getting recorded e.g. https://cdn-api.co-vin.in/api/v2/appointment/sessions/public/calendarByDistrict?district_id=725&date=20-05-2021
		9. Note: district_id=725, 725 is the district id for your search


3. Register your primary and alternate phone numbers in call me bot portal by following the steps in this page: https://www.callmebot.com/blog/free-api-whatsapp-messages/

4. Change the following values:
		phonenum = '+91xxxxxxxxxx' - Enter your primary phone number
        apikey = 'xxxxxx' - Enter your api key for primary phone number
        sendToAltPhoneNum = true - Keep as true if you want to use an alternate phone number, else change to false
        alt_phonenumber = '+91xxxxxxxxxx' - Enter your alternate phone number
        alt_apikey = 'xxxxxx' - - Enter your api key for primary phone number
		
5. Save the file and close

6. Click on index.html file and open in browser

7. Keep it open in a browser tab and get on with your regular work

8. If slot is available for your search you will receive a message in Whatsapp from the CallMeBot phone number. Keep the number saved in your phone during setup


STAY SAFE AND ALL THE BEST!!!!!!!!


