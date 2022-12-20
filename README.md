# Homework5
Task can be found in AWS_TF Final Task (1).pdf file.
We were asked to make:
1. Internal and external load balancers, both can be found in loadbalancer folder in main.tf.
2. 4 web servers, in WebServer folder.
3. 4 application servers, in Application server folder.
4+5. S3 bucket and rds, done in CreateAll.tf

to run the code simply tun:
  terraform init
  terraform plan
  terraform apply
 
please note that the load balancers expect you to have 2 subnets in 2 availability zones in your default vpc, we were not asked to do it in the task so I didn't because I already made them in previous class task.

note: don't forget to run "terraform destroy", or your instances will keep running.
