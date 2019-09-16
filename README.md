# Containers

Install packages for building and running Linux containers.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

| name               | description                           | type | default                   |
| ------------------ | ------------------------------------- | ---- | ------------------------- |
| container_packages | List of container packages to install | List | [buildah, podman, skopeo] |

## Example Playbook

```yaml
- hosts: workstations
  tasks:
  - import_role:
      name: containers
```

## License

MIT
