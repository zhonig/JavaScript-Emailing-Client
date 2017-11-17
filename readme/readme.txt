The goal is to implement a few missing features from an incomplete email client. There are two main components:

1) Styling the client.
- try to get as close to the final-result.png as you can. we don’t need pixel perfection, but we do want the relevant colored borders, rounded edges, etc.
- there exists a solution without altering the HTML, but feel free to change it in any way, name new classes, etc.
- the specific places to work on are the classes `email-search`, `sidebar-divider`, `sidebar-notification`, `sidebar-icon`, `sidebar-item`

2) Making it functional. You will need to implement javascript functions (function signitures are provided) to make the proper emails displays.

The two functions you’ll need to implement are:

1. “render”, which should grab all emails using “fetchEmailsFromDatabase” and run them through “getFilteredEmails” and show the emails in the inbox as designated by the image
2. “getFilteredEmails”, which should filter emails using input from “getSearchInput”, a function that is provided for you. You do not need to implement anything to get the search input or trigger the application of the search. The specifics of the filtering is detailed in the function signature.

You should make heavy use of but not change the provided helpers. Feel free to use the included lodash or jquery libraries if useful.