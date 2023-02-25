# Mobile-Architect-Programming

    The final project for our CS360 Mobile Architect and Programing class was to develop a working app. We were given three options to choose from. I chose to develop an inventory tracking app to help a user track and manage available inventory. The main requirements for the app were as follows:
  - Have a login feature with a database to store user login information
  - If a user did not have an account, an option to create an account must be included
  - Inventory must be able to be added, removed, and updated to a database and displayed as a grid
  - The app must utilize notifications (including implementing permission requesting) to notify the user of low quantities
  
    Many different screens were necessary to address these requirements in an organized fashion. The login screen would accomodate logging in, the registration screen helped users create an account, the main screen displayed all items in the inventory within a recyclerview, and a settings screen was needed to toggle permissions for notifications and set when to deliver those notifications. I also chose to implement an item update screen to handle all updates made to existing items. This choice was made to avoid overwhelming the user with clutter on the main screen. That was only one choice made with the user in mind. Text sizes and item spacing was also chosen with the user in mind, as well as a contrasting color choice which both helps the user and adheres to android guidelines. The overall flow of screens was another choice made with the user in mind. I wanted to model the app around the user's workflow and how I expected them to navigate from screen to screen. In the end, these choices lead to a clean app that is setup to help the user track their inventory in the best way possible.
  
    Developing the app was a process that was done in stages. Documenting requirements was first. Documentation had to be thorough to ensure a successful product. The next phase was planning. Wireframe templates were designed to envision what the screens would look like and how they would interact with eachother. This step helped save a huge amount of time in development as I already had an idea of where everything was going and how it should act. Lastly was the coding. This, by far, took the most time and the process for this changed over time for me. It started out all over the place, jumping from issue to issue. I found that it caused smaller issues to become larger and ended up pivoting to a more focused development where I stayed on one part as much as possible until it was completed. This cut down on issues and sped up development drastically. In the future, this is how I will start my development. Testing was done in stages, usually at the end of a finished screen, but is also something that ended up changing. I found half way through development that my database stopped recording new users. I had tested the account creation process a few times at the beginning of development and then stopped, thinking it was fine. Something that I did later in coding had broken that process and it went unfound for a long time. This is when I started testing everything at the end of a process.
    
    I'm most proud about two parts of this app. The recyclerview is the first just because it is probably the most complex part of the entire app and is something I had never heard of before, let along implemented. It turned out clean and functions well. The other part I'm proud of is the notifications part, particularly requesting permissions for it. This is something that I found out had changed fairly recently with Android now requiring permissions for notifications. Knowing that made it feel a little more real to me in terms of keeping up with the industry.
  
  
Below are version notes that I kept during development while loading new versions each time an accomplishment was made. It helped me backup files, document some of my issues, and ensure I knew what was needed next.


Version Progress

02/15/2023 - User database setup and login function working

02/16/2023 - Add user function working (need to implement confirmation message and check for dups)

02/16/2023 V2 - Add user function now has working confirmation message

02/16/2023 V3 - Item database and add item function working with confirmation message

02/17/2023 - Recycler view implemented

02/18/2023 - Primary keys now working for login and item databases.

02/18/2023 V2 - Successfully passing values from recycler view to update item activity (including auto populating item details)

02/19/2023 - I couldn't get my update function to work for the items. Turns out I was passing the text field instead of the list.
                       
02/21/2023 - Ran into an issue last night where trying to implement requesting permissions caused me to notice that my database
             hadn't been updating in quite some time. After hours of searching, I found a few issues with naming and an if statement.
             This version has a working delete function and working permission request toggle.
