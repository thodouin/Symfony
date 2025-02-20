# symfony

## Installation

Créez le fichier docker-compose.yml

```bash
$ docker-compose up -d --build
$ docker-compose exec web symfony new . --version="7.2.x" --webapp --no-interaction
```

Créez le dossier app, qui contiendra l'application