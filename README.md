# Visual Bible History

I've always wanted to view the history of the bible in a visual way. This web app will attempt do just that. I am putting this on github so that others will be able to download it and to have a backup of sorts.

I want to include a few things:
1. A family tree type of view to trace Jesus' blood line BUT also attempt to capture all Bible Characters as far as possible
2. A time line view to see when certain people lived
3. Extending this time line view to see when certain events happened. (e.g. the fall of Isreal, the Flood, when the Abrahamic covenant went into fulfillment and so on)

This is an ongoing project and it's going to be slow! Why?
1. I am working on this in my free time
2. I am using this opportunity to try doing the entire SDLC, from design to you know, whatever.
3. I've only just started using angular and am still learning how to use it correctly
4. Sass... Same point as above.
5. I am sure I am forgetting something. Oops.

## TO DO

Here I have added a really basic task list of what I think I am going to need to do. I put this here so that I have somewhere I can refer to.

### Family Tree
> I will first do the 'View' Page
#### Design Stuff

- [x] create a design of what I want the app to look like. Use XD or something 
- [ ] put my design through a ux test by asking a couple of people what they think
- [ ] do a technical store first design

#### Coding Stuff


##### Basics
- [ ] Create Module for Family Tree
- [ ] Create Models for Persons, Tags, and the relationship PersonTags
##### Server-ish
- [ ] Create adapters and services to connect to external service/DB
- [ ] **Research & implement** Create a DB and a service endpoint. (Questions: HOW??? Used to use PHP for this. Still viable?) 
##### NgRx-ish
- [ ] Create State for Persons Tags and PersonTags (reducer, incl. LoadStatus')
- [ ] Create Actions
- [ ] Create Selectors
- [ ] Update Reducer
- [ ] Create Effects
##### Container-ish
- [ ] Parent Container
- [ ] Family Tree Component
- [ ] Card component to show character information
- [ ] **Research & implement** How do I do the fancy animation Stuff that Angular is so cool about?? How do I draw on canvases. Is this something I can do?

#### Journey Notes
28/07 OMW, have you seen [this website](https://www.figma.com/)? I love it. Wow! Helped me created the design. Has an XD feel to it. And is free for your first few projects. 
Created the design of what I am thinking of [here](https://www.figma.com/file/IiqK5ku18xePBP1QoIQM2C/Bible-His-Story?node-id=0%3A1)

30/07 So I've done a little research and it did not take me very long to discover Firebase. I think I am going to give this a go. But a new problem arises. Originally I had said I am going to do the 'view page' for this app. But I realise now that I probably need to do the crud so that I can start to add data. Whoops. I will try to finish up the design for the create today. Links I might need:
[Nice tutorial](https://www.techiediaries.com/angular-firebase/angular-9-8-firestore-database-crud-tutorial/)
[Official AngularFire package](https://firebaseopensource.com/projects/angular/angularfire2/)
