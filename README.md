# Cool-Lookin-Rocks
This Tableau project transforms my personal collection into a fun, interactive dashboard. By blending Figma design with custom data shapes, I’ve mapped out everything from color trends to quartz counts. It’s a playful proof-of-concept showing that even a simple jar of rocks can tell a beautiful data story.

# Goals 
To visualize my rock collection. I just had to put it into storage and I’ve always been fond of it. When you see it stacked in a jar or spread about a space, it’s hard to see what spread of data you have. All together on the sheet is much clearer + I learned more about my collection! 

# Finished Project: 
Sift through my rock collection on Tableau Public [here] <br> 
<br> 
**Deliverables** 
- A Tableau Public Dashboard 
-   A dataset of my rocks 

# Programs Used: 
- Excel for data collection 
- Word for Viz Draft 
- Tableau for Visualization 
- Copilot/Gemini 
    - Used primarily to troubleshoot errors 
- Figma for the panning graphic 
- Google Form for the form! 

# Analysis Questions and Findings 
- What color predominates the rock collection? 
    - **We primarily have blue! If you consider clear-white-grey-salt and pepper as the same color, then those neutrals dominate for sure.**
- What type of rock do you have the most? 
    - **I have a lot of Quartz! It’s widely distributed and comes in a lot of colors, so I think that makes sense.** 

# Data Collection and Disclosures and Data Opportunities: 
I collected this data when I was putting up my rocks from a nice little jar into storage to make some space. I want to display them in the future properly in a bigger home. I kept out a few of my favorites— the labradorite slab, the druzy quartzes, and the fluorite pillar— and the rest is safely in a tote. This was definitely a “Why not?” project and less of a “let's be as accurate as possible” endeavor. I started a luster column, but I once again realized I didn’t know anything about rocks or geology and dumped it. Plus, by the time I got around to recording color and suspected type, it was months later, so I also only had the photos to go by! One day I will pull them back out, take better photos (with an object to scale), maybe do a few hardness tests/reactiveness tests so I can narrow down more than just “this one is purple!” and “Google Lens thinks it is a natural diamond” lol.  

# Dash Design and WIPs 
<img width="810" height="464" alt="image" src="https://github.com/user-attachments/assets/2aa15535-141b-4bc4-8616-2b62810efd8b" /> <br>
Viz Theory draft for this one. I want it to be simple, and I liked the idea of introducing a Google Form to take submissions suggestions on what the rock could be (I'm certainly no geologist haha). <br> 

I struggled to make the chaos of the rectangles on the single line look right. Plus, the simple nature of it didn’t really match the ruggedness of a rock collection. It felt more like I was looking at piano keys or children’s watercolors. <br> 

Plus, if it’s not clear, I’m not trying to oversell what this dataset is. A common theme I was seeing in Vizzes on Tableau Public is the use of Large Impactful Titles and clever background usage where the image bleeds into the data. So, a lot of this viz turned into design work! <br> 

<br> 
<img width="970" height="729" alt="image" src="https://github.com/user-attachments/assets/8ed5c1b2-d05d-412a-b51f-69ab6c9d3e13" /> <br>

I took [this photo](https://nantahalagemmine.com/wp-content/uploads/2025/04/gems-mined2-980x735.jpg) from Nantahala Gem mine as it captured a lot of where my gem curiosity and joy originated from as a kid. Finding treasures has always been something I've enjoyed! Since it conveys my level of knowledge well and is the “perfect” container for my rocks, I took it into Figma, a tool I'm trying to get better at, and recreated it! The result came out better than I could’ve hoped! Tying in this sand photo from Pexels and this rock icon from flaticon, we had ourselves all the elements needed to create a fun dashboard! <br> 

<img width="806" height="521" alt="image" src="https://github.com/user-attachments/assets/4f27809f-4825-4745-bd35-aa231b4434e6" /> <br>

Pre-Polish ^, we have most of the bones for the dash. The Filter Texts kinda bug me a bit as they look a bit tacked on.  

# Color Palette Assignment 

I massively struggled with the color palette this project. The brown tones do not play nicely with the bold saturated colors from all the rock types. Any saturated background color would distract from the tray and data itself. I went with a cream background, but the color was so strong. Adding in that gritty texture helped tie the dashboard back towards natural ground tones but didn’t distract the data.  


# Data Construction Notes 

This project had 62 custom shapes! I struggled to apply the photos to their respect ID’s despite them matching. I encountered a VERY [insightful article](https://medium.com/@yvette110/automatic-assignment-of-shapes-in-tableau-dbb104c22e6b) about assigning palletes and modifying the twb file in notepad to automatically align. Sounds lengthy but they had some tips to make it a quicker process, plus doing it numerically was much easier than squinting at the VERY tiny screen you’re provided in the custom shapes menu! <br>

Another struggle I encountered was getting the rocks to wrap to fix the container. I did this in my Dragon Souls Summer project before ultimately abandoning the dot idea, but I couldn’t figure out how haha. <br> 
To achieve this, we reworked the rock page and created a dummy column and rows calculated fields using index() to simulate a structured data space.  

# Credits 
- [Textured Sand](https://www.pexels.com/photo/close-up-of-sandy-beach-texture-in-harris-scotland-34208456/)
- [Rock Icon](https://www.flaticon.com/free-icon/rocks_17943980?term=rock&page=1&position=66&origin=search&related_id=17943980)
- [Rock Tray Reference Photo](https://nantahalagemmine.com/wp-content/uploads/2025/04/gems-mined2-980x735.jpg)

# Reflection: 

There is not enough discussion in the data space for taking simple concepts and making them beautiful. Where are people getting these beautiful graphic design level art skills from??  It’s the design factor that takes a plain dashboard and invites all sorts of users into the space. This was the first dash where I felt that creativity added to the dataset 😊. I also enjoyed utilizing photos in tool tips and getting better at formatting those! It’s refreshing to see how a simple dataset can still work a lot of our data viz brains.  

<br> 

Thank you for reading! 

 

 
