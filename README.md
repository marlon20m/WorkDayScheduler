Work Day Scheduler
 
 For this HW I went through all of the trails and turbulations nessecarry and learned definitively that less is more. At first I created my html through tables (without bootstrap) stubbornly doing things my own way and added a jquery menu theme called accordion specifically to make the design of the UI nicer. 
 
 Upon inpection of the work that I had done so far I realized that there was no way that I would be able to dynamically reuse this html to create a functional UI not to mention the Jquery menu was making it slow. Never the less I left it on the UI for design purposes and it did not look bad. 
 
 I redid the entire html tables in Jquery form but I did not realize that I was missing bootstrap for later functionality. 
 
I then began my init function which created all of my hours attaching them to my table rows along with a save button function to add all of my textarea(#eventStored) to local storage. 

*This however was faulty becasue I came across a completely static functionality where I could only add this save function 9 times for the local storage to work. 

THIS IS WHERE I DECIDED TO have my bootstrap added and commence a for loop for the save while also adding the moment js to the init function which is where I created my table and hours. I added var militaryTime and created a if else statement adding the momentjs currentTime for comparison. And created a color change. 

I apologize for having so many comments and I hope this explains better the process that I went through to get this result. I have learned that less is more with this HW and realize that I should have let go of the things that I am use to and get comfortable with new code languages because in the long run it will benefit me immensely. 

Thank You for Reading !
