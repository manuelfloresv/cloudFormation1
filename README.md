Este es un repositorio de configuracion de cloudFormationde AWS para crear una insfraesstructura de AWS con:

Script tomando desde https://www.infoq.com/articles/aws-vpc-cloudformation/ para crear el VPC
+ VPC con DNS y HOSTNAME habilitado
   - Subred Publica 1
   - Subred Publica 2
   - Subred Privada 1
   - Subred Privada 2
+ IGW
+ Creación de tablas de enrutamiento y ruta por defecto

Script tomado de https://github.com/ACloudGuru/intro-to-CloudFormation_AC para crear los EC2
+ Security Group para Publicas, RDS
+ EC2 para conectarnos
+ ALB (Balanceador de aplicacion)
+ Launch Config
+ Auto Scaling Group


Referencias:

+ https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/Welcome.html
+ https://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html
+ https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/ 
+ https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/walkthrough-crossstackref.html
+ https://medium.com/@anupam.ncsu/reference-resource-from-one-cloud-formation-stack-in-another-during-formation-f5c80679f0fd
+ https://aws.amazon.com/es/premiumsupport/knowledge-center/cloudformation-reference-resource/
+ https://github.com/gravitational/teleport-quickstart-aws/blob/master/oss.yaml
+ https://github.com/aws-samples/ecs-refarch-cloudformation/blob/master/infrastructure/load-balancers.yaml


