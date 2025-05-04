# 🤖 Installation d’un environnement Robot Framework

---

## 🐧 Pour Linux

### 📥 Installation des dépendances

```bash
sudo apt install -y nodejs
sudo apt install python3-pip
sudo apt-get install python3-venv
```

### 🧪 Création d’un environnement virtuel

```bash
python3 -m venv rf
```

### ▶️ Activation de l’environnement

```bash
source rf/bin/activate
# Pour désactiver :
deactivate
```

### 📦 Installation de Robot Framework et modules

```bash
python3 -m pip install robotframework
pip3 install robotframework-browser
pip3 install robotframework-robocop
```

### 🌐 Initialisation du navigateur pour Robot Framework

```bash
rfbrowser init
```

### ▶️ Exécution d’un fichier .robot

```bash
robot test.robot
```

---

## 🪟 Pour Windows

### 📥 Installation de Python (via Chocolatey)

```powershell
choco install python
```

### 🧪 Création d’un environnement virtuel

```bash
python -m venv RobotFramework
```

### ▶️ Activation de l’environnement

- Pour `cmd` :
```cmd
RobotFramework\Scripts\activate.bat
```

- Pour `PowerShell` :
```powershell
RobotFramework\Scripts\Activate.ps1
```

### 🔄 Mise à jour & installation des paquets

```bash
pip install --upgrade pip
pip install robotframework
pip install robotframework-browser
pip install robotframework-robocop
robot --version
```

### 🌐 Initialisation du navigateur

```bash
rfbrowser init
```