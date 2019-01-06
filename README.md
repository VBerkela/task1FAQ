# task1FAQ
Frequently Asked Questions(PHP/Laravel/MySQL)
Frequently Asked Questions

Tech stack:
Laravel
PHP 7.2/7.3
MySQL 5.7/8.0
Docker


Admin have possibility to add some frequently asked questions and show it on frontend.

1)as an admin I can go to admin panel
2)as an admin I can see FAQ menu item and FAQ Category menu item
3)as an admin I can go to FAQ GRID page
4)as an admin I can see “Add FAQ” button and GRID with next columns:
    a)ID
    b)Title
    c)Question
    d)Status - Enable/Disable
    e)Category
    f)Actions - Edit/Delete
5)as an admin I can go to “Add FAQ” page and I can see form with the next fields:
    a)Title - text fields (100 characters) - required
    b)Category - select - required
    c)Status - select - Enabled/Disabled
    d)Question - Textarea (500 characters) - required
    e)Answer - Textarea (500 characters) - required
    f)Save - button - send form to save faq action
    g)Cancel - button - I will be redirected to grid page
6)as an admin I can go to FAQ Category GRID page
7)as an admin I can see “Add Category” and FAQ Categories GRID with the next columns:
    a)ID
    b)Category Title
    c)Action - Edit/Delete
8)as an admin I can go to Add Category page and I will see form with the next fields:
    a)Category Title - text - 100 characters - required
    b)Category Description
9)as an admin I can push button save and category should be saved
10)as an admin I can push Cancel button and I will be redirected to Category GRID

Frontend
1)as a user I can go to index page and I can see Frequently Asked Questions separated by categories
2)as a user I can make search on FAQ
3)as a user I can open and read answers

