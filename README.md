# Deploy a High Availability Webapp using CloudFormation

This project Using CloudFormation (infrastructure as a servies) to deploy a high availablity website.
![](./ProjectDesign.png)

## Files 

1. `Infrasturcture.yml` contain CloudFormation script to create Networks and servers needed to serve WebApp.
2. `Parameters.json` contain any parameter needed such as subnets environmentname, CIDRs, instance type
3. Create.sh used to create stack  
4. destroy.sh used to delete stack

## Creating stack example 

```bash
./create.sh Testing Infrasturcture.yml Parameters.json
```

## WebAPP URL 

http://testi-webap-1vzdardgu3ndd-848405100.us-east-1.elb.amazonaws.com/

