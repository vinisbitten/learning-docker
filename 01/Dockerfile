FROM debian:latest

# definir metadados à imagem
	# sintaxe -- >  <chave>=<valor>
LABEL maintainer="Vinícius Bittencourt <bittencourt1310@gmail.com>"
LABEL build_date="2022-01-12"

# códigos para customização da imagem
RUN apt-get update && apt-get upgrade -y
RUN apt-get install nginx -y

# expor portas
EXPOSE 80

# comando para iniciar o NGINX no Container
CMD ["nginx","-g","daemon off;"]