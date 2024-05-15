# Ex04 Places Around Me


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
```C
ex6.html
<HTML>
    <HEAD>
        <TITLE>My City</TITLE>
    </HEAD>
    <BODY>
        <h1 align="center">
            <font color="ligthred"><b>Tirupati</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Rajkiran.j(212222043006)</b></font>
        </h3>
        <CENTER>
            <img src="C:\Users\Rajkiran\Pictures\Screenshots\maps.png" usemap="#mymap" height="500" width="1000">
            <map name="mymap">
                <area title="Venkateswara Temple" href="temple1.html" coords="652,320,880,398" shape="rect">
                <area title="Akasaganga Teertham waterfall" href="waterfall.html" coords="452,600,208" shape="circle">
                <area title="Padmavati Temple" href="temple2.html" coords="819,400,981,881" shape="rect">
                <area title="Govindaraja Temple" href="temple3.html" coords="705,315,935,337,710,414,637,317" shape="poly">
                <area title="Kodandarama Temple" href="temple4.html" coords="422,481,119" shape="circle">
            </map>

        </CENTER>
    </BODY>
</HTML>
temple1.html

<HTML>
    <HEAD>
        <TITLE>temple1</TITLE>
    </HEAD>
    <body bgcolor="lightblue">
        <h1 align="center">
            <font color="red">Tirupati</font>
        </h1>
        
        <h3 align="center">
            <font color="yellow">Venkateswara Temple</font>
        </h3>
        <hr color="yellow" align="center">
        <br>
        <p><h4>
            The Sri Venkateswara Swami Temple is a Hindu temple situated in the hills of Tirumala at Tirupati in Tirupati district of Andhra Pradesh, India. The temple is dedicated to Venkateswara, a form of Vishnu, who is believed to have appeared on the earth to save mankind from trials and troubles of Kali Yuga. Hence the place has also got the name Kaliyuga Vaikuntha and the deity here is referred to as Kaliyuga Prathyaksha Daivam. The temple is also known by other names like Tirumala Temple, Tirupati Temple and Tirupati Balaji Temple. Venkateswara is known by many other names: Balaji, Govinda, and Srinivasa.[4] The temple is run by Tirumala Tirupati Devasthanams (TTD), which is under control of Andhra Pradesh Government. The head of TTD is appointed by Andhra Pradesh Government. The temple is one of the Pancha Kshethram where Maha Lakshmi was born as Bhargavi - the daughter of Maharishi Bhrigu. The other four temples of the Pancha Kshethram are Sarangapani temple, Kumbakonam, Oppiliappan temple, Nachiyar Koil and Sundararaja Perumal Temple, Salem.
        </h4></p>
    </body>
</HTML>
waterfall.html

<HTML>
    <HEAD>
        <TITLE>Waterfall</TITLE>
    </HEAD>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="red">Tirupati</font>
        </h1>
        
        <h3 align="center">
            <font color="cyan">Akasaganga Teertham waterfall</font>
        </h3>
        <hr color="red" align="center">
        <br>
        <p><h4>
            Located at a proximity to the Tirumala temple, Akashganga Theertham is of great religious significance to the devotees. It is also a picturesque tourist destination which is visited by nature lovers from different parts of the country.

            Followers believe taking a dip in the plunge pool of this holy waterfall washes one of their sins. Akashganga Theertham is known for retaining its water throughout the year. The main abhishekam (bathing) ritual of the deities of Tirumala temple is performed in the waters of the Akashganga waterfall. According to popular belief the waters of Akash Ganga waterfall originates from the lotus feet of Ananda Neelayam.
        </h4></p>
    </body>
</HTML>
temple2.html
<HTML>
    <HEAD>
        <TITLE>temple2</TITLE>
    </HEAD>
    <body bgcolor="violet">
        <h1 align="center">
            <font color="green">Tirupati</font>
        </h1>
        
        <h3 align="center">
            <font color="lightgreen">Padmavati Temple</font>
        </h3>
        <hr color="maroon" align="center">
        <br>
        <p><h4>
            This beautiful temple dedicated to Goddess Padmavati is situated in Tiruchanur, a small town near Tirupati. Also called as Alamelumangapuram, the temple is believed to be very significant for Hindus as Goddess Padmavati is said to be very benevolent and readily forgives her devotees. The temple has an inscription that expounds on the history of the place. According to it, there was a temple dedicated to Lord Venkateshwara in Tiruchanur originally. Since it was quite cramped, it was difficult for priests to perform rituals and all activity was moved to another premise. Eventually, only two important rituals were performed at the original site. Over time, even this stopped and the place faded into insignificance. However, in the 12th century, it again came into the limelight when the Yadava kings built the Shri Krishna Balaram Temple here. Later, in the 16th and 17th centuries, the deity of Sundara Varadaraja was installed and a temple was built for Goddess Padmavati. Legend has it that the goddess was born in a lotus pond that is now a tank within the temple.  
        </h4></p>
    </body>
</HTML>
temple3.html
<HTML>
    <HEAD>
        <TITLE>temple3</TITLE>
    </HEAD>
    <body bgcolor="red">
        <h1 align="center">
            <font color="blue">Tirupati</font>
        </h1>
        
        <h3 align="center">
            <font color="white">Govindaraja Temple</font>
        </h3>
        <hr color="lightgreen" align="center">
        <br>
        <p><h4>
            The temple is one of the largest temple complexes in Andhra Pradesh.[citation needed] A 50 m high, seven storied Rajagopuram was constructed on east entrance of the temple by Matla Anantaraja, a local chieftain.[3] This structure has Ramayana scenes and portrait of Matla Anantaraja and his three wives carved onto the passage walls.[3] Towards the west of Rajagopuram, there are two enclosures of the temple, arranged one behind the other. The outer enclosure hosts sub shrines of the consort of Govindaraja - Pundarikavalli (a form of Lakshmi) and Alvars. The inner enclosure hosts the main shrine of Govindaraja along with shrines of Krishna with his consort, Andal. Towards south west corner of the inner enclosure, there is a shrine dedicated to Kalyana Venkateswara which had a mandapa with finely finished colonettes on the outerpiers and with central space lined with yalis projecting inwards. The pavilion in the middle had columns of grey green granite and wooden roof.[3]

            Besides Govindaraja, the shrines of Parthasarathy (the former presiding deity) and Kalyana Venkateswara are considered religiously significant.
            
            Govindaraja temple also has shrines of goddess Padmavati, Ramanuja and Andal near the entrance. There is a structure housing the Vishnu avatars to the right side of the entrance as like common in other Vishnu temples. There are also shrines dedicated to Chakratalwar, Lakshmi Narayana, Anjaneya and Tirumala Nambi.
        </h4></p>
    </body>
</HTML>
temple4.html

<HTML>
    <HEAD>
        <TITLE>temple4</TITLE>
    </HEAD>
    <body bgcolor="violet">
        <h1 align="center">
            <font color="maroon">Tirupati</font>
        </h1>
        
        <h3 align="center">
            <font color="blueviolet">Kodandarama Temple</font>
        </h3>
        <hr color="green" align="center">
        <br>
        <p><h4>
            Sri Kodandaramaswamy Temple is one of the famous temples, after Tirumala Venkateswara Temple, in the holy city of Tirupati located in Tirupati district of Andhra Pradesh, India. The temple is dedicated to Lord Rama an incarnation of Vishnu along with Sita and Lakshmana. The temple also has a sub-shrine for Anjaneya the mount of Lord Sri Rama.
            Rama Navami is celebrated with major grandeur at this temple which includes Hanumantha Vahana Seva in connection with Sri Rama Navami day, followed by Sri Sita Rama Kalyanam on Dasami and Sri Rama Pattabhisheka Mahotsavam on Ekadasi. The nine-day annual brahmotsavams celebrated every year which falls between March and April is another biggest event in the temple.[1] The Annual three-day Teppotsavams(Float festival) will be celebrated during April at the temple where the processional deity of Sri Rama along with Sita and Lakshmana will taken over a float in Sri Ramachandra Pushkarini.
       </h4></p>
    </body>
</HTML>
```


## OUTPUT
![Screenshot 1](https://github.com/Rajkiran276/NearMe/assets/147471453/18af6055-e258-4f38-9770-ddd1c83d4326)
![Screenshot 2](https://github.com/Rajkiran276/NearMe/assets/147471453/ffa9e0c9-e769-42f3-9d29-0571d060ef0e)
![Screenshot 3](https://github.com/Rajkiran276/NearMe/assets/147471453/bb21d04e-726c-4eeb-9178-f8ac45dacdc4)
![Screenshot 4](https://github.com/Rajkiran276/NearMe/assets/147471453/357f4931-aa87-4c10-9bb9-5b5294c06810)
![Screenshot 5](https://github.com/Rajkiran276/NearMe/assets/147471453/c59b1d2c-150b-42a5-b0f2-f03cec65be09)
![Screenshot 6](https://github.com/Rajkiran276/NearMe/assets/147471453/aeceaa95-510c-44e7-8a20-53a8f503fbda)










## RESULT
The program for implementing image maps using HTML is executed successfully.
