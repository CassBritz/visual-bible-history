# Visual Bible History

I've always wanted to view the history of the bible in a visual way. This web app will attempt do just that. I am putting this on github so that others will be able to download it and to have a backup of sorts.

I want to include a few things:
1. A **family tree view** to trace Jesus' blood line BUT also attempt to capture all Bible Characters as far as possible.
2. A **time line view** to see when certain people lived
3. Extending this time line view to see when certain events happened. (e.g. the fall of Isreal, the Flood, when the Abrahamic covenant went into fulfillment and so on)

This is an ongoing project and it's going to be slow! Why?
1. I am working on this in my free time
2. I am using this opportunity to try doing the entire SDLC, from design to you know, whatever.
3. I've only just started using angular and am still learning how to use it correctly *(Update 5/5/2021: I've been using Angular for roughly a year now and feel much more confident about this)*
4. Sass... Same point as above.
5. I am sure I am forgetting something. Oops. 

Progress for the entire project will be tracked [here](https://trello.com/b/QA7xKg5p/task-board) by means of a regular kaban board. I love the scrum methodology but since I am a full team of 1 at this stage, I think I will not do full scrum planning etc. I'm just going to add as I see things are needed.

#### Journey Notes
*28/07/2020* OMW, have you seen [this website](https://www.figma.com/)? I love it. Wow! Helped me created the design. Has an XD feel to it. And is free for your first few projects. 
Created the design of what I am thinking of [here](https://www.figma.com/file/IiqK5ku18xePBP1QoIQM2C/Bible-His-Story?node-id=0%3A1)

*30/07/2020* So I've done a little research and it did not take me very long to discover Firebase. I think I am going to give this a go. But a new problem arises. Originally I had said I am going to do the 'view page' for this app. But I realise now that I probably need to do the crud so that I can start to add data. Whoops. I will try to finish up the design for the create today. Links I might need:
[Nice tutorial](https://www.techiediaries.com/angular-firebase/angular-9-8-firestore-database-crud-tutorial/)
[Official AngularFire package](https://firebaseopensource.com/projects/angular/angularfire2/)

*5/5/2021* So... I told you this is going to be a slow process. Life. Sigh. On the up side, I have taken the reigns here again and I have a little more experience now around Angular and NgRx. What I still need to learn is Angular Fire. But that's not so bad. As I was designing this last time I realised that I am going to need a framework of some type that can help me with the css layout. I had thought of bootstrap but I don't quite know how to integrate that with Angular. Now that I have a bit more knowledge I see a lot of things I need to change on this plan. I want a nice way to be able to show it. So I've replaced the checkbox task list with the kaban style table above. If you want to see that first checklist I guess you can look in the commit history. 🙂

*5/5/2021* One other thing: I was able to create an empty angular project and firestore and connect the two together AND deploy it. [Here is the link](https://chronicles-c7e22.web.app)
