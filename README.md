# Cyber Security

## Ower
- 6702041511039
- Suphaporn Toomthong
- s6702041511039@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running services
### Database
```sh
docker compose -f db.yaml yp # monitoring
docker compose -f db.yaml up -d # background
```

### Admin
```sh
docker compose -f admin.yaml yp # monitoring
docker compose -f admin.yaml up -d # background
```

### App
```sh
docker compose -f app.yaml yp # monitoring
docker compose -f app.yaml up -d # background

