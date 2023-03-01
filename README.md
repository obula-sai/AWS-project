# AWS-project


 1. created a vpc with 4 subnets ( 2 public & 2 private )


2. Uploaded files into s3


3. Created a policy and role for s3


{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1677670893301",
      
      "Action": "s3:*",
      
      "Effect": "Allow",
      
      "Resource": [
      
        "arn:aws:s3:::sai-project",
        
        "arn:aws:s3:::sai-project/*" 
      ]  
    }  
  ]  
}


4. Created a mysql instance using RDS service


5. Updating the endpoint,db username,password,db name details in db.php file and upload it into s3


6. Created an classic-load balancer


7. Created launch configuration with linux ami “ami-03f6a11788f8e319e”


8. Created Autoscaling groups with launch configuration
