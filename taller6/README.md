# Ansible Taller 6

# Instrucciones

1. **Crear instancias en AWS con las etiquetas: Name (ansible_api\*), Application (frontend, api y database) y env (prod y dev)**
2. **Comprobar instancias:** 
- `ansible-inventory --graph -i inventories/dev/inventario.aws_ec2.yml`
- `ansible-inventory --graph -i inventories/prod/inventario.aws_ec2.yml`
3. **Run playbooks:**
- `ansible-playbook site.yml -i inventories/dev/inventario.aws_ec2.yml`
- `ansible-playbook site.yml -i inventories/prod/inventario.aws_ec2.yml`