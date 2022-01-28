YO I USED MAC OS , OK!
I didnt test it on windows yet,
but can do it and figure everything out.
if you create an issue on github, i will help you
########################
#How to use my Todo App#

pre: run the init_db.py to create a database.db

I. Start the database server:
> $ cd database-server
> $ source venv/bin/activate (Mac)

Windows, should be: $ venv\Scripts\activate
but that doesnt make sense since theres no Scripts folder,
that means you'll have to create a virtual environment for yourself:
> python3 -m venv venv
> $ venv\Scripts\activate (entering the virtual environment)
> $ pip install flask

NOW
> $ export FLASK_APP=main.py , Windows: use "set" instead of "export"
(do this every time you open a new terminal

> $ flask run

Now it should give you an ip-address with a port,
which you can type into your browser as a url.
Done.

II.For the Web Application to start,
open up a new terminal and navigate into the "todo-app" folder
i think you will have to globally install the npm package manager.
but i'm not sure.

> $ npx ng serve --open (opens the app in the default browser)

if you already have a browser-tab with the correct ip-adress
you can just do:
"$ npx ng serve"

If you have any questions you can make a issue on github.
Notice: the project is still in progress and will have updates throughout the years.