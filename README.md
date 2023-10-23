Playing with https://github.com/ansible-collections/cloud.terraform

```
python3.11 -m venv .venv
source .venv/bin/activate

pip install -r req.txt
ansible-galaxy collection install -r req.yml
```

```
cat .env
export ARM_CLIENT_ID=
export ARM_CLIENT_SECRET=
export ARM_SUBSCRIPTION_ID=
export ARM_TENANT_ID=

source .env
az vm list
```

```
ansible-playbook -i localhost, -e repo_main_dir=$PWD p2/p2.yml -vv
```
