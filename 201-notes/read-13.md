
#Readings

Local Storage is a potent tool that can personalize the user experience on a site by remembering data about the user or even their inputs.

Reading
[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

Why would a developer use local Storage for a web application?  
> Local Storage can be used to implement features such as a logged-in state as they travel to different pages. It can remember settings like dark mode and other accessibility options. Users can personalize their profiles, and the site will remember their settings without the use a of database, or having to modify a Schema for small features. 


What information should not be stored in local Storage?  
>Passwords, and personal identifying data such as names and birthdays. Anything that can be used as a way to exploit the user.



Local Storage can store what type of data? How would you convert it to that type before storing it?  
>Local storage stores all data as strings, so it may be required to .stringify() prior to sending data into Storage. When reading stored data, you can use the JSON.parse() method to turn data from a string back into its standard datatype.




## Things I want to know more about
