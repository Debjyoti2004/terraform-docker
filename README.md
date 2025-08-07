# 🚀 Terraform NGINX Docker Project

This project demonstrates how to use Terraform to pull the official NGINX Docker image and run it as a container locally using the `terraform-provider-docker`.

---

## 🧰 Prerequisites

- [Docker](https://www.docker.com/)
- [Terraform](https://developer.hashicorp.com/terraform/downloads)

---

## ⚙️ Terraform Commands

### Initialize the Terraform configuration

```bash
terraform init
```
![init](public/init.png)

###  Preview the execution plan
```bash
terraform plan
```
![plan](public/plan.png)
![plan](public/plan2.png)

###  Apply the configuration
```bash
terraform apply -auto-approve
```
![apply](public/apply.png)
![apply](public/apply2.png)

🟢 NGINX should now be running at: *http://localhost:8080*
![apply](public/home.png)
![apply](public/container.png)

### Destroy the infrastructure
```bash
terraform destroy -auto-approve
```
![apply](public/destroy.png)
![apply](public/destroy2.png)
