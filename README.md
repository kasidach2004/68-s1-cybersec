# Cyber Security

## Information
- kasidach Prabpal (NOT) 
- 6602041620017
- s6602041620017@email.kmutnb.ac.th

## Environment
 ```sh

 cp env.simpe_admin .env

 ``` 
## Running a service
### Admin
  ``` sh
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #background
=======
## Environment
 ```sh

 cp env.simpe .env

 ``` 
## Running a service
### Database
  ``` sh
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #background

  ``` 