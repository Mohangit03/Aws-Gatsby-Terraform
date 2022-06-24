# Aws-Gatsby-Terraform
AWS - Gatsby Website Creating by Using Terraform
Creating SSL Certificate
•	Go to AWS Management  Go to Amazon Certificate Manager  Request and Create the Certificate  Copy the CNAME Name and CNAME Value  Open the Freenom Account  Go to the Nameservers  Paste the CNAME Name and CNAME Value in Freenom Domain.
•	Now SSL Certificate is created successfully.
 
 

 

Create Hosted Zone by Route 53
•	Go to the AWS Management Console  Go to the Route 53  Create the DNS Hosted Zone  Enter the Domain Name  Create the Hosted Zone.
 
 

Create S3, Cloud Front & Route 53 Using Terraform
•	Create the S3 for using the Terraform Codes.
•	Then upload the Front-end Framework for the Gatsby Website using the AWS Management Console.
•	Create the Cloud Front by using the Terraform Codes.
•	Create Route 53 by using the Terraform Codes.
•	Then the Cloud Front and SSL Certificate are attached using the Terraform Codes.

 
 
 
 
 
 
 
 
•	Open the Terminal and do the following Terraform Commands.
# terraform init
# terraform plan
# terraform validate
# terraform apply
 
 
 
 
•	Copy and Paste the SSL Certificate ARN, Domain Name and Hosted Zone ID.
 
•	Now Deploying the Terraform Codes Successfully.
 
 
•	Go to the S3 Bucket  Upload the Gatsby Website Framework  Then Copy the Cloud Front Domain URL  Paste the Chrome.
 
 
 
 
 
•	Copy the Distribution Domain Name and Paste it to Chrome.
•	Now Gatsby Website Frontend Page is Hosted because S3 is only allowed to the Static web hosting so Front-end Page only Hosted.
 




•	Now Destroy all Terraform Codes.
