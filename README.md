# WIK-DPS-TP02
TP2 Deveops

Afin de lancer le premier dockerfile avec l'utilisateur appuser:
```
cd /app
docker build -t devopstp2 . 
docker run -p 8080:3000 --user=appuser devopstp2v2
```


Afin de lancer le second dockerfile (dockerfile2.dockerfile)
```
cd /app
docker build -f Dockerfile2.Dockerfile -t devopstp2v2 .
docker run -p  8080:3000 --user=appuser devopstp2v2
```
