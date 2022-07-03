# Dog Shop

INTRODUCTION

IMAGES OF SITE 

## Goals of the site:

1. 
2. 
3. 

## User Experience 

### User Stories 

#### Site Users:

1. As a Site User I can 
2. As a Site User I can 
3. As a Site User I can
4. As a Site User I can 
6. As a Site User I can
7. As a Site User I can 
8. As a Site User I can 
9. As a Site User I can 
10. As a Site User I can 

#### Site Admin:

1. As a Site Admin I can
2. As a Site Admin I can
3. As a Site Admin I can
4. As a Site Admin I can
5. As a Site Admin I can

### Type of Visitors 

1.
2. 
3. 

### Wireframes 



## Features 

### Feature 1 - 
 
### Feature 2 - 

### Feature 3 - 

### Feature 4 - 

### Feature 5 - 

### Feature 6 - 

### Feature 7 - 

### Feature 8 - 

### Feature 9 - 

### Feature 10 - 

### Feature 11 - 

### Feature 12 - 

### Feature 13 - 

### Feature 14 - 

### Feature 15 - 

### Feature 16 - 

### Feature 17 - 


## Features to implement in future versions

### Feature 1

### Feature 2

### Feature 3


## Technologies used

- HTML5

HTML5 is a markup language used for structuring and presenting content on the World Wide Web. It is the fifth and final major HTML version that is a World Wide Web Consortium recommendation.

- CSS

Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language.

- JavaScript

JavaScript is a dynamic programming language that's used for web development, in web applications, for game development, and lots more. It allows you to implement dynamic features on web pages that cannot be done with only HTML and CSS.

- Python 3.2

Python is a high-level, interpreted, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. 

### Frameworks, Libraries & Programs

### Frameworks

- [Django 3.0.1](https://www.djangoproject.com/): 

Django is a free and open-source, Python-based web framework that follows the model–template–views architectural pattern. 
 
- Django All Auth 
- Django Shortcuts
- Django Contrib
- Django Conf
- Django.db
- Django Crispy Forms 

- Render
- Redirect
- Reverse
- HttpResponse
- get_object_or_404
- Path
- Decimal
- OS

- [Bootstrap](https://getbootstrap.com/)

Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains HTML, CSS and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.

###  Libraries 


### Programs

- [GitHub](https://github.com/) is the repository used for projec codes to be pushed from VSCode.

- [GitPod] was used for version control.

- [Balsamiq](https://balsamiq.com/) used to create user flowmaps during the design process.


## Testing 

## Stripe (Payments)

1. Visit [Stripe](https://stripe.com/gb) and click 'Start Now'
2. Register an account following their process
3. Verify your email address
4. Copy Stripes JavaScript from their documentation and add into the corejs of all site pages - this increases security and fraud detection from Stripe 
5. Copy the public key from Stripe and add to your view for checking out / processing a sale
6. Setup Stripe variable using public key
7. Create instance for Stripe elements
8. Use the Stripe element to create a card element 
9. Attach card element to the targetted div 


## Deployment 

### Heroku

1. On Heroku create an account and log in.
2. Click new and create new app.
3. Choose a unique name for your app, select region and click on Create App
4. Under the Settings click Reveal Config Vars and set IP to 0.0.0.0 and the PORT to 5000
5. Go to the CLI and type $ sudo snap install --classic heroku
6. Type $ heroku login command into the terminal
7. Create requirements.txt ($ sudo pip3 freeze --local > requirements.txt)
8. Create a Procfile ($ echo web: python app.py > Procfile)
9. Go back to Heroku, under Deploy find Existing Git repository and copy the command:$ heroku git:remote -a <app_name> Paste this into the terminal.
10. (If repository was not created already, type:
11. $ cd my-project/
12. $ git init
13. $ heroku git:remote -a <app_name>)
14. Type $ heroku ps:scale web=1 into the terminal.
15. Go back to Heroku, and at Settings copy https://<app_name>.herokuapp.com/
16. In the terminal type git remote add http://<app_name>.herokuapp.com/
17. Type git push -u heroku master
18. In the app dashboard, under Settings click on Reveal Config Vars
19. Set "SECRET_KEY"
20. Once the build is complete, go back to Heroku and click on Open App

### AWS (Amazon Web Services)

1. 
2. 
3. 
4. 
5. 
6. 
7. 
8. 
9. 
10.



## Credits 

 * To ensure my CSS code was formatted correctly, I ran it through a formatter which can be found here: [CSS Code Formatter](https://www.freeformatter.com/css-beautifier.html#ad-output)
 * To ensure my HTML code was formatted correctly, I ran it through a formatter which can be found here: [HTML Code Formatter](https://www.freeformatter.com/html-formatter.html)
 * To ensure my JavaScript code was formatted correctly, I ran it through a formatter which can be found here: [JavaScript Code Formatter](https://beautifier.io/)
 * To ensure my Python code was formatted correctly, I ran it through a PEP8 formatter which can be found here: [Python Formatter](https://codebeautify.org/python-formatter-beautifier) 


## Content 

* 
* 
*


All content has the sole use for education.


### Code 

*
* 

### Credits

*
*


