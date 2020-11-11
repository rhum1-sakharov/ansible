# lancer une recette 
  
  ```
  ansible-playbook -i hosts playbooks/install.yml  --vault-password-file .vault_pass
  ```

# créer un role 
  
  Ici le role "tools"
  ```
  ansible-galaxy init tools  
  ```

# créer un password

  ```
 ansible-vault encrypt_string  --name mysql_root_password --vault-id .vault_pass
  ```
