# How to import the collection and use the playbooks
```
pip install -r py-reqire.txt
ansible-galaxy collection install collections/ascii17 --force
```

## Examples
```
ansible-playbook -i inventory/titania playbooks/k3s.yml
```