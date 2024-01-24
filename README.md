This is a simple project that aims to use Terraform to deploy EC2 instance on AWS with Keypairs (Genereted using ssh-keygen command).
After successful deplyoment I have used provisioners (File and remote-exec) to copy a script from local machine to remote machine and execute the script to deploy a Web server using HTTPD service.
