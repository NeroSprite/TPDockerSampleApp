# Dockercompose

Pour lancer les 4 nginx et le load balancer il suffit de faire:
```bash
docker compose up
```

# Docker FaceApp

Build et lancement :
```bash
docker build -t appface .

docker run -d -p 8080:8080 appface
```

**Antoine Degas**