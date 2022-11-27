# understanding-terraform-the-hard-way-with-kojitechs

# Understand basic Terraform Commands
- terraform init # 
- terraform validate
- terraform plan
- terraform apply
- terraform destroy
- terraform refresh 
# terraform console

## variable data type 

```bash

" " :> string
[] = list 
80 = number 
bool = true/false 
{}  =  map 

### complicated
[""] => list(string)
[{}] => list(map)
{[]} => map(list)

```


```bash
export AWS_ACCESS_KEY_ID=
export AWS_SECRET_ACCESS_KEY=
export AWS_SESSION_TOKEN=
aws sts get-caller-identity 
aws sts assume-role --role-arn "arn:aws:iam::674293488770:role/Role_For-S3_Creation" --role-session-name terraform-session

```