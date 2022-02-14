# Python Live Project
<br>
<br>

## Overview

During these couple weeks at The Tech Academy we worked on developing a website that allowed users to create objects/items for a database, and also allowing them to edit or delete objects/items from the database using the MVT Django framework. During my two week sprint, using Azure DevOps, I would check the scrum board to see my assigned stories. We also implemented Agile and Scrum methodologies with sprint planning, daily stand-ups, and retrospective meetings.

## CRUD Functionality

We were tasked with back-end stories, as well as front-end stories to style and build our structure for our apps. Below I have included some descriptions of the stories I worked on, along with some code snippets as well as snippets of the app.

* Create Items

* Retrieve

* Update Items

* Delete Items


### Create Items
Here I created my model, added migration. Then I created my model form that includes any inputs needed. And to finish the story, I added a template for creating a new item and a views function that would render the template and utilize the model form to save items to the database.
<br>
<br>
![](snippets/model.png)
![](snippets/create_template.png)
![](snippets/views_create.png)
![](snippets/createform.png)


### Retrieve Items
I also needed to create a template to display the items saved in the database. Also a views function to collect all items from the database and send them to my display template.
<br>
<br>
![](snippets/display_template.png)
![](snippets/views_display.png)
![](snippets/displaydb.png)

### Update Items
Here I had to create a views template and function that would render a selected item from the database and be able to edit it.
<br>
<br>
![](snippets/edit_template.png)
![](snippets/view_edit.png)
![](snippets/edit1.png)
![](snippets/details1.png)

### Delete Items
Next I added a delete template and views function to be able to delete a selected item from the database.
<br>
<br>
![](snippets/delete_template.png)
![](snippets/view_delete.png)
![](snippets/delete1.png)


### Skills Learned
Some skills that I aquired through the Live Project:

* Working in a team enviroment
* Agile and Scrum methodologies
* Better understanding of Django
* How to utilize MTV design pattern
* Using version control to better manage everyones code for the project


### Roadblocks
* One of my biggest roadblocks was not being able to get styling to display what I was looking for. So I studied the the bootstrap documentation better, and studied other's code to help get a better grasp of implementing bootstrap to my forms and tables.

* Another roadblock I run into is basically connecting the dots, i.e. when and where to call classes, variables and methods. So I reached out to my project manager and scrum master and with a little guidance I was able to complete my stories.

### End Note
After completing this project, I definitely feel more confident in what knowledge I've learned through my boot camp, and there will be more to come for this project. I plan on adding more to with APIs, webscraping and getting a better understanding of applying bootstrap.
