# Comandos para ejecutar python

```bash
cd app
pip install -r requirements.txt
python main.py
```

```bash
#Comando para correr prueba unitaria
python -m pytest app/tests/
```

# Comandos para Terraform
```bash
cd terraform
terraform init
terraform fmt
terraform validate
terraform plan
terraform apply
```

```bash
#comando para destruir la infraestructura
terraform destroy
```

# Comandos para Ansible
```bash
cd ansible
ansible all -i inventory -m ping
ansible-playbook -i inventory playbook.yml
```