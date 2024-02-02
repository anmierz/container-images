## Obraz z repozytorium pakierów Archlinuxa

Budowanie.
```
buildah build --tag archlinux-mirror:latest image/
```

Uruchomienie.
```
podman run --detach --name=arch-mirror -p 8080:8080 archlinux-mirror:latest
```
