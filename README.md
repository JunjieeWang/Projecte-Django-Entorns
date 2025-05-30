# Projecte-Django

Repositori per a executar automàticament els tests per al projecte Django amb GitHub Actions.

## Introducció

Aquest projecte és un gestor de cotxes esportius. Permet visualitzar, filtrar i consultar cotxes per autor o etiqueta.

## Instal·lació ràpida (local)

1. **Clonar el repositori**
```bash
git clone https://github.com/JunjieeWang/Projecte-Django.git
```

2. **Unzipejar el projecte**
```bash
sudo apt install unzip
unzip Projecte_Django_Junjie_Wang.zip -d Projecte-Django
cd Projecte-Django/Projecte_Django_Junjie_Wang
```

3. **Instal·lar les dependències**
```bash
pip install -r requirements.txt
```

4. **Executar migracions**
```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Descarregar les dades**
```bash
python manage.py loaddata authors.json
python manage.py loaddata tags.json
python manage.py loaddata cars.json
```

## Execució del projecte

1. **Executar el servidor**
```bash
python manage.py runserver
```

2. **Accedir a l'aplicació**
```
http://127.0.0.1:8000/
```

## Execució dels tests

1. **Des de la terminal local**
```bash
python manage.py test cotxes
```

2. **Automàticament amb GitHub Actions**

Aquest projecte conté un fitxer `.github/workflows/python-tests-with-unzip.yml` que:

- Descomprimeix el `.zip`
- Instal·la Python 3.11
- Instal·la dependències (`requirements.txt`)
- Executa migracions
- Executa els tests

Revisa la pestanya **Actions** del repositori per veure els resultats.

