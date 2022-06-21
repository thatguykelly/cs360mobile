# cs360mobile

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

    The goal was to create a functioning inventory app. There were a few user needs. 
    1) We needed to check the username and password against the database when the user attempts to log in. If the user has 
       never logged into the application before, the user should be able to create a new login and password. The 
       application needs to save these to a table in the database. 
    2) Create: The user should be able to add items to a database.
       Delete: The user should be able to remove items from a database.
       Update: The user should be able to change the value associated with individual database items (e.g. the number of a 
       specific item in an inventory or the date of an event). 
       Read: The user should be able to view all of the database items displayed as a grid.
    3) If the user grants permissions, the application should send alerts to the user as SMS messages. The alerts 
       correspond to the specific notification trigger of the application you chose (low inventory, an upcoming event, or
       reaching a goal weight). If the user denies permission, then the rest of the application should still continue to 
       function without the SMS messaging notification feature.
    4) Employ industry standard best practices such as in-line comments and appropriate naming conventions to enhance 
       readability of code.
       Have I kept my classes concise?
       Is my style consistent throughout the code?
       Would my naming conventions make sense to anyone else who looked at my code?
       Do my in-line comments contain enough useful information?

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
    
     I had a login screen. There was a register screen for first time visitors. The main Home screen was the list of items 
     in a grid. There is a pop up screen for adding an item as well as one for editing an item. Deleete and SMS notifications
     options were on the bottom of the inventory screen. These included pop up screens to confirm or deny. I wanted it to be as 
     easy as possible for the user to navigate. I feel they were successful because it worked. It delivered the information in
     a clean manner.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

    I had to research much of the code from our Zybooks textbook. I liked the idea of seaparating some of the code into separate 
    Java classes. I used trial and error frequently. This was a good strategy for me since I'm not very familiar with Android
    Studio. I feel that the code trees will be extremely useful in the future and I plan on referencing them on more projects.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

    I used the testing features within Android Studio. Once I had problems, I would diagnose and figure them out. Needless to say,
    I did have alot of problems as I worked. It's important because it was able to show me where pieces of the puzzle dont fit. It
    taught me how to trouble shoot and gave me insights regarding how Android Studio works.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

    The Java code was the toughest for me. I don't have much experience with it yet. While the Zybooks exercises gave us a lot to build off of, the official java site       was invaluable. I had to start over from my project 2 design. It was close to it but the xml was messy and I wanted a different look. 
    

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

    I believe right now I'm efficient in the UI design and building with xml. I really enjoy this aspect.
