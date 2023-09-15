+++ 
draft = true
date = 2018-06-30
title = "digital naturalism"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
front = false
thumb = ""
year = ""
+++

input tribeNet and biolum textile here. 

TribeNET was developed during the [Digital Naturalism Conference](https://dinacon.org) in 2018, on the island of Koh Lon, Phuket, Thailand.

We considered a new communication method for our tribe while adventuring within the island. We desired the ability to communicate in more tonal short messages like birds and other animals. This is part of our theory to try to design to engage and merge with nature, instead of designing ‘on top’ of nature or not considering nature and its inhabitants in design processes. 

{{<figure src="/images/tribenet/tn1.jpg" caption="TribeNET. Photo by Umeed Mistry" width="100%">}}

# Textile

Walking the on beach the first day on the island, we came across a tree with something stuck in it, and it was a tartan!  Having an affinity for all things tartan, we found this serendipitously perfect for our tribeNETs textile needs. We were also able to find another small rag of the tartan in a nearby tree stump. We washed the textile and hung it to dry in the sun.

{{<figure src="/images/tribenet/tn2.jpg" caption="Tartan pattern textile found on the beach." width="100%">}}

# Patterning

The pieces of tartan were patterned, marked and cut, beach side. Using string to translate live measurements and marking the pattern pieces with washed up beach coral pieces. I cut the pieces using first aid kit scissors and hand sewed the pieces together. I stitched the electronics to the wearable pieces and made the appropriate channels to protect wiring and cords. The last pieces to to be attached were the protective mesh shell forms over the esp8266 Node MCU modules. All pieces were constructed with reusability in mind, as if we were in actual survival, we’d want to be able to reuse and alter pieces as necessity and need called for.

{{<figure src="/images/tribenet/tn3.jpg" caption="TribeNET pattern pieces." width="100%">}}

# Buckram Shell Castings

To create the mesh networks protective meshes, we cast buckram over various seashells from the island. These forms we created with water and buckram, and rubber bands from the dinner food boxes to hold the forms while they dried. After carefully unwrapping the dried formed buckram we were left with the mesh shapes to protect TribeNET electronic components.

{{<figure src="/images/tribenet/tn4.jpg" caption="Buckram shell castings." width="100%">}}

# Mesh Network

The three wearables are linked together via a mesh network based on the esp8266 Node MCU modules. These nodes are easily programmable via the Arduino IDE, with the complexities of mesh network topologies abstracted out. Two nodes essentially translate an input signal into tones, sent to the output node (worn by Elizabeth). Each node included an addressable RGB LED stick which shows information about the mesh topology, including if a node is online or not. MQTT was utilized as the base data protocol for publishing and subscribing to the different nodes’ data stream.

<video controls src="https://www.dinacon.org/wp-content/uploads/2018/09/tribeNet_nodes.m4v" width="100%"></video>

# Camera Node

The Camera node takes a live video feed and runs a kmeans clustering of the color information of the input video frame. The camera is mounted to the front of the wearer, giving the system a view in front of the hiking party. These predominant colors are encoded into tone and duration information and transmitted to the Speaker node.

{{<figure src="/images/tribenet/tn8.jpg" caption="TribeNET Camera Node." width="100%">}}

{{<figure src="/images/tribenet/tn9.jpg" caption="First person and third person views of the Camera Node." width="100%">}}

# Proximity Node

The Proximity node takes a series of ultrasonic sensor inputs distributed along the height of the human wearing them and translates this “section” into tones. Because the sensors are distributed along the height of the wearer, the textile pattern extends from the shoulder to the ankle. These tones are transmitted to the Speaker node.

{{<figure src="/images/tribenet/tn7.jpg" caption="TribeNET Proximity Node." width="100%">}}

# Speakers Node

The Speaker node receives signals from the other nodes in the system and creates a melody which describes the current reality of the hiking party. The data from the nodes was strictly mapped from sensor signal inputs into tone and duration. The resulting melodies must be learned to be understood. The speakers were sourced from the airline headphones we received on our way to Koh Lon. The internal components were harvested from their plastic casing and rewired to the mcu. While this is a low power, low volume solution, it worked very well for the hiking party.

{{<figure src="/images/tribenet/tn6.jpg" caption="TribeNET Speakers Node." width="100%">}}

<video controls src="https://www.dinacon.org/wp-content/uploads/2018/09/Sounds.mp4" width="100%"></video>

{{<figure src="/images/tribenet/tn10.jpg" caption="TribeNET Speakers Node" width="100%">}}

# Hike 

TribeNET was used on a hike through the paths of Koh Lon. During this hike the hiking party started to get used to the melodies created by the Speakers Node, These melodies were a combination of the sensor data, so it corresponded to the colors on the Camera Node and the ultrasonic sensors on the Proximity Node. While the hike was short, the party already could start to discern the melodies created when they were in different positions and next to different kinds of vegetation.

{{<figure src="/images/tribenet/tn11.png" caption="TribeNET. Photo by Mark Iifana." width="100%">}}

bioluminescent textile

A rapid experiment resulted from an evening of swimming with the Dinacon group in the bioluminescent waters off of Koh Lon, Thailand. Wondering if it was possible to bring the glow of the dinoflagellates into a textile, I mocked up a sample using fiber optic threads and natural wool roving. 
Using .25 mm fiber optic threads I tied knots in various locations of the thread strands to create the points of light, or “dinoflagellates.” Some used 2, 3, 4, or 5 strands and then knotted for size variation, in an attempt to create depth within the textile. 
I used 100% wool roving, torn into small pieces and laid out into the sample rectangle shapes in a criss cross fashion, alternating directions in the style of felt creation. I made two of these wool pieces, each with 5+ layers of roving pieces. 
The fiber optic stands were then gathered at one end and bound, and then I placed the bundle of fiber optic “dinoflagellates” on one layer of the wool sample, spreading the fiber optic threads out to cover the full area of the wool. Then I placed the second roving sample on top the fiber optics, sandwiching the fibers between the two wool pieces. 
This was then stamped on by my assistant to begin felting and then placed into a undergarment laundry bag to be fully massaged by the sea. The felting process was completed by the washing in the sea, with non-toxic dish soap and the waves pounding on the wool fibers. I rung out the textile and then hung it over a nearby tree branch to dry in the sun. 
We tested the textile that night by plugging it into our LED dongle, and the textile illuminated, making a quick sample of a super soft bioluminescence textile.
