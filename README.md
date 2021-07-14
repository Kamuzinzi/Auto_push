# Auto_push
This project is for creating or updating a file on GitHub repository.


## Install all the required libraries

```bash
pip install pip==21.1.2
pip install pybase64
pip install requests
pip install SQLAlchemy==1.3.24
pip install GitPython==3.1.18
pip install PyGithub==1.55

```

## Get a GitHub Token steps
1. Verify your email address, if it hasn't been verified yet.
2. In the upper-right corner of any page, click your profile photo, then click Settings.
3. In the left sidebar, click Developer settings.
4. In the left sidebar, click Personal access tokens.
5. Click Generate new token.
6. Give your token a descriptive name.
7. Select scopes.
8. Click Generate token.
9. Remember to copy it before you leave the page.

## Use of the token

Open the credentials.py and replace the generated token with the string in the quotes.
Note. credentials.py is incrude in .gitignore

##Run the backup.py file to create the model

python backup.py


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


