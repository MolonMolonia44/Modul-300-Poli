### **Erstelle ein Image**
```
docker build -t <image-name> .
```

![Architecktur Docker](Screenshots/1.png)

### **Erstelle ein Container**
```
docker run -p 80:80 -p 443:443 -d <image-name>
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/2.png)

Beim aufrufen der Seite http://localhost sollte man direkt auf https:// geleitet werden und nach User gefragt werden:
![Architecktur Docker](Screenshots/3.png)
![Architecktur Docker](Screenshots/Localhost.png)