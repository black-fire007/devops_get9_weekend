# note for docker compose

docker compose : used to work with 
multiple containers environment

### yaml
Yaml aint a markup language

it is a file that commonly used:
- docker compose
- configuration (application.yaml)
- kubernetes (yaml for mainfest)
Yaml file often `.yaml or yml`

&Simple comparison
```bash
# json for student
{
    "name": "james@gmail.com",
    "email": "james@gmail.com" ,
    "subjects": [
        "Java",
        "Python"
    ],
    "origin": {
    "city": "Phnom penh",
    "country": "Cambodia"
    }
}

# yaml file sample for student
name: james
email: james@gmail.com
subjects:
    - java
    - Python
origin: 
    city: phnom penh
    country: Cambodia

### Basice Command for docker
# to run all containers i  detecth mode

docker compose up -d
docker ps
docker ps -a
docker compose ls

docker compose down 
docker compose dewn -v #down all and valumn
dockers compose config #check the configuration of the docker compose file  true or false
dockers compose config --services

```