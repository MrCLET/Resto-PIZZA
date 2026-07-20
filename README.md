# Resto-PIZZA
Web application for pizza restaurant avec Django
# 🍕 Resto-PIZZA

Application web de restaurant de pizzas développée avec **Django**.
Site vitrine + commande en ligne pour une pizzeria.

🔗 **Démo en ligne** : 🟨 _à ajouter après déploiement (voir plus bas)_

![Aperçu de Resto-PIZZA](docs/screenshot.png)
> 🟨 Remplace par une vraie capture : crée un dossier `docs/`, ajoute une image `screenshot.png`.

## ✨ Fonctionnalités

🟨 _Garde uniquement les lignes vraies, supprime les autres :_
- Présentation du menu (pizzas, prix, descriptions)
- Page de détail par produit
- Panier / commande en ligne
- Interface d'administration Django (gestion des produits)
- Design responsive

## 🛠️ Stack technique

- **Back-end** : Python, Django
- **Front-end** : HTML, CSS
- **Base de données** : SQLite

## 🚀 Installation locale

```bash
# 1. Cloner le dépôt
git clone https://github.com/Mr-clement/Resto-PIZZA.git
cd Resto-PIZZA

# 2. Créer et activer un environnement virtuel
python -m venv venv
source venv/bin/activate        # Windows : venv\Scripts\activate

# 3. Installer les dépendances
pip install -r requirements.txt

# 4. Appliquer les migrations
python manage.py migrate

# 5. Lancer le serveur
python manage.py runserver
```

L'application est accessible sur `http://127.0.0.1:8000/`.

## 👤 Auteur

**Clément AMLAGAN** — Développeur Fullstack
🌐 [Portfolio](https://clement-amlagan-portfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/clement-amlagan-20231234a)
