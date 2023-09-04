![[DronePrimaryTargets.png]]

#### Aerospace Security: Drones - Introduction To Module 

This module of the notes will be talking about why drones are a primary target for cyber security researchers and will also highlight some key points. Later on, this section will be much more advanced and also have more wider points. However, for now, it will stay simple. Before we get into everything, lets get into the topics that will be discussed. 

> **Note**: Any form of terminology you do not understand in this module will be stored in the "Terminology" section of this notes list.

* **Why Drones** --> This section will talk about why drones are targeted, what makes them easier to target, why they are important to research and more!

* **Areas Of Research** --> This section will explain some primary areas of security research for drones.

> **Note**: I would like to help you take notice of the factor that aerospace security similar to automotive security pretty much all fields are applicable. This includes reverse engineering ( firmware, protocols, networks, systems, files, setups, algorithms, key management systems, etc), digital forensics,  protocol research, radio communications, network security, web security, app security, and more.

#### Aerospace Security: Drones - Why Drones

Alright so this is where things get weird, who would have thought that aerospace cyber security included drones??? Actually- everyone whos ever even dipped their toes in it should have imagined that. Well, fuck, where do we start? For this particular section we can start by discussing what the fuck? Yes, wtf, that is how we are going to start this. 

Before we get into why drone hacking is a primary thing, we need to make sure we have a base understanding of what type of drones exists. So, if you have not checked terminologies, UAVs are not just military- in fact, UAVs also exist for humans! You know how some people go to stores and purchase a small $500 UAV / drone? Yes, those can be hacked to! So, drones are a primary target for a few reasons which have been listed below.

* Affordability -> You may question this one given some UAVs especially military tech can go as far as a million dollars per drone- but yes that is my general statement to include non military tech as well. The affordability of drones just period makes it way easier to access. For example, a basic DJI drone is like $370+ which is not much for a powerful and far ranging drone with good camera quality. This falls into our next point.

* Accessibility -> Almost anyone has access to a drone especially in today's world even despite their over the $100 limit for pricing. The accessibility of drones can actually go quite far and can help people become much more fluid and knowledgeable in the drone hacking field.

* Fluidity -> When I use "fluid" in a sentence, you know shit has gotten real! Yes, drones are quite fluid, they are constantly changing in numerous ways and forms such as their structures, networks, logging and event recording systems, radio transmission techniques, FPV techniques, data transmission techniques, scalability, flexibility and more. So how does this make is suitable for being hacked? Would this not make it harder for hackers? Yes and no. If a drone is fluid, then this means you can find more vulnerabilities for a specific system that might be easier to replicate, not to mention you may also be able to modify some systems better than others and may be able to study and understand forms of say communication way more easily given you are getting a good understanding of what systems are being used.

* FFAH -> What is FFAH? Well, this is my way of saying Fucking Fun As Hell! Yes that is  correct, you read that correctly. Given how fluid and affordable drones are off the shelf and how easy they can be to manipulate in specific states, it can be truly fun to just go walk outside and hack a drone. I mean, cmon- your friends will think your a total badass hahah! I mean, at that fucking point you are, no? This is where the drone security aspect comes into play, sure hacking drones without missiles or some million dollar equipment is not that fun but in general- who does not want to go and hack a drone! 

* Room For Growth -> This point is the best point of them all. When it comes down to hacking drones, due to the fluidity and diversity of the systems and mechanisms, there is always going to be room for growth in your knowledge. Because of the constant ability to research new systems and mechanisms, you will also learn new techniques to say bypass specific security measures on the networks or radio transmission systems within the drone! Isnt' that fun?

* Used Pretty Much Everywhere -> Alright, automotive cyber security is one road that will be more popular because literally close to every single human being on earth owns or has access to a vehicle in some shape or form. Drones- not so much. While drones are heavily accessible and easy to buy, not every single person needs or uses one for general everyday tasks such as a vehicle. But, this does not mean drones are still not used heavily because they are! They are used for video/photo (graphy), testing and general experimentation, systems development, experimentation and more! But what about the more- humanitarian aspect? Well, as we have also discussed, drones are used in warfare even to combat other teams and not always are they these massive UAVs. Take the image below which shows a soldier, who is apart of the Ghost battalion of the 4th brigade of the Russian armed forces. In the image shown below this point, the soldier is holding a drone that actually does not seem military. Well it turns out that this drone had a StarLink module in it and was reverse engineered by Ukrainian military forces! This is exactly where general drones can also be applied, in warfare. Sometimes you may even see DJI drones used in combat!

![[GhostBatWarRU.jpeg]]

