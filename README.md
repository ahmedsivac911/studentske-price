# studentske-price
PHP/Codigniter web site

URL: http://studentskeprice.000webhostapp.com/

Admin URL: http://studentskeprice.000webhostapp.com/admin

Admin username: admin
Admin password: admin

Studentske price is a website I created using PHP and CodeIgniter, following MVC paradigm. For the time being, the only purpose of this web site is to demonstrate my skill in web development, focusing on PHP, CodeIgniter, understanding of MVC paradigm and OOP design. Some interesting features are:
  - upvote/downvote system which uses ajax and php cookies and allows users to make either upvote or downote of a story
  - rubrike: uses php/mysql pagination to display 15 stories at a time, ordered by either popularity or date
  - admin pages: uses php sessions and sha1 encryption to log in as administrator and either approve or delete new stories 
  - new stories are added to mysql table novaprice, and are moved to table prica after approved by administrator
  - form validation of all forms on the website
  
 Possible improvements (which should be made and I could make them if I had enough time, but as I said, this website is for demonstration only so I lack motivation):
  - add either facebook or manual comments to stories written
  - allow users to change their vote
  - allow administrators to actually edit stories
  - overall better design and more mobile-friendly (not my area of expertise, I prefer back-end)
  - possibly make users register and login before writing stories
  - etc.
  
The website was created all by myself, and that includes both front-end and back-end (ofcourse, with help of my friend Google), as well as designing a mysql database. The complete web site is available for download in sp.rar file (I know, not a git way but still, serves its' purpose). Write a story, make a suggestion or get me a job. And have a nice day.
