# spring-podman
Applicazione a Moduli

## Creazione del container per applicazione.

Creazione dei container dell'applicazione.
```shell script
sudo podman-compose up -d
```

per aggiornare la versione del container
```shell script
sudo podman-compose up -d --build
```

## Creazione del modulo

```shell script
git submodule add https://github.com/ddalpra/supportapp.git supportapp
```