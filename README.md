### Create a full-stack pplication using Flask and Stream


Installing
* Pip install flask-wtf flask-login flask-mail flask-migrate

Flask-WTF(What Thee Form)- a form and validation package to aid the creation of forms ,by adding features like CSRFtokens and alerts

Flask-login- a session management package hat handles user authentication, so that we can verify users and pass correct information to them

Flask-Mail - an email package that sends out emails to users --we will use it to send confirmation to users upon registration and it will also help in changing a user's email or password.

Flask-Migrate is a database versioning tool which let us keep a record of changes made to our database tables, by handling additions and subtractions of columns from tables.