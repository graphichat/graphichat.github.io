---
title: "Ubre for Rural and Non Urban Areas"
time: 2024-12-22 11:00
categories: [Design Process]
tags: [Design Process, Portfolio]
---

# Introduction

Expanding the Uber app to cater to rural and non-urban areas presents a unique opportunity to bridge the gap between technology and accessibility. The target audience for this project has users with diverse challenges, including low digital literacy, limited network connectivity, and difficulties in pinpointing accurate locations in remote regions. Addressing these challenges requires a user-centric design approach that also should considers the constraints of the environment the user is in but still deliver an intuitive and reliable overall solution.

This document which I have created outlines the detailed design process I have done to create a solution that enhances the Uber app’s usability for rural users. I made sure to capture every stage of the process from understanding the unique pain points and constraints of rural users to ideating, prototyping, and justifying the proposed solutions.

Key highlights of the document include:

- Researched the challenges faced by rural and non-urban users when using private transport services.
- User personas that represent the primary user groups, ensuring solutions are tailored to their specific needs.
- Ideation and brainstorming processes that focus on creative, inclusive, and practical solutions.
- Low to mid-fidelity wireframes demonstrating key features and user flows for the proposed solutions.
- A detailed explanation of the design choices, supported by insights from the user analysis and problem definition.

By documenting this design process, I aim to create a path so that it not only resolves the immediate pain points but also sets the foundation for further innovation in rural transportation services. The proposed solution aligns with Uber’s goal to expand its reach while fostering trust, usability, and satisfaction among rural users.

# Defining the Problem

Expanding ride-booking services like Uber to rural and non-urban areas presents unique challenges due to the distinctive needs and constraints of users in these regions. Many rural users struggle with low digital literacy, limited access to reliable network connectivity, and a lack of familiarity with app-based solutions. Moreover, the absence of clear landmarks and poor GPS accuracy further complicate pick-up location identification.

Additional challenges include:

- Users’ reliance on family members or neighbours to book rides due to tech unfamiliarity.
- The need for scheduling rides from locations where users are not physically present.
- Drivers’ unfamiliarity with rural routes and local navigation nuances.
- Language barriers and the preference for cash transactions.

The current solutions do not sufficiently address these constraints, leading to inefficiencies, mistrust, and a poor user experience. The task requires designing an intuitive, reliable, and accessible solution that simplifies ride-booking, supports offline functionality, and accommodates users with varying levels of technical proficiency. The goal is to ensure that the solution aligns with the unique cultural, social, and technological realities of rural and non-urban users while enabling accurate location sharing, efficient scheduling, and seamless communication with drivers.

# Researching the Problem

Often when we think of digital solutions for the Rural and Non urban people, we need to consider lot of variables. There are challenges in various dimensions and often the user requirements are completely different from that of Urban population. Here are some of the problems I identified during my research on this problem.

## 1. Technology and Digital Literacy

- People have low familiarity with Apps, so they often are unaware of complex navigation gestures like zoom, pan, swipe gestures and other hidden gestures. Any solution we build should be simple and any action should be made visible and simple to achieve.
- In Rural India, people prefer to have things in their own language. Also many might not know English and hence when building the app, it should be local language first approach.
- There is still limited Internet coverage in Rural and Non Urban areas. Hence the solution should be adaptable to low network.
- Also Rural people might not be having high processing mobile devices. Hence the solution we bring should be minimal and should not be consuming much processing power.

## 2. Infrastructure Limitations

- In many rural places there is no proper landmarks available so pinpointing the exact location without gps is a challenge
- Low GPS Accuracy in cheap mobile phones might lead to wrong location sharing in time of booking.
- There might be less drivers available since many prefer to go to urban cities to earn more.

## 3. Social and Cultural barriers.

- Many users depend on younger generation family members to help with apps.
- Many people often call up their personal connections to book cabs or arrange vehicles for them
- Users tend to not pay through card, in app payments, and prefer to pay through cash or upi in some cases.
https://www.figma.com/board/iNtB8pcgQ4lyIfBslXpMk5/Uber-for-Rural-and-Non-Urban-Users?node-id=3-5&t=B40P3ESWX5KX7Lmo-4



# User Personas

When thinking about the users there are different types of potential users in Rural Areas. These include children going to school, graduates going to college, farmers going to town, ladies going to shopping, etc. I have picked two personas due to time constraints.

### User Persona 1 : Manoj Kumar of 40 Years is a farmer

Ravi is a farmer who lives on the outskirts of a village and relies on Uber for transport to the local market. He is responsible for delivering fresh produce to the market on time to earn his livelihood. Ravi has limited familiarity with technology and struggles with navigating complex mobile apps. Due to unreliable network coverage on his farm, he often depends on his son to help book rides. He would like to independently book rides for his recurring needs while ensuring the accuracy of pick-up locations.

### User Persona 2 : Sunitha is a married woman of 34 years is a house wife

Sunita is a homemaker in a small town who uses Uber to arrange transport for her children’s school pick-ups and drop-offs, as well as rides for visiting relatives. She is moderately tech-savvy but often finds app interfaces overwhelming. Sunita is keen on ensuring that her children reach school safely and that her relatives are picked up on time from bus stops. She prefers cash payments but occasionally uses digital wallets for convenience.

