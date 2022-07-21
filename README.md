# Prueba de Kubernetes
Esto es una prueba "basica" para empezar a entender a Kubernetes.

En esta tendremos 2 aplicaciones de nodejs:
- Prueba1
- Prueba2

para que funcione primero se deben de compilar las imagenes, para esto se debe de ejecutar el siguiente comando:

```console
$ docker compose build
```

y luego subir la configuracion del kubernetes, para esto se debe de ejecutar el siguiente comando:

```console
$ kubectl apply -f kube
```