# CIDM5310
## 2021 Repo
### Book title

__Initialize__

Add a new repo

`git init`

__Git ignore__

Do not track instructions

__git add__

Add files for tracking

`git add -A`

__git commit__

commit recent tracked changes

`git commit -m "message`

__set up remote__

set up a remote peer (like github)

`git remote add origin https://github.com/Slimjim821/CIDM5310.git`

__push to remote__

push to the remote peer (github)

`git push -u origin master`

## Setup steps for virtual Environment and Jupyter Notebook use

1. make virtual environment: `py -m venv ch3_env`

2. Activate virtual environment
`.\env\Scripts\activate` (assumes you are on windows using powershell)
in git bash `source env/bookmarks/Scripts/activate`

3. Install requirements
`pip install -r .\Requirements.txt`

4. Run Jupyter Lab: `Jupyter lab`

Notes:
CSS Styles not working when copied over from github (p.99)

Resolution: I had to remove the quotes("") from outside of the brackets {} in <link href={% static "css/base.css" %} rel="stylesheet">, otherwise autopep8 was incorrectely moving the quotations

django.template.exceptions.TemplateSyntaxError: Could not parse 
the remainder: '=="dashboard"' from 'section=="dashboard"'
Had to add spaces between "=="

Could not get the google, Facebook, or twitter login to work