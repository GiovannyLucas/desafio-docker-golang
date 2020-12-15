# desafio-docker-golang
Desafio do curso FullCycle, no módulo de DevOps, trabalhando com docker.

### Descrição do desafio
> Deverá ser criada uma imagem docker de golang, que ao executar o comando de running, imprima na tela a mensagem: "Code.education Rocks!"

### Requisitos
1. O nome da imagem deverá ser: username/codeeducation
2. A imagem deverá ter menos de __2MB__ de tamanho

  
### Para rodar
##### Dockerhub :whale:
`docker pull giovannylucas/codeeducation` <br/>
`docker run giovannylucas/codeeducation` <br/>

##### Diretamente :zap:
`
git clone ...
` <br/>
`
cd desafio-docker-golang
` <br/>
`
docker build -t giovannylucas/codeeducation .
` <br/>
`
docker run giovannylucas/codeeducation
`
<br/>
<br/>
