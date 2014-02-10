## Flask Tutorial

We are following http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

### Up to:

  * Part 3 "Improving field validation"
  * Part 2, no problems
  * Part 1, no problems

### Important points

  * to run, use `./run.py`
  * view with `http://localhost:5000`, `http://localhost:5000/login`, etc.

### Jinja2 syntax

  * `{{...}}` for templates
  * `{%...%}` for control statements
  * `a.b` and `a.b.c` for nested dictionary keys

### Tools

  - WTForms: forms framework
  - `wtforms.validators.Required`: checks that form is not empty
  - `redirect('path')`: redirect to `'path'`
    `flask.ext.wtf.Form`: forms

### Comments

I began working through this tutorial at the "Flask Workshop with PyLadies" on 20131218 (http://www.meetup.com/flask-nyc/events/154634982/. Instructor: Sean Patrick Murphy (Johns Hopkins)

Sean Patrick Murphy: Flask is preferable for learning because a single-file web server can be constructed in merely 10 lines.

