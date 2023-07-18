# Starter Project

## Push to Gitlab Registry

`docker login registry.gitlab.com `

- supply username and Access Token

`docker build --tag <Docker Image name> --file <specific Dockerfile> .`

`docker build -t registry.gitlab.com/cyber-security-associates-ltd/starter-project -f staging.Dockerfile .`

`docker push registry.gitlab.com/cyber-security-associates-ltd/starter-project`