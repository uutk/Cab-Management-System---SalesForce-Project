# Cab-Management-System---SalesForce-Project

This is a very basic `Cab Management System` made for SalesForce Platform as our Summer Training Project. 
We developed it within 1 week, while learning SalesForce side by side, so it's not going to be the BEST logic or cleanest work/project you've ever seen.
This project was developed with the mindset of "Using SalesForce without letting the users know about it". What does that even mean?
We wanted to create a website where users can book a cab, get the cab assigned and then get the bills on their registered E-Mail IDs.All this on SalesForce platform, but the user won't see anything related to SalesForce. They should simply see the website, do their work and be done with it. That's it.


#The Team

Team had 6 members, and here are their names :

1.) [Dhruv Kanojia](https://github.com/Xonshiz)

2.) Hinshu Jain

3.) [Ankit Passi](https://github.com/ankitpassi141)

4.) [Devesh Shyngle](https://github.com/deveshyngle)

5.) Raghav Sharma

6.)  Rasil Banga

We're all in our 3rd year of college and are pursuing "C.S.E" from Northern India Engineering College (N.I.E.C).
Not sure why, but we decided to go with the name "Cab Job" as our project name. Maybe because of some dirty reference lol.

#Limitations

1.) There's no `Driver` access currently.

2.) No real time tracking. Hence, the distance calculated in Bill is the `Straight Path` to destination from pickup.

3.) Poorly written VisualPage Code.

4.) User Passwords saved in Object's field as simple text.

#Strong Points

There aren't a lot of strong points for this project, but I'll list some of them anyway :

1.) Since the project is hosted on SalesForce, the data is being transmitted via HTTPS. So, data is somewhat safe

2.) Based on triggers and classes. So, not `marjor` relationship is needed among various objects.

3.) Proper Errors are generated on wrong data.

4.) Real Time validation of input on Sign Up page.

5.) Highly Customizable

#How to Use

Using this is pretty simple. You'll need to make 4 objects from your side and make some fields in all the objects (would hardly take an hour).
Since this project heavily uses Standard Objects from SalesForce, you won't have to specify objects on each and every page. Most of the work is being done on `Account` Object.
I'll post an image to all the objects and their fields in description as soon as I get the time, so everyone knows which object is being used.
All you need to do is, copy the codes from respective folders and just make just a little changes here and there (if you want).

#File Naming
I've organised all the pages, classes and triggers in respective folders with proper extension. The code is well idented, it won't be highlighted on GitHub, because it doesn't support this SalesForce yet, I guess.
File Naming is pretty simple and straightforward, so there shouldn't be a problem. However, in trigger, I followed a special naming pattern.
For example : `Lead_To_Customers (Lead)`

This says that name of trigger is "`Lead_To_Customers`" and it is being activated on "`Lead`".

Rest is self-explanatory!
