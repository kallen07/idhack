PEACE CORPS WEB APP (GO EXPLORE THE PEACE CORPS)
DOCUMENTATION

TEAM MEMBERS:
Elena Cokova 			(elena.cokova@tufts.edu)
Kevin Dorosh 			(kevin.dorosh@tufts.edu)
Kalina Allen 			(kalina.allen@tufts.edu)
Kevin Liu  			(kevin.liu@tufts.edu)
Jeremy Colebrook-Soucie 	(jcoleb01@tufts.edu)


THE IDEA:
This web app is intended to pipque interest among highschool & college 
students (rather than to recruit people to apply for positions).


MAIN STAGES:
1. Code that can get all the data from Peace Corps' API- this eventually 
   became CallWebAPI()
2. Code that parses the data from CallWebAPI and chooses a random job 
   'opening'- which eventually became CallPeaceCorps()
3. Code that displayes the description from the random job as well as a 
   photo (ideally this photo would be related to the job but no photos were 
   avaliable so a URL was hardcoded). Functionality to swipe left to change
   the information displayed.
4. A hashtable that holds keywords (e.g. 'Spanish') that are associated to
   a ranking (e.g. 3). All the rankings start at 0, but increase by one if 
   a description/photo related to that keyword is upvoted.
5. An algorithim that shows related description and photos based on the 
   items that you upvoted. (So the display is only random at the beginnning).


OUR SUGGESTIONS
Pictures from the job openings
Database that includes previous Peace Corps assignments
Allow for use of "and" when searching API with keywords


