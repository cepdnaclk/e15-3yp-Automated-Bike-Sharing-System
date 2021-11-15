---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e15-3yp-Automated-Bike-Sharing-System
title: Automated Bike Sharing System
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Automated Bike Sharing System

---

## Team
-  E/15/179, KARUNARATNE S.M.A.K., [anandi.karunaratne@gmail.com](mailto:anandi.karunaratne@gmail.com)
-  E/15/092, EKANAYAKE I.U., [imeshuek@eng.pdn.ac.lk](mailto:imeshuek@eng.pdn.ac.lk)
-  E/15/325, SANKALPANA W.A.P.C., [chalanisweerarathna@gmail.com](mailto:chalanisweerarathna@gmail.com)

## Table of Contents
1. [Introduction](#introduction)
2. [Hardware & Software Designs](#hardware-and-software-designs)
3. [Links](#links)

---

## Introduction  

[Intro](https://youtu.be/jAxNeGySm2U)  



Today vehicles are a huge problem in the world, starting from the environment pollution arranging parking space causes deforestation. Moreover, people don’t have enough time to workout and to attend a gym. Therefore Today, more than 600 cities and more than 200 universities around the globe have their own bike-share systems, and more programs are starting every year. The largest systems are in China, in cities such as Hangzhou and Shanghai. In Paris, London, and Washington, D.C. highly successful systems have helped to promote cycling as a viable and valued transport option. Bike-share has taken many forms over the course of its development, from free bikes left for a community to use at will to more technologically advanced and secure systems.

As the most of the universities have a wide area of land, transportation within the university causes the time to waste, accidents, congestion because of using the private vehicles, parking problems and the energy consumption related to the mobility of workers and students of the universities. The bicycle sharing programs have received increasing attention in recent years with initiatives to increase bike usage, better meet the demand of a more mobile public and lessen the environmental impacts of our transportation activities. So, the project aims to introduce automated bike sharing system to minimize the above impacts while evaluating the mobility patterns of academic campuses and assessing the energy consumption and pollutant emissions produced by the universities. This system provides the users to unlock the chosen bicycle in the substations via a mobile app and start riding, check the availability of bicycles and authorized people to track the path of rides of all users.

 

Mainly targeting universities with a wide area of land to have a proper transportation system for inter-travel other than using private vehicles or taxis. This can be categorized into a few clusters.

- Mobility for employees – providing transportation options that assist University employees to conduct their duties and responsibilities in an efficient, environmentally-friendly manner
- Safety through reduced motor vehicle traffic – reducing the amount of motor vehicle traffic in areas with complicated infrastructure or high pedestrian volumes
- Health through increased physical activity – providing methods for employees and students to add more movement into their daily routine, thus impacting alertness, health, longevity, and more
- Environmental benefits of reduced motor vehicle traffic – reducing greenhouse-gas emissions, decreasing impervious surfaces for parking lots, decreasing the need for road maintenance 
- Social benefits through enhancement of bicycling culture – supporting a culture that sees cycling as a preferred transportation mode choice, and a community that respects and works with the different transportation options
- Convenience factor – providing efficient transportation choices to aid users in arriving at destinations quickly and safely by reducing the need to always be in search of a bicycle or car parking area as well as the need to have to do own maintenance on bicycles
- Economically self-sustaining – implement a system that will pay for itself and reduce transportation costs for the campus community
 

- Research opportunities – provide the potential for research in urban planning, kinesiology and community health, marketing, environment, engineering, and more, with opportunities to publicize findings internationally 
- Education campaign – participate with the campus-wide bicycle education campaign, by creating a platform for information sharing
- Enhanced Image of the Campus – Implementing a bicycle sharing program would improve the campus’ standing as a preferred employer and be an attractive feature for prospective students. This could positively impact recruitment and retention.


## Hardware and Software Designs

### Network and Web Application  

First to handle the whole system, a web application will be implemented for the administrative purposes. Basic features will be registering the riders, monitor the bike usage and to track the picks and docks.

Next, for the users, an mobile application will be implemented in android platform which helps to find the nearest docks using the google maps, and to unlock it via the QR scanner by scanning the QR code in the lock.

For these applications HTML, CSS, JavaScript and PHP will be used for the front end.  

### HARDWARE DESIGN  

Implementation of smart locks for bike dock stations is the main task under hardware design. Smart lock is going to be designed using a linear actuator (solenoid) which triggered when the current flows. The smart lock unlocks when the rider reads the QR code and locks when the rider returns the bike.

Each lock in dock station contains RFID reader and lock components which are connected to an Arduino Nano board. Those Arduino Nano boards are connected to an Arduino mega board using I2C communication bus. GSM/GPRS module is used for the wireless communication between the hardware components and the server. In between the server and the hardware components, there is a MQTT broker which is primarily responsible for receiving all messages, filtering them, decide who is interested in it and then sending the message to all subscribed clients.  

### Video animations and Demonstration

- [The Locking Mechanism Simulation](https://youtu.be/phcyKz8i7iQ)  

- [Locking Mechanism Design Animation](https://youtu.be/VSDKW8W9EvU)  

- [Demonstration Video](https://youtu.be/fSkReVzAp0A)





## Links

- <a href = "https://github.com/cepdnaclk/e15-3yp-Automated-Bike-Sharing-System" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e15-3yp-Automated-Bike-Sharing-System/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
