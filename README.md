# Dockerfile

### Imagem do Docker com Jenkins LTS, Docker e cliente do Scan de Vulnerabilidade da Anchore:

https://github.com/antonionovaesjr/Dockerfile/blob/master/Jenkins_Docker_AnchoreCLI/Dockerfile

Usuário padrão da imagem ROOT

Portas para expportar:
- 8000
- 50000

Volume para mapear:

- /var/run/docke.sock
- /var/jenkins_home
