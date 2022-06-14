# Django-Poll_Creator Apps

Django poll app is a full featured polling app. You have to register in this app to show the polls and to vote. If you already voted you can not vote again. Only the owner of a poll can add poll , edit poll, update poll, delete poll , add choice, update choice, delete choice and end a poll. If a poll is ended it can not be voted. Ended poll only shows user the final result of the poll. There is a search option for polls. Also user can filter polls by name, publish date, and by number of voted. Pagination will work even after applying filter.

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h2>Prerequisites</h2>
<code>python== 3.5 or up and django==2.0 or up</code>

<h2>To migrate the database open terminal in project directory and type</h2>
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code>

<h2>To use admin panel you need to create superuser using this command </h2>
<code>python manage.py createsuperuser</code>

<h2>To Create some dummy text data for your app follow the step below:</h2>
<code>pip install faker</code>
<code>python manage.py shell</code>
<code>import seeder</code>
<code>seeder.seed_all(30)</code>
<p>Here 30 is a number of entry. You can use it as your own</p>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000 in your browser</p>

<h2>Project snapshot</h2>
<h3>Home page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Login Page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Registration Page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Poll List Page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Poll Add Page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Polling page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Poll Result Page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Poll Edit Page</h3>
<div align="center">
    <img src="#" width="100%"</img> 
</div>

<h3>Choice Update Delete Page</h3>
<div align="center">
    <img src="#"</img> 
</div>

<h2>Author</h2>
<blockquote>
  Rakesh Kumar<br>
  Email: rakesh0506907@gmail.com
</blockquote>

<div align="center">
    <h3>========Thank You !!!=========</h3>
</div>
