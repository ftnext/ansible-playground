# Tidy playbooks in directories

Source code of https://nikkie-ftnext.hatenablog.com/entry/tidy-ansible-playbooks-in-directories (in Japanese)

```shell
$ diff fabulous-playbook.yml tidy/located-playbook.yml

$ ansible-playbook -e subject=spam fabulous-playbook.yml
$ ANSIBLE_ROLES_PATH=$PWD/roles ansible-playbook -e subject=spam tidy/located-playbook.yml

$ diff hoge.txt tidy/hoge.txt
```
