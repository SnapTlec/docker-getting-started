## Objetivo
Documentar às primeiras 20h de estudo sobre docker. Estudarei utilizando a documentação oficial e o curso da alura _Docker: Criando e gerenciando containers_.

## Rodando o Projeto
Para a buildar imagem e disponibilizar a aplicação na porta _8484_ da máquina host.
```
//Construir a imagem utilizando o Dockerfile
docker build snapTlec/app-node:1.0 .

//Obter o ID da imagem
docker images

//Criar o container e rodar a aplicação
docker run -d -p 8484:3000 <IMAGE ID>
```
## Credito
Aplicação Web utilizada foi adquirida no curso do Alura. Crédito ao Daniel Artine.

# Referências
- [Curso Alura](https://www.alura.com.br/curso-online-docker-criando-gerenciando-containers)

- [Documentação Oficial](https://docs.docker.com/get-started/)
