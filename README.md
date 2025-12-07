
# DevOps Projekt – Flask Webalkalmazás

Ez egy egyszerű Flask alapú webalkalmazás, amely a böngészőben a „Hello GDE” üzenetet jeleníti meg.


## BUILD

1. Repository klónozása:
   git clone https://github.com/kalmankzi/DevOps-Projekt.git
   cd DevOps-Projekt

2. Build:
   pip install -r requirements.txt

3. Alkalmazás indítása:
   python app.py

4. Böngészőben elérhető:
   http://localhost:8080

## Projekt felépítése

- app.py              – Flask webalkalmazás
- requirements.txt    – Szükséges Python csomagok listája
- README.md           – Dokumentáció

## Verziókezelés (Trunk-Based)
main a fő ág
módosítások feature branch-ekben készültek egy health feature
git használat

## DOCKER

Indisd el a Docker Desktopot
Powershell
git clone https://github.com/kalmankzi/DevOps-Projekt.git
docker build -t devops-projekt .
docker run -p 8080:8080 devops-projekt

## VS Code Dev Cont használat
Használata:

Intisd el a Docker Desktopot
VS Code → Dev Containers bővítmény telepítése
Projekt megnyitása VS Code-ban
Ctrl+Shift+P → “Dev Containers: Rebuild and Reopen in Container”
Az alkalmazás Dockerben fut és elérhető:
http://localhost:8080


## Szerző

Kalman Zoltan LJ4HGU 
2025 – GDE DevOps beadandó
