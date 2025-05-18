# 🚀 Script Python AWS S3 – Projet Cédric

Premier projet AWS Cloud de Cédric Haegele :  
un script Python simple qui envoie un fichier local dans un bucket Amazon S3 à l'aide de **Boto3**.

---

## 🧰 Technologies utilisées

- Python 3.13
- Boto3
- AWS CLI
- Amazon S3

---

## 📦 Fonctionnement

Ce script fait les étapes suivantes :

1. Crée un fichier texte nommé `test.txt`
2. Se connecte à AWS S3 via les identifiants configurés avec `aws configure`
3. Envoie le fichier dans le bucket `cedric-s3-demo`
4. Affiche un message de succès

---

## 🔐 Prérequis

- Avoir un compte AWS
- Avoir installé AWS CLI et configuré (`aws configure`)
- Avoir créé un bucket S3 (`cedric-s3-demo`)
- Avoir les bibliothèques suivantes installées :
```bash
pip install boto3
# Script Python AWS S3  par Cédric
