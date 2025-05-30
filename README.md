# Projecte-Django

Repositori per a executar automàticament els tests per al projecte Django

## 🧾 Introducció

Aquest projecte és un gestor de cotxes esportius. Permet visualitzar, filtrar i consultar cotxes per autor o etiqueta.

## ⚙️ Instal·lació ràpida

1. **Clonar el repositori**
```bash
git clone https://github.com/JunjieeWang/Projecte-Django.git
cd Projecte-Django
```

2. **Instal·lar les dependències**
```bash
pip install -r requirements.txt
```

3. **Executar migracions**
```bash
python manage.py makemigrations
python manage.py migrate
```

4. **Descarregar les taules**
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
