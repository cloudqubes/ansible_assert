## How to use Ansible for verifying configurations

`ansible_assert` is a collection of Ansible playbooks that demonstrate how to use Ansible for verifying configurations without actually changing.

## How to run the playbooks

1. Clone the repo.
2. Update the hostnames in the `hosts` files.
3. Run a playbook: `ansible-playbook -i hosts file-content-check.yml`

Read [How to use Ansible for verifying configurations](https://www.cloudqubes.com/recipe/ansible-verify/) for more details.