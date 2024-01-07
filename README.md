# WSO2IS 6.1.0 Dockerfiles

Este repositorio contiene los siguientes recursos docker : 
- Recursos de Docker de WSO2 Identity Server Versión `6.1.0` para Alpine y Ubuntu
- Instrucciones de despliegue

**Tener en cuenta que se requerirán tener instalados alguna herramienta GIT (gitbash, fork, etc) y docker/docker-compose instalado en el sistema**

## Instrucciones de instalación y despliegue
```shell
# Recursos docker de wso2is
dockerfiles/ubuntu/is
├── Dockerfile
├── README.md
├── docker-compose.yml
├── docker-entrypoint.sh
└── wso2is-6.1.0.zip

1 directory, 5 files
```
## Instrucciones de instalación y despliegue
```shell
# Descarga del repositorio
git clone https://github.com/instructorinnovaappstar/wso2is.git
```
```shell
# Ubicandonos a la ruta de los recursos docker
cd dockerfiles/ubuntu/is
# Construyendo la imagen docker
docker-compose build
# Desplegando el servidor wso2is 
docker-compose up
```
