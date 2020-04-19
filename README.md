# assignments
Here i share some of my assignments given for Java course at my master's.

The project is a basic Java servlet example created by basic HTML through JSP 

- Display “Home” and “Register” menu items (User has not logged in)
- Display Login form
o Display error on wrong username-password
o After successful login:
§ Display Home page.
§ Write “Welcome [USERNAME]” at the top of the page (all pages)
§ Display “Home”, “My Links”, “Post Link”, “Logout” menu items.
- When “Logout” clicked, log the user out, switch menu items and remove welcome message.
- Display all links posted to the application
o Details: Link title, link address, post date, number of views and username
- Display Search functionality.
o When a keyword is entered and “Search” button clicked, filter the links according to the search
criteria.
o When “Reset” is clicked, display all the links posted.
- When a link is clicked, increase the view count and redirect the user to the link address
- When a username is clicked, display the links of the user. On the page, display “[USERNAME] Links”
text as header

Registration
- Provide username and password to login
- If username exists inform the user
- Upon successful login, inform the user that they must login

My Links
Only logged in users can access. If otherwise, display home page.
- Display logged in user’s links (Title, link address, post date, views).
- Users can delete their links, page is refreshed after delete.

Post Link
Only logged in users can access. If otherwise, display home page.
- Link title and Link address must be entered by the user
- Post date is insertion date
- Username-link address are primary keys together on the database, thus a user cannot post the same link
twice, inform the user if they try otherwise.
- Upon submit, display My Links page


