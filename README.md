# Classification — Machine Learning

## 1. Prérequis

Vérifier l'installation de Python :

```bash
python --version
```

## 2. Créer et activer l'environnement virtuel

Créer l'environnement :

```bash
python -m venv .venv
```

Activer sous Windows PowerShell :

```powershell
.\.venv\Scripts\Activate.ps1
```

## 3. Installer les bibliothèques

Mettre à jour pip :

```bash
python -m pip install --upgrade pip
```

Installer les bibliothèques nécessaires :

```bash
python -m pip install numpy pandas scipy matplotlib seaborn scikit-learn statsmodels
```

## 4. Installer Jupyter Notebook

```bash
python -m pip install jupyter ipykernel
```

Vérifier l'installation :

```bash
python -m jupyter --version
```

## 5. Installer les extensions VS Code

Installer les extensions suivantes depuis l'onglet **Extensions** de VS Code :

- **Python** — Microsoft
- **Jupyter** — Microsoft
- **Pylance** — Microsoft

Installation possible depuis le terminal :

```bash
code --install-extension ms-python.python
code --install-extension ms-toolsai.jupyter
code --install-extension ms-python.vscode-pylance
```

## 6. Configurer le notebook

1. Ouvrir le projet dans VS Code.
2. Ouvrir le fichier `.ipynb`.
3. Cliquer sur **Select Kernel**.
4. Sélectionner l'environnement Python `.venv`.
