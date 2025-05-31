# 🛠️ Projecte Django - Entorns

Aquest projecte utilitza **Django** i genera automàticament la documentació dels fitxers `.py` mitjançant **PyDoc**, gràcies a un workflow de **GitHub Actions**.

Cada vegada que es fa un `push` a la branca `main`, la documentació es torna a generar i es publica automàticament a GitHub Pages.

---

## 📄 Documentació

👉 [Veure la documentació de cotxes.models](https://junjiewang.github.io/Projecte-Django-Entorns/cotxes.models.html)

---

## 🚀 Funcionament del workflow

1. Es descomprimeix l’arxiu `.zip` del projecte
2. S’instal·la Django
3. Es genera la documentació HTML amb `pydoc`
4. Es verifica que s’ha creat correctament
5. Es publica automàticament a la branca `gh-pages`

---

## 🔧 Tecnologies utilitzades

- Python 3.11  
- Django  
- PyDoc  
- GitHub Actions  
- GitHub Pages

---

## ✅ Activació de GitHub Pages

Per consultar la documentació generada, ves a `Settings > Pages` i comprova que la branca `gh-pages` estigui activada amb la ruta `/ (root)`.

---
