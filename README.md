# ToDoList
To build this app, I hv start by creating a virtual environment and setting up a Django project. 
Next, I hv designed a data model that represents the relationships between to-do items and lists. 
I used Django’s built-in object-relational mapping tool to automatically generate the database 
and tables that’ll support this model.

As I develop Django to-do list app, I hv use Django’s handy runserver command whenever i need 
to verify that things are working as expected. This can help even before your web pages are ready,
thanks to Django’s ready-made admin interface.

Next, I developedd own web pages to display my app. In Django, these take the form of templates. 
Templates are skeleton HTML pages that can be populated with real application data.

Templates aren’t meant to provide much logic, such as deciding which template to display and what 
data to send it. To perform that logic, I needed views. Django’s views are the natural home for the
application’s logic.
I coded views and templates for list creation and updates, as well as for the items that those 
lists will contain. 

Finally, I added new user interface by adding, editing, and deleting to-do lists and to-do items.
