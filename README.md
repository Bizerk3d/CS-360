# CS-360
Coursework for SNHU's CS-360: Mobile Architecture and Programming

**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**

The goal of this app was to create an inventory tracking app that utilized CRUD methods to add, edit, and delete items in an inventory with ease.  It was designed to allow users easy access to this functionality over the top of a database (SQLite) that stored their inventory - so the user need is anyone with an inventory to keep tabs on, whether professionally or personally.  The app also features a second table for login information, so that users can authenticate credentials.  Finally, an SMS alert system was set up to notify users when inventory reaches critically low levels.

**What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**

I designed a pair of login screens - one for registration and one for login for ease of authentication.  For the Home page of the app, I utilized a RecyclerView with a Grid Layout so that the items are easily viewed, can easily be scrolled, and so that it automatically updates when changes are made, such as deletions/additions.  Additionally, an edit item screen and a new item screen were utilized as well, for the aforementioned reasons.  My designs were made with simplicity in mind and for ease of user interaction.  They were successful because they all serve a different purpose, so the app keeps the desired functionality and keeps design clean with different screens for different needs.

**How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?**

I broke down each activity on its own and incrementally worked on each part, testing frequently, especially once I started bridging activities together to make sure everything still functioned well.  This is an approach that will serve me well on future work.

**How did you test to ensure your code was functional? Why is this process important and what did it reveal?**

I frequently used the debugger in addition to just running the code after adding new methods, functions, activities, etc.  The debugger gave me great insights a few times where something was crashing or not functioning as expected.

**Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?**

I had to innovate the most on the development stage to add new elements that were unexpected, such as when I encountered challenges from a standard grid layout, so I used the recycler view to make a much better main page of the inventory for the users.           

**In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

Overall, I think it all demonstrates a fair amount of aptitude, but the seamless functionality in the Home page, where users can easily add items and delete them - all with appropriate system messages as needed and automatically moving activities when it makes sense to do so.  Since this is the core of the app, I think this was the most successful area of my design.
