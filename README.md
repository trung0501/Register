🏷️ Program Name: Login Signup Form

🎯 Program Purpose: Create a friendly, beautiful and easy -to -use user interface for logging and registering user accounts on the website. This interface makes it easy for users to access the system with an existing account or a new account registration.

🧩 The main component of the program:

   1. HTML: Login form (.form-box.login), Registration form (.form-box.register), Toggle block between two forms (.toggle-box with 2 toggle-panels). 

   2. CSS: User interface design (colors, layouts, form transition effects), Optimized for both large and small devices (responsive). 
    
   3. JavaScript: Handle the transition effect between two forms by adding/removing the active class to the .container element

⚙️ Principle of operation:

   1. The default interface shows the login form.

   2. When the user presses the "Register" button, the active class is added to the .container, which causes:

      . The login form to move off the screen.

      . The registration form appears instead.

      . The background effect and the elements move smoothly thanks to CSS transitions.

   3. Conversely, when the user presses the "Login" button, the active class is removed, and the interface returns to the login state.

✅ Advantages:

   1. Modern, friendly and professional interface.

   2. Smooth effect, convert form without loading page.

   3. Responsive design, compatible with many screen sizes.

   4. UX/UI optimization: intuitive icon, easy -to -see color, easy -to -use form.

   5. Integrated social network login (Google, Facebook, GitHub, LinkedIn icon).

   6. Separation between HTML, CSS and JS, easy to maintain.

❌ Limit:

   1. There is no connection to the backend system or database, so it is not yet possible to log in/register.

   2. No advanced valid test for the form (advanced validation) such as checking the strength of passwords, checking the overlapping email, ...

   3. Do not handle errors or notify the user when filling out wrong.
    
