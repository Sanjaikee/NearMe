# Ex04 Places Around Me
#Date: 12-04-24
## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.
### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish 

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageMap</title>
</head>
<style>
    *{margin: 0;}
</style>
<script>
    function coordinate(event)
    {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("Text1").value=x;
        document.getElementById("Text2").value=y;
    }
</script>
<body>

    <IMG src="![WhatsApp Image 2024-04-16 at 15 31 13_854b5ee9](https://github.com/Sanjaikee/NearMe/assets/150231888/19112091-d331-4625-81bc-3d4644a5870a)" width="1535" height="650" usemap="#MapNew" onmousemove="coordinate(event)">
        <MAP name="MapNew">
            <AREA shape="rect" coords="160,359,376,443" href="https://www.makemytrip.com/hotels/hotel-listing/?topHtlId=201712071752368734&city=CTMAA&country=IN&checkin=04132024&checkout=04142024&roomStayQualifier=2e0e&totalGuestCount=2&roomCount=1&cmp=googlehoteldfinder_DH_META_Paid_selected_IN_mapresults_201712071752368734&_uCurrency=INR&Campaign=20613919640&locusId=CTMAA&locusType=city&mtkeys=b1e79af8-c554-48b3-a52c-85fea70907c2&au=&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iBWH_sKzcQ-sYrPVV0CsKUtGbCrrPjzCzd6cFU2R0VyBaiO8_RWIQaAlTaEALw_wcB" title="Moon view beach resort">
                <AREA shape="rect" coords="406,278,536,332" href="https://www.agoda.com/search?campaignid=21176660567&searchdatetype=selected&lt=1&numberofchildren=0&childages=&gsite=mapresults&partnercurrency=INR&roomid=655899473&pricetax=330.62&pricetotal=3085.76&rateplan=937fa546-fec5-fcbc-2b5d-04f22c071a13&usercountry=IN&currency=INR&userdevice=desktop&verif=false&audience_list=&mcid=332&booking_source=cpc&adtype=1&push_id=CgYIgJbnsAYSBgiAueywBhgBIKDy7xIqDBgBKggiAggBKgIIBA%3D%3D937fa546-fec5-fcbc-2b5d-04f22c071a13_20240412_10&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5g7RTaTN6JjXjGwhXTSIBNj2jEWvioBiR5E6ERoIoKHIBOLpYgYDhwaAkeBEALw_wcB&los=1&adults=2&rooms=1&checkin=2024-04-13&checkout=2024-04-14&selectedproperty=39581984&city=17269&cid=1918349&pslc=1&ds=IUpATh8VkRCiNnAT" title="Laksh Grand Resort">
                    <AREA shape="rect" coords="539,345,667,407" href="https://www.goibibo.com/hotels/meta/google/4354390963378411938/3540257811845764463/%7B%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22ibp%22:%22v15%22%7D/?hquery={%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22qd%22:%2220240413-20240414-1-2_0%22,%22ibp%22:%22v15%22}&utm_source=meta&cmp=META|google|cpc_hpa|googlehoteldfinder|Hotel_Price_Ads_3540257811845764463|META&utm_medium=cpc_hpa&utm_campaign=Hotel_Price_Ads_19905350044_3540257811845764463&vendor=gds&p=1636.40&c=INR&bookingSource=commissions&adType=1&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iq5W5ntjSqfMfzNq0F0wSaCOn3dwkJw3Tig3aqE1EUBWPbvzKjAhcaArdQEALw_wcB" title="Country club Lee Crysstal - Boutique Hotel">
                        <AREA shape="rect" coords="742,162,919,218" href="https://www.makemytrip.com/hotels/hotel-listing/?topHtlId=202109211631562045&city=CTMAA&country=IN&checkin=04132024&checkout=04142024&roomStayQualifier=2e0e&totalGuestCount=2&roomCount=1&cmp=googlehoteldfinder_DH_META_Paid_selected_IN_mapresults_202109211631562045&_uCurrency=INR&Campaign=20607960138&locusId=CTMAA&locusType=city&mtkeys=3ea0338e-cf36-453a-bc7c-c382698d6ca7&au=&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5gWDllpXvek6_tZCDcm1sRYgZE-3w3I1jYg2b3tZrbNOFVXFiORQK4aAhM3EALw_wcB" title="Le Grace chennai ECR">
                            <AREA shape="rect" coords="1102,397,1302,447" href="https://www.goibibo.com/hotels/meta/google/4354390963378411938/9148435948091139586/%7B%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22ibp%22:%22%22%7D/?hquery={%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22qd%22:%2220240413-20240414-1-2_0%22,%22ibp%22:%22%22}&utm_source=meta&cmp=META|google|cpc_hpa|googlehoteldfinder|Hotel_Price_Ads_9148435948091139586|META&utm_medium=cpc_hpa&utm_campaign=Hotel_Price_Ads_19905408880_9148435948091139586&vendor=&p=21186.90&c=INR&bookingSource=commissions&adType=1&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iVKB2gnAmkqssixOUUTLRI5VUHnbzeIEoIB9OKpfHmnlCtRsgHHs4aApKbEALw_wcB" title="Mer Vue Villa (Beach house)">
                                <AREA shape="rect" coords="1076,69,1220,112" href="https://www.agoda.com/search?campaignid=21176660567&searchdatetype=selected&lt=1&numberofchildren=0&childages=&gsite=mapresults&partnercurrency=INR&roomid=565105220&pricetax=183.60&pricetotal=1713.60&rateplan=85baaefd-ec1c-e203-6ca2-f8eb2c1cb9fb&usercountry=IN&currency=INR&userdevice=desktop&verif=false&audience_list=&mcid=332&booking_source=cpc&adtype=1&push_id=CgYIgJbnsAYSBgiAueywBhgBINymhAEqDBgBKggiAggBKgIIBA%3D%3D85baaefd-ec1c-e203-6ca2-f8eb2c1cb9fb_20240412_10&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5g9nlLSTab6PdGHzDlDE_O3sPX4chFt2OcJ6MSwmuQdiKuXjwJ9wcwaAkkYEALw_wcB&los=1&adults=2&rooms=1&checkin=2024-04-13&checkout=2024-04-14&selectedproperty=2167644&city=17269&cid=1918349&pslc=1&ds=lMZDA4D1wPuieZNR" title="Grand Bay resort">
        </MAP>
        <br>
        X-coordinate
            <input type="text" id="Text1">
        Y-coordinate 
            <input type="text" id="Text2">
