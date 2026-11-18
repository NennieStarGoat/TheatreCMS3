# TheatreCMS3
 C# and .NET Capstone Project
Code Summary
-created two column layout by configuring .home-row as a flexbox container with .home-col1 taking 2/3 of the width and .home-col2 taking up the final 1/3
-made all section headings the same all caps font Oswald by importing from google fonts and styled appropriately
-built a vertically scrollable .spotlight-scroll feed in the left column with spacing between production posters and a custom scrollbar
-scaled images appropriately so that they would be proportional and capping their height
-added a (non-functional) "Click to Support" button, styled appropriately
-configured the .sponsors-container to align the logos and allow them to scale and wrap when space allows
-linked the NAYA Family Center image for the Land Acknowledgement appropriately
-set the title page to "SignIn" and to inherit the shared site structure
-created a jQuery function once the document is loaded to count all <p> elements inside #PersonList and replaces a count of 0 with the actual total
-created a blog author model with properties for an ID, name, bio, start date and departure date
-registered blog author with Entity Framework to generate the corresponding SQL table with migrations
-added user interface (CRUD) to allow for adding, viewing, updating, and removing author profiles
