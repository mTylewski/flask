# Moje Flask App


- W projekcie wykorzystamy virtual environment, dla utworzenia hermetycznego środowisko dla aplikacji:

  ```
  # tworzymy hermetyczne środowisko dla bibliotek aplikacji:
  $ python -m venv .venv

  # aktywowanie hermetycznego środowiska
  $ . venv/bin/activate
  $ pip install Flask
  

- Uruchamianie applikacji:



   ```
  # tworzymy hermetyczne środowisko dla bibliotek aplikacji:
  $ export FLASK_ENV=development
  $ export FLASK_APP=hello
  $ flask run
