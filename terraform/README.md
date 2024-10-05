                                   Jenkins Master server setup through Terraform Code

step -1 : Login to your local Machine > create a dir (mkdir terratest) > cd terratest > ssh-keygen (generate key to login purpose) > name the private key as terra-key 
step -2 : git clone https://github.com/swainraj/Wanderlust-EKS-Jenkins.git
step -3 : go to cd Wanderlust-EKS-Jenkins/ > cd terraform/ > terraform init > terraform paln > terraform apply (got to us-east-2 region one Ec2 instance has been launched)

Reference Screenshot :-

![image](https://github.com/user-attachments/assets/7717cb33-189c-487f-91e4-945c922c7929)
