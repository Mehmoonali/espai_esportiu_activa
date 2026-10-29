# DEPLOY.YML I MKDOCS.YML

## QUÈ ÉS DEPLOY.YML?

L'arxiu **deploy.yml** permet publicar automàticament la nostra pàgina web a GitHub Pages.

Cada vegada que fem un canvi al repositori i el pugem a GitHub, aquest fitxer executa les accions necessàries per actualitzar la web automàticament.

### CAPTURA DE DEPLOY.YML

![Deploy](img/deploy.png)

---

## QUÈ ÉS MKDOCS.YML?

L'arxiu **mkdocs.yml** és el fitxer principal de configuració de MkDocs.

Serveix per configurar el nom de la web, les pàgines del menú, el tema visual i altres opcions del projecte.

### CAPTURA DE MKDOCS.YML

![MkDocs](img/mkdocs.png)

---

# CANVIS REALITZATS

## CANVI DEL NOM DE LA WEB

### ABANS
nav:
  - Home: index.md
### DESPRÉS
nav:
  - Inici: index.md
  - Objectiu: objectiu.md
  - Serveis: serveis.md
  - Deploy i MkDocs: deploy-mkdocs.md

# FUNCIÓ DELS DOS ARXIUS

## DEPLOY.YML
S'encarrega de publicar la web automàticament a GitHub Pages quan es realitza un canvi al repositori.

## MKDOCS.YML
S'encarrega de configurar l'estructura i l'aparença de la web.

# RESULTAT FINAL
Gràcies als canvis realitzats, hem personalitzat la nostra pàgina web ReservaFàcil per a l'Espai Esportiu Activa i hem configurat la seva publicació automàtica.

CAPTURA DEL RESULTAT FINAL
![MkDocs](img/web.png)
