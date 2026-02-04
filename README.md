# Projets

Ce dépôt regroupe plusieurs projets personnels et expérimentaux en développement web et mobile.

## API Django

**Stack :** Django, Django REST Framework, Python, JWT  

API REST permettant :
- création et authentification d’utilisateurs
- calcul de surfaces
- calcul de résistances thermiques à partir de plusieurs couches de matériaux

**Installation**
```bash
git clone https://github.com/charlottecordelle/3D-API.git
cd api
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## Maison 3D – Angular

**Stack :** Angular, TypeScript, ThreeJS  

Application web interactive pour visualiser une maison en 3D :
- rotation, zoom et déplacement de la caméra
- affichage ou masquage d’éléments de la maison

**Installation**
```bash
git clone https://github.com/charlottecordelle/3D-API.git
cd modelisation_maison
npm install
ng serve
```
