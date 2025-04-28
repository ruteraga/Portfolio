Django 
  Username: admin
  Password: django123

The main goal was to create a website where you can easily add projects on a website portfolio using a database.

Model Project
   title= title for your project
   description= description to be seen about your project
   tags= they are the identifier used for each project block. All of them should be portfolioModal followed by the next number. For now it has 1 to 6. portfolioModal1 - portfolioModal6. The next project should be portfolioModal7 and you continue the same way
   link= link for your project
Model ProjectImage
  project= foreign key to Project
  image=image for your project
Model Tag
  name=name of tag used in project model

Hope this helps!
   
