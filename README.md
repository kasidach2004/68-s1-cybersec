# Cyber Security

## Information
- kasidach Prabpal (NOT) 
- 6602041620017
- s6602041620017@email.kmutnb.ac.th


## Environment
 ```sh

 cp env.simpe_app .env

 ``` 
## Running a service
### Database
  ``` sh
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #background
  ``` 

  ### APP
  ``` sh
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
  ``` 