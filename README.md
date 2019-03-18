# Dockerfile

### Imagem do Docker com Jenkins LTS, Docker e cliente do Scan de Vulnerabilidade da Anchore:

Imagem: antonionovaesjr/jenkins-docker:0.3

https://github.com/antonionovaesjr/Dockerfile/blob/master/Jenkins_Docker_AnchoreCLI/Dockerfile

Usuário padrão da imagem ROOT

Portas para exportar:
- 8000
- 50000

Volume para mapear:

- /var/run/docker.sock
- /var/jenkins_home
