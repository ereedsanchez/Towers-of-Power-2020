# Towers-of-Power-2020

7 Billion people around the world still do not have access to interent. For some, it is too expensive. 
For others, market faliures with ISPs and traditional communications providers who don't see a proft margin for rural and underdevloped communities, have left many people with out connectivity. 

I was one of those people.  When living in Bluefields, Nicaragua, I was unable to get a residential internet connection even though I lived a 10minute walk from the University.  My only options where expensive (U$5 for 1GB) celular connections.  This led me to start my own rural ISP in Nicaragua, and deploy community Open Source Cellular Networks. 

In this class you will learn the modern - and not so modern technologies - used to connected the disconnected.  
This is a crash course in real world networking technologies, including long distance wifi, Mikrotik routers, Open Source GSM and Fiber PON networks. 

Students will get hands on experience with equipment now used by MicroISPs and Community Networks.   
Guests speakers, may include Peter Bloom from Rhizomatica (Indigenous GSM Networks), Jane Coffin from the Internet Society, and others who will elaborate on current trends, challenges and avenues for disconnected communities aroudn the world.   


# Class Dates
  1. 
  2. 
  3. 
  4. 
  5. 
  6. 
  7. 
  
# Materials 
+ Mikrotik hAP
+ Raspberry Pi
+ 
  
# Office Hours
I will be available for office hours by appointment .... 
 
ereedsanchez@gmail.com

# Syllabus
## Week 1
### Introduction to Towers of Power
+ Student Introductions: an ITP tradition!
+ Syllabus and expectations
+ History of SayCel
+ History of Netowrks
+ OSI Model 
+ Introduction to Mikrotik 

#### Homework: 
Mikrotik Lab #1, Mikrotik Lab #2


## Week 2
Hotspoit

## Week 3





+ Basic of GSM Infrastructure
+ Basic Terminal Workshop https://docs.google.com/presentation/d/1tLC7XzMhGAKJri2ZYf2lvHvoR0w-OxHzxErKkz0C_jI/edit?usp=sharing

#### Guest Speaker: [Peter Bloom, Rhizomatica](https://www.rhizomatica.org/)

  
1. [Install Virtual Box/ Linux Ubuntu](https://github.com/saycel/towers-of-power/blob/master/virtual-box/VirtualBox.md)
2. [Install GQRX on Virtual Machine using the Terminal](http://gqrx.dk/download/install-ubuntu). After the last command, you can exit the process by pressing ctrl-z. Start GQRX by typing "gqrx" in the terminal.  
3. Order RTL-SDR.  
4. Find the IMSI and IMEI number for your phone/account. Write a blog post explaining how you found your IMSI/IMEI number.  
5. Read [Built to Last by Jim Collins](https://www.amazon.com/Built-Last-Successful-Visionary-Essentials/dp/0060516402) Chapters 1 & 2. Write a blog post about the reading.  
6. Optional: [history of internet infrastructure](https://www.theatlantic.com/technology/archive/2015/11/how-railroad-history-shaped-internet-history/417414)


## Week 2 
### Building a GSM Network from software to hardware installation.
+ Basic SDR introduction and options for building an GSM network. 
+ History of Open Source Cellular - Osmocom, OpenBTS, YateBTS, Rhizomatica, Open Cellular   
+ Rhizomatica / SayCel installation Software Overview: Osmo-NITB, Osmo-TRX, Freeswitch, Kannel, RAI, etc
+ Rhizomatica / SayCel installation Hardware Overview: Nuran Litecel, Antennas, Cables, Solar, etc. 
+ Tower Installations, maintenance and concerns.  
+ Virtual Private Networks (VPN) - Why it’s important and why we use it. 

#### Homework:  
1. [OpenVPN Assignment](https://github.com/saycel/towers-of-power/blob/master/openvpn/open-vpn.md)   
Write a blog post about your experience. 
2. Read [Built to Last by Jim Collins](https://www.amazon.com/Built-Last-Successful-Visionary-Essentials/dp/0060516402) Chapters 3 & 4. Write a blog post about the reading.  


## Week 3 
+ SayCel Update
+ Software Osmocom / Rhizomatica / Puppet GSM / Software Installation
+ Tower Installation Procedures

### Radio Waves, SDR, Wifi and Politics
+ Basic Radio Wave propagation, modulation
+ SDRs- what equipment is available? 
+ Long Distance Wifi Backhaul
+ RTL-SDR - Demo RTL-SDR in class.  We will use the RTL-SDR to see phone calls we make with an our open source cellular system.  
+ [Dhruv Mehrotra: Satellite Sounds](http://satellite-sounds.dhruvmehrotra.info),
+ [Surya Mattu: SDR 101 + Analog TV](https://samatt.github.io/sdr-101)

#### Guest Speaker: [Kurtis Heimerl](https://www.engr.washington.edu/facresearch/newfaculty/2015/kurtis-heimerl) - University of Washington, [ENDAGA](https://www.endaga.com/), [FACEBOOK](https://code.facebook.com/posts/1754757044806180/introducing-opencellular-an-open-source-wireless-access-platform), 

#### Homework: 
1. Start thinking about your final project - Research a community that needs communications technology or think about an innovative application of the GSM spectrum and how it can be used in rural development work.   Write a blog post about it. 

2. Do one of the following assignments below (you may work in groups): 
+ Look at Radio spectrum and record something interesting. If you don’t know what it is, try to figure it out, better yet try to demodulate it.  

3. Come up with an initial idea of a community porblem that could be solved using a GSM solution. Can be a local problem, or a problem in a developing region.  It can be eviornmental or social.  Write a blog post, and we will go over this in the next class.  



## Week 4 
+ Discuss Built to Last 
+ Discuss Ideas for Final
+ Discuss RTL-SDR Homework
+ Review Radio Spectrum

### Getting Hardware to speak GSM
+ Overview of different hardware options: GSM modems, GSM modules and shields, GSM breakout boards for micro-controllers and micro-controller platforms.
+ Communicating with GSM hardware and setting the hardware up: AT Commands.
+ Hands-on demo in pairs or small groups on how to use a serial communication application to talk to GSM breakout boards and more.
+ How to send an SMS and review of SMS protocol.

#### Homework (you may work in groups):  
1. Define your groups and final Project
2. Write a brief synopsis of the project. 


## Week 5
### Phone Based Applications 
+ Twilio - Overview of how to use Twilio to make phone based projects.
##Business, Budgets, Proposal, and Raising Financial Capital.
+ All the important details a tech person needs to know to run a business.  

#### Guest Speaker: [Kashif Ali / Facebook Open Cellular](https://code.facebook.com/posts/1754757044806180/introducing-opencellular-an-open-source-wireless-access-platform)

#### Homework (you may work in groups):  
Work on your final!
Your final will be a pitch to potential investors about a location you want to install a cellular network, a product that uses the GSM spectrum, or telephony service.  Your project should be useable in developing communities and you should have an understanding of the background of the region or people your service or product would target. 

For next week you will present the class with a prototype in order to beta test and allow us to provide constructive criticism.
The prototype can be a simple paper prototype or a complex system. The objective is to have a clear understanding of the product or service. In addition to your prototype prepare your inital pitch.  


## Week 6
### Prototype Workshop
+ Present your prototype.  
+ Present your initial pitch.  


## Week 7
### Final Presentations / Pitch your Project
