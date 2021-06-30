# A BlogSite built with Flask 

I have created a web application using flask framework and python. It's a blog based application where different users can sign up and sign in to share and read different posts. It has simple and useful login/register forms. Users can update their accounts and add/change their profile pictures. I have used Flask, Python, Bootstrap, SQLAlchemy. 

**There are somethings you need to know.**

**1. SQLAlchemy**

Only basic pieces of SQLAlchemy are used in this. We are using this for to create real users and posts. 

**Here is more information on SQLAlcehmy and ORM https://www.youtube.com/watch?v=jaKMm9njcJc&list=PL4iRawDSyRvVd1V7A45YtAGzDk6ljVPm1**

**2. ORM**

Normally with python we can manage our SQL queries. ORM allows us to write Python code instead of SQL queries to create, read, update and delete data and schemas in our database. It requires minimum knowledge of SQL. You can use different databases without changing your code.

**Steps to run**

1. Clone the repository on your device in your IDE's, I use PyCharm for my Pyhton projects.
2. pip install flask 
3. pip install flask_sqlalchemy (for more information you can visit https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
4. Create your classes and after that do these steps, there are exists in the site above.
- from yourapplication(the name of your .py file) import db
- db.create_all()
- from yourapplication import User, Post 
- **user and post were my classes**
- user1= User(username='user', email='user@example.com', password='password')
- db.session.add(user1)
- user2= User(username='user2', email='user2@example.com', password='password2')
- db.session.add(user2)
- **after you add all the users you want**
- db.session.commit() 
- User.query.all() 
- **with this you can see your tables and after you're done**
- exit()
5. Same way you can add posts
6. Start your code from your development environment. 



# File Structure

<p>
  <img src="https://github.com/ezgikorkmmaz/turkai-flask/blob/master/static/img/structure.png" width="350" title="hover text">
</p>


