# Ansible Common Roles
Common roles on servers which try to abstract OS.

## How to use it
### Prerequisites
Your roles must be in a `roles` directory at project root.

### Steps
```bash
git submodule add https://github.com/leroyguillaume/ansible-common-roles.git roles/common
```
You need to include handlers in your playbooks:
```yaml
handlers:
  - include: ../roles/common/handlers.yml
```

## Documentation
Each role is documented as header of `main.yml` file.
