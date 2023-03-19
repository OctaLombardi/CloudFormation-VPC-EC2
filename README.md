# CloudFormation-VPC-EC2
Usar AWS CloudFormation para crear una AWS VPC y una instancia de Amazon EC2.  
El objetivo es crear una plantilla de CloudFormation con los siguientes componentes:
          una nube privada virtual de Amazon,
          una puerta de enlace de Internet adjunta a la VPC,
          grupos de seguridad para acceder a la VPC configurada para permitir el SSH desde donde sea,
          una subred privada dentro de la VPC,
          una instancia de Amazon EC2 (T2.micro) dentro de una subred privada.
