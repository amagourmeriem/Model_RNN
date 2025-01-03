🌟 Projet RNN - Prédiction Séquentielle 📈
Bienvenue dans ce projet de réseau neuronal récurrent (RNN) ! 🚀 Ce guide vous aidera à installer et exécuter le projet étape par étape. 💻

🛠️ Prérequis
Avant de commencer, assurez-vous d'avoir :

Python 3.8 ou une version supérieure 🐍
Pip pour installer les dépendances 📦
Git pour cloner le dépôt 📂
Une machine avec au moins 8 Go de RAM 💾

📥 Installation
Clonez le dépôt 🌐
Utilisez Git pour cloner le dépôt et accéder au dossier du projet :

git clone https://github.com/username/rnn-project.git
Ensuite, entrez dans le dossier : cd rnn-project
Créez un environnement virtuel 🐾

Créez un environnement virtuel avec la commande suivante :
Sur Linux/Mac : python -m venv venv puis source venv/bin/activate
Sur Windows : python -m venv venv puis venv\Scripts\activate


Installez les dépendances 📦

Installez toutes les bibliothèques nécessaires avec :

pip install -r requirements.txt

📊 Données
Téléchargez les données d'entraînement 📂
Placez vos fichiers de données dans le dossier data/.
Exemple de fichiers requis :

data/input_sequences.csv
data/target_values.csv

Préparez les données ⚙️
Exécutez le script de préparation :

python preprocess.py
🚀 Entraînement
Lancez l'entraînement 🏋️‍♂️
Utilisez la commande suivante pour entraîner le modèle :

python train.py --epochs 50 --batch-size 32
Les modèles entraînés seront enregistrés dans le dossier models/ 📁.

📈 Évaluation
Évaluez le modèle 🧪
Testez la performance du modèle avec cette commande :

python evaluate.py --model models/best_model.h5
Consultez les métriques affichées dans la console 📊.

📤 Prédiction
Prédisez de nouvelles données 🔮
Faites des prédictions avec :

python predict.py --input data/new_input.csv
Les résultats seront sauvegardés dans un fichier nommé predictions.csv 📑.

🧹 Nettoyage
Pour supprimer les fichiers temporaires : 🧽

python cleanup.py
🛠️ Dépannage
⚠️ Si vous rencontrez des problèmes de mémoire, essayez de réduire la taille des lots avec l'option --batch-size.
🐛 En cas de bugs, vérifiez les fichiers de logs générés dans le dossier logs/.
🎉 Amusez-vous bien avec votre projet RNN ! 😊
Si vous avez des questions, n'hésitez pas à ouvrir une issue ou à envoyer un e-mail à mariemamagour317@gmail.com. 📩
