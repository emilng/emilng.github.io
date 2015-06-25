---
layout: post
title: Paperless Post
---
<div class="showcase-header">
I worked as a full-stack developer for 5 years on the stationery customization tool and on the presentation of the customized stationery to recipients. Initially, most of the front-end work was in Flash but due to its decline was replaced with JavaScript. When adding front-end functionality, I often had to update the accompanying back-end which was written in Rails and Ruby with a Postgres database. Back-end changes included updating the API, the content management system (CMS), and relevant unit tests. 
</div>

### Minimum Viable Product
I was the first full-time employee and was the primary developer working on tools to allow users to create their own custom stationery. I implemented much of the initial stationery customization functionality for the site launch including the photo panning and resizing functionality seen below.

![photo stationery](/images/paperlesspost/photo_stationery.gif)

### Stationery Sets
I wrote code that allowed for automated rendering of different arrangements of stationery sets. Cards and envelopes could be reordered, positioned and rotated in relation to each other, drop shadows could be customized, and sets could be rendered as flat or standing.
<div class="inline-container"><img class="inline-image" src="/images/paperlesspost/multicard_layouts_1.jpg" alt="rotated layout" /><img class="inline-image" src="/images/paperlesspost/multicard_layouts_2.jpg" alt="rotated layout 2" /><img class="inline-image" src="/images/paperlesspost/multicard_layouts_3.jpg" alt="standing layout 2" /></div>


### Envelope Content Editing
I was responsible for all of the editable features of the envelope. The style of the text, the postmark, the stamp, envelope liner and envelope itself are all&nbscustomizable.

![envelope content editing](/images/paperlesspost/envelope_content_editing.gif)

### Envelope Opening Animation
The envelope opening animation uses a real-time 3D rendered envelope. I created the initial texture map template and animation tool for determining the timing for the animation.

![envelope opening animation](/images/paperlesspost/envelope_opening.gif)

### Envelope Interaction
After the initial card animation, one can interact with the envelope by viewing both sides and opening and closing the flap. I programmed all of the interaction including inertia physics.

![envelope interaction](/images/paperlesspost/envelope_interaction.gif)

### Back-end Work
#### Updating Data Models
Initially, each stationery card had only one side so the data model only allowed for a single text container. I refactored it to allow for multiple text containers and wrote a script to update all the stationery to use the new model.  

#### Improving CMS Workflow
When designers created new stationery, text container dimensions had to be manually entered into the CMS. The designers would determine the dimensions in an image editor then copy over each value separately into the CMS. I created a tool that allowed them to select the text area directly on the image in the CMS, saving them many hours of work.  

#### Rewriting Flash Functionality
The decline of Flash necessitated porting all of the Flash functionality to HTML so that existing stationery would render exactly the same as before. I did extensive work in parsing vector graphics and fonts in the Flash file format and extracting the formatting.


