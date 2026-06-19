---
title: "Pendant YSWS Project"
author: "esemv"
description: "My project for Pendant YSWS"
created_at: "2026-06-18"
---

# JOURNAL.md

My journey in designing and making this project!

### Total Time: approx. 5 hours

For this project I wanted to make a 'light bar' that turns on gradually with the twist of a knob, but circular.

I used EasyEDA to create the schematic, and I found that the LM3914 IC with a potentiometer would be good for this.

I was able to look at the datasheet and other examples to piece together the schematic. The hardest part was finding what LEDs and switch to use.

The switch is there to make it so that I can change the mode from 'Dot' to 'Bar', which is turning on one at a time, or cumulatively turning them on, leaving the one's before on.

Here are some photos from along the way. The schematic took me about 3 hours to make, including the time of researching the components and the datasheet.

<img width="748" height="339" alt="Screenshot 2026-06-18 at 6 30 25 PM" src="https://github.com/user-attachments/assets/70d4300b-e2b8-473b-bc3a-6021184d71ac" />

<img width="449" height="380" alt="Screenshot 2026-06-18 at 8 13 55 PM" src="https://github.com/user-attachments/assets/39884ca4-d846-45f7-832a-968140373929" />

<img width="824" height="371" alt="Screenshot 2026-06-18 at 8 16 42 PM" src="https://github.com/user-attachments/assets/adc80c75-7a76-413f-925d-c14f79cb5141" />

I then converted this to a PCB, and it took about 1 hour to wire and add the ground pour. This was my first time doing a ground pour, which was cool. I also figured out that EasyEDA has a build-in function to arrange the LEDs in an even circle.

Here are some photos!

<img width="588" height="573" alt="Screenshot 2026-06-18 at 8 24 31 PM" src="https://github.com/user-attachments/assets/3cb54346-3b9f-4769-9b05-2a565c7a3821" />

<img width="675" height="590" alt="Screenshot 2026-06-18 at 9 34 00 PM" src="https://github.com/user-attachments/assets/b4a55ba2-ca76-4564-9dc3-964b5e923ce3" />

<img width="585" height="543" alt="Screenshot 2026-06-19 at 6 00 24 AM" src="https://github.com/user-attachments/assets/666084e4-cb1b-4487-b015-0054dcacea01" />


Finally I made the case, which took about 1 hour. For now, it is two parts where the bottom is covered, and the top is open to see the LEDs and turn the knob. They will be joined with screws and heatset inserts. I may improve this in future but for now it'll work fine!

<img width="791" height="619" alt="Screenshot 2026-06-19 at 1 15 15 PM" src="https://github.com/user-attachments/assets/cb5a4572-98c1-489c-8ba2-1795d72da397" />
