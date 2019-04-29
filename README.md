### Description

In order to learn and practice CSS layout properties, you will duplicate the given image by downloading the **index.html** starter file, adding a CSS file, and adding CSS rules to make the page look identical to the image.

### Learning Objectives

* You should know how to use css layout properties
* You should know how to run a python script
* You should know how to use python variables
* You should know how to read/write to a file using python

### Performance Objectives

* Demonstrate knowledge of css layout properties

### Deliverables

* A GitHub repository containing an **index.html** and **styles.css**

### I'm a Web Developer Mode

In order to learn and practice CSS layout properties, duplicate the attached image, **octodex.png**.

1. Create a project folder under your code directory
2. The attached **index.html** file (see below) includes the html for this project. Save the file inside your project directory. **DO NOT MODIFY THE HTML**
3. Create a Python webserver to serve your project files
4. Add a CSS file and add CSS rules to make the page look identical to the attached image, **octodex.png**
5. Create a text file to hold the number of times your page is viewed
6. Create a variable in your Python web server to track the number of times the page is viewed
7. Update your Python web server to open the file and read the contents out. Create a new variable that will hold the contents of the file.
8. If the file is empty use the value of 0 (zero). Otherwise use the string contents of the file.
9. Convert the contents to an integer and assign this numeric value to your counter variable.
10. Increment the counter variable up every time the web page is viewed.
11. Using a print statement print the value of your counter variable to the console.
12. Write the value of your counter variable back to your tracking file.
13. Deploy your site to Heroku
	1. Create a file called `Procfile` in your project
	2. Put the following in that file: `web: gunicorn app:app`
	3. Install `gunicorn` in your project: `pipenv install gunicorn`
	4. Commit your `Procfile`, `Pipfile`, and `Pipfile.lock` files.
	5. Login to heroku and add a new app to your account
	6. On the deployment tab select the github option and then pick the correct repo.
	7. Turn on automatic deployment down below.
	8. Click to deploy the project one time manually.
	9. Wait for the deployment to finish then click the link.
	10. Make sure the project is loading properly.
14. Submit your project (see below)

### Hey, Mikey, I Think He Likes It Mode

Add 3 more Octocats to your web page. Use the Octodex at  [http://octodex.github.com](http://octodex.github.com) if you need some images, or draw your own and include them in your Github repository.

### Caffeinated Mode

Try making your web page responsive when the browser is resized.
