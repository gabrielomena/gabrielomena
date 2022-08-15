1 - Vamos criar uma conta na AmazonAws para subir a aplicação:
https://portal.aws.amazon.com/billing/signup?nc2=h_ct&src=header_signup&redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation&language=pt_br#/start/email

2 - Após criar a conta procure o serviço Lightsail: https://lightsail.aws.amazon.com/ls/webapp/home/instances

3 - Crie uma nova instância
![print01](https://user-images.githubusercontent.com/49401569/184731202-325a9263-1854-4f89-990f-c9badf7c0e4b.png)

4 - Escolha o sistema operacional que será instalado. De preferência LINUX.
OBS: Por ser um sistema relativamente novo só tem servidor no EUA porém mesmo estando lá a velocidade é muito boa.
![image](https://user-images.githubusercontent.com/49401569/184731565-dadfe7f4-6b8d-46d7-94d4-d069fcc7000f.png)

5 - O Lightsail nos dá várias facilidades na hora de escolher como o sistema irá se comportar, veja que ele nos da várias opções de SO com aplicações pré instaladas
<br>
![image](https://user-images.githubusercontent.com/49401569/184732131-8e714160-e6c2-43af-b995-7a015e62c5a6.png)

Porém para nossa aplicação usaremos o docker, então precisaremos apenas do SO. Escolha a opção de Somente SO e o sistema Ubuntu 20.04 LTS<br>
![image](https://user-images.githubusercontent.com/49401569/184731933-0bddef6c-ae42-4e4a-8fcc-c7665cc2b547.png)

Para nossa aplicação usaremos o plano de 2gb, que já é mais que o suficiente para rodar várias aplicações.
![image](https://user-images.githubusercontent.com/49401569/184732442-61e9bfd8-cdca-43d3-88c3-0d83f72928ac.png)

Aqui vamos nomear nossa máquina virtual, porém podemos deixar o nome padrão, agora só clicar em Criar Instância
![image](https://user-images.githubusercontent.com/49401569/184732630-596b33bb-cb5d-42ca-9b7f-00104c591b38.png)

Agora só clicar na máquina que foi escolhida
![image](https://user-images.githubusercontent.com/49401569/184732729-6977365a-f15a-4c96-b36c-429e16133c09.png)

Temos algumas informações importantes nesta tela:
Primeiro aqui conseguimos ver o ip público que é por onde será acessado da internet
![image](https://user-images.githubusercontent.com/49401569/184733023-ac10c3b0-4de2-4314-b032-3f8503010865.png)


