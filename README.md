# packer-jenkins-aws
Packer template to build a Centos 8 image with Jenkins ready to use on AWS.

- Exportar credenciales (link pendiente)
- Debe existir una VPC en la cuenta
- Colocar Filtro para imagen, verificar owner para no usar una imagen maliciosa
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/finding-an-ami.html
- Colocar filtro para encontrar VPC (default), Subnet y Sec group. (Deben existir)