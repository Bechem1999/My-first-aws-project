# My-first-aws-project
My first project about aws titled: Securing my s3 bucket and iam user
The objective was to understand how misconfigured s3 buckets and iam policies can lead to security issues and gow to fix them
The tools needed included: AWS CONSOLE, IAM, S3, AWS CLI(optional)
THE STEPS INVOLVED:
- Create a new S3 bucket named atemlefac-cloudsec-demo1
- Upload a sample text file( e.g, sensitive txt)
- Make the bucket publicly accessible (simulate a misconfiguration)
- Create an IAM user called Junior-analyst with full S3 access
- Fix the misconfiguration by removing public access from the bucket and apply a bucket policy that restrict access to only the IAM user
Enable S3 server access logging for auditing  
