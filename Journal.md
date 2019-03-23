# 19/02/2019
Used my previous work on coursework 1 to create my first package, spent time sorting out the files neately and also looked over my code
so that i could create a helpful guide as to what each of the  scripts do and how they work, only problem i ran into was trying to remember how
each one worked but it was quite easy in the end.

# 08/03/2019
Made a first person movement from scratch using two scripts one to control the camera with the mouse and the other to control the movement of the object, the main problem i was having was that due to the way that the script was it allowed for the camera to swing all around the Y axis, so you could spin around the Y axis which felt a bit sick and not good at all. to fix it i looked online and found what was called a clamp by using the clamp i could set it so that the camera could only move in the Y axis a certain way of course this could be used for the X axis too but i wanted needed it to be done for the Y axis since it would make the first person expierence feel a whole lot better. after saving it i tested it for myself and everything worked fine in the end of course the movement felt quite fast but that is a easy fix since i can adjust the speed of the character in unity itself so i believe this package is quite a success although there isn't much in terms of scene assets.

# 08/03/2019
Made a package that utilises OnTriggerEnter, it's to open a door but it doesn't mean it's for the door only could probably use it on other 
items that i want to move when the player enters it's collision like the floor. was having a problem with getting the animations to work
due to triggers, at first i used a Trigger parameter but i was having difficulties with the script so instead i opted to use a Bool which was easier to understand and use in my final package.
