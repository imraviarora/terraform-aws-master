# Jenkins Install in EC2 Instance


## Usage

```hcl
module "ec2_instance" {
  source     = "git::https://github.com/easyawslearn/Terraform-Tutorial.git/EC2withJenkins"

  region        = "us-west-2"
  key-name      = "ec2-demo"
  instance_type = "t2.micro"

}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| region | AWS region | string | us-east-1 | yes |
| key-name | ec2 access key name | string | ec2-demo | yes |
| instance_type | ec2 instance_type | string | t2.micro | yes |
