# demoservers
<!-- #some needed codes

./update.sh demoserverstack demoservers.yml demoservers.json
./create.sh demoserverstack demoservers.yml demoservers.json


aws cloudformation create-stack --stack-name demoserverstack --template-body file://demoservers.yml    --parameters file://demoservers.json  --region=us-east-1


aws cloudformation update-stack --stack-name demoserverstack --template-body file://demoservers.yml    --parameters file://demoservers.json  --region=us-east-1

aws cloudformation describe-stacks --stack-name demoserverstack


-->
<!-- 


      #from port80 to port 80 i want to traffic everywhere
      SecurityGroupIngress:
      - IpProtocol: tcp
        FromPort: 80
        ToPort: 80
        CidrIp: 0.0.0.0/0
      SecurityGroupEgress:
      - IpProtocol: tcp
        FromPort: 80
        ToPort: 80
        CidrIp: 0.0.0.0/0 -->