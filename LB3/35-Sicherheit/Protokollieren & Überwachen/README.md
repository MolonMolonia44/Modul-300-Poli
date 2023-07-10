### **Erstelle ein Image**
```
docker build -t mein-image .
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/1.png)

### **Erstelle ein Container**
```
docker run -p 8080:8080 mein-image
```

Nachdem ausführen des Befehls sollte das so aussehen:
![Architecktur Docker](Screenshots/2.png)

Schlussendlich sollte man unter http://localhost:8080 das hier sehen:
![Architecktur Docker](Screenshots/3.png)