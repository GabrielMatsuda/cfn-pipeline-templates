# cfn-pipeline-templates


1- Criar manualmente Stack para inicializacao de credenciaos e pipeline para CI/CD de templates de pipeline
aws cloudformation create-stack --stack-name pipeline-control --template-body file://pipeline-control.yml --capabilities CAPABILITY_NAMED_IAM --region sa-east-1

aws cloudformation update-stack --stack-name pipeline-control --template-body file://pipeline-control.yml --capabilities CAPABILITY_NAMED_IAM --region sa-east-1

aws cloudformation delete-stack --stack-name pipeline-control --region sa-east-1


