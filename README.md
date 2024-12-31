# custom-infinispan
To redeploy the infinispan cluster please follow the steps
checkout to prodops repo
go to ansible/playbooks dir
execute the following command
  ansible-playbook infinispan.yml --vault-password-file ~/Downloads/vault_prod -e "deploy_env=production"
