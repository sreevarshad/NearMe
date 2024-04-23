# Ex04 Places Around Me
## Date: 05/04/2024

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
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">CHENNAI</font></h1>
        <h3 align="center">
            <font color="blue">NITHYA SHREE B (212223220071)</font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="550" width="1300">
            <map name="MyCity">
                    <area shape="rect" coords="350,220,400,270" href="park.tml" title="sivan park">     
                    <area shape="rect" coords="750,270,850,350" href="temple.html" title="Tirumala Tirupati">
                    <area shape="rect" coords="400,600,500,650" href="college.html" title="SRM Institute of science and Technology">
                    <area shape="rect" coords="1100,250,900,300" href="centre.html" title="cheenai Trade center">
                    <area shape="rect" coords="800,300,750,350" href="library.html" title="Anna Cetenary library">
            </map>
        </center>
       

    </body>
</html>

temple.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">chennai </font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">Tirumala Tirupati</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Tirumala Tirupati Devasthanams new temple dedicated to Goddess Padmavathi Ammavaru, the divine consort of Lord Venkateswara, coming up at T Nagar in Chennai in the neighbouring state of Tamil Nadu, is gearing up for the Mahakumbhabhishekam in March this year.
            The erection of the new "Dwajasthambham" (flagpost) was ceremoniously carried out by the temple priests at the new temple complex at T Nagar on Thursday.
            The new temple is being established in an extent of 14880 sft land at GN Chetty road in T Nagar, which was donated to the TTD by noted South Indian actress P Kanchana.
The construction works of the temple is being completed by spending Rs.7 crore and the construction of the Rajagopuram works costing approximately Rs.1.1 crore is being completed from the donation extended by AJ Sekhar Reddy, special invitee to the TTD trust board.
TTD's Chennai local advisory committee president AJ Sekhar Reddy, TTD JEO V Veerabrahmam IAS and Chennai committee members took part in the Dwajasthambham erection ceremony held at the temple.
        </font>
        </p>
    </body>
</html>

center.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">chennai </font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">cheenai Trade center</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Chennai Trade Centre is a permanent exhibition complex in Nandambakkam, Chennai, hosting several trade fairs and conventions round the year. It is the first fair infrastructure that has been developed by India Trade Promotion Organisation (ITPO)—the premier trade promotion agency of the Government of India, Ministry of Commerce and Industry—outside Delhi.[1] A joint initiative of the ITPO and the Tamil Nadu Trade Promotion Organisation, which hold 51 and 49 percent stakes, respectively, the Trade Centre was designed by C R Narayan Rao,[2] and was commissioned in January 2001, while the convention centre was commissioned on 1 November 2004. The exhibition hall was constructed at an estimated cost of ₹ 23 crore and the convention centre at a cost of ₹ 22 crore.[3] Together, these centres cover 10,560 sq m and are fully booked for 75 days in a year.[4] Built over an area of 25.48 acres, the centre comprises four modules of 4,400 m2 each of exhibition halls and support services to be built in a phased manner.[5] In the first phase, two air-conditioned halls without pillars or columns encompassing areas of 5,000 m2 and 1,850 m2 were constructed. There are three halls, viz, Hall No. 1 (4,400 m2), Hall No. 2 (1,760 m2) and Hall No. 3 (4,400 m2). The halls feature a height of 6 m to display all merchandise including machinery. These have been supplemented recently with a modern, fully air-conditioned convention centre. All the halls are inter-linked, and Hall No. 3 is connected with the convention centre. The convention centre can accommodate 2,000 people with a provision for dividing the hall into two equal parts and has an audiovisual facility suitable for multi-purpose use such as conferences, conventions, cultural shows, and so forth. The Chennai Trade Centre is managed by Tamil Nadu Trade Promotion Organisation (TNTPO), a joint venture of ITPO and Tamil Nadu Industrial Development Corporation (TIDCO).

    
        </font>
        </p>
    </body>
</html>

park.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">chennai </font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">sivan park</font>
        
        
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Sivan Park is a lovely park located in Chennai’s KK Nagar. The municipal corporation of Chennai is responsible for the upkeep of this park. It is popular among locals living in KK Nagar, and serves as an excellent spot for jogging and cycling. What’s more is that the park is conveniently accessible from numerous locations across Chennai.
            The park boasts a 15-foot-tall statue of Lord Shiva.
            It is chock full of various species of plants and trees, creating plenty of shaded areas to relax in.
            There is a nursery in the park that sells potted plants and ornamental plants to visitors.
            The Sivan Park also has a play area for children equipped with many kinds of swings and slides.
            It is equipped with an impressive lighting system that gives the park a fantastic look at night.
            Some of the trees found at the Sivan Park include Nagalinga, Neem, Acacia, Jaggery Palm, Gulmohar, Peepul, Ashoka, Banyan, Pungai and Sapota.
            Every year, the park hosts the Chennai Sangamam.
            
     
        </font>
        </p>
    </body>
</html>

college.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">chennai </font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">SRM Institute of science and Technology</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            SRM University is ranked 4th by Outlook 2023 under the Engineering category, 4th by Times 2023 for BBA, and 14th by NIRF 2023 under the Architecture category. Founded in the year 1985, SRM Institute of Science and Technology or SRM IST (formerly known as SRM University) is a top-ranked university that is part of the SRM Group of Institutions. Accredited by IET Engineering, the Engineering Accreditation Commission of ABET, the Computing Accreditation Commission of ABET, NBA, and the NAAC with A++ Grade, SRM Chennai is approved by the UGC and AICTE.


        </font>
        </p>
    </body>
</html>

library.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">chennai </font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">Anna Cetenary library</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Anna Centenary Library (ACL), a state-of the-art library was inaugurated on September 15, 2010 on the occasion of the 102nd birth anniversary of the former Chief Minister of Tamil Nadu Dr. C N Annadurai popularly called ‘ANNA’. By reason of his great interest towards the books and library, this library is named as ‘Anna Centenary Library’. The foundation stone laid on August 16, 2008, completed in a short span and declared open to the public from 20th September 2010.

            The built up area of this centralised air-conditioned library is 3.75 lakh sq. ft., encompasses ground and eight floors. At present, it hosts five lakhs books covering a wide range of subjects to serve the information needs of the public, academic and corporate community. Our Library has a Braille Section, Own Books Reading Section, Children Section, Periodicals and Newspapers Section, Tamil books Section, English Books Section and Digital Library. In addition, the library has a Conference Hall that can facilitate 150 members.
        </font>
        </p>
    </body>
</html>

```




## OUTPUT
<img width="576" alt="WEB" src="https://github.com/sreevarshad/NearMe/assets/128129573/2d379f95-2718-4567-8f40-3bd8323c8dbe">
<img width="609" alt="temple" src="https://github.com/sreevarshad/NearMe/assets/128129573/26d3aae2-0178-4653-8f04-55ae842d1081">
<img width="605" alt="Screenshot 2024-04-23 110409" src="https://github.com/sreevarshad/NearMe/assets/128129573/a32d2229-9289-4919-84bf-ae68e8f6af6f">
<img width="605" alt="park" src="https://github.com/sreevarshad/NearMe/assets/128129573/f1165d6c-57d8-43a8-a79a-dfc679cfb2c7">
<img width="602" alt="college" src="https://github.com/sreevarshad/NearMe/assets/128129573/50c05567-5d17-4967-ad4b-2c9fa95ae3be">
<img width="605" alt="library" src="https://github.com/sreevarshad/NearMe/assets/128129573/1712aa52-3794-4871-9ecd-493dce21a3fd">








## RESULT
The program for implementing image maps using HTML is executed successfully.

