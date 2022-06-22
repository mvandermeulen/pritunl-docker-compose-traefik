# pritunl-docker-compose-traefik
How to configure Pritunl Server - Docker Compose / Traefik / Ratting A+ SSL Labs on AWS<br>
Link da implementação: https://www.youtube.com/watch?v=JTKHFjijb9Y<br>
<b>Obs:</b> <br>Caso queira trocar a porta da VPN, alterar no <b>docker-compose.yml</b> e alterar no security group. 
<br>Caso queira mais de um server na VPN, alterar o range de portas no security group e no docker-compose.yml.
Existem outras formas de fazer a automação dessa VPN, seja com git clone e um sed para substituir o email e subdomínio, tirando a necessidade de criar a policy e de usar um bucket, fiquem a vontade.
Porém dessa forma conseguimos exercitar mais coisas, como IAM Policy, Role, S3 e Route53.
SSL Labs (Screenshot 1)<br>
![alt text](https://raw.githubusercontent.com/aldeiacloud/pritunl-docker-compose-traefik/main/images-ssl-labs/ssl-labs1.png)<br>
SSL Labs (Screenshot 2)<br>
![alt text](https://raw.githubusercontent.com/aldeiacloud/pritunl-docker-compose-traefik/main/images-ssl-labs/ssl-labs2.png)
