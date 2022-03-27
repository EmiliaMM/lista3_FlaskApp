# lista3_FlaskApp
1. Stwórz folder FlaskApp
	
> mkdir FlaskApp
> cd FlaskApp

2. Tworzymy środwisko dla bibliotek aplikacji.
	
> py -3 -m venv venv

3. Aktywowanie środowiska.

> venv\Scripts\activate
  
4. Instalowaie Flask.

> pip install Flask
#sprawdz czy się udało
> pip list
  
5. Stwórz hello.py plik w pliku o treści,:
	from flask import Flask

	app = Flask(__name__)

	@app.route("/")
	def hello_world():
    		return "<p>Hello, World!</p>"

6. Zapisz w folderze FlaskApp.

7. Declare Hello_world.py as flask app.

> set FLASK_APP=Hello_world.py

8. Uruchom Flask app.

> flask run

9. Skopuj url i uruchom w przeglądarce - sprawdz czy działa
10. Zapisz wyniki
> pip freeze > requirements.txt

