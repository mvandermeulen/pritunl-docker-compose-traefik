# pritunl-docker-compose-traefik
How to configure Pritunl Server - Docker Compose / Traefik / Ratting A+ SSL Labs on AWS.<br>
<b>Link: https://www.youtube.com/watch?v=JTKHFjijb9Y</b>
#
<b>Sobre o vídeo:</b> <br>Caso queira trocar a porta da VPN, alterar no <b>docker-compose.yml</b> e alterar no security group. 
<br>Caso queira mais de um server na VPN, alterar o range de portas no security group e no <b>docker-compose.yml</b>.<br>
Existem outras formas de fazer a automação dessa VPN, seja com git clone e um sed para substituir o email e subdomínio, tirando a necessidade de criar a policy e de usar um bucket, fiquem a vontade.<br><br>
Porém dessa forma conseguimos exercitar mais coisas, como IAM Policy, Role, S3 e Route53.
#
<b>About the video:</b> <br>If you want to change the VPN port, change in <b>docker-compose.yml</b> and change in security group.
<br>If you want more than one server on the VPN, change the port range in the security group and <b>docker-compose.yml.</b><br>
There are other ways to automate this VPN, either with git clone and a sed to replace the email and subdomain, removing the need to create a policy and use a bucket, be my guest.<br><br>
But this way we can exercise more things like IAM Policy, Role, S3 and Route53.
#
SSL Labs (Screenshot 1)<br>
![alt text](https://raw.githubusercontent.com/aldeiacloud/pritunl-docker-compose-traefik/main/images-ssl-labs/ssl-labs1.png)<br><br>
SSL Labs (Screenshot 2)<br>
![alt text](https://raw.githubusercontent.com/aldeiacloud/pritunl-docker-compose-traefik/main/images-ssl-labs/ssl-labs2.png)

