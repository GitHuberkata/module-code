# Sample repo with code in a module for creation of ec2 instance

### How to use
1. Get the repo
```
git clone https://github.com/GitHuberkata/module-code.git
```
2. Navigate to projects 
```
cd projects
```
3. Execute 
- `terraform init`
- `terraform plan`
- `terraform apply`

4. If you want to add only a module for creation of ec2 instance in your own configuration, copy the folder "modules" and allocate it in your code:
```
module "ec2_module" {
    source = "../../<YOUR ROOT FOLDER LOCATION>/modules"
}
```

