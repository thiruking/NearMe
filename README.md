# Ex04 Places Around Me
## Date: 06/11/2024

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
Execute the programs and publish them.

## CODE
```

map.html

<html>
   <head>
        <title>image map</title>
</head>
   <body><center>
    <h1 style="color: aqua;">MY CITY</h1>
    <img src="Screenshot 2024-12-06 113553.png" alt="Sample Image" usemap="#my-map" class="image-map" width="800px" height="680px">
<map name="my-map">
      <area shape="circle" coords="459,358,71" href="krishnagiri.html" alt="Area 1">
     <area shape="rect" coords="282,48,492,132" href="FORT.HTML" alt="Area 2">
        <area shape="poly" coords="382,679,538,705,465,606,399,620,387,650" href="TEMPLE.HTML" alt="Area 3">
        <area shape="circle" coords="192,323,75" href="POOR.HTML" alt="Area 4">
        
  </map></center> 
</body>
</html>

krishnagiri.html

<BODY style="background-color: brown;">
    <HR>
        <HR>
    <CENTER><h1>KRISHNAGIRI</h1>
<P style="color: aqua;">Regional Development Plan to be developed for Krishnagiri
    This article from The Hindu Business Line discusses the need to identify sunrise sectors and sub-sectors for the district. 
    United Farmers Front stage protest demonstration in Krishnagiri
    This article from The Hindu discusses the protest demonstration held by the United Farmers Front near the new bus stand. The protest raised several demands, including a Minimum Support Price (MSP) and a waiver of farm loans. 
    Two children die after cattle feed bags fall on them in Krishnagiri
    This article from The Hindu discusses the deaths of two children who were playing in a room where cattle feed was stocked at a poultry farm. 
    New classrooms inaugurated in Krishnagiri
    This article from The Hindu discusses the inauguration of new classrooms and a lab at a school in Krishnagiri. 
    40 new schemes for Krishnagiri to avert future disasters
    This article from The Hindu discusses the plans to implement over 40 schemes in various parts of the district to prevent future disasters. 
    Krishnagiri is a city in the state of Tamil Nadu, India. It is known as the "Mango Capital of India" because of the fertile land and access to fresh water that make it ideal for growing mangoes. </P>
</CENTER>
</BODY>

fort.html

<BODY style="background-color: brown;">
    <CENTER>
        <H1>KRISHNAGIRI FORT</H1>
    </CENTER>
    <HR>
        <HR>
            <P style="color: aqua;">
                இந்தியாவின் தமிழ்நாட்டின் கிருஷ்ணகிரி மாவட்டத்தில் அமைந்துள்ள கிருஷ்ணகிரி கோட்டை , பல்வேறு வம்சங்கள் மற்றும் காலனித்துவ சக்திகளின் வீழ்ச்சியையும் ஓட்டத்தையும் கண்ட ஒரு வலிமைமிக்க வரலாற்று கோட்டையாகும். இந்திய தொல்லியல் துறையின் கீழ் தேசிய நினைவுச்சின்னமாக இப்போது பாதுகாக்கப்படும் இந்த கோட்டை , பல நூற்றாண்டுகளுக்கு முந்தைய வளமான வரலாற்றைக் கொண்டுள்ளது.
            </P>

</BODY>

POOR.HTML


<BODY style="background-color: blueviolet;">
    <CENTER>
        <H1> POORVIKA </H1>
    </CENTER>
    <HR>
        <HR>

            <P style="color: aqua;">
                Poorvika is the Largest Tech Retailer in India, spanning across 460+ showrooms in and around Tamil Nadu, Karnataka, Pondicherry, Mumbai and Pune, famous for their touch & feel Live Demo experience before buying. Poorvika sells a wide category of devices in its showrooms and Online portal, ranging from the Best Smartphones, Laptops, Computers, Smart Devices, and Smart TVs to Accessories. Smartphone lovers await an enthralling experience at Poorvika. Having served over 5 Crore+ Happy Customers, Poorvika takes pride in being India's leading retailer for Top Brands like Apple, Samsung, Oppo, Vivo, Xiaomi, OnePlus, Redmi, Realme, Nokia, etc.
            </P>
</BODY>

TEMPLE.HTML

<BODY style="background-color: blueviolet;">
   <CENTER>
        <H1> TEMPLE </H1>
   </CENTER>
   <HR>
    <HR>
   <P style="color: aquamarine;">
    Kattuveera Anjaneya Temple is located at Krishnagiri in Tamil Nadu is said to be 2500 years old and this Anjaneya here ensures that the one wish which one pray with full devotion is said to come true, within 3 months.

At the counter if one pays Rs.50/- a saffron bag with coconut, betel leaves and coconut is handed to us which has a number written on it and one card containing the same no. Pray for the fulfillment of one wise and along with a dakshina the saffron bag is tied and kept inside the sanctum of Anjaneya where the poojari does a small pooja and hands back to us.

The devotee has to complete 11 rounds of the temple chanting the mantra “sri Ram jai Ram Jai Jai Jai Ram” and once the 11 pradikshna is over then the saffron bag is kept along with the other devotees bags separately for 3 months. It is believed that the one wish which you want to be fulfilled gets fulfilled, and once the wish is fulfilled you are expected to return and claim the saffron bag from the temple.

There is one natural rock formation Nandi which one cannot miss and shows the presence of shiva too here.
   </P>
</BODY>


```


## OUTPUT








## RESULT
The program for implementing image maps using HTML is executed successfully.
