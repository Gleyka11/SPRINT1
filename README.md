<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1> Projeto da disciplina de Adminstração de sistemas abertos </h1>
    
</head>
<body>
    <h1> Primeiro SPRINT </h1>
    <h2>Requisitos da atividade</h2>
    <ul>
        <li>Criação do repositório com a estrutura do projeto</li>
        <li>Configuração da primeira zona de DNS (ifrn.asa.br).</li>
        <li>Configuração do proxy reverso (HTTP) com um host virtual para o servidor Web Content</li>
        <li>Configuração do Servidor Web Content contendo um site no WordPress do IFRN</li>
    </ul>
</body>
</html>

<h2><b>Comandos usados:</b></h2>

<i>Criar o repositorio no git e clonar:</i>

    git clone https://github.com/Gleyka11/SPRINT1.git

<i>Para subir os containers no docker:</i>

    Docker-compose up


<b><i>Dica para criar o seu certificado ssl:</b></i>

Faça o update e upgrade e depois instale o nginx:

    apt-get install nginx
    
Inicie o serviço Nginx: 

    systemctl start nginx

Siga o passo a passo:

    https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-nginx-on-centos-7

