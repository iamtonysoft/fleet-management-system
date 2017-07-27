# Fleet Management System

**What features we need to have for our kick starter?**

**Initial Features:**
- Real-time Tracking
- Route History
- Fleet Maintenance
- Monitor Idling


**Extended Features:**
- Real-time Over Speed Alerts
- Anti-Tamper Alert
- Prevent Cargo Theft
- Door Monitoring
- Stop Fuel Theft
- Anti-theft Device
- Eliminate Side Trips


**What do we need to materialize?**
1. We need to choose a GPS Tracking Device to be used for our Fleet Management System.
2. We need to find a specific vendor that can give us the functionality we need for our own system via integrating the GPS Tracking Device capabilities.
3. Our initial costing.
4. Learn about our competitors.


**List of competitors here in the Philippines**
- [Manila GPS Trackers] (https://manilagpstrackers.ph)
- [Globe MyBusiness Tracker] (https://mybusiness.globe.com.ph/mybusiness-tracker/)
- [Tramigo GPS] (http://tramigogps.com/)
- [Remora Tracker] (http://www.remoratracker.com.ph)
- [Phil Track] (http://login2.philtrack.com/home/)
- [Car Track Fleet Management For Vehicle] (https://www.cartrack.com.ph/fleet-management-for-vehicles/)


## GPS Tracking Device Costing

**Things to consider on buying a device**
1. Overview of the functionalities.
2. Costing, if we are going to buy a cheap one and we can lessen around 1000-2000 pesos per device on each vehicles but we cannot extend the functionalities of our own system because it will rely on the device capabilities.


**List of available devices and cost**
- Plug and play GPS Tracker OBD Port – (price range from 4000 up to 5000 pesos)
- GPS Real-time Tracking Device and Alarm RF - V9 (price 2480 pesos)
- GPS Vehicle and Personal Tracker, Quad Band M142 (price 3480 pesos)
- GPS Vehicle Monitor Tracking System FK001C (price 4980 pesos)
- GPS Vehicle Tracking Device M104 Black (price 6280 pesos)
- GPS Vehicle Tracking Device M104 with Engine Cut-OFF (price 4980 pesos)
- GPS Vehicle Tracking Device M133 (price 4380 pesos)


**List of vendors for GPS Tracking Device**
- [Goodhand88] (http://goodhand88.com/shop/index.php?route=product/category&path=84)
- [Dychitan] (http://dychitan.com/)

## Additional Device for System Monitoring (GSM Modem) Sending and Receiving SMS

- Wavecom Fast Track GSM Modem (price range 2800 to 3000 pesos)

## Web Based Application

- Programming Language: PHP (Tentative)
- Scripts: Webpack, ExpressJS

**Things to consider where to deploy the application (Domain Registration/Hosting)**

**Outsource:**
1.	Monthly / Yearly Subscription
2.	Web Traffic Cost (Maximum Allocated Bandwidth) it will depend on how many users will connect through our application. (Included in the bundle but might get additional charges if exceed)
3.	99% Uptime. No Maintenance Cost.

**Internal:**
1.	Installation Cost
2.	Network Hardware Device Cost
3.	Server & Maintenance Cost


## For Web Domain Registration/Hosting

**Source:** [Phalcon PHP Hosting] (https://phalconphp.com/en/hosting)

- Amazon Web Services: (price depends on what type of service)
- ASPnix: (price ranging from $15 to $35 / Year)
- DigitalOcean:  (price ranging from $5 to $80 / Year)
- Fortrabbit: (price ranging from $5 to $30 per App Monthly)
- Linode: (prince ranging from $5 to $80 / Month)
- WebFaction: (price ranging to $10 to $240 / Month)
- Windows Azure: (price ranging to $13 to $261 / Month)

**Note: There are some hosting provider that does not include a domain name registration so it might be different on the actual cost. Of course I will prefer that we will purchase a bundle that includes both. On purchasing a web hosting first we will purchase a small bundle then we scale up our bundle subscription as we scale up our system.**

## How this thing works?

- Once we acquire a GPS Tracking Device we need to install it on the vehicle. The device must also have a sim card installed. On initial testing there are commands (built-in on the device) that we can send through sms and the device will send us back a message about its location (coordinates Latitude and Longitude). Now on integration on our system application (web based) we also need a device connected to the computer that can receive a sms which is the use of gsm modem then the system application will save its received information through our database and also to have a history of its previous locations.

## Google Maps Usage

**Standard Usage Limits**

- Free until exceeding 25,000 map loads per 24 hours.
- After exceeding the free usage limits, billing at $0.50 USD / 1000 additional requests, up to 100,000 per 24 hours.

**Premium Usage Limits**

- Depends on plan that we will avail and applications we need (ex. JavaScript API, Mobile SDK, Street View, Geocoding API, Map Directions API)

**Source:** [Google Maps Premium] (https://developers.google.com/maps/premium/calculate-credits)

