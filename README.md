# Contacts-Manager-SQLiteApp-Python-API
# PyContacts: A Pythonic Contacts Manager with SQLite and API Integration with APIs
### Utilizing SQlite database, SQlite studio, read-write functionality to delete/edit/update contacts with Python, and more. 

This is a project for managing contacts using a graphical user interface (GUI) built with the Tkinter library in Python. The project provides a contact management system with features such as adding new contacts, viewing existing contacts, deleting selected contacts, and modifying selected contacts. 

The contacts are stored in an SQLite database (contacts.db) and the GUI allows users to interact with the data through a tree view widget. 

Additionally, the project includes an API for interacting with the contact data programmatically, providing external access to the contact management functionality.

## Some examples from the project:

Creating tables in the database:

![Tables](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Create_Table.jpg)

Creating contacts in the database:

![Contacts](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Create_Contact_list.jpg)

Downloading Tkinter, our Python GUI:

![GUI](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Install_Tkinter.jpg)

Starting Code:

![Starting Code](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/starting_code.png)

Adding a logo and code for widgets for the application:

![Logo](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/building_apps.png)

Adding a LabelFrame, labels, entry fields for contacts, and a button:

![Buttons And Fields](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Adding_buttons_fields.jpg)

Now, we’re going to add another label where we’d be able to see a message come up when we add or delete a lead or a contact.
We’re going to be using a treeview widget from tkinter that will allow us to display messages. Some of the code development:

![Code Development](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/code.jpg)

So right now, we’re seeing a message area but it’s not populated yet:

![Message Area](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Developing_app.jpg)

Changed some fonts and bolded the font. Also added a scroll bar and buttons to modify or delete entries. 

![Scrollbar and more](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/scrollbar.jpg) 

Creating a function to be able to call the GUI:

![GUI](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Function_Create_GUI.png)

Importing the SQL database into my application:

![SQL](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/import_SQL.jpg)

I'll create another function to be able to interact with the database. I'll also create a function to add new contacts into the database, validate inputs, and be able to fetch all records from the database to be able to display in treeview, the function that allows this in the application:

![treeview](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/add_new_contacts.jpg)

Adding contacts:

![Hermione_contact](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/add_contact_hermione.png)

Adding contact message:

![message](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/adding_contact_message.png)

Now that we can add records and see it in the app, we want a way to delete records as well:

![delete_contacts](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/delete_contacts.jpg)

I'll also add this code block to deal with exceptions if you try to delete without having selected anything:

![exceptions](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Creating_exceptions.jpg)

Wiring up buttons for the modify selected button and changing contacts:

![Buttons](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/modify_bottons.jpg)

Testing “modify selected” button:

![Items_not_selected](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/No_items_selected.jpg)

Creating virtual environment, installing Django, installing REST framework

![VM_Creation_Django](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Creating_VM_Django_Install.jpg)

Registering products:

![Registering_products](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Django_Product_Registration.jpg)

Creating API infob backend:

![API_info_](https://github.com/MayCooper/Contacts-Manager-SQLiteApp-Python-API/blob/main/Images/Django_Admin.jpg)
