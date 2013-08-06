Tango
=====

Faster, simpler django content management.


##Installation:

###Install via pip:

    pip install git+https://github.com/tBaxter/Tango.git

If you're installing in a fresh, brand-new virtualenvironment -- and you are using a virtualenvironment, right? -- 
then you'll see a lot of stuff fly by. Don't worry, that's just the dependencies. 
If your environment already has the usual stuff installed (Django, PIL, etc), then you'll speed through the Tango install. 
For more info, see the "Dependencies" section.

###For a new project, run the [Tango Starter Kit](https://github.com/tBaxter/tango-starter-kit): 

    django-admin.py startproject --template=https://github.com/tBaxter/tango-starter-kit/archive/master.zip test_project

*Note: test_project should (of course) be the name of your project*

### Run syncdb or South.

And start adding content. That's it.

##Dependencies (these should be installed for you)
[Django 1.5.1 +](https://www.djangoproject.com)
PIL or Pillow (Your choice)
[Easy-Thumbnails](https://github.com/SmileyChris/easy-thumbnails)  
Markdown & Typogrify for nice text formatting 
django-filter
python-dateutil
vobject
[Python-Twitter](https://github.com/bear/python-twitter) (if you want to auto-tweet news items)

### Recommended
South  
docutils  