please find the detailed personas here


https://www.figma.com/board/iNtB8pcgQ4lyIfBslXpMk5/Uber-for-Rural-and-Non-Urban-Users?node-id=9-209&node-type=section&t=B40P3ESWX5KX7Lmo-11

# Ideation on the Problem

Here is the ideation bubble map I have created when ideating for the Uber for Rural and Non Urban Users.

https://www.figma.com/board/iNtB8pcgQ4lyIfBslXpMk5/Uber-for-Rural-and-Non-Urban-Users?node-id=14-676&node-type=section&t=CtFdgIvL15Xsxtg6-11


During the ideation phase, I was focussing on addressing the unique challenges faced by rural and non-urban users while using ride-booking services like Uber. I had listed lot of ideas brainstormed to ensure inclusivity, usability, and scalability. Below are the key ideas generated during this stage:

### Key Features and Solutions:

1. **Simplified Booking and Scheduling**
   - **Book Based on Slots:** Allow users to book rides in advance for specific time slots.
   - **Predefined Templates for Recurring Rides:** Enable quick selection of frequently used routes such as “Home to Market” or “School Drop-off.”
   - **Book for Family/Friends:** Support booking rides for others with ease.
2. **Enhanced Location Features**
   - **Option to Add Landmarks/Favourite Spots:** Users can save specific locations for faster selection.
   - **QR Codes for Sharing Precise Pick-up Points:** Simplify location sharing for areas with poor GPS coverage.
   - **Look Around Option:** Provide an option to view nearby drivers or pick-up points.
   - **Allow Users to Describe Pick-up Points Without GPS Reliance:** Text or voice-based descriptions for remote locations.
3. **Accessibility Enhancements**
   - **Local Language Support:** Ensure the interface is available in regional languages.
   - **AI Voice-Based Booking:** Voice-assisted booking for users with low digital literacy.
   - **In-app Guides:** Simple tutorials on how to use features, delivered in-app.
4. **Connectivity Solutions**
   - **Work in Low Network Areas:** Ensure core functionality is available offline or with minimal data.
   - **Booking via SMS/WhatsApp:** Alternative booking methods for users without app access.
5. **Driver and User Coordination**
   - **Share Driver’s Real-Time Location with Family Members:** Allow users to share live trip details.
   - **Notify Users When a Driver is Nearby:** Push notifications for better coordination.
   - **Display Expected Wait Times:** Provide accurate wait time estimates for rural areas.
6. **Optimised App Experience**
   - **Minimal App Size:** Ensure the app is lightweight and compatible with older devices.
   - **Optimised App Mode:** Low-power mode for extended usability during long trips.
7. **Social and Economic Features**
   - **Group Users from Nearby Locations:** Offer affordable shared rides for users in close proximity.
   - **Incentives for Booking for Others:** Reward users for facilitating rides for neighbours or family.
   - **Transparent Pricing Breakdown:** Show detailed fare estimates to build trust.

# Flows

https://www.figma.com/board/iNtB8pcgQ4lyIfBslXpMk5/Uber-for-Rural-and-Non-Urban-Users?node-id=23-1494&node-type=section&t=CtFdgIvL15Xsxtg6-11


# Design Wireframes

## 1. Booking a ride.

In Rural users often go to regular places. For regular use there might be 4 to 5 places where they go regularly. Hence I have brought the suggestions to the booking screen. There are times when people book for relatives and friends often because of relatives might be illiterate or not tech savvy. So gave option to book a ride to a friend also in the main ride screen.

![[Pasted image 20241222211550.png]]

## 2. Selecting a Location

When selecting a location the user has to pick mostly from the known locations. If it is his first time there should be option to see and know his location and also save that location for future booking.

![[Pasted image 20241222211607.png]]

# Conclusion

In this project, I aimed to address the unique challenges faced by rural and non-urban users when accessing ride-booking services like Uber. The design process involved identifying pain points, such as low digital literacy, poor GPS accuracy, limited connectivity, and cultural nuances. I proposed a variety of solutions through ideation, focusing on inclusivity, usability, and scalability.

Key solutions included features like predefined location templates, QR-based location sharing, voice-assisted booking, offline capabilities via SMS/WhatsApp, and user-friendly interfaces with regional language support. I also explored enhancements to driver coordination and optimized app experiences tailored for older devices and low network areas.

This project demonstrates a user-centric approach to problem-solving, addressing real-world issues with thoughtful design solutions. Given additional time, I would further refine these ideas to make the product even more intuitive, scalable, and impactful. It has been a fulfilling experience to create designs that could significantly improve the lives of rural and non-urban users while aligning with business goals.

I thoroughly enjoyed working on this project, as it allowed me to tackle unique challenges and design solutions that could make a real difference for rural and non-urban users. It was both exciting and rewarding to brainstorm and implement ideas that cater to diverse user needs while aligning with business goals. I believe that, with more time, I could refine the product even further to make it even more user-friendly and impactful.
