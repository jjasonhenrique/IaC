# Treinamento Descomplicando Ansible

Projeto para instalação de um cluster Kubernetes utilizando o Ansible + AWS.
Projeto com contribuição dos alunos

## Pré-Requisitos

## Criação de usuário IAM na AWS
```
- https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_users_create.html
```
## Instalação AWS CLI
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```
## Configuração usuário IAM na máquina que irá administrar o Ansible
```
- Ir em um terminal Linux
- Digitar aws configure
- Será solicitado o AWS Access Key ID e AWS Secret Access Key que foram criadas na etapa de Criação de usuário IAM na AWS

- Mais informações => https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-quickstart.html
```

## Fases do Projeto
```
- Provisioning => Criar as instâncias para o nosso cluster na AWS.
- Installl_K8s => Instalação  componentes Kubernetes, Criação do Cluster, Join Workers no Cluster.
- Deploy_App_v1 => Deploy de uma aplicação exemplo versão 1 no cluster Kubernetes.
- Deploy_App_v2 => Deploy de uma aplicação exemplo versão 2 no cluster KUbernetes.
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
