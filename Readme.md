# The Forth time
* git init
* git add README.md
* git commit -m "first commit"
* git remote add origin https://github.com/joblackpoc/django_blog.git
* git push -u origin master
* …or push an existing repository from the command line
* git remote add origin https://github.com/joblackpoc/django_blog.git
* git push -u origin master


- pythonanywhere -> web -> add a new web app -> manual config -> python 3.7 -> next

	* Code section
	* WSGI -> right click open new tab -> scoll down to django section -> uncomment all in django section
		* path = '/home/djangonatthawut/djago_blog'
		* os.environ['DJANGO_SETTINGS_MODULE'] = 'blog_project.settings'
		* save
		
- virtualenv section
	* /home/djangonatthawut/.virtualenvs/envs -> save
	
- static files
	* url -> /static/
	* /home/djangonatthawut/django_blog/static -> save
	* url -> /media/
	* /home/djangonatthawut/django_blog/media -> save

- console -> base console
	* mkvirtualenv -> --python=/usr/bin/python3.7 envs -> enter
	* pip install django
	* pip install django-crispy-forms
	* pip install pillow
	* pip show django-crispy-forms
	* git clone https://github.com/joblackpoc/django_blog
	
- files -> djangonatthawut/django_blog/blog_project -> settings.py 
	* DEBUG - False
	* ALLOWED_HOSTS - ['djangonatthawut.pythonanywhere.com']
	* STATIC_ROOT - '/home/djangonatthawut/django_blog/static'
	* MEDIA_ROOT = '/home/djangonatthawut/django_blog/media'
	* save

- console -> 
	* ls
	* cd django_blog
	* ls
	* python3 manage.py collectstatic
	
- Dashboard -> web -> click Reload Djangonatthawut.pythonanywhere.com
	* click -> djangonatthawut.pythonanywhere.com
	
	
	
	
	
	
	
	
	