So, this is where we can conclude this section. Drones are pretty much where everyone starts in the aerospace cyber security world. This is actually a great place to start because of how fluid drones are and how diverse they are! Not to mention, drones are used in many different applications and are used in many different scenarios! Now, lets get our assess up and moving onto the next section!

#### Aerospace Security: Drones - What Areas Of Research

This is kind of a hard section to talk about directly since drone security or really any form of aerospace security entails many different fields. However, I have tried my best to narrow it down in some shape or form! Below is a list of bullet points that shows the fields of CyberSecurity research with drones!

* Reverse Engineering -> Reverse engineering is most likely the biggest method and research area on this list. In fact, I can assume that most people especially in the drone security space have utilized reverse engineering at least once. Some people are familiar with reverse engineering just reverse engineering some form of binary or something when in reality, RE is more than that! Reverse engineering comes in many shapes and forms such as reverse engineering protocols, encryption methods, encodings,  firmware, applications and more! So where do all of these fields come in handy? Well, when it comes to the area of hacking drones, being able to reverse engineer protocols and systems such as communication systems on the drone is actually quite helpful if you are trying to find some form of vulnerability or even get a understanding of a system. I am sure, if you have heard of RE, you are familiar with the fact that reverse engineering is simply taking a specific object such as an application or protocol and reversing the functionality from the inside out or the outside in by picking apart specific methods. Lets take Apple's proprietary protocol AirPlay for example. If you were to reverse engineer this protocol, you would first have to utilize protocol analyzers such as Wireshark to understand how the protocol is used, where it is sent, how and why it is sent and to understand data payloads and limits. You would then use other various systems and frameworks to analyze the protocols internals and finally build your own plausible implementation by understanding the protocols structure. This is the same thing with drones, you would reverse engineer the systems or communications inside of the drone so you can build your own version or even modify existing ones within the drone itself. Reverse engineering may also be in the field of reverse engineering its firmware since that can also give you a good understanding of how the drone works from the inside out and also how you can modify some of the systems on there or maybe even bypass a security mechanism on the drone. Concluding, reverse engineering is a very important field that almost every aerospace cyber security researcher especially tackling drones should understand.

* Digital Forensics -> Digital forensics- ah yes, the forgotten about field of both drones, satellites and even vehicles. Something that I have learned in todays world especially when working in the vehicle security sector is that digital forensics is not all the most helpful thing in the world. Despite it being good to practice, it just is not applicable in many standard cases and may only be used in very specific scenarios that even standard digital forensics experts might not come across. This can be due to various reasons such as data being manipulated, damaged, or purposely frauded in an attempt to "deep fake" information on the device which almost every cyber criminal may want to do. But in general, digital forensics is the forensics of the digital realm which can go deep into investigating traffic or systemic logs that the drone or aerospace systems manage and capture or even go as far as investigating the systems on the drone for specific suspicious activity. Digital forensics is something we will go deeper into later but this can also include checking images for general location snapshots, checking specific files logged on informational units, checking specific controllers for location information, and even go as far as checking audio and visual formats for specific sets of metadata.

* Protocol Research -> Protocol research is one confusing one, where does this ever become applied to the world of drones? Well, if you generalize protocol research and include it with radio communications, then you can infer that protocol research is pretty welcomed into this field. For those who do not understand, protocol research is the research of specific network protocols to help identify specific vulnerabilities. See drones and general aerospace systems use multiple forms of general communication and even serial communication such as CAN ( Controller Area Network ). Understanding and being able to research into protocols like CAN and even understanding the physical systems used to convey those communications may allow people to easily manipulate messages on the network!

* Web Application Testing -> Web applications, ah yes, the fuckboy of the future. Web is the future let me tell you that now. You may be confused here, but lets seriously think this over. When it comes to modern day technologies, drones have to have some form of external communication no matter if its WiFi or Bluetooth- there is always some way to reach other servers and systems out there. The reason drones may be using this is because they need to fetch real-time information for the users end, of course this leads to the use of web applications within the drone that can communicate with external systems which may also be used to work with third party applications that are tailored to the flight experience. The issue with this is that given how unattended web application security is in todays world even when looking at vehicles ( where something as much as an IDOR vulnerability still exists) we can clearly assume that drones are also not going to have that much security. So, the web application and security testing aspect will go quite a long way given the recon aspect and exploitation aspect will play a heavy role when testing the applications on a drone!

In general, there are a ton of fields in the aerospace realm especially applying to drones that can be applied to your research. As I have mentioned in my automotive cyber security roadpath and series, it pretty much applies everything due to the modern technologies and systems that are used within. 