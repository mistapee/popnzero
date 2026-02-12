# popnzero
Pop'n controller set out for 1u keys

![20260212_041912 - Copy](https://github.com/user-attachments/assets/9f1365c6-38a9-44fd-b92d-778f5eeab0ee)


We went and ordered the pcb+plate design with RGB LEDs and keyswitch LEDs, the design is 13.7cmx7.7cm and we're very happy with the results. The layout is angled the same as other controllers, but with appropriate spacing to find your way around the pad while gaming - for instance, the fight board caps we used on the larger controller look amazing on this, but, it loses the spacing and actually playing with it is a nightmare turning it in to a novelty which is everything we wanted to avoid.


![20260212_041939](https://github.com/user-attachments/assets/a2de53e8-954a-4593-96f3-1ed674122d4d)


GPIO used, for technical infos for GP2040-CE or whatever:
0 - aux switch
1 - rgb led
2 - btn8
3 - led 8
4 - btn 9
5 - led 9
6 - btn 7
7 - led 7
8 - btn 6
9 - led 6
10 - btn 5
11 - led 5
12 - btn 4
13 - led 4
14 - btn 3
15 - led 3
26 - btn 1
27 - led 1
28 - btn 2
29 - led 2

5v - to rgb leds
gnd - connected to gnd plane
3v3 - unused



![20260211_163613](https://github.com/user-attachments/assets/1e847bb0-2116-4d36-8ebb-16ec4cec14e8)



-everything below is old and we will come back to

2 types of single PCB, and a dual layer LED version. This will take some time to fill with all the files as I wouldn't give what's needed to get them made without having some to show they work

<img width="35%" height="35%" alt="3D_PCB2_2026-01-04 (4)" src="https://github.com/user-attachments/assets/3b2d4190-b3a2-4075-b966-1a53c9d7b980" />
<img width="35%" height="35%" alt="3D_PCB2_2026-01-04 (1)" src="https://github.com/user-attachments/assets/00538c4f-a4a3-4a71-885a-e395223074e6" />


i've known plenty of people play AC dumps right on their keyboard. we can do better surely?

this is the choc low profile version - i've not updated my models to include the caps for this one.
- actually buying caps for low profile isn't great as they cost a fair bit with little choice especially if you're trying to have the right colours.



<img width="35%" height="35%" alt="3D_PCB2_2026-01-04 (5)" src="https://github.com/user-attachments/assets/03a328be-b2fa-42c9-9198-333771f9cfaf" />
<img width="35%" height="35%" alt="3D_PCB2_2026-01-04 (6)" src="https://github.com/user-attachments/assets/e5977531-3d18-4c0a-ba7a-245e679c0200" />


i originally wanted to make a business card where the design ended up about the size of a credit card. it worked fine but it wasn't very practical. in playing with the Pico sized Pop'n controllers 1u keys are too spaced out. 

i own an official AC size controller i imported from Japan. very expensive, not good enough - so i bought one from Yuancon and love it. but the size is too much, the domed buttond and the size of it (similar to my full sized sdvx etc i guess) the controller gets put away and playing the game isn't as casual and easy as it could be. making other people's pocket/pico ocntrollers brought back the spontaneous fun, set out right to be easy to feel your way around, good reliable switches... the fun came back... pick it up and put it down whenever, but most importantly just naturally pick it up more.

it also became apparent the keys not being round or domed didn't really make a massive difference, its not as if the UI gets confusing due to not matching,. it works fine.




this is the bottom layer of the 2 laye LED version, but i've removed the key LEDs as i've not yet settle on what works. an LED on every key at this size is quite over the top even on the scrappy little test set up i'm using. i do plan on leaving out any mounting holes as once the 9 switches are fitted the bottom layer is very firmly attached and the whole thing is solid and looks cleaner.


<img width="35%" height="35%" alt="3D_PCB2_2026-01-04 (9)" src="https://github.com/user-attachments/assets/8a81427e-2d39-4f13-b5cb-2657aec5ddef" />


this is the top plate to the larger 'pico' version, but the top plate for the 2 layer 1u would be similar. i have no idea where the proper one is right now. on other designs with 'plate' layers the process of importing images to then render in to copper layers is so long winded and annoying. i have a replacement SDVX plate coming up soon that I drew in the copper layers as traces, filled regions then removed traces to end up with my nod to the Yuancon SDVX lite, that I really like, and I'm including the spelling issues too. This here design below, without any copper layers under the solder mask, should _in theory_ work quite well with the upward facing 5050 RGB's, doubling up the mask front and back should still help the logo and design elements to pop. 
we will see as a test run of these plates are arriving today, will update!


<img width="35%" height="35%" alt="3D_popn_pico_plate_2025-12-31" src="https://github.com/user-attachments/assets/01025df1-d91f-4dca-8748-d9a89dd55404" />
