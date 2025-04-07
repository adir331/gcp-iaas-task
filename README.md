# GCP IaaS Task

This project provisions basic infrastructure in Google Cloud using Terraform. It creates:
- A custom VPC network
- A subnet
- A firewall rule
- A virtual machine instance (e2-medium)

## Usage
1. Set your GCP credentials.
2. Create a  file based on the 
3. Run [0m[1mInitializing the backend...[0m
[0m[1mInitializing provider plugins...[0m
- Finding latest version of hashicorp/google...
- Installing hashicorp/google v6.28.0...
- Installed hashicorp/google v6.28.0 (signed by HashiCorp)
Terraform has created a lock file [1m.terraform.lock.hcl[0m to record the provider
selections it made above. Include this file in your version control repository
so that Terraform can guarantee to make the same selections by default when
you run "terraform init" in the future.[0m

[0m[1m[32mTerraform has been successfully initialized![0m[32m[0m
[0m[32m
You may now begin working with Terraform. Try running "terraform plan" to see
any changes that are required for your infrastructure. All Terraform commands
should now work.

If you ever set or change modules or backend configuration for Terraform,
rerun this command to reinitialize your working directory. If you forget, other
commands will detect it and remind you to do so if necessary.[0m
4. Run [0m[1mvar.project_id[0m
  GCP project ID

  [1mEnter a value:[0m [0m