</body>
</html>
Output:

![Screenshot 2024-04-16 151657](https://github.com/Sanjaikee/NearMe/assets/150231888/d15eddc4-3412-40d6-adb9-c31f1f28834a)


![Screenshot 2024-04-16 151901](https://github.com/Sanjaikee/NearMe/assets/150231888/341fc177-c409-47f8-af15-5156b31f3508)

![Screenshot 2024-04-16 152005](https://github.com/Sanjaikee/NearMe/assets/150231888/03cf2e5f-9468-4ab8-b542-c79101f9265f)

![Screenshot 2024-04-16 152122](https://github.com/Sanjaikee/NearMe/assets/150231888/232c9bcb-fc9a-4a58-9d9d-fdc514c8f59e)

![Screenshot 2024-04-16 152143](https://github.com/Sanjaikee/NearMe/assets/150231888/b2895d8a-bf9f-4e9d-a3e4-7c3319b14213)

![Screenshot 2024-04-16 152155](https://github.com/Sanjaikee/NearMe/assets/150231888/93bf8c2f-302a-44b6-a777-1675e2cbb4c3)

![Screenshot 2024-04-16 152205](https://github.com/Sanjaikee/NearMe/assets/150231888/da20a5a6-8315-44d6-93c3-753179f11f23)

![Screenshot 2024-04-16 152218](https://github.com/Sanjaikee/NearMe/assets/150231888/79224e8a-f618-4d73-9475-fe1ec7d44e53)

![Screenshot 2024-04-16 152234](https://github.com/Sanjaikee/NearMe/assets/150231888/a76c9c7b-0eed-4665-91e0-03af54ac9b37)

![Screenshot 2024-04-16 152248](https://github.com/Sanjaikee/NearMe/assets/150231888/689cf54d-a1df-4fd7-a319-1fbb80934c70)

![Screenshot 2024-04-16 152255](https://github.com/Sanjaikee/NearMe/assets/150231888/77a22aa7-119d-4b26-88a1-cf332cf9a9eb)


![Screenshot 2024-04-16 152304](https://github.com/Sanjaikee/NearMe/assets/150231888/842419a3-560e-4661-96b4-727fc721ec62)

## RESULT
The program for implementing image maps using HTML is executed successfully.





